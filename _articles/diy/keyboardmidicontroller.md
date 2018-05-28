# diy midi controller from an old toy keyboard

i would like some small portable 'keys' that output midi for creating chords, patterns etc into synths. i have a small ardunio that should be up for the job. i beleive it is possible to output midi through the ardunio usb, which could be wired to a port and installed in the keyboard.

some things i would need to do for this project:

- power the ardunio from a point inside the keyboard
- figure out how to matrix the keys into ardunio inputs
- research, flash and test the code needed
- wire the parts together and install midi port

optional extra things to investigate while building:

- switching between midi out mode and normal keyboard operation
- reversing the process for a midi in mod
- buttons to move up/down octaves
- pots for cc control (and up/downs)

## research :

this project on [Code Tinker Hack] outlines how to use an ardunio and a 74HC595 [Parallel-out shift]
to get midi out. it seems that using the usb to output midi, although possible may be more hassle than straight from the board (and at no advantage for my use). this example uses 8 digital pins on the board to control for 32 notes : 8 rows to the ic , 4 columns to ardunio plus 3 control pins from ardunio to ic (pwm) plus 1 (tx) out to midi socket. if i did want to have octave control/cc would need to make sure i have enough pins (analog ones for cc).

the keyboard i have (casio sa-1) also has 32 keys. on a quick inspection it is not obvious where the traces from the keys go, ~~but i could guess it also~~ found this info on the [circuitbenders] forum that should have all the info i need for the wiring - also it seems like the control buttons are also avaliable on the same matrix, ~~although this may require two ics and more pins to take advantage of...~~ should be just adding two more columns to the matrix

the ardunio pro micro that i have, according to [sparkfun] has 18 i/o pins. assuming we only read 32 keys from the board, this will use:

- pin 1 (the only tx) out to midi port
- 3 digital pins to communicate with ic
- 4 digital for the columns of keys matrix
- plus another 2 digital for the columns of control keys

that will leave us 8 pins, all of which are analog in. this means 8 pots for cc control is possible ; plus 16 assignable buttons, which could be used for:

- 2 buttons for octave up and down
- 2 buttons for cv-bank up and down
- sysControls ??
- otherthings that midi controllers do ??

as an aside re midi-in control: [Amanda Ghassaei's instructable] post describes how to get input from midi into an ardunio using an 6N138 optocoupler and a single pin (rx) in. i dont think it would be feasable or desirable to have both midi in and midi out from the same keyboard using just a single ardunio micro. ~~also i still wouldnt quite know how to output to the keys.~~ a second read of the ShiftOut tutorial on the ardunio website shows an example with leds which confirms the same meathod can be used for outputs as inputs. it would be fun to mod midi input to one of my other keyboards in this way.

## the plan:

i chose this keyboard to modify for two reasons:

- it is the smallest and lightest keyboard i have, making it easy to transport
- i only just got it for $1 at the the dumpshop and didnt know if/how well it worked - experimenting on a keyboard i wasnt as emotionally attached to yet (i have around 8 other toy keyboards i orinately bought to mod but have grown too attached to them the way they are) 

i couldnt resist testing it out though and not only does it work, it sounds great ! there are heaps of awesome strange settings in the sound bank, and its size is so endearing! (also by far the best demo tune i have !) this makes it slightly harder to begin work on this keyboard, but it is possible that i wont have to sarifice its function as a keyboard to use it as a midi controller.

my plan is to have a switch and led that puts it into midi controller mode. this will cut power to the keyboard circuit and route it to the ardunio. i will wire my connections straight onto the board, on the pinouts of the main ic (which shouldnt affect the function when the ardunio is not powered on ?)

i will also remove the built in speaker (rip) and use that space for the midi switch/light and a number of pots that will control cc








[Code Tinker Hack]: http://www.codetinkerhack.com/2012/11/how-to-turn-piano-toy-into-midi.html
[Parallel-out shift]: https://www.arduino.cc/en/Tutorial/ShiftOut
[circuitbenders]: https://www.circuitbenders.co.uk/forum/index.php?topic=1391.0
[sparkfun]: https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide/hardware-overview-pro-micro
[Amanda Ghassaei's instructable]: http://www.instructables.com/id/Send-and-Receive-MIDI-with-Arduino/
