# ARMAZE

## Introduction
Welcome to ARMAZE! In this project, we've developed an Augmented Reality (AR) maze game using Unity. By leveraging AR capabilities, our game brings maze-solving to life, allowing players to scan an image target and bring forth a virtual maze challenge right before their eyes. Our AR capabilities are powered by Vuforia, a plugin seamlessly integrated into the Unity platform.

![Main ARMAZE Screenshot](https://github.com/sphexas/ARMAZE/assets/37029200/e45beaf7-67db-4611-b300-ffb401be05c8)

## Gameplay
The game presents players with an interactive ball maze compatible with both Android and iOS platforms. By using the device's front-facing camera, the game tracks an image target, which then projects the virtual maze for players to navigate. 

Our chosen image target for this maze is displayed below:

![Maze Image Target](https://github.com/sphexas/ARMAZE/assets/37029200/1a59fc9e-ec01-4e06-b985-38f979d5bfdf)

## Building Steps
1. **Set Up Vuforia:** Begin by creating a developer account on Vuforia. Add the above maze picture to your image target database. Download a copy of the database for Unity 3D, as well as the Vuforia plugin for Unity.
   
   ![Vuforia Setup](https://github.com/sphexas/ARMAZE/assets/37029200/c4948526-072a-4e6b-a5ad-d21a2af7e876)
  
2. **Unity Integration:** Import the Vuforia plugins and image databases into Unity. Set up the necessary prefabs and ensure that the image target is configured correctly within Unity.

3. **Maze Design:** In Unity, overlay a 3D maze design on the image target. This will serve as the virtual challenge players must navigate.

4. **Ball Mechanics:** Introduce a sphere (the ball) into the game. This ball will be controlled by the players, navigating through the maze. Implement the necessary scripts to control ball movement, spawning, and game mechanics.

   ![Ball Mechanics](https://github.com/sphexas/ARMAZE/assets/37029200/e19c2294-53f5-4f30-b7b6-b34ec6fb1152)

## 3D Mode
In addition to our AR maze, we've developed a 3D mode for maze gameplay. This mode serves as a testing ground for our ideas and features. While primarily for experimental purposes, this 3D maze offers players an alternative way to experience the game, complete with UI enhancements, multiple levels, background music, and additional features.

![3D Maze Screenshot](https://github.com/sphexas/ARMAZE/assets/37029200/ff85ce42-f720-4a21-ae3e-992417ed564e)

For those interested, the 3D Maze project can be accessed [here](https://github.com/Yucong-cheems/3Dmaze.git).

