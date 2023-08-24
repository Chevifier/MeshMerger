# Mesh Merger

Tool Script for combining meshes multiple meshes into a single mesh for less draw calls

## HOW TO USE

1. Add the MeshMerger.gd to a MeshInstance3D node
2. Add all your mesh objects as child nodes.
3. [Optional] Create a Static/Rigid Body Node.
4. [Optional] Set Static/Rigid Body Node as Collision Parent Path.
5. Press Merge Meshes in the properties window.
   
   

## Functions

  `Collision Parent Path` - Path to Static or Rigid Body

  `Btn Merge Meshes` - Combine all children objects of type MeshInstance3D

  `Btn Clean Meshes` - Clear Mesh combination(Delete Combined Mesh)

  `Toggle Children Visibility` - Show/Hide child mesh objects

  `Delete Child Meshes on Play` - Delete child meshes at runtime

## Links

Original By [Tomanski](https://youtu.be/4dTqVmnDT_w?si=-Qg_vjbGt3447-Wv)

Updated to Godot4.X by [Chevifier](https://www.youtube.com/channel/UCDjKBPa2h9Uunwfw3DTsRCw)