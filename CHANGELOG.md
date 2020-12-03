LeapUnrealModules  - Change Log
===============================

Versions

### Version 0.3.9
* Updated to work with Unreal Engine V4.25 and latest release of the LeapUnreal plugin (V3.6.0)
* UNREAL-56 Fixed LiveLink compilation issue related to AnimGraphNode_LiveLinkPose_043E904945C258D1A611D5968D234F1A'. Unknown structure
* UNREAL-73 Updated copyright notices
* Added an empty class to force plugin recompilation

### Known Issues and Workarounds

* UNREAL-52 If you run a packaged application with the VRPickupDrop level set as the start up level then head tracking seems to break. This appears to be associated with the physics hands prefab. As a workaround: if you place a leap hands pawn into the same level at the same position then everything works as expected. Although there is a suspicion that both the physics and leap hands are tracking and updating a mesh concurrently.

---

Copyright © 2012-2020 Ultraleap Ltd. All rights reserved.

Use of the Leap Motion SDK is subject to the terms of the Leap Motion SDK Agreement available at https://developer.leapmotion.com/sdk_agreement, or another agreement between Ultraleap Ltd. and you, your company or other organization.