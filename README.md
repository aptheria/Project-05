# Project 5
## Implementation / Features you added
Controls:
* Player can be controlled by keyboard and mouse, WASD to move and mouse to move camera
* Player shoots by holding or clicking left click, the longer the player shoots the more recoil and bullet spray increases, shooting is also loud
* Player can hold right click to aim allowing for quieter movement and better accuracy at the cost of moving slower
* Player can hold left shift to sprint allowing for faster movement at the cost of being louder and less accurate
* Player can press Q to open and close a diegetic minimap to see the enemy positions and maze, but opening the minimap makes noise and requires the player to look down to read it
* The game automatically locks the cursor but the U key can unlock and the L key can relock the cursor
* The Escape key takes the player to the main menu when in a level

UI: 
* Health bar that blinks based on how low the player's health is 
* Stamina bar that changes color based on stamina level, if the player completely runs out of stamina they have to wait until it recharges to 30% before they can sprint
* Difficulty level changes color from green to red depending on Difficulty level
* Remaining enemies / Starting enemies ratio displayed, when remaining enemies equals zero the level is completed and exit point spawns
* Score is displayed, score is increased by killing enemies, score increase from killing enemies is scaled to difficulty 

Difficulty: 
* Every time the player completes a level the difficulty increases
* As difficulty increases: levels get darker, skybox tints red, reverb increases, enemies can hear the player better
* Difficulty ratings past 10 make only very minimal changes. but still give more score on enemy kill

Enemies: 
* Enemies start chasing the player when they can see the player (player is close enough with no walls between and within 90 degrees of enemy eye) 
* Enemies face the player when player noise exceeds a certain threshold
* Enemies have 3D models, lights, post processing, particle systems, and sounds
* Enemies have intresting death animations
* Flamethrower enemy has more HP and damage but is slower and has a shorter range
* Laser enemy is flying and longer range but has less HP

Other features: 
* Functional Main menu screen and Game over screen
* Gun moves with recoil, plays gunshot sound, shows muzzle flash on shot, draws bullet trail, plays bullet fly by sound, plays impact particles and noise
* Proceduraly generated maze
* Black hole object that takes the player to the next level, distortion particles, motion blur vibration, when the player gets close they get pulled in, also distorts camera and audio based on distance
* Lit Fog on tiles
* Overall great deal of polish

## References
Asset Store Imports:
* Shaders: https://assetstore.unity.com/packages/vfx/shaders/ultimate-10-shaders-168611
* Fire VFX: https://assetstore.unity.com/packages/vfx/particles/fire-explosions/free-fire-vfx-266227#description
* Particle Shaders: https://assetstore.unity.com/packages/vfx/shaders/particle-shaders-vol-1-35069
* Enemy 3D models: https://assetstore.unity.com/packages/3d/characters/robots/sci-fi-drones-90326#content 
* Maze Materials: https://assetstore.unity.com/packages/2d/textures-materials/metals/yughues-free-metal-materials-12949 
* Gun VFX: https://assetstore.unity.com/packages/vfx/particles/war-fx-5669 
* Skybox: https://assetstore.unity.com/packages/2d/textures-materials/sky/allsky-free-10-sky-skybox-set-146014 
* Player Gun 3D Model: https://assetstore.unity.com/packages/3d/props/guns/sci-fi-gun-light-87916 

Sounds:
* https://freesound.org/people/Aptheria/?downloaded_sounds=1%23sounds 

## Future Development
Better organization and optimization would be necessary but more player abilities and more enemy types.

## Created by
Andrew Theriault