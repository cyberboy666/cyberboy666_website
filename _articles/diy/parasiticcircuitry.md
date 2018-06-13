---
type: diy
layout: page
---

# pARasITicCirCUitRy

> _"the hostile swarm rewires internal circuitry of its host: a salvaged PlayStation One. it feeds this to the hijacked controller, allowing you to play endless combinations of visual distortion and harsh signal corruption"_

![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-01.png)

An interactive video-game glitch-art installation

<iframe src="https://player.vimeo.com/video/232211856?title=0&byline=0&portrait=0" width="640" height="468" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## details

![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-02.png)

this installation takes a number of "bend points" on a playstation One's graphics chip and connects them (via a relay board and an ardunio) to a second 'glitch' controller. player one controls the game (Spyro was my favorite) while player two controls the visual corruption. 

more examples of the kind of video bends exposed can be seen in this video : 

<iframe src="https://player.vimeo.com/video/185451870?title=0&byline=0&portrait=0" width="640" height="468" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>


![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-03.png)
![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-04.png)
![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-05.png)
![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-06.png)
![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-02.jpg)
![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-03.jpg)

### finding bend points



### programmatically switching glitches

when i decided to try triggering these glitches programmatically, (rather than the more traditional circuit bender approach of physical switches and pots) my first thought was using a switching ic like CD4066 ([Charles Werbick's project] programmatically creates patches on a tr626 with an array of CD22M3494s) however i could not get these ic's to work. i suspect small resistance leaks from the chips may have been too high for this circuit, but didnt have time to figure out exactly why it wasnt working. instead, i ordered an [array of relays] (physical switches electronically controlled by electromagnets ). although less compact than using ic's (which wasnt a concern for installation setting) one advantage of these is the satisfying clicking noise and flashing lights !

### hijacking a ps1 controller

once the glitches were being switched by relays, the final step was to connect these to a ps1 controller. fortunately there existed a good [ardunio psx library] which does most of the heavy lifting. we cut the controller cable and connected wires to the ardunio as suggested on the library.

from here it was relatively straightforward to write some code that took in controller inputs and sent out relay commands. you can see/use the [code we wrote].

### future ideas

some other things we didnt include but could be fun:

- a button to toggle 'hold' for current bent
- basic sequencing : perhaps a bmp input for switching glitch in time to music 

thanks to Andy Raba for designing the text : 

![parasiticcircuitry](/images/diy/parasiticcircuitry/parasiticcircuitry-07.jpg)


[Charles Werbick's project]: https://www.youtube.com/watch?v=f6S4W0K_GYc
[array of relays]: https://www.aliexpress.com/item/5V-16-Channel-Relay-Board-Module-Optocoupler-LED-for-Arduino-PiC-ARM-AVR/32834755914.html
[ardunio psx library]: https://playground.arduino.cc/Main/PSXLibrary
[code we wrote]: https://github.com/langolierz/playstation-glitch-hack