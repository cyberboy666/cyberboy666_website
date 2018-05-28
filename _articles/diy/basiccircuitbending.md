# basic circuit bending

i am more interested in building circuits that i understand , but also
enjoy the idea of some basic circuit bending.

## line out mod

the first thing needed when converting toys into sound sources for 
performance/processing is the ability to add a line out jack to it.
usually these toys have built in speakers, which ideally i would
like to keep where possible, by using a switching 3.5mm jack socket.

the other thing to consider is converting the signal level going to the
speaker to line level, more appropriate for headphones , mixers etc. 
(seems this is as easy as adding a resistor in series as described at
[anti-theory], although [circuitbender] suggest another circuit ~~i dont really
understand...~~ i think r2 is a placeholder for the impedance of the speaker
while r1 is just the resistor in series)

i dont think it is possible to add resistance to the line out path while 
keeping the speaker level the same when using a switching jack (the path from
switch to output is internal)

other options include :

- a volume pot (that can be adjusted from speaker level to
line level) and a switching jack
- a switch that turns the speakers on and off (so you always have the line
out option and can choose when to use the speakers) + jack with resistors

## musical farm

to practice these simple skills i am going to mod a toy called `musical farm`
to have a line out and a bunch of switches to trigger the sounds. 

- it will have a line out as described on circuit benders, and a switch to disconnect
the speaker
- might add a dc power input option?.
- there will be a rotary switch to select the bank, and five push buttons to play
each sound

some additional things to try but not necessarily for the first cut : 
- see if the circuit responds to being battery staved
- triggering the sounds from gate (using a 2n3904 perhaps)

[anti-theory]: http://www.anti-theory.com/soundart/circuitbend/cb16.html
[circuitbender]: https://www.circuitbenders.co.uk/tips3.html
