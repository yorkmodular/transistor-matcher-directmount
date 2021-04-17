**This module is now discontinued - there will be no more made unless there is sufficient demand to justify a new run of boards.**

**Information provided here is provided under the terms of the Creative Commons License Attribution-ShareAlike 4.0 International**

First of all, you're probably wondering what a direct mount module is - easy, it's a panel-sized PCB which you attach directly to your rack. 
Maybe not so good for performance use, but for tinkering around it's perfect.

This is a board which will hopefully make the act of matching transistors rather less tiresome - it was born out of the need to get matched 
pairs of transistors for some forthcoming modules which require them.

I can't claim that I came up with the circuit - it was designed by Ian Fritz and has been floating around the internet for a good few years now. 
His original article can be found [here](https://web.archive.org/web/20151002134800if_/http://home.comcast.net/~ijfritz/MiscProj/transmat001.pdf) 
(PDF - slightly technical) and there's a slightly less technical over view [here](https://kassu2000.blogspot.com/2015/10/transistor-matching.html). 
Needless to say, for a circuit which uses a handful of passives, it is both simple and very effective.

There's provision for matching both PNP and NPN transistors, and each has a couple of test points to which you can connect a DVM or similar to 
measure the differential voltage (or not) of a transistor pair. This is a simple build, and the only remotely exotic components required are two 
pairs of matched 100k resistors (I used 0.1% tolerance resistors in my build because there's no kill like overkill) otherwise it's stuff you'd 
probably find lurking in your bits box.

If you plan to fab your own boards, I *strongly* recommend having them fabbed from 2mm substrate rather than 1.6mm - it'll cost a bit more but the
end result will be far more sturdy (and less flexible)
