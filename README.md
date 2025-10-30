godot-isoland-public​
Project Introduction​
This project is a game-related project developed based on the Godot engine (judging from the file structure and content, it may be related to island exploration and plot interaction). The project contains in-game resources such as dialogue texts. Through the dialogue content, we can get a glimpse of the background stories of the characters in the game. For example, there is an old man waiting for a boat ticket, mentioning his wife researching time machines and going to sea, etc., which builds the basic narrative elements for the game.​
Directory Structure Explanation​
Assert/Text/: Stores text resources in the game​
dialogA.txt: Contains the main dialogue content of the characters, involving the character's background, description of his wife, and requests for help (finding the mailbox key), etc.​
dialogB.txt: A short dialogue showing the character's thanks after receiving the boat ticket​
Development Instructions​
This project is developed based on Godot 4+ engine, and relevant ignore configurations have been set in .gitignore​
Text resources can be expanded or modified according to the development of the game plot to enrich character stories and game content​
If using Mono for development, related directories such as .mono/ have been ignored to avoid including unnecessary files in version control​
Usage Methods​
Ensure that Godot 4+ engine is installed​
Clone this project to the local​
Open the project through the Godot engine to develop or run​
Notes​
When submitting code, Git will automatically ignore the files specified in .gitignore, no manual processing is required​
Please keep the encoding format of text resources consistent to avoid garbled characters​
If you need to export the game, relevant configuration files (such as export.cfg) need to be managed by yourself, and such files are ignored by default in this project
