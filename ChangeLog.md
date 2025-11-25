Balance Patch: 1.0.1 "Re Bark"
----------------------------------------------
- Updated Plugins
- Changed Stay Reward Window (3 -> 6) Seconds

Initial Release: 1.0.0 "Show Dog"
----------------------------------------------
- Updated Unreal Engine (5.5)
- Updated some UI text

Beta Release: 0.3.0 "Looking Flexible"
----------------------------------------------
- Added Difficulty Description
- Updated UI Layout
- Improved Readability
- Added Difficulty slider to story mode select
- Added mechanism to hide difficulty slider when going back to menu
- Removed Level Regression from Very Easy difficulty
- Added Difficulty Setting Backend - Stored in Instance
- Added Difficulty check for Reward time
  - 0 -> 6 Seconds
  - 1 -> 5 Seconds
  - 2 -> 4 Seconds
  - 3 -> 3 Seconds
- Made Ajax not release while training stay if difficulty is easier or lower
- Added If Difficulty is less than 3 -> Random sit disables after sit training is complete
- If Difficulty is Easy or lower, Ajax now shows side view of sitting
- Lightly optimized NPC dog
- Revamped Fetch logic to improve/stabilize Ajax behavior
- Improved ButtonMessageUI Opening Sequence
- Updated Crosshair UI:
  - Now Includes first task
  - Is now hidden until prompted to do first task

Beta Release: 0.2.14 "July Jubilee"
----------------------------------------------
- Changed Case "HAL/PlatformFilemanager.h" -> "HAL/PlatformFileManager.h"
- Updated size of DefaultEngine.ini
  - Now Includes Mac Build Info post config Reset
- Updated Plugins
- DP-9: Fixed Issue where button text would appear without proper dialog ready
- Updated configuration settings, character blueprint, UI assets, and hardware collector code
- Added New Current Task UI

Beta Release: 0.2.13 "Mellowing the Yellow"
----------------------------------------------
- Added Game Version to title screen
- Now retrieving Project Data for game initialization and hardware data from .info file
- Code Cleanup
- Added Controller input detection to adjust UI elements
- Added Logic for UI Elements to switch to showing Gamepad Commands
- Moved initialization info to newly included package file DogPark.info
- Updated Plugins
- Added Splash for Mac
- Improved Controller compatibility
- Enabled TSR
- Included AppLocalPrerequisites
- Set Mac Metal to minimum
- Set Mac EditorDefaultArchitecture & DefaultArchitecture to Universal
- Resolved Issue with Intel Machines -> Removed Config
- Now setting DogPark.info with the Project Settings
  - Stored in DP_Instance
  - Used for sourcing Title and Version for Hardware Collector
- Enabled Metahumans Plugin
- Improved and fixed Game Initializer

Beta Release: 0.2.12 "Don't Forget These!"
----------------------------------------------
- Implemented Flip Rewards
- Added Flip Timer
- Added New Game Initializer
- Code Cleanup

Beta Release: 0.2.11 "Looking Ready for QA"
----------------------------------------------
- Added mac Versioning for compile and signing
- Enabled Pak Signing
- Added SaveGame Persistent Data
- Fixed Settings Presets not working properly
- Revamped Progression of Dialogue
- Added Volume slider to Settings
- Overall UI improvements
- Cleaned up Blueprints
- Added Backup timer for Ajax to Sit
- Disabled Sit Command for Sit level 1
- Fixed Validation Bugs
- Forcing Windowed mode on start
- Started working on Master Volume control
- Added VFX Quality Setting to Shadow Quality Setting
- Added Sound Classes
- Fixed bundle prefix
- Added custom tick logic to rings
- Added Logic outline for random flip
- Added better logic to: Player Wrench, Ajax Anim, Ajax Dog, Give Treat Comp, StayDistWheel, Button Message UI

Beta Release: 0.2.10 "Looking Fast"
----------------------------------------------
- Integrated Flags for return level up
- Performance Enhancements - Added LODHider -> Removes Attached Elements based on Quality Settings.
- Added Checks for Hold Fetch object to make sure there is only one.
- Reduced number of dogs on menu scene.
- Added Call Button - May have ajax look at player or start following
- Enabled More Comprehensive Encryption
- Removed FPS from distribution Builds
- Added Regression Message
- Improved Delay Timers for Clear Message
- Blueprint Cleanup
- Fixed Compile Crash
- Changed Non-Shipping Packaging settings

Beta Release: 0.2.9 "Looking Coached"
----------------------------------------------
- Fixed reward bug with Ajax sitting; overhauled tutorial dialogue logic.
- Adjusted fountain volume; added fireflies and improved water terrain.
- Integrated level cap bump to 4; no dialogue for Stay level 2.
- Checks and dialogues for Come/Return training levels.
- Modularized fetch mechanic; faster jump and treat animations.
- Updated UI animations and CineCamera; cleaned blueprints and ButtonUI.
- Added Mac build icon and re-baked all levels.

Beta Release: 0.2.8 "May-be its May-belline"
-----------------------------------------------
- Updated to Unreal 5.4.1
- Menu Updates & Animations
- Map Updates
- Game Performance Optimizations
- Game Development Environment Fixes
- Reworked Reward Logic
- Many Bug Fixes
- Plugins Updated

Beta Release: 0.2.7 "Looking at Rings"
------------------------------------------
- Menu Updates
- New Radial Menu
- Game Performance Optimizations
- Overhauled Dog Training
- Added Training Regression
- Dev Environment Updates
- Plugins Updated
- Leash Rebound Physics
- Added Development Menu functionality

Beta Release: 0.2.6 "Looking Around"
------------------------------------------
- Menu Updates
- *Many* Bug Fixes
- Ajax Behavior Refined and Modulated
- Improved Dialogue with NPCs
- Map Optimizations
- Map Updates
- Added Dog Skills
- Added Additional Modularity to individual behavior
- Added Treat/Reward System
- Added Player Crouch
- Systems Optimizations
- Refined Command System
- Rebuilt Navigation
- Added Animations

Beta Release: 0.2.5 "Looking 'Well Rounded'"
------------------------------------------
- Added Dynamic Stress System
- Added Additional NPC Behaviors
- Added Treat Throwing
- Added Custom Loading screens
- Added and Fleshed-Out 'Move further away' dialogue
- Fixed Some AI issues causing npcs to get stuck on each other
- Fixed Backend Engine Issues related to NPC Characters
- Fixed Garbage Collection issues in Memory for Dialogue Plugin Events

Beta Release: 0.2.4 "Looking 'fetching'"
------------------------------------------
- Added Fetch Mini-game
- Added Wave 2 of Ajax Animations
- Added Quality Presets
- Added Loading screens
- Added Remaining Dialogue options
- Added Objective Marker Arrow
- Updated Game-modes
- Updated Widgets
- Updated Plugins

Beta Release: 0.2.3 "Looking Spiffy"
------------------------
-Updated to Unreal 5.3.2
- UI Improvements
- Dog AI & Behavior
- Leash & Command System
- Cinematic Main Menu
- Stylized Materials
- Fleshed Out and Improved Dialogue
- Additional Controller Functionality
- Menu Functionality is more clear
- Etc... See dev branch

Beta Release: 0.2.2 "The Big One"
------------------------
- UI Improvements
- Dog AI & Behavior
- AI Improvements
- Menu Implementation
- Game-mode implementation
- Map separation
- Controller Functionality
- Dog Stress System
- Soccer Mini-Game
- Etc... See dev branch

Beta Release 0.2.1
-------------------------
- Added Animations
- Added State Machine
- Improved Dialogue backend
- Improved Settings Menu
- Updated Plugins
- Updated UI
- Updated Project Files

Release 0.2.0 Beta
-----------------------------
- Preview Build For AI Education Conference