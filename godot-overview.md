# Godot Overview

Godot is a free, open-source engine for 2D and 3D game development. It uses GDScript (a Python-like scripting language). Beginners should download Godot, create a new project, and learn core concepts like Scenes and Nodes. The official "Your First 2D/3D Game" documentation is highly recommended.

## Resources
- Beginner intro video: https://www.youtube.com/watch?v=nAh_Kx5Zh5Q&t=296
- 2D character setup & movement: https://www.youtube.com/watch?v=LOhfqjmasi0&t=505
- Recommended channels: Clear Code, Brackeys, BornCG, GDQuest
- Official documentation: Godot docs (search "Your First 2D/3D Game")

## Key beginner concepts
- Nodes & Scenes: Everything is a node (e.g., `Sprite`, `Timer`, `Camera`). Nodes are organized into Scenes, which are saved as `.tscn` files.
- The Scene Tree: Scenes are structured hierarchically; you can instance (nest) scenes inside other scenes.
- GDScript: The primary scripting language for game logic—attach scripts to nodes to control behavior.
- Signals: Nodes emit signals when events occur (e.g., a button press), allowing other nodes to react.
- Project setup: Create a dedicated project folder and choose a renderer (e.g., Forward+ for 3D; Mobile/Compatibility for 2D or lighter projects).

## First project steps
1. Download Godot from the official website.
2. Create a project in the Project Manager (New Project → choose folder).
3. Build a basic 2D game:
    - Add a `CharacterBody2D` node for the player.
    - Add a `Sprite2D` for visuals.
    - Use a `TileMap` to create the level.
4. Add motion using velocity and `move_and_slide()` inside a GDScript attached to the player node.
5. Run the game: press F5, select the main scene, and play.

**Recommended resources: Official Godot documentation and tutorial channels like Clear Code, Brackeys, BornCG, and GDQuest.**
