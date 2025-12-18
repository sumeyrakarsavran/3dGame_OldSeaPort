3D Game – OldSeaPort

<br><br>

A Unity-based 3D game project simulating an old seaport environment with basic character interaction and navigation.

<br><br>

📌 Table of Contents

About
<br><br>

Features
<br><br>

Built With
<br><br>

Project Structure
<br><br>

Gameplay Overview
<br><br>

Core Systems & Mechanics
<br><br>

How to Run Locally
<br><br>

Controls
<br><br>

Future Improvements
<br><br>

License

<br><br>

About
<br><br>
This repository contains a Unity 3D project titled OldSeaPort — a small-scale 3D game concept built using Unity and C#. The project demonstrates foundational 3D gameplay elements such as player movement, physics, navigation, and scene design in a seaport setting. The codebase primarily consists of C# scripts for game logic, with shader assets for visual rendering and Unity scene assets. 
GitHub

<br><br>

Features
<br><br>
✔ Fully modeled 3D environment representing an old seaport
<br>
✔ Player controller for movement and camera look
<br>
✔ Basic physics interactions (collisions, ground detection)
<br>
✔ Shader assets for environmental visuals
<br>
✔ Scene setup ready for expansion and content addition

<br><br>

Built With
<br><br>

Unity – Game engine for development

<br>

C# – Primary scripting language

<br>

ShaderLab – Shaders for materials and effects

<br>

Unity Physics – Built-in 3D physics system

<br><br>

Project Structure
<br><br>

3dGame_OldSeaPort/
├── Assets/                # Game assets: models, scenes, scripts
│   ├── Scenes/            # Unity scene files
│   ├── Scripts/           # C# gameplay and utility scripts
│   ├── Materials/         # Materials & shaders
│   ├── Prefabs/           # Reusable 3D objects
│   └── Textures/          # Textures for models
├── ProjectSettings/       # Unity project configuration
├── Packages/              # Unity package manifest
├── .gitignore


<br><br>

Gameplay Overview
<br><br>
OldSeaPort places the player in a 3D harbor environment where the main interactions include exploring the scene, navigating terrain, and potentially interacting with basic objects. The focus of the project is on environment design and core movement mechanics rather than fully-fledged combat or quest systems.

<br><br>

Core Systems & Mechanics
<br><br>
Player Movement & Camera:

The player character is controlled via keyboard input.

A simple first-person or third-person camera system follows or orients relative to player input.

Physics & Collisions:

Utilizes Unity’s 3D physics components (Rigidbody, Colliders) to handle environmental collisions and gravity.

Ground detection prevents falling through meshes.

Shaders & Materials:

Shader assets (ShaderLab/CG) are used for visual enhancement of water, terrain, and objects.

Scene Design:

The main scene represents an old seaport with docks, terrain, and objects placed to create atmosphere.

<br><br>

How to Run Locally
<br><br>

Install Unity Editor — Use the recommended Unity version matching the project’s ProjectSettings (check ProjectSettings/ProjectVersion.txt).

Clone the repository:

git clone https://github.com/sumeyrakarsavran/3dGame_OldSeaPort.git


Open the project: Launch Unity Hub → Add the project directory → Open.

Open the main scene: Navigate to Assets/Scenes/ and open the primary scene.

Play: Press the Play button in the Unity Editor.

<br><br>

Controls
<br><br>

Action	Key
Move Forward	W
Move Backward	S
Strafe Left	A
Strafe Right	D
Jump	Space (if implemented)
Camera Look	Mouse Movement

Note: Controls may vary depending on the configured input system in Unity.

<br><br>

Future Improvements
<br><br>
✔ Add interactive NPCs and objects
<br>
✔ Expand seaport assets (ships, crates, water effects)
<br>
✔ Navigation waypoints and mission markers
<br>
✔ Audio ambience (waves, seagulls, footsteps)
<br>
✔ UI elements (map, inventory, objectives)

<br><br>

License
<br><br>
This project is open source and free to use. No explicit license file is included — attach an appropriate license (e.g., MIT) for clarity.
