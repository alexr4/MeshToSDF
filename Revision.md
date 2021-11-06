# Revision list
This file list all the revisions/updates made from the original fork.
Please see the original project from Aman Tiwari for full implementation: https://github.com/aman-tiwari/MeshToSDF

## 2021/11/06
* Set namespace for possible npm package release
* Remove all VFXGraph calls from script
* Remove All URP/HDRP element from scene to work on legacy
* Remove material output and replace with public geter
* Add ```OnDrawGizmos()``` Visualizer using ```DrawTexture3DVolume()``` and ```DrawTexture3DSlice()``` (see more : [DrawTexture3DVolume](https://docs.unity3d.com/2020.1/Documentation/ScriptReference/Handles.DrawTexture3DVolume.html) and [DrawTexture3DSlice](https://docs.unity3d.com/2020.1/Documentation/ScriptReference/Handles.DrawTexture3DSlice.html))
* Change float ```sdfResolution``` into ```PowerOf8Size``` enum to keep power of 8 consistency in sdf cube size
* Remove initialization and update from ```Awake(), Start() and Update()``` and set to public methods ```InitBuffers() and ComputeMeshToSDF()``` to be able to be called outside the main class