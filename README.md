# Unreal Landscapes 03 - A free PCG (Procedural Content Generation) plugin #

A *free* Unreal *Procedural Content Generation (PCG)* plugin. It allows you to drop PCG graphs as splines into your levels and then define any number of mesh groups via *data assets*, which are then easily customized using many parameters. 

This allows you to *use PCG without having to familiarize yourself with the structure of PCG graphs*.

## Updates ##
*2024-08-11:*
- Added individually calculated bounds boundaries per Static Mesh to make self pruning more exact
- Added Static Mesh specific Weight (chance to be selected) and BoundScale (extend mesh bounds to allow/disallow overlap)
- Moved Debug mode into the Data Asset - now switchable per Mesh group between:
	- No Debug
	- Debug with custom colored cubes
	- Debug with Static Meshes and colored Wireframes to show bounds
	- Debug with Static Meshes and colored x.y.z axis Tripods


## Links ##
- UEPastebin: https://bit.ly/PCG_Template - Subgraph for info, but easier to use this plugin!
- Tutorial video: [english](https://youtu.be/DzZpST0NMaA) | [german](https://youtu.be/5vYoQ1HrX70)

This plugin is part of my small [Youtube channel](https://www.youtube.com/channel/@BastianDev) discussing various aspects of Unreal development.

If you have any remarks, improvements or questions, best post them into the regarding Youtube tutorial chats groups.

## Overview plugin ##
![Looped PCG structure](https://github.com/DeveloperBastian/PCG_Templates/blob/main/Resources/PCG_Template_Structure.png?raw=true)




