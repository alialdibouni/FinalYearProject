# Ground Zero 

# Patch Notes

### Version 0.0.6

(NOTE: This Build only has MP_Map_001 packaged, any attempt to load up the other maps or modes will result in a crash!)

------
#### Additions
------
#### Weapon Changes
- Assault Rifle Buffed
- Explosion Radius Expanded
- Pistol Properties Changed
- Sniper Rifle Properties Changed
- Grenade Launcher Explodes on Impact

#### Gameplay Changes
- Added Health Pack
- Changes to Player's Tag. Visibility hidden after 2500 units + hides behind wall. 

#### UI Changes
- Added Killfeed
- Added Hit Markers
- Changes to "TEAM WIN" UI (Button enabled after 3 seconds)
- Changes to Settings Menu (Invert Y Axis + Mouse Sensitivity)
- Added Health UI for when player picks up Health Pack
- Added Bloody Screen effect when getting hit by player
- Damage Indicators
- Indication that you killed a player

#### Other Changes
- Hold Right Click for ADS
- Preview Weapon for each class when selecting a team and class
- Damage Values when hitting Opponents
- Added Credits to Main Menu

#### Fixed Bugs
-----
- On start, when player picks up health pack, server shows it picked up but not for client. After respawn time, server calibrates pickup and works as normal
- Damage value for AR, Pistol and Sniper Works. Grenade Launcher and RPG damage displayed as 0.

#### Known Bugs
-----
- If Player is in Character Select and Changes Team, it changes team but doesn't kill them or switch them to the correct team (If Lobby Team)
- When gun hits 0, gun sound stops as well as animation
- Sometimes Character Station doesn't allow player to change classes (Might switch back to old system of switching classes)
- When searching for games. People hosting in Europe, Other Region can't find game
- Mouse settings don't work in Main Menu
- if player gets double kill, kill medal overlays ontop of each other
- Damage Indicator shows up after the second shot. Not the first. (Affects client not server).
- When zoomed with Sniper, Damage value moves (since relative to screen).
------
## Version 0.0.5

(NOTE: This Build only has MP_Map_001 packaged, any attempt to load up the other maps or modes will result in a crash!)

#### Additions
------
- Added a Settings Menu
- Balanced Weapons
- Changed Walk Speed and Animation to Jog Animation and Speed
- Changes to Class Selection (Can change class in menu as well as at Character Station)
- Added Jog Animations
- Added Shooting Animations
- Fixed Aim Offset (For looking up)

#### Fixed Bugs
-----
- If Player used Autofire weapon, while holding left click, when the ammo hits 0, the weapon keeps shooting
- Player can fire while reloading
- Player Camera and Gun clipping throuhg walls (First person)
- When player switches class while scoped in at character station, the scope remains
- When the player is dead, the player can scope in

#### Known Bugs
-----
- When the gun hits 0, gun sound stops
- Sometimes character station doesn't allow player to change class
- If player is in Character Station and changes team, it changes team but doesn't kill or teleport to the corresponding player start. 						

------

## Version 0.0.4

#### Additions
------
- Added random coin spawning (Might use for Potential Game Mode)
- Added Sprint Direction to see the direction of player
- Added Weapon Switching Sounds
- Added Scope Functionality
- Added Sniper Rifle to Recon Class
- Added Character Station for changing Class in game

#### Known Bugs
-----
- When in Menu (in game), player can shoot whilst in menu 								
- Hitscan weapon and shoot spawned coin											
- When player is Dead, Player can Scope in										
- When player switches class while scoped in, the scope remains	

------
## Version 0.0.3

#### Additions
------
- Added Game mod and map name Displaying in game on a Board
- Added Scoring to when a player kills an enemy
- When changing teams, player gets killed and then is moved to other team
- Changed where when selecting a Class at the start of the game, player cannot change it in game (Subject to be Improved in later version)

#### Fixed Bugs
------
- Player can shoot AR While Dead
- When Client joins server, Pick a team widget doesn't display
- Grenade Launcher Projectile explodes in 2 places on Client and Server
- Scoreboard not showing in Client
- Shotgun particles only showing 2 impact bullets 
- Shotgun shooting incorrect number of bullets

#### Known Bugs
-----
- When in Menu (In Game) Player can shoot whilst in menu

------

## Version 0.0.2.1

* Implemented Spawn Protection
------
## Version 0.0.2

* Implemented Class Selection
* Character Visuals changed based on Class
* Weapon Optimization and Expansion
* Added Grenade Launcher
* Added Grenade Launcher Projectiles
* Changes to Host Game Menu
* Changes to Singleplayer Menu
* Added MultiPlayer Co-Op and SinglePlayer Maps (Placeholder)

------

## Version 0.0.1

* Basic Character Movement
* Sprint and Weapon Implementation
* Health and Damage Implementation
* Player Name Tag above Player Head
* Ability to have Secondary Weapon with Switching
* Added Projectiles (Bullets)
* Death Ragdoll and Respawn System
* Created Main Menu
* Creation of Lobby and Listen Servers
* Steam Plug Integration
