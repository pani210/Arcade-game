# Classic Arcade Game Clone Project

## Table of Contents

- [Instructions](#instructions)
- [Contributing](#contributing)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking your submission.

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

Your **README.md** file should be updated with instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests
## I followed the following steps for completing the project:
# cloning of the project:
- After reading and verifying the instructions,I got the GitHub link about the skeleton project which was provided by the *UDACITY* in rubric structure.
- After downloading the files from GitHub,I extracted all the files and observed the structure of files.
1.`index.html`
2.`style.css`
3.`app.js`
4.`engine.js`
5.`resources.js`
6.`README.md`
### Modifications to the code ###
1. Firstly,I created a empty canvas,I initialised`canvas-width`and`canvas-height`to some values.
2. Declared a enemy with function x,y,and speed `function(x,y,speed)`.
3. I also inserted an image named for enemy as `bug`.
4. Then,I created a player names as `Hero`.
5. Everytime the enemies position will be updated during te game.
6. I've named a parameter named as dt(a time delta between ticks) which will ensure the game runs at the same speed for all computers.
      `Enemy.prototype.update = function(dt)`.
7. coordinates have been applied to player in a specified coordinates in which direction he has to move(upward,downward,sidewards).
8. Implemented the below functions for a player:
    - render()
    - update of() and
    - handleInput()
9. I've created a class for player for updating and rendering the hero `Hero.prototype.update=function(dt)` and `Hero.prototype.render = function()`.
10. similarly implemented for enemy activity:
    - render() and
    - update()
11. I placed all enemy objects in an array called `allEnemies`,`var allEnemies=[];`
12. I placed the player object in a variable called `player`,`var enemyLocations=[];`[some values].
13. Whenever the hero touches the enemies the player will initialised to starting position.
14. The player has to reach the other side of the canvas without touching the enemies,if he touches he will send back to initial position.
15. In this game we use arrow keys for functioning of the game and for operations.
16. To play this game for a long time the player shouldn't hit the enemies.

### output of the game ###
1. Player will always tries to score without touching the enemies.
2. If he hits the enemies a sweetalert will be displayed by showing congratulations and score will be displayed.
3. A button also displayed showing that play again. 

### How to play and run the game ###
1. After completion of project without any error.
2. Run the index.html in your favourite browser and you will see the game panel on your screen.
3. you can move your player by navigatinal keys:
   - left
   - right
   - top and 
   - bottom.
4. The player shouldn't collide with the enemey.
5. If player reaches the watermark area he will automatically comes to initial position and score will be awareded as five points.
6. whenever the player collides the enemey the game will ends automatically and the score will be displayed on the screen using sweetalert.
7. If you  want to play again just click the button `play again` in the alert. 
   
