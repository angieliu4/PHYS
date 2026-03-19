## Game Overview

### Title
DREAMSURF (working title)

### Concept
* A fast-paced FPS inspired by ULTRAKILL and ENA: Dream BBQ - platform and shoot your way through levels full of mixed media enemies
* You play as a bounty hunter racing through people's dreams to kill your target

### Targeted Aesthetics
* MDA Aesthetics: Fantasy, Challenge

### Game Flow
* Progress through levels, getting instrutions / tutorial from a character on a radio on your HUD, as well as updates on your current objective, as well as possibly little quips on actions the player takes
* Each level can be replayed for a better rating
  
### Player Controls
* Mouse 1 - shoot
* Mouse Wheel - switch weapons (number keys also work)
* Mouse rotates camera / player
* WASD - movement
* Shift - dash
* Space - jump
  
## Mechanics

### Rules
* Stamina depletes after dashing twice mid-air
* Different cooldown depending on weapon
* Enemies drop health
* Killing enemies in quick succesion fills energy meter, used to activate bullet-time ability

### Physics
* Gravity applies to most entities, however some enemies are flying and are not affected by gravity
* Falling off the world will take you down to 10 health and teleport you to the last platform you were standing on (unless your health is below 10, in which case you die and restart at the last checkpoint

### Movement
* Most enemies have very simple pathfinding logic, however some will try to stay far away from you and shoot projectiles at you, although they are easy to catch up to because you are significantly faster

### Actions + Abilities
* Grapple
* Bullet-time ability

### States
Briefly describe conditions for losing, winning, advancing or leveling-up, and character states, like invisible, running, sliding, etc.

### Core Game Loop
* Die many times while playing each level, improving more and more each time
* Complete the level and move on to the next more difficult level
* Unlock more weapons, enemies, and movement tech the further in the progression you are
* Likely one boss per level at the end of the level, or similarly a particularly difficult wave of enemies

### Level Design
* Reach the end of the level after fighting enemies and platforming to the exit where you likely will fight a boss to advance to the next level
## Game World

### Setting
* Surreal dreamlike environments
  
### Characters + Game Objects
* Player character
* Enemies
* Animated character portrait at top of HUD for dialogue
* Boss enemies (possibly with voice lines?)
### Art Style
* 2D stylized enemies (and collectibles?)
* Pixelated


### Sounds + Music
* Fast paced adaptive music based on if you're fighting enemies or not
  
### Menus
* Start menu
* Game over screen (restart)
* Pause menu w/ settings
* Level select

  
### Heads-up Display (HUD)
* Health bar
* Energy bar
* Collected items
* Timer
* Score / rank
* Player Character portrait
  
## Project Management
### Release Date
List a possible release date for your game and milestones for the project (dates when specific parts of the project are due).
### Dev Log
Keep track of your progress by keeping a brief journal of updates throughout the game development process. Add screenshots and/or a bulleted list of changes and additions made to the game.

