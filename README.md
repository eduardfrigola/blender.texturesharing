# WIP Syphon integration

# Texture Sharing addon V0.0.1 for Blender 3.0.x

[Spout](http://spout.zeal.co/) / [Syphon](http://syphon.v002.info) for Blender allows to stream texture streams from blender.

This works only for Windows 10 64 bit and macOS 12.x

## Installation

Please make sure you have the most current Blender 3.0.x installed.

1. [download](https://github.com/eduardfrigola/blender.texturesharing/releases) the addon from the **releases**

2. Open Blender > Menu >  Preferences > Add-ons > search for and enable the 'Texture Sharing' add-on  

3. Press the button to install the SpoutGL or syphonpy library via pip.

4. Once the SpoutGL / syphonpy library is installed, disable and reenable the addon.

5. Save and close preferences.

## Usage

Currently it is only possible to send Spout / Syphon streams, but not to receive them.

For streaming you need a Camera object.

The plugin adds a Panel to the Camera properties called 'Streaming Texture'. The following properties are available:

* The streaming name is default set to the camera name.
* capture/streaming resolution.
* show preview inside viewport.
* use eevee color management (recommended)
* chose a workspace with the desired render / shading preferences
* chose a scene and layer setup to render

You should be able to create as many Cameras with streams as you wish.

## Credits

Blender Plugin by Martin Froehlich.

### Special Thanks:
Obviously Lyn Jarvis for developing Spout in the first place. And without [SpoutGL for Python](https://github.com/jlai/Python-SpoutGL) developed by Jason and the valuable [hint](https://docs.blender.org/api/master/gpu.html#rendering-the-3d-view-into-a-texture) from Jonas Dichelle I would still dab in darkness...
People from V002 for Syphon and Alex for [syphonpy](https://github.com/njazz/syphonpy)

[CAD_Sketcher](https://github.com/hlorus/CAD_Sketcher) showed me how to dynamically install the needed SpoutGl library. Hurray to Opensource!

Python support by Florian Bruggisser
