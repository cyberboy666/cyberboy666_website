---
type: diy
layout: page
---

# eurorack research

since i plan on building a number of video and audio units it seems necessary to try implement some 
standards around supplying power , size , transport , communication , etc .

eurorack is a popular standard for modular synth systems. it makes sense to build to this for my own projects
so i have some experience if i ever want to create tools for others. there is a learning curve to eurorack
but should make things easier in the long run.

i want to document my exploration into [diying for eurorack]. a larger list of project ideas, and useful information is already there.

## open source hardware

one of the other draws to the eurorack format is its close association with the open source hardware movement. this definition written by [Open Source Hardware Association] is based on the idea of Open Source Software and is used as a successful buseness model by a number of eurorack module makers. a good introduction to the open eurorack scene is described in a four part blog by [Horizontal Pitch]. advantages of this format are discussed by [Create Digital Music] and [Music Things Modular blog]. i would like to learn about designing, building, selling and contributing to this community. a good way to start would be to create a eurorack system, build existing open modules, build my own hacky projects to spec + licience / credit them correctly.

## eurorack case

starting small , i would like to ~~try 3d printing a frame and rails , thus creating useful resources for entering modular at lowest cost~~ . 3d printing is an interesing option to explore but is probably easier to start with some plywood screwed to a case.(an example of [3d rails] here , a plastic crate case as described on [morocco daves blog]  he also describes using [makerbeam] for his rails , which is an alternative to the real thing from [synthrotek]. both seem quite expensive to get shipped to nz. heres [more info about rails] including the specs and measurements of the commonly used ones you can buy.

## eurorack power supply

this seems to be somewhat complicated and buying something might be easier than diy-ing but i would
like to do some research on this. a diy build is described on [mfos] blog which looks like it will be good for me. different options depending on the size / use case : 

- mfos converting ac wall supply for small systems
- using a switching supply salvaged from an old computer (again hacky, may introduce some noise)
- mfos circuit stepped down from ac - diy , linear , best quality for price
- buy something professional

(if you plan to use lots of expensive gear it is safer/better to buy a serious power supply/ kit like [case power] )

## euro project idea

### existing projects

there are a bunch of projects, resources and ideas around the internet to choose from. heres a list of some ideas:
- [aisynthesis] : not sure if open? , but sells beginner pcb and panels with info about how the circuits work
- [mutable instruments] are famous in the eurorack world for designing interesting and unusual (mainly digital) modules , all open source, these looks like pretty advance projects , but could be fun to try some day !
- perhaps second most popular open eurorack projects are on [music things modular] , also a really nice website and some interesting blog posts... 
- [befaco] have a sweet looking range of modules, all open , with workshops also in larger euro cities (based in spain)
- [gmsn] is another fully open system with lots of interesting and useful looking modules
- [rebel technology] is another collective who publish their work as open hardware
- there are a few open source hardware projects on [HackMe]'s site
- if it gets to this , [lzx] have two series of open source video modules : cadet and castle (note: sounds like some video parts can be expensive and difficult to find)

### personal projects

more of these on [diying-for-eurorack] page

- my animal farm circuit would be a good silly practice example for the format (basicly a circuit bent toy that can trigger animal sounds - would be cool if it could trigger by gate although im not sure how to do this yet). also would be interesting if other circuitbent toys could be installed like cartages i saw on a circuit bending challange once...
- the midi splitter could be made to spec - run off 5v hopefully and with jack out options too
- the modded volcas could be put into 3d printed cases like i saw online - this leaves plently of room for extending the fuctionally with breakout board-like panel while in euro (hopefully connected in a way that can be removed if portiblity is desired)
- the dr110 drum machine could be made into a large panel (with breakouts for individual out / gate in , other modes) or could be left in small form factor with midi mod...
- the vga synth idea is perfect for this format. some other video parts would work too including simple dirty mix, and the video box
- a simple ardunio squencor as shown on lmnc looks fun / other ardunio thing...
- mounting and expanding the fluxus to this format

[morocco daves blog]: https://moroccodave.com/2017/02/14/more-making-modular-synth-case/
[makerbeam]: https://www.makerbeam.com/makerbeam-1500mm-1p-black-makerbeam.html
[synthrotek]: http://store.synthrotek.com/Eurorack_Vector_Rails
[case power]: http://store.synthrotek.com/Case-Power-PCB-and-Protective-Cover_p_587.html
[mfos]:http://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&VPW=1356&VPH=532
[3d rails]: https://www.thingiverse.com/thing:2489238
[more info about rails]: https://synthracks.com/eurorack-rails
[aisynthesis]: https://aisynthesis.com/
[mutable instruments]: https://mutable-instruments.net/
[befaco]: https://www.befaco.org/en/
[gmsn]: https://gmsn.co.uk/
[Open Source Hardware Association]: https://www.oshwa.org/definition/
[Horizontal Pitch]: http://www.horizontalpitch.com/2015/09/1271/
[Create Digital Music]: http://cdm.link/2015/09/means-meeblip-synth-open-source-hardware/
[Music Things Modular blog]: https://medium.com/music-thing-modular-notes/why-open-source-music-hardware-works-for-music-thing-modular-6ac004ac4553
[rebel technology]: https://www.rebeltech.org/
[HackMe]: http://hackmeopen.com/
[music things modular]: http://www.musicthing.co.uk/
[lzx]: https://www.lzxindustries.net/product-category/eurorack/diy/
[diying for eurorack]: {{ site.url }}/{{ page.type }}/diy-guide-to-eurorack
