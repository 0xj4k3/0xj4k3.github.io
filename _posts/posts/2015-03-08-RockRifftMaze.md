---
layout: post
title: Rockulus Rifft Maze
---

Through the freedom of being asked 'what would you like to create at work this week?' and excitement of recently acquiring an Oculus Rift DK. I had a go at hacking together a maze game to saunter around in whilst listening to music for MixRadios very first hack week. 

The project was written in Javascript using mrdoobs excellent 3D Javascript library [threeJS](http://threejs.org/) to render WebGL 3D graphics in the browser and setup for the rift camera using the threeJS OculusRiftEffect. I hooked up the [MixRadio public API](http://dev.mixrad.io/doc/rest/) to pull music clips into the game.

Highlights of the hack were using arrays to make a grid to build the level. This makes a useful and reusable visual representation for building out levels. Oculus Rift integration and reading rift data in real time to use for things like collision detection, hey it wasn't laggy! And most excitingly ,writing JS in 4 days that results in 3D graphics in my browser at a very playable framerate. 


[Play](http://almerc.github.io/RockulusRifft/)

*If you have a rift be sure to install and run Oculus Bridge (from Oculus Bridge folder or [Oculus Bridge](https://github.com/Instrument/oculus-bridge)).

[Project Home](http://github.com/Almerc/RockulusRifft/)

![RockRifft]({{ site.baseurl }}/images/RockulusScreenshot.png "RockRifft")




 



