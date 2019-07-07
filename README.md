# Balloons! A balloon popping game



## About
### Technologies used
Balloons! is implemented in HTML5 and Javascript.

### Game play
The aim of 'Balloons!' is simply to pop as balloons as quickly as possible. The more balloons popped, the more points.

### Features
A balloon appears at the bottom of the canvas element and rises up and disappears through the top of the canvas element. The balloon starts at a random position at the bottom of the canvas. The balloon has a random colour. The player aims at the balloon with the mouse and tries to click on the balloon before it disappears. 

### Missing features
The game is currently missing a score counter.
A balloon should 'pop' once it is hit.
Only one balloon appears at a time. There should be more to make it more challenging.
The rate at which balloons appear should gradually speed up to make the game incrementally more challenging.

### Planned features / would be nice to have
The balloons would not disappear off the canvas but would gradually fill up the canvas until the canvas is completely full, at which point the player 'loses'. 
A touchscreen version.

### UX
Minimal UX was implemented as focus was on getting a working game up and running.

### Testing
Does game load?
Does clicking on balloon record a hit?
Does clicking outside balloon record a miss?
Do key presses affect the game?

### Deployment
Github Pages:  https://leocullenloerch.github.io/balloons/

### Ackowledgements
The basic canvas setup and game outline was based on parts 1 and 2 of the Mozilla tutorial: https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript
The code to check if a mouse click is inside a balloon is based on: https://stackoverflow.com/questions/16792841/detect-if-user-clicks-inside-a-circle
Returning a random colour from an array is based on code from: https://timonweb.com/tutorials/how-to-get-a-random-value-from-a-javascript-array/


