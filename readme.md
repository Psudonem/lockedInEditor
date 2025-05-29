# What is this?

A little engine for quickly coming up with game ideas

# NOTICE

This code base is very unoragnized. I am working on organizing it now.

All of this is very, very WIP. I could axe all of this tomorrow and rewrite it in a whole different manner. The mission shall remain the same.

# Why make this?

- to quickly come up with ideas
- to quickly test ideas
- and to provide a bunch of stuff prototype assets that can be used with a bigger, better engine

# Phases

### Phase 1 (current phase)
- DONE ~~let the user save and load their work ~~
- DONE ~~Let the user edit multiple maps~~
- DONE ~~Let the user name each map~~
- DONE ~~let the user copy and paste tiles~~
- DONE ~~decide if i want to add color or not~~
- DONE ~~add names to each tile~~
- DONE ~~multiple maps in one file (tbh not hard, but not at the top of the list)~~
- IN PROGRESS: mouse over the map location and see a speech bubble pop up with your cursor (if there is one)
- tile object settings
    - object type 
        (player, wall, decor, walker, hostile)
        - player - the one the player controls
        - wall - impassable object that player, and objects cannot go through
        - decor - basically something that is in the background that the player can walk on top of. Can be an npc you walk through, or some sort of background decor
        - hostile - will try to kill the player.. somehow

        - gravity effected (yes/no) sets if effected by gravity in preview modes.
- mouse over tile in map and see the details in a preview window


## Phase 1.5 - Code Restructure

- Restructrure the code to make it more readable
- Documentation



### Phase 2
- **Establish Client-server relationship**
    - server and client side saving and loading of project data, good for building expansion windows.
- Tile editor QOL Changes:
    - ms paint style color selction for tile editor
    - fill tool for tile editor
    - straight line tool for tile editor
    - fit 64 tiles in tile preview.. or make the preview tab scroll somehow
    - remove all those unused buttons

- Tile New Settings
    - set what the player sprite is
    - "door" object, to teleport player to another room

- Map Editor
    - have tile placing mode, message placing mode. Remove middle mouse button for placing messages
    - let the user use middle mouse to scroll through tiles
    
- New Screen Areas
    - add screen area for editing monsters/beasts (name, HP, attack points)
    - scrolling the map. currently the maps are 90x90 tiles, but the user can't scroll them yet. Add a way to pan the camera and lay more tiles.
- let the user click on tiles in the tile preview window for editing


- let the user use middle mouse to select sections of the map to copy, paste and do things



- **playable preview modes** rename these.. but yeah. playable preview modes in the style of each of these. 
    - PC-88 Popful Mail Style
    - Sharp X1 Curse of Mars style
    - Sharp X1 Xanadu Style
    - Famicom Dragon Quest Style

- **establish expansion window**
    - multi browser tab expansion mode... a new tab for a new, consolodated set of features. expansion modes windows... call each new window a special expansion mode. base engine is on one screen, the other screens might have other optional parts of the experience (more in depth character/npc/monster designer + map editor, battle system editor, or some platform specific testing suite)

### Phase 2.5 Expansion Windows
- in depth character/npc/monster designer + map editor
- battle system editor, 
- platform specific testing suite

### Phase 3

- some super powerful server side export options (thats right this is a full stack app that acts like a normal python web lol... i can explain... the internal server hosts the web app and the web app sends data to the server so the server can do OS functions like disk drive writing and executing other functions that might benefit your game dev.. see next bullet for ideas on what that means)
- interfacing with other engines... IE your project file can turn into a godot or unity project file. Or maybe it turns into a few C language files so that you can use in your homebrew game projects. Maybe it runs a full build, so it can turn your little diagram into a fully executable windows demo of your world. maybe we just want some pngs of the tilemap and maps. maybe we want to automate a report for a TDD..  lots of options there, none of them really that hard to make


# Big picture Todo

- adding npcs
- monsters database
- items database

# Sections
- sprite editor
    - edit 32 monochrome tiles
- object editor
    - each object has a type
    - npc types can have dialog
    - monster types can walk around


# methodology
- no submenus, what you see is what you get




# todo















- SCOPE LIMITER: each sprite is an object, and can have different behaviours set (wall, free, player, wander, pickup, door | killable y/n | hp | what item does it drop when killed ).. if super todo is activated and we create multiple screens, then this doesn't have to be the case anymore.. i feel like this could snowball into something messy so i should probably just stop here lmao.

# super todo





