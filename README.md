# TileServer-GL
TileServer-GL on a NVIDIA Jetson Xavier NX

Our daily application which relies on maps such as the few famous Google Maps or Baidu maps all work on some form of serving of tiles and adding on layered information that is useful to the users.  But behind these maps are OneStreetMap.  But while, it's easy to say that you can imbed in information, there are quirks and understanding of any tileserver system.  https://github.com/maptiler/tileserver-gl is one such application.

The core of the code uses node.js and there are many mapbox addons that one can add to it.  Took me awhile to get this ported rightly from a non-ARM system to an ARM.
In the midst of doing this, I discovered core basic Problem Determination Skills.  Such as why is it that Sharp and VIPS cannot work hand in hand and how do you then merge everything back to Tileserver-GL

Here's the screen capture of how it works.  I will use this repository to document down exploration of Maps on the NVIDIA Edge device.  

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ULwp1_AGEOQ" target="_blank">
  <img src="http://img.youtube.com/vi/ULwp1_AGEOQ/0.jpg" alt="TileServer-gl" width="640" height="480" border="0" /></a>
