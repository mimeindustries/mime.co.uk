---
title: Kickstarter Update - Brains!
author: Benjamin Gray
date: 2015/03/28
layout: post
original_url: http://shop.mime.co.uk/blogs/news/56793925-kickstarter-update-brains
original_id: 56793925
---

Reposting this from the Kickstarter Update. A word to whet the appetite of any good zombie! Today the latest version of the MeBrain or Brains board has been sent for a prototyping run at Ragworm in the UK. It’s totally redesigned in the last few weeks due to a revelation in design from fellow Kickstarter Ben Pirt. Take a look and see if you can see what’s been done.

<figure><img class="fit" src="https://ksr-ugc.imgix.net/assets/003/505/887/5e7afd089ea02f37e7596ffa5adf6794_original.jpg?v=1427365545&amp;w=700&amp;h=&amp;fit=max&amp;auto=format&amp;q=92&amp;s=20ac8035203276d363b80cc322531a3c" alt="Brains Board V2.0 Prototype PCB Layout - Front">
<p> </p>
<figcaption>Brains Board V2.0 Prototype PCB Layout – Front</figcaption></figure>

<figure><img class="fit" src="https://ksr-ugc.imgix.net/assets/003/505/891/44663327b71282de1d6ffc44f7a93aaf_original.jpg?v=1427365630&amp;w=700&amp;h=&amp;fit=max&amp;auto=format&amp;q=92&amp;s=dc14e67a3a69a0ebb62f872a5096c1d5" alt="Brains Board V2.0 Prototype PCB Layout - Rear">
<p> </p>
<figcaption>Brains Board V2.0 Prototype PCB Layout – Rear</figcaption></figure>

Did you spot it? Well on the PCB it could well be a lack of it. The bill of materials (BOM) on the PCB has been drastically reduced. It now just contains a voltage regulator, a level shifter, a diode, a resistor and a bunch of decoupling capacitors. “Where have the Brains gone?” I hear you cry – well that’s the clever bit stolen from Ben Pirt. Rather than reinvent the wheel, layout an Arduino Leonardo board again and have all of the parts pick and placed on a custom design I’ve decided to use a plug in solution in the form of the Arduino Pro Micro – or more accurately clones of said board. The final Brains PCB will have an attribution to the original designers of the Pro Micro (the wonderful folk at Sparkfun) as the clone boards never do! And will also carry some other attributions to the clever and wonderful people who have let me steal their ideas whilst bringing the board to life.

It will also be apparent that I’m a little behind on schedule. The process of pulling apart business interests in the MeArm was fairly costly in terms of time (not to mention money) – but the project is again going in the right direction and building some momentum. I’m really happy with the new layout of the board and think that it makes it fit better with the ethos of the original MeArm. In that when a new board is spun out there will be an easy and cheap upgrade path as you can pull off all of the parts from your old board and plug them into the new one, the only tricky soldering being the bluetooth module – but as I’ve selected the popular HM-11 bluetooth low energy module replacing it isn’t likely to break the bank.

Although I’m doing everything I possibly can to deliver on schedule I’m mindful of the words of&nbsp;Shigeru Miyamoto “A delayed game is eventually good; a bad game is bad forever.” I want the MeArm to be a really good game!

Once I’ve worked out Github again I’ll share the KiCad files – so those with some knowledge can point out my errors! Watch [this space](https://github.com/MeArm/Hardware) for updates!

Thanks again for your patience and support.

Ben


