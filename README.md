SkeletonAnimationDesignPanel
======================
This fork has been converted to be used with the IDE Visual Studio Code + [vscode-as3mxml](https://github.com/BowlerHatLLC/vscode-as3mxml) extension. 
The following [SkeletonAnimationLibrary](https://github.com/DragonBones/DragonBonesAS) library is already included to reduce setup steps.

How to build the source code:
1. Make sure you have Visual Studio Code and the mentioned [extension](https://github.com/BowlerHatLLC/vscode-as3mxml) installed.
2. Download [Flex SDK](http://download.macromedia.com/pub/flex/sdk/builds/flex4.6/flex_sdk_4.6.0.23201B.zip) to `./sdk`.
3. Open `./DragonBonesDesignPanelPlugin` folder in Visual Studio Code.
4. [Select Workspace SDK](https://github.com/BowlerHatLLC/vscode-as3mxml/wiki/Choose-an-ActionScript-SDK-for-the-current-workspace-in-Visual-Studio-Code) to the Flex SDK that was downloaded in step 2.
5. Run Task: "Build release"
6. (Optional) Run Task: "Run release"

### Differences to DragonBone's
- Export to Spine feature (....todo)

### Copyright
Copyright 2012-2013 the DragonBones Team