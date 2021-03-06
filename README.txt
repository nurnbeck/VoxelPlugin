﻿Docs: http://wiki.voxelplugin.com
Issues: https://gitlab.com/Phyronnaz/VoxelPluginIssues/issues

Support:
- UE Forums: https://forums.unrealengine.com/community/released-projects/125045-voxel-plugin
- Discord: https://discord.gg/58ZqEbg

For more info, check the website: https://voxelplugin.com

## Installation

* In your project's directory, create a folder named Plugins
* Copy the Voxel folder into it. You should have something like
```
    MyProject
    ├── Content
    └── Plugins
        └── Voxel
            └── Voxel.uplugin
```
* If you want to use it in your C++ project: add **"Voxel"** as public dependency in **MyProject.Build.cs**. You should have
```
    PublicDependencyModuleNames.AddRange(new string[] { "Core", "CoreUObject", "Engine", "InputCore", "Voxel" });
```

## Quick start

* Add a **VoxelWorld** to your scene
* Set your player controller to the **VoxelComplexController** (need to toggle *Show Plugin Content*)
* Hit play