# React-Shooter

React shooter is a simple space shooter intended to test game design patterns
within React, using [react-game-kit](https://github.com/FormidableLabs/react-game-kit).

**The game is in early stages so please only check out this project if you
are a developer interested in learning or contributing.**

**The Digital Ocean [Hacktoberfest](https://hacktoberfest.digitalocean.com/)
event seems to have attracted the attention of new contributors. Please do
not be discouraged if your pull request is not accepted into the project at
this stage.**

## Installation
  `git clone https://github.com/danbruce/react-shooter`  
  `cd react-shooter`  
  `npm install`  
  `npm run-script build_all`  
  `npm run-script start`  
  `open http://localhost:3000 in your browser`

## Core Game Mechanics

The game is a space shooter with the player controlling a space ship along the
bottom axis of the screen. The space ship can move horizontally and fires up the
screen in traditional "Space Invaders" style.

Unlike traditional shooters, in this game the core focus is not to shoot the
enemies directly. Instead, your shots control the movement of the Lightball, a
powerful orb of color that can destroy your enemies. Your shots can pull the
Lightball in one of four directions depending on the Lightball's current color
and the color of shots. Destroy your enemies by forcing the Lightball to collide
with them, while avoiding their attacks and not being hit by the Lightball
yourself!

## Contributing

Please read the [contributing guide](CONTRIBUTING.md).
