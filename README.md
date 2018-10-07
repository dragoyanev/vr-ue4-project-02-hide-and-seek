# Unreal Engine 4 VR Advanced Starter Project READ ME

This project is part of [Udacity](https://www.udacity.com "Udacity - Be in demand")'s [Unreal Engine 4 VR Nanodegree](https://www.udacity.com) and is based on the template project provided by the course in [GitHub](https://github.com/udacity//Unreal-Advanced-Project-Template).

This project makes a game within Unreal Engine 4 for room-scale VR. It is needed to utilize motion controllers for a kitchen-themed interaction game. Spawn object (plate) at random amongst several predefined places. 

## Necessary Controller
 - The project is developed and tested with Oculus Rift

## Necessary Software
- [Epic Games Launcher, Unreal Engine 4.15](https://www.unrealengine.com/en-US/blog)
- [Oculus Home](https://www.oculus.com/setup/)

## Audio Assets
- Original samples downloaded from [freesound.org](https://freesound.org)

## Detailed description
The goal is to find the hidden object(plate) and bring it to the target place. After the plate is hold at the target place it is teleported to a new random hidden place.

- Player should go over the "Red button" in the scene with one of the controllers meshes to start the game.
- The game can continue infinitely long.
- There is timer showing how long was played continuously after start of the game. 
- When game is started/restarted the score and timer are restarted
- Score is increased after every successful goal completion.
- The player can move around by teleporting himself using the right controller trigger button. Holding the trigger button is drawn the treactory for teleportation. When the trigger button is released a ball is triggered according the treactory and when it touches its final point the pawn /player is teleportat at that point.
- The hidden object can be bring to the target position using the left controller grip button.
- The timer starts on event (StartTimer) casted by overlaping "Red button" in the scene with any of the controllers.
- Audio cue is played when plate is at target place
- Audio cue is played in loop when the level starts and different sound is played when the game is started