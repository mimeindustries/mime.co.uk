---
title: Hacking the MeArm Brains Board
author: Benjamin Gray
date: 2015/11/23
layout: post
original_url: http://shop.mime.co.uk/blogs/news/68196933-hacking-the-mearm-brains-board
original_id: 68196933
---

![](/assets/blog/2015-11-23-hacking-the-mearm-brains-board/Heisenberg_Square_large.jpg)

There are two main ways to set up your MeArm Brains Board so you can change the code or run your MeArm with Snap (a Scratch like coding language). To keep things simple it's best to disengage the Pro Micro Clone from your MeArm Brains Board for initial programming. It's one less thing to troubleshoot!

However first we must identify the version of Pro Micro that you have. Helpfully (with the help of a supplier mistake) we changed version from 3V to 5V. To identify the version you have look at the silver rectangle shown at the opposite end of the board to the USB jack.

![](/assets/blog/2015-11-23-hacking-the-mearm-brains-board/ProMicroVolt_large.jpg)

The 3V board has 8.000 on that rectangle and the 5V board has 16MHz on it. Now you know what you have, select the correct one when you program. If you don't it won't damage the board but you will need to perform a little trick before you reprogram it. Essentially it's resetting the board using a piece of metal (like a paper clip) between the GND and RST pins and re uploading the code to the board on the correct setting. The trick is in the timing. Click Upload and then reset the board with the paper clip.

##   
1. The Traditional Method

Download version 1.6.5 of the&nbsp;[Arduino IDE](https://www.arduino.cc/en/Main/OldSoftwareReleases#previous). There are problems with the later versions and the chip that we use.  
Install the Arduino IDE file following the onscreen prompts.   
Once installed start the Arduino IDE and go to

> File \> Preferences

and under

> Additional Boards Manager URLs:

paste the following:

> https://raw.githubusercontent.com/sparkfun/Arduino_Boards/master/IDE_Board_Manager/package_sparkfun_index.jsonClick OK  
  
Then go to   
> Tools \> Board: \> Boards Manager

Type Sparkfun and click to install Sparkfun AVR Boards   
  
Close then go to

> Tools \> Board:

and select Pro Micro.

> Go to Tools \> Processor

and select "ATMega32u4 (3.3V, 8MHz)" or&nbsp;"ATMega32u4 (5.0V, 16MHz)" depending on your board.  
&nbsp;  
Plugging in your Pro Micro Clone via USB should now install the correct driver. If it fails, please use [this driver file](http://mearm.io/guides/sparkfun.inf) (right click and save file as).  
  
You are now ready to start programming your Pro Micro Clone (MeArm Brains Board)

- Pros - traditional method, easier to troubleshoot, good online support for Arduino IDE.
- Cons - time consuming.

## 2. The Modern Method

Download [Google Chrome](https://www.google.com/chrome/) (if you don't already have it)  
  
Head over to [Codebender.cc  
](https://codebender.cc/?referrer=MeArm) Create an account and follow the on screen prompts.&nbsp;   
Your Pro Micro is now ready to program!&nbsp;

Pros - Faster!  
Cons - support not as comprehensive as with Arduino IDE

## What next?

Now you can start experimenting. The MeArm Brains board comes with a controller and LCD and we have examples of how to get these running. But the controls aren't perfect for a reason, so you can make them how you like them! Check out the code and our Pin Out diagram so you can get started!

![](/assets/blog/2015-11-23-hacking-the-mearm-brains-board/PinOutProMicro_grande.jpg)

A great way to experiment is to use a visual programming language like Snap (similar to Scratch) and our next tutorial will show you how to do that in a very quick and simple way!


