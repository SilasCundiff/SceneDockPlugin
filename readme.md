# A Scene Dock Plugin for Godot

![demonstration of some of the features](SceneDock_demo.gif)

This is a small plugin I wrote for personal use with Godot. I'm still relatively new to Godot, and I kept finding myself fighting with Godot's file explorer and scene panel. I wanted a way to quickly navigate between scenes and scripts, and to quickly open them in the editor. 

More importantly, I wanted an easy way to see every place a Node was an instance of a scene. While my projects so far have been small, I can see this being a huge help in larger projects where instanced nodes are used in several scenes.

## Features
- Quickly navigate between scenes and scripts by double-clicking on them in the dock, if they are open in the editor they will be focused.
- Single click opens the scene or script in the inspector instead.
- Filter by name or node type.
- See every place a node is instanced in a scene.
- A setting to view folders as complete paths, not just the folder name.
- View your addons scenes and nodes, this was helpful for me while developing this plugin itself. (disabled by default)