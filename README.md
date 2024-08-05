# Warehouse Wreckage 

## Gameplay video: [Imgur](https://imgur.com/a/zarrylon-warehousewreckage-oznt9q0)

## Description
Section 2 project from "Unreal Engine 5 C++ Developer: Code Your Own Unreal Games" course by GameDev.tv.
In addition, I implemented my own modifications using what I learned in the section and from various online resources. 

The game logic was implemented entirely using Blueprints.

## My modifications
* Universal prop actor class "BP_BaseProp", which uses variables for static mesh and mass.
* Prop actor removal by checking if it's out of map (by Z-axis).
* Projectile actor removal by using a "Set timer by event".
* Win condition: remove all Prop actors (by shooting them off the map). Implemented with Event Dispatcher called "OnPropDestroyed".
* Display screen in the level that shows information about player controls, the game's goal and the number of props remaining.
* Keyboard event for shooting a projectile is Left Mouse Button (instead of Spacebar).
* Additional keyboard events: 'R' for reloading ammo and 'Tab' for restarting the level.
