# TPS-UE5

- Gameplay Description
 - Player: Third-person character with basic movement (walk, run, jump), aiming, and firing mechanics.
 - Enemies: Simple AI-controlled enemies with basic movement and attack patterns.
 - Objectives: Complete three levels with progressively increasing dificulty, focusing on specific programming challenges outlined below


## Level 1: Movement Basics
 ### - Player movement utilizes root motion or animation blendspace with proper physics interaction.
 - In this section, we expect seamless walking with default 3D person animations.
   
 ### - Implement collision detection and response for the player and environment.
 - In this section, we expect the player to interact with the environment. This interaction is touching the wall when close enough. This behavior can be implemented with hand ik.


## Level 2: Shooting Mechanics
 ### Integrate a basic health system with visual feedback.
 - Player’s health will be shown on UI with both text and health bar.
   
 ### Implement a projectile-based weapon system with accurate firing and hit detection.
 - Player will shoot a projectile. If a projectile is fired when aimed at an enemy, this projectile will lock on the enemy and follow him.
 
 ### Add enemy spawning with basic AI movement, pathfinding, and shooting.
 - Enemy will shoot us, follow us and move around.
 
 ### Create a scoring system that tracks enemy kills and displays it on the UI.
 - Enemy kills will be displayed on the UI.


## Level 3: Advanced Features
 ### Introduce environmental hazards and interactive elements requiring additional scripting.
 - There will be 2 different hazardous floors, one will slow down other one will damage us.
 - There will be 2 different interactive elements. One will be used to open and close door, the other one will be used to move some platform up and down.
   
### Implement basic inventory management for different weapons.
- Open inventory and drag and drop items to your character. There will be 2 different weapons (rifle and pistol) and 2 different body armors (one has 100 bonus health, other one has 200 bonus health).
- When one weapon is equipped, other weapon swaps back to inventory
- Equipped weapon should be placed in the hand.
- When one armor is equipped, other armor swaps back to inventory
- Equipped armor should be visible (by either changing character mesh, or mesh color) and player health should increase according to armor stat.
- Armor has health attribute only
