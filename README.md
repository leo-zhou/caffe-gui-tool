Caffe Gui Tool
==============

Node based Gui for creating caffe networks

Master branch requires manual setup, although no compilation, and prebuilt is ready to go, but ~100mb compressed

ConvNet

![alt tag](https://camo.githubusercontent.com/31e4f9dd627afa62bb0366eae79e9254dfb94934/68747470733a2f2f646c2e64726f70626f7875736572636f6e74656e742e636f6d2f752f31303836303234342f676875622f53637265656e73686f7425323066726f6d253230323031342d31302d31392532303133253341333025334132312e706e67)

Autoencoder

![alt tag](https://camo.githubusercontent.com/d28a002ce2c7139877f2c1e8fa3f935ed57fa055/68747470733a2f2f646c2e64726f70626f7875736572636f6e74656e742e636f6d2f752f31303836303234342f676875622f53637265656e73686f7425323066726f6d253230323031342d31302d31392532303133253341333025334131352e706e67)


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
