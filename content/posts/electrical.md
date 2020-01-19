---
title: "Cheaper to write software"
date: 2020-01-11T23:12:03-06:00
draft: false

tags:
- rant?
- software
- thoughts

categories:
- reflection

---

Recently i've had to develop some software that needed to interface an Arduino, well it wasn't originally like that. It was supposed to have some lcds and 8-segment displays which the arduino could drive and show temperature values via sensors. The problem was that I had to modify my whole plan because of the complexity involving electrical components, specially the LCD. I needed to connect more than 6 cables just for having that ugly screen, plus transistors and potentiometers the internet reccomended. I got to the point were it was exhausting to connect every single pin so I just decided to hook up a Bluetooth module which will redirect the sensor values to my computer.

The following is a tweet reply from someone on the internet that bought a chinese 18650 lamp and discovered a whole new world of flashlight firmware. He explains that there are 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">flashlights use one button for controls for the same reason microcontrollers use one button for debug interfaces: adding more firmware is orders of magnitude less expensive than adding more mechanical features</p>&mdash; whitequark (@whitequark) <a href="https://twitter.com/whitequark/status/1201613014245498881?ref_src=twsrc%5Etfw">December 2, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 
