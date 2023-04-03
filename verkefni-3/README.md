# Vega’s Adventure - Game Design Document
© 2023 Marteinn S.
  
### Game Design


#### Summary
Vega’s Adventure is a 3D platformer inspired by classic 32-bit era games. Players take on the role of Vega who must complete all levels on the four homeworlds and defeat the evil sorceress, freeing his species in the process.

#### Gameplay
You play as Vega, the beacon of light. He must maneuver his way around various obstacles around the four homeworlds. Each homeworld has various portals that lead the player to the levels of that homeworld. Some portals are locked and can only be unlocked by satisfying certain conditions in other levels.Once he has completed every level in a homeworld, he can repair his ship and progress to the next homeworld. During each flight to a new homeworld, he will have to defeat a boss enemy to complete his flight. His ultimate goal is to free all of his allies, and optionally to collect all the gems and in the end, progressing to the homeworld located in the midnight zone and defeating the evil sorceress which imprisoned his kind, once and for all. 

#### Mindset
Playing as Vega, players should feel like the hero. They are powerful and adventurous throughout their adventure but must still face various challenges. The difficulty level is not too high but enough to put your skills to the test. The main challenge comes from the platforming nature of the game, allowing players to cross levels in creative ways.


### World and level design
All four homeworlds are based on a specific time of day correlating with how far into the dark side of the planet they are. The first homeworld is sunrise, the next mid-day, then evening and lastly, midnight. As it gets darker and darker and you get closer to the sorceress's lair, the theme starts to shift and levels and enemies get tougher and tougher to beat. 




#### Story
In the peaceful world of Serenity was the peaceful planet Zoroxia. The Zorons had lived there peacefully for over 200 years and had designed technology which allowed them to live in harmony with nature. As peace reigned grew a secret group led by the evil sorceress. Their master plan was to imprison all the Zorons and take over the planet Zoroxia. As the sorceresse’s coup went down, a Zoron named Vega returned from his years-long mission to find his species imprisoned and their very rare eggs guarded and hidden all over the world. He knew that it was his duty to defeat the evil sorceress and free all of the Zorons from captivity. On his mission, he encounters a variety of enemies, rescues his friends, and finally, defeats the evil sorceress in her lair deep down in the dark side of Zoroxia. 



### Technical  
#### Screens:  
Title Screen  
 - Options  
  
Game  
 - Level overview
 - Health indicator
 - Extra lives indicator
 - End Credits
 - Game Over
 - Homeworld to level transition screen
 - Level to homeworld transition screen


### Controls
Vega’s Adventure is designed to be played with a controller but keyboard controls will be available for those who prefer keyboards or don’t have access to a controller. In addition to horizontal mobility via the joystick, players can jump and use a ranged and melee attack. Vega can also activate his glider while in mid-air by pressing the jump button a second time. Interactions with in-game objects are intuitive and straightforward, such as breaking pots and boxes with melee or ranged attacks, pushing levers by walking into them, and pressing buttons

### Mechanics
Vega’s ranged attack will be reflected by certain surfaces. To achieve this, a script will be used to change the projectile’s rotation accordingly. This mechanic allows for some interesting design choices in levels which might for example require Vega to hit a button by bouncing the projectile off one of those surfaces

Vega’s glider ability allows him to cross greater gaps between platforms and allow for much more creativity in the level design. In order to glide, he must simply press the jump button a second time after jumping. This can for example be used to hide certain collectibles or other objectives in places that might not be obviously accessible to the player

Vega has a limited number of lives. If he falls into the void or loses all of his hitpoints, he dies and respawns at a checkpoint in the level, or the beginning if no checkpoint is present or reached. He can collect more lives by collecting alien artifacts hidden throughout the levels, each giving him one extra life. If he loses all of his lives, he must start his adventure over
 
Vega also has limited health. At the start of the game he has four hit points and all attacks will only remove a single point from his health with a few exceptions (bosses perhaps for example).. 

Vega can activate power-ups which grant him some sort of enhancement or new ability. For example, a higher jump, a tougher melee attack or a new ranged attack. These are activated by walking through small “upgrade gates” placed in some levels. 

Vega can free his allies by completing levels and finding Zoron eggs hidden all over the world by the sorceress’s goons. To rescue eggs, you have to find them and walk up to them, and they will be sent back home.















### Characters

#### Vega
The titular main character of the game, Vega is the adventurous Zoron who must save his species from the evil sorceress. 

#### Jaxx
A Zoron Vega encounters in the third level of the main world. He returns with him to the main world after completing the level, and helps Vega fix the spaceship after he completes all the levels. He is seen attempting to fend off the sorceress’s goons in his level.

#### Orion
A Zoron Vega encounters in the bossfight after completing the first main world. After being freed from Sir Bankroll’s captivity when Vega bribes Bankroll to release him he is seen flying in circles over the arena and helping Vega by dropping him powerups that allow his melee attacks to knock enemies back a far distance. This enables Vega to hit the boss down into the lava surrounding the platform the fight takes place on. After successfully doing this 4 times, the boss finally drowns in the lava, allowing Vega to continue his flight to the next homeworld.

#### Sir Bankroll
One of the few third parties in this game, Sir Bankroll is an Arcto, a bear-like creature which has been hired by the sorceress to keep Orion in captivity in the first main world. After taking a bribe from Vega (if he can afford it), he lets his prisoner go and travels to the next homeworld. This process repeats itself for every homeworld, and is a way to have Vega be introduced to and make friends with different characters. They all help in some way after being freed.

#### Gartus
One of the sorceress’s goons, turned into a large round monster with two legs. He is the first boss which the player meets, right after starting his flight to the second homeworld. Vega’s ship is forced to land on his island boss platform, and as a result Vega must defeat him. To begin with, he uses a relatively fast charging attack to try and hit the player. After being hit into the lava once, he alternates between his charging attack and backing up and spewing flames which travel fast over the ground, in Vega’s direction. He must jump at the right time to avoid being hit by these flames. After being hit an additional second time, he adds a new attack to the rotation. He backs up a short distance from the player if too close and jumps high in the air, then coming down at incredible speed, causing a shockwave to move down the platforms. If the player does not jump right before Gartus hits the ground, he is stunned and knocked back slightly. Gartus will use one of his other attacks at random a very short time after landing, almost certainly hitting the player if they are stunned.  

### Graphics
#### Style Attributes
Vega’s Adventure has a PlayStation 1 inspired visual style including pointy low-polygon models and vibrant colors. The game is very retro looking and meant to recreate the look and feel of the 32-bit era games

Players will be given very limited visual feedback as the gameplay is almost self-explanatory. A health and extra live indicator will be present in a HUD but no other text will be on the screen except during level transitions, on portals or in dialogue

The look and feel of each homeworld is based on how close they are to the “dark side” of the planet. Starting with a sunrise theme and progressing towards a midnight feel. Soundtracks and level design will reflect this.


### Sounds/Music
#### Style Attributes
Vega’s Adventure will feature a rhythmic soundtrack heavily inspired by Stewart Copelands work on the Spyro series. Each homeworld will feature a main theme and certain levels within will feature unique a track based on the theme of the homeworld

Sound Effects will be simplistic but clear as was common on the PS1. Vega’s Adventure goes for a cartoony style when it comes to sound effects, very vibrant just like the color scheme. 

#### Music Needed
A track for every homeworld, each with a different feel inspired by the four seasons
A soundtrack for the bossfight after each homeworld is completed, inspired by the homeworld that comes after it
A few basic tracks for key levels, other levels may re-use tracks
Happy ending
