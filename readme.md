building an AR ARt Gallery using A-Frame and WebXR 


This repository follows the steps to build an A-Frame AR Art Gallery.  

A-Frame is syntatic like HTML to build VR/AR experiences on the web.  Documentation, etc. at https://aframe.io

1. We begin with the A-Frame Hellow World ([aframeHW.html](aframeHW.html)) as an introduction to A-Frame.

2. Next, We build a 4m x4m room with 4 walls and a ceiling ([aframeroom.html](aframeroom.html)) as the beginning of a VR art gallery.  But there is no art!

3.  [aframeroomart.html](aframeroomart.html) adds one piece of art, but the room feels really empty.

4.  [aframeroomart2.html](aframeroomart2.html) adds more art to 3 walls (and close to realistic size), and adds a 3D model of David behind the viewer.

5. But this is all VR.  Can we do AR with A-Frame?  Yes,  hiro.html is an intro.

6. [ARt.html](ARt.html) uses 4 patters that can be hug on the real wall for AR.js to add AR art over the top.

I have extended this demo into WebXR using https://github.com/dougsillars/ar-with-webxr.  This requires Android 8.0 or higher, Chrome Canary 70, so is mostly for demo purposes, but feel free to try it out.
