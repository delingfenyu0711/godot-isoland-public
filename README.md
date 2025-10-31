# Godot Isoland

Project Overview

This repository hosts a public prototype of Isoland—a game developed with Godot Engine 4+ centered around island exploration and story-driven interactions. 

The core assets included focus on narrative foundations, with dialogue files that establish character backstories and key plot points:

- A central character arc involving an elderly figure waiting for a boat ticket
- References to a spouse’s research on time machines and maritime journeys
- Quest-like interactions (e.g., requesting help to find a mailbox key)
- Resolution moments (e.g., expressions of gratitude after receiving the ticket)

The project serves as a starting point for expanding the game’s story, adding gameplay mechanics, or refining the dialogue system.


---

Directory Structure

Path
Description
Assert/Text/
Root directory for all in-game text resources
Assert/Text/dialogA.txt
Primary dialogue file: Contains character backstories, relationship details, and help requests
Assert/Text/dialogB.txt
Secondary dialogue file: Short, context-specific lines (e.g., post-ticket gratitude)
.gitignore
Git version control exclusion list (Godot auto-generated files, Mono assets, etc.)


---

Prerequisites

Before running or modifying the project, ensure you have the following installed:

- Godot Engine 4.0+: Download from the official Godot website
- (Optional) Mono Runtime: Required only if you plan to add C# scripts (included with Godot’s "Mono" release)
- A text editor (e.g., VS Code, Sublime Text) for modifying dialogue files


---

Installation & Setup

1. Clone the Repository

Open your terminal and run:
```
git clone https://github.com/delingfenyu0711/godot-isoland-public.git
```
2. Open the Project in Godot

1. Launch Godot Engine
2. Click Import > Navigate to the cloned godot-isoland-public folder
3. Select the project.godot file (auto-detected by Godot)
4. Click Import & Edit to load the project

3. Run the Prototype

Click the Play button (▶️) in the top-right corner of the Godot editor to test the current build.
