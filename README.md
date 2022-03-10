# Combat-Simulator-WOTR

This project was created by Patrick Mooney for the WOTR Board Game community.

It is a program that can roughly calculate (+/- 1%) the odds of winning a battle given the number of units, type of battle, and combat effects played.

It is helpful for understanding how to maximize your chances of winning a battle, and which cards are best. 

It can also be used to know which battles are fruitless, and which battles are in your favor.

DO NOT USE THIS PROGRAM TO CHEAT DURING A GAME. IT IS FOR ANALYTICAL PURPOSES. USING THIS PROGRAM DURING A GAME IS LIKE USING A CHESS ENGINE, OR GOOGLE DURING A TEST.

All planned cards are already implemented. Many cards that have to do with companions require too much fundamental rewriting of the code. Other cards, like the card cancelling ones, are pointless
Isengard Elites are possible down the road.


Sources of Error:
The casualty algorithm does not consider cards (it may take an elite instead of a regular in a normally optimal manner, depleting value from We Come to Kill)
1's arent guarunteed misses.
Most cards do not consider play conditions (anduril, valour, mumakil, etc)

The code currently runs 25,000 simulations to get a decently accurate value (it seems to fluctuate a percent or so)

Tested on: Google Chrome

