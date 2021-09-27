# Multi-COD .cfg menu (RAW)

Multi-COD .cfg menu

**Features:** 

- Fully customisable
- Simple default controls (1 button for executing, 2 buttons to move and open, 1 button to go back/close)
- Big amount of menus and options can be loaded (currently tested and implemented 11 menus and 12 options per menu)

Supported games:
~~~~
- Call of Duty 4 (Singleplayer & Multiplayer) [Original, cod4x]
- Call of Duty: Modern Warfare 2 [IW4x, MW2:Reimagined, Modded singleplayer with console unlocked]
~~~~

Default controls:

[ J ] - opens the menu / goes UP (Menu needs to be preloaded into the game via exec)

[ K ] - goes DOWN

[ V ] - goes back / closes menu (Also melees)

[ SPACE ] - selects a menu/option (Also jumps/changes stance)

Current bugs:
1. Does not properly work on these resolutions
 
- 640x480
- 800x600

A fix would be to change the game resolution or reduce the amount of symbols in menu.

2. In some games after executing the menu line ''Unknown cmd updategameprofile'' will break the menu structure.
No fix for now. (Maybe wait after drawing the menu and then open menu?)
