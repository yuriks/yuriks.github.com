---
layout: post
title: 1GAM - Blow up stuff!
date: 2013-02-07 21:11
tags: 1GAM gamedev
---

Since the last post I:
* Added parallax layer to the starfield background. I'm not sure yet if I'll keep it, because it's kinda unrealistic (Assuming the stars are far enough that they'll appear as points, they would be far enough to not parallax at all and always stay fixed on the same spot.) and also seems to mess up the relative sense of movement of the player. I'll probably add foreground "space debris" layers that are on a similar plane of movement as the player instead.
* Some internal code refactoring. With more to come. Yay exciting.
* Drones now have shield and hull integrity meters and you can shoot and kill them! Shield recharges and has a nice effect when you hit it. Drones break into space junk when their hull is completely destroyed.

It's now finally starting to shape into something that could be called "playable", except without much of a goal or challenge. Because of that, I made a new [Windows build](/files/2013-02-07/SpaceCrawler-win32-3c0cc9.7z). Please try it out!
