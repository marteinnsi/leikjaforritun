# Vega’s Adventure Game Design Document
© 2023 Marteinn S.













 

### Game Design


#### Summary
Vega’s Adventure is a 3D platformer inspired by classic 32-bit era games. Players take on the role of Vega who must complete all levels on the four homeworlds and defeat the evil sorceress, freeing his species in the process.
#### Gameplay
You play as Vega, the beacon of light. He must maneuver his way around various obstacles around the four homeworlds. Each homeworld has various portals that lead the player to the levels of that homeworld. Some portals are locked and can only be unlocked by satisfying certain conditions in other levels.Once he has completed every level in a homeworld, he can repair his ship and progress to the next homeworld. During each flight to a new homeworld, he will have to defeat a boss enemy to complete his flight. His ultimate goal is to free all of his allies, and optionally to collect all the gems and in the end, progressing to the homeworld located in the midnight zone and defeating the evil sorceress which imprisoned his kind, once and for all. 

#### Mindset
Playing as Vega, players should feel like the hero. They are powerful and adventurous throughout their adventure but must still face various challenges. The difficulty level is not too high but enough to put your skills to the test. The main challenge comes from the platforming nature of the game, allowing players to cross levels in creative ways

### Technical
#### Screens
Title Screen
  - Options


Game
  - Level overview
  - Health indicator
  - Extra lives indicator


End Credits

### Controls
Vega’s Adventure is designed to be played with a controller but keyboard controls will be available for those who prefer keyboards or don’t have access to a controller. In addition to horizontal mobility via the joystick, players can jump and use a ranged and melee attack. Vega can also activate his glider while in mid-air by pressing the jump button a second time. Interactions with in-game objects are intuitive and straightforward, such as breaking pots and boxes with melee or ranged attacks, pushing levers by walking into them, and pressing buttons

### Mechanics
Vega’s ranged attack will be reflected by certain surfaces. To achieve this, a script will be used to change the projectile’s rotation accordingly. This mechanic allows for some interesting design choices in levels which might for example require Vega to hit a button by bouncing the projectile off one of those surfaces

Vega’s glider ability allows him to cross greater gaps between platforms and allow for much more creativity in the level design. In order to glide, he must simply press the jump button a second time after jumping. This can for example be used to hide certain collectibles or other objectives in places that might not be obviously accessible to the player

Vega has a limited number of lives. If he falls into the void or loses all of his hitpoints, he dies and respawns at a checkpoint in the level, or the beginning if no checkpoint is present or reached. He can collect more lives by collecting alien artifacts hidden throughout the levels, each giving him one extra life. If he loses all of his lives, he must start his adventure over
 












### Graphics
#### Style Attributes
Vega’s Adventure has a PlayStation 1 inspired visual style including pointy low-polygon models and vibrant colors. The game is very retro looking and meant to recreate the look and feel of the 32-bit era games

Players will be given very limited visual feedback as the gameplay is almost self-explanatory. A health and extra live indicator will be present in a HUD but no other text will be on the screen except during level transitions, on portals or in dialogue

The look and feel of each homeworld is based on how close they are to the “dark side” of the planet. Starting with a sunrise theme and progressing towards a midnight feel. Soundtracks and level design will reflect this.

### Sounds/Music
#### Style Attributes
Vega’s Adventure will feature a rhythmic soundtrack heavily inspired by Stewart Copelands work on the Spyro series. Each homeworld will feature a main theme and certain levels within will feature unique a track based on the theme of the homeworld

Sound Effects will be simplistic but clear as was common on the PS1. Vega’s Adventure goes for a cartoony style when it comes to sound effects

#### Music Needed
A track for every homeworld, each with a different feel inspired by the four seasons
A soundtrack for the bossfight after each homeworld is completed, inspired by the homeworld that comes after it
A few basic tracks for key levels, other levels may re-use tracks
Happy ending
