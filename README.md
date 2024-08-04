# Warehouse Wreckage
## Description
Section 2 project from "Unreal Engine 5 C++ Developer: Code Your Own Unreal Games" course by GameDev.tv.

Also added my own modifications based on what I've learned in the course.

## Gameplay
Wreak chaos in the warehouse! Player needs to shoot props to push them out of the map.

Game logic was implemented by using blueprints and physics.

## My modifications
* Class inheritance for props (BP_BaseProp and its child classes).
* Keyboard event for shooting a projectile is Left Mouse Button instead of Spacebar.
* More keyboard events: R for reloading ammo and Tab for restarting level.
* Projectile actor destruction using Set timer by event.
* Prop actor destruction by checking if it's out of map bounds (Z-axis).
* Win condition by destroying all Prop actors. Done by using Event Dispatcher.