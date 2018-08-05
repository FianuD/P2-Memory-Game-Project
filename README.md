# Memory Game Project

Classic Memory Game: The object of the game is to find the matching pairs of the hidden cards.

## Table of Contents

* [Game Rules](#game-rules)
* [How To Play](#how-to-play)
* [Screenshot](#screenshot)
* [Summary Of How Game Was Built](#summary-of-how-game-was-built)

## Game Rules

* Click on a card to start the game.
* Keep revealing and matching cards with identical faces.
* Your moves are counted as you proceed the game.
* Moves equal or below 16 will get you 3 Gold Stars.
* Moves greater than 16 and less than 25 will get you 2 Gold Stars.
* Moves 25 or higher are 1 Gold Star.
* The game can be restarted by hitting the restart button.

## How To Play

* Download or clone the repository on your machine.
* Extract the .zip file.
* Open the index.html in your browser.

Note: Internet connection required to load font awesome cards.

## Screenshot

![Screenshot of Memory Game](https://github.com/FianuD/P2-Memory-Game-Project/blob/master/img/Matching-Game.png)

## Summary Of How Game Was Built

Alterations were made to the HTML and CSS.

* Classes and IDs as targets for both CSS and JavaScript.
* Added modals
* Media query added to CSS for responsiveness.

The Dom was manipulated with vanilla JavaScript.

* Created a deck of cards that shuffles when game is reset.
* Added a counter to keep track of number of moves made.
* Added a timer to show length of playtime in minutes and seconds.
* Created a pop-up modal for when player completes the game.