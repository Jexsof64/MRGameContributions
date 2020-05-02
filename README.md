# MRGameContributions

This README provides sectioned explanations of how to incorporate various components and assets from things that I have worked on into the group repository for "Inkdye".

<u1><b>BEFORE ANYTHING ELSE</u1><p>
It is recommended to simply downoad this repository to a folder and handle the contents of it on a case-by-case basis. Trying to simply merge this repository with the group's or any other repository that has contents in it may have unknown and damaging consequences.</b>

<u1><b>Main Menu</b></u1><p>
The Main Menu can be found as a scene within "Assets/Scenes" as "Main Menu". Simply dragging this scene into the respective Scenes folder of the repository should suffice, however a change will need to occur within the accompanying "MainMenu" script located at "Assets/Scripts". Line 10 has a literal reference to the scene to be loaded, set by default to "SampleScene" - to make this work for the game you will probably need to change the scene to be loaded to the EXACT name of the correct or desired one.

<u1><b>Player HUD (Heads-Up Display)</b></u1><p>
The Player HUD is located in the 'Canvas (Player HUD)' of the "SampleScene", located in "Assets/Scenes". This set of UI - a health bar and Mag-Ink bar - makes use of the "Player" and "StatBar" scripts within "Assets/Scripts" and should not pose a problem once they are dropped into the corresponding "Scripts" folder.

The components of the Player HUD can be found in the Canvas of the "UserInterface" scene of "Assets/Scenes".

<u1><b>Leveling System</b></u1><p>
The leveling system is comprised of the "Player" and "Level" scripts located in "Assets/Scripts" and within Unity is attached to the 'Player' object in the Hierarchy within "SampleScene" of "Assets/Scenes".

<u1><b>Melee Enemy (So Far)<b></u1><p>
The Melee Enemy is composed of the Melee Enemy Model, 'Canvas (Enemy UI)', and has the "MeleeEnemy" script attached to it. Enemy UI uses the "Billboard" scripts to have the UI face the Player. Since I was unable to manage to get animations to work fully with the model it is recommended to copy or replicate the Hierarchy Components on a different GameObject to retain functionality.

UI for enemies in general should be in the "UserInterface" scene.
