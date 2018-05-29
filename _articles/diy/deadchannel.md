---
type: diy
layout: page
---

# DEADCHANNEL

> _“The sky above the port was the color of television, tuned to a dead channel.”_
 ― William Gibson, opening line of Neuromancer

![deadchannel](/images/diy/deadchannel/deadchannel-02.png)

An interactive video-art-installation created from salvaged and repurposed cyberjunk. Created by Tim Caldwell and Ian Matthews; inspired by tutorials on [Cracked Ray Tube]

<iframe src="https://player.vimeo.com/video/176073551?title=0&byline=0&portrait=0" width="640" height="468" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## Synopsis

The cathode ray tube is the epitome of obsolete technology. For fifty years this icon of prosperity has been the centrepiece of every living room. Now it languishes sadly in overcrowded landfills…too cumbersome to store, too awkward to move and too expensive to recycle. 

This installation is a resurrection of dead media.

Using a specially designed and custom built signal switcher with a collection of modified video devices and DIY circuits, the six CRT televisions can be torn in and out of sync, patched together with competing signals and gently coaxed into spilling neon colours in time to the surrounding music. This is video art that can be performed as an instrument.

Analog video is driven by a continuous electrical signal, in contrast to the discrete array of zeros and ones driving digital video. Distortion that would break digital transmissions can cause an analog display to bend in infinitely glorious and interesting ways. By exploiting the physical quirks that distinguish CRTs from their digital successors, this installation celebrates the unique aesthetics and ambience of analog video -an important relic of communication culture and history.

Today’s televisions, phones and media players are displaying a quality of image beyond retina resolution. This means a film made one hundred years from now will display no different to one today – our eyes can never distinguish more detail. Never again will we have the collective nostalgia of different display formats: the warm carbon arcs behind scratched film print of the 70s, the low-fi VHS fuzz of the 80s, or that timeless impenetrable wall of static - the colour of television tuned to a dead channel.

As our window to the world becomes immaculately polished, have we filled the cracks that let the truth in?

![deadchannelexample](/images/diy/deadchannel/deadchannel-05.png)

![deadchannelexample](/images/diy/deadchannel/deadchannel-07.png)

## details

the first step was collecting some tvs to use. this was relatively easy since many people seemed to be getting rid of them. (crts costing $25 to recycle at Wellington City Landfill helped. i also ended up collecting some straight from the Landfill Recycling Centre)

we decided on 6 teevees in total, (striking a balance between visual impact, and how much enthusiasm we had for storing / moving these suckers ) four 14" and two 21". luckily two of the smaller ones were studio monitors which made forming a 'stack' much easier.

### horizontal and vertical flip mod

![deadchannelexample](/images/diy/deadchannel/deadchannel-04.png)

[picture of switches]

the first mod we did was installing two (DPDT) switches per tv for horizontal and vertical flips. This exploits a [well documented] quirk of analog displays, simply flipping the wires to the deflection coil directly impacts the direction the picture is scanned. (interesting since the equivalent for digital is still quite processor heavy )

with these in place we could setup a 'mirror' or 'kaleidoscope' effect around the four 14" screens. by using on-off-on (DPDT) switches we could also set the screens to vertical/horizontal lines (disconnecting an axes from the coil - more on this next)

### diy electromagnets mod

![deadchannelexample](/images/diy/deadchannel/deadchannel-06.png)

following cracked ray tube's [electromagnet tutorials] we built 6 electromagnets and installed them in each crt with some #8 wire. these can be interacted with by a 1/8" jack which causes the displays to 'wobbulate' and colours to disperse in time to music. this effect is best when the signal is run through a audio amplifier. we found a old microsystem at the dump which performed this task in our setup. this also creates a nice coloured visualiser effect when the horizontal beam is disconnected:

![deadchannelexample](/images/diy/deadchannel/deadchannel-08.png)

although possible to connect via cables from a sound board at a show, we found it was easier to set up a microphone recording all ambient noises. especially at 'bass-heavy' events this made for nice audio-interactivity without the hassle of running wires.

### custom signal switcher

[picture of switcher]

to allow real time control over the teevee stack we wired up a custom signal switcher which allows each tv to be torn in/out of sync and continuos control over the levels sent to the electromagnets.

there is also a comprehensive patch-bay that allows different signals to be sent to each tv, or combinations sent to groups of twos or threes.

(note that this switcher is passive so the signal is quite thin when sent to all six - this however caused a desirable glitching effect that we decided to keep )

[well documented]: http://www.thegleek.com/bobroberts/yoke.html
[Cracked Ray Tube]: http://crackedraytube.com/
[electromagnet tutorials]: http://crackedraytube.com/textstutorials.html