# LeapUnrealModules
Leap UE4 modules and examples. Drag and drop content for your leap needs. Depends on the plugin found under https://github.com/leapmotion/LeapUnreal

## Setup

This repository uses [git-lfs](https://git-lfs.github.com/). If you do not have git-lfs, please download from https://github.com/leapmotion/LeapUnrealModules/releases

## Modules

So how do interact with the Leap Motion? Easy, find your use case below and tinker away!

### Hello World

[VRHelloWorld.umap](https://github.com/leapmotion/LeapUnrealModules/blob/master/Content/Modules/HelloWorld/VRHelloWorld.umap). Bare minimum VR map to see if tracking is working.

### VR Pickup and Drop

[VRPickupDrop.umap](https://github.com/leapmotion/LeapUnrealModules/blob/master/Content/Modules/PickupAndDrop/VRPickupDrop.umap). Play with physics actors and pick them up. When you run out of cubes, spawn more by hitting a big red button. Supports very simple kinematic and non-kinematic item pickup and movement.

[![VR pickup and drop](https://img.youtube.com/vi/dkZD1JuSSnM/0.jpg)](https://youtu.be/dkZD1JuSSnM)

### UMG UI

[UMGUIExample.umap](https://github.com/leapmotion/LeapUnrealModules/blob/master/Content/Modules/UMGUI/UMGUIExample.umap). An example using Widget Interactors to enable finger based touch UI using vanilla UMG widgets. Includes basic vertical momentum scrolling support.

### Debug

[TrackingTestbed.umap](https://github.com/leapmotion/LeapUnrealModules/blob/master/Content/Modules/Debug/TrackingTestbed.umap). If you want to test tracking and read plugin stats, this module's map and blueprints gives you more resources to help debugging. This module also contains world space umg consoles. Useful for debugging text and values in VR.

### Rigging

[CustomRigHello.umap](https://github.com/leapmotion/LeapUnrealModules/blob/master/Content/Modules/Rigging/CustomRigHello.umap). A map with various skeletal meshes auto-mapped. Investigate various anim blueprint to see how each rig was done. See https://github.com/leapmotion/LeapUnreal#custom-rigging for rigging api documentation.


### (future examples...)


Contribute to the repo or suggest examples under https://github.com/leapmotion/LeapUnrealModules/issues
