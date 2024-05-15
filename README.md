# Unity-Group-Project
Repo containing a unity project made as part of a uni module.
Download the Windows Build folder to play the game, or download the TGP_GroupProject folder to look at the source code.

During this project, I worked on a number of things. I started off on creating the bomb system where the player could place and throw bombs that would then explode after a set amount of time. 

I then did a bit of level design using the Unity assets that we had sourced. I worked on designing level 2 and 3. I designed these levels by placing assets in the level to create the level path that I thought looked good. I then implemented the AI that a team-member had been working on so that the level would have patrolling enemies. I also worked on a PVP level with obstacles for the players to hide behind, but this level never made it into the game.

After this, I created a collectable system which allows the players to walk into specific objects with the "Collectable" tag to acquire more ammo. Following this, I implemented the ammo system so that the player could only place the specific bombs if they had any.

I then created a script that would allow the vehicles placed in the level to be blown up. This script checks how much health the vehicles have, and if it reaches 0, the vehicle asset will be replaced with an exploded version.

Finally, I added some polish and QA to the game by implementing enemy death when their health reaches 0, creating an audio manager that could play background music, and adding sound effects to the final boss.
