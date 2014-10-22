caffe-gui-tool
==============

Node based Gui for creating caffe networks

Master branch requires manual setup, although no compilation, and prebuilt is ready to go, but ~100mb compressed

Installation
==============

Git prebuilt Binaries (Simpler, but less reliable)
- extract blender archive in presetup
- launch blender with ./blender

Use
============
- Click the 'New' button on the bottom part of the screen to create a new network
- Name your network in this box, and ENSURE THE 'F' BUTTON NEXT TO THE NAME IS CHECKED
- Use shift+a to start adding nodes
- Join up, and fill in all the required fields. All networks require a data node, and solver node.
- When ready, select all nodes by single, (or double if required) tapping 'a', then press spacebar.
- type 'solution' in the search bar
- select 'create solution' and press enter
- This will create the required prototxt files in the config directory.
- Mark the train file as executable
- run the train file


Limitations
=============
- Negative gradient on ReLu not yet supported
- ReLu not calculated in place
- Many nodes not yet supported
