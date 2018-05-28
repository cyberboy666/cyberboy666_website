---
type: diy
layout: page
---

# volca beets mod

analog drum machines are interesting in part because of the opportunity
to modify them. besides being probably the most affordable analog drum machine
available today, the beets is infamous for it's weak snare sound and the rumors
surrounding it.

i mainly want to fix the snare sound but am also interested in exploring the other mods people have done on a volca beats

## the c78 snare mod

it seems like (perhaps among others) Darren Glen discovered and posted a 
[video of a mod] he found to improve the volca snare in 2014.
it involves a 104 Cap soldered to some points on the board ([full video])

some time after this it surfaced that there was a different point on
the board (labeled c78) for a surface mount version of the 104 cap to be placed.

the existence of this labeled (but empty) pad on the board increased the suspicion
tht korg knew about this improved snare sound before launching Volca beets.
the most likely explanation is it was a manufacturing error that would have been 
too expensive to recall, although some have suggested it was a malicious crippling of the 
machine...

finally, because soldering onto micro smd boards is difficult, in 2016
[Animal Factory Modifications] suggested another point on the board where 
the 104 cap can be connected (a larger diode pad instead of the small capacitor one)

there is also the option to add in a switch or pot to have even more control over 
the snare sound. 

-i quite like the idea of soldering the points to two pin sockets 
that can be exchanged for different capacitors (or reverted to the original) if desired
- im not sure whether i want a pot to fine tune this sound - will have to try it out first

## individual out mod

it seems one of the main differences between 'toy' analog drum machines 
(volca beets, boss dr-110) and 'real' ones is the ability to have individual sound
outs.
this is useful if you want more control mixing the sounds on an external mixer, 
and if you want to add some effects to one drum sound but not another.
it is also quite easy schematically to achieve (just attaching jacks for line out at the 
correct place on the board). 
the difficulty in the volca beets case is finding the space to house these new jacks
(since the device is so small)

- i would mainly be interested in having bass and snare out i think although interested
in what it might looks like with the others as well
- i have ordered some 3.5mm jacks from ali which look like quite a small footprint.
i am keen to have a look inside once they arrive to decide if i should try this mod

## midi out/thru

it seems like korg has labeled inside all the volca machines some points that could 
be hooked up to a 5din socket for midi out/thru (i need to confirm / understand if they
can do midi out - it seems unlikely)
- i wont have a huge need for this mod when finish building the midi splitter, although
again, am interested in how to make these little 'toys' more interesting in general.
- personally i dont like aesthetically how another din socket looks on the volcas,
i think i would be more happy with a 3.5mm jack for midi out.
(i found a midi to 3.5 cable on ali which i ordered to test the assignment)
- another idea i had was to investigate the possibility of re-using the
'sync out' jack port to output midi instead when selected by a switch.
this would allow the functionality with minimum disruption
to the aesthetic of the face plates, although this would involve cutting the traces
on korg's board which seems more risky than just adding some solder points,
i will think about whether im willing to do this once its opened up.

## other mods

in Darren Glen's videos he also mentions a hat -> triangle mod, some toms mods
something on the pwc sounds. i might be interested in at least listening to these!

another interesting resource is the [beatsmod] : an extensive breakout box
for volca beats.
it also includes gate triggering, cv control over a bunch of stuff etc etc

(this is probably a bit beyond what i want to do with this machine but def is interesting)

[video of a mod]: https://www.youtube.com/watch?v=m6nYy1mtYks&feature=youtu.be
[full video]: https://www.youtube.com/watch?v=7P3bmype2c0
[Animal Factory Modifications]: http://www.animalfactoryamps.com/single-post/2016/09/20/PSA-The-Korg-Volca-Beats-Snare-Mod---now-easier
[beatsmod]: https://www.metatronicmods.com/beatsmod.html
