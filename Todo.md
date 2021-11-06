# Revision list
This file list all the todo to make from the original fork.
Please see the original project from Aman Tiwari for full implementation: https://github.com/aman-tiwari/MeshToSDF

* [] Check if numthread of dispatches can be full dynamic (see keijiro implementation)
* [] Skinned mesh is baked into a TMP mesh. Doies this mesh could be defined as a private param to avoid ```DestroyImmediate``` call ?
* [] Offset is a public param, could it be dynamic ?
* [] Scale by is a public params, could it be dynamic ?
* [] Sample Thickness ? Try it with a Raymarching material
* [] Can the SDF be filled (right now it's hollow)