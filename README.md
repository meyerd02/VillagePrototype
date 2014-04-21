VillagePrototype
================

Three.js-powered RTS camera with simple buildings &amp; landscape. I will be implementing functionalities over unregular periods of time, but will try to follow through the list.

To do:
---
- [x] Canvas initialization
- [x] Flat terrain
- [x] Moving camera
- [ ] Simple terrain & textured buildings (update: wireframe/solid/clay material enough for this step)
- [ ] UI for camera control
- [ ] Textures
- [ ] Mouse click-object intersection

How to run:
--
No server needed, downloading & extracting the zip from [here](https://github.com/sasoh/VillagePrototype/archive/master.zip) + opening __main.html__ in a WebGL-supporting browser ([Can I use WebGL](http://caniuse.com/webgl)) would be sufficient.

Status update:
---

__2014-04-21__

Proper COLLADA export from 3dsmax of given models not absolved of problems. Simple diffuse map textures seem not to be loading. Investigation so far not helping. Will be trying other formats (first with the good old _.obj_). Updated to do list with some things that would be needed.

__2014-04-11__

Got sample models from 3D artist friends. Should be looking at file loading now. And maybe rearrange the buildings. Setting better near/far planes & toying with the fog might be an interesting point to focus at at some point.


__2014-04-09__

Added autoscroll & zoom capability.