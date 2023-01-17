# Welcome to my portfolio represented in a 2D platformer way. 

## Technology Stack used:
* React Native Game Engine 
  * **WHY?** 
    * To have the game loop 
    * Manage/Manipulate our game entities
    * Get Unreal Engine / Unity like *Component-Entity-Systems* pattern.
* Matter JS 
  * **WHY?**
    * 2D physics library for help with projectiles
    * Moving the character
* lodash
  * **WHY?**
    * Makes JavaScript easier by taking the hassle out of working with arrays, numbers, objects, strings, etc
    * Always nice to have, makes programming faster. 
* d3-interpolate
  * **WHY?**
    * To help create a nice jump curve so that the action is not stuttering and gradually goes from *low* value to *high* value. 
* [OpenGameArt](opengameart.org)
  * **WHY?**
    * To get copyright free spritesheets, audio (Sound FX, background music).
* [Aseprite](https://www.aseprite.org/)
  * **WHY?**
    * To edit, slice and scale the sprites. 

## Installing all the required libraries before compiling. 
#### METHOD 1 (locally)
*Saving all the libraries locally in the folder project is located*
* npm install --save react-native-game-engine 
* npm install --save matter-js
* npm install --save lodash
* npm install --save d3-interpolate

#### METHOD 2 (globally)
*Saving all the libraries locally in the folder project is located*
* npm install --save -g react-native-game-engine 
* npm install --save -g matter-js
* npm install --save -g lodash
* npm install --save -g d3-interpolate





