---
title: Running the MeArm with Arduino and Snap (a Scratch like language).
author: Benjamin Gray
date: 2015/11/23
layout: post
original_url: http://shop.mime.co.uk/blogs/news/69361349-running-the-mearm-with-arduino-and-snap-a-scratch-like-language
original_id: 69361349
---

To start this tutorial we'll assume you have a constructed MeArm and an Arduino compatible controller, such as the MeArm Brains Board. If not check these links:

- [MeArm Kit](http://mearm.com/collections/mearm)
- [Build your MeArm](http://www.instructables.com/id/MeArm-Robot-Arm-Your-Robot-V10/)
- [Hacking the MeArm Brains Board](http://mearm.com/blogs/news/68196933-hacking-the-mearm-brains-board)

In addition to these you're going to need:

1. PC or Mac - with administrator access (will Raspberry Pi do? Don't know yet, let me get back to you on that!).
2. Arduino IDE or Codebender app in Chrome.
3. [Snap4Arduino](http://s4a.cat/snap/)- Downloaded and Installed.
4. USB cable - appropriate to your Arduino compatible.

Plug in your Arduino via USB and open your Arduino IDE (or Codebender). Go to

File \> Examples \> Firmatta \> Standard Firmatta

Select your device and COM Port and upload the Standard Firmatta sketch (Arduino programmes are called sketches).

Now open Snap4Arduino. Go to the Arduino category in the top left of the program click Connect Arduino. If the sketch was uploaded correctly and your Arduino is connected via USB it should now be connected!  
  
Now we're going to get you started by moving the Claw!  
Download this example: [MeArmClaw](http://mearm.io/guides/MeArm%20Basic%20Claw)&nbsp;(Right click and save as)&nbsp;  
Import the code you've just downloaded by going to the file icon and Import (the file may be in your downloads).

With the MeArm connected you should now be able to run the code by clicking the green flag and pushing the up and down keys on your keyboard you'll be able to control the claw!!! If you go to far it will beep instead of move.  
  
Hopefully you should be able to see the simplicity of the code that achieves this fantastically quick control method.   
  
Check out this diagram and see if you can change the servo you're controlling to the middle servo...  
 ![](/assets/blog/2015-11-23-running-the-mearm-with-arduino-and-snap-a-scratch-like-language/PinOutProMicro_large.jpg)&nbsp;  
You can copy code blocks by right clicking on them and left clicking duplicate. By changing the control key, the variable that you're changing (claw) and servo pin number (ClawPin) you can control all of the other servo motors!

Now I'm going to find out why I can't take screen grabs right now then get back to you on this tutorial. Hopefully it's got you started and wanting more! Please let me know how you get on in the comments or forums.

&nbsp;

&nbsp;

&nbsp;


