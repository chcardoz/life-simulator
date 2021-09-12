# life-simulator

## What is the game about

Welcome to Life Simulator, where you are stuck in a endless loop of "life" before you gather enough points in different categories to go to Mars and grow some potatoes with Elon Musk.

## Where can I find the game

[Life-Simulator](https://chcardoz.github.io/life-simulator/)
If you want to reset the game state, just navigate to the welcome screen and all the variables will be resetted. 

## Graph diagram

The graph diagram can be found under the docs folder.

## Technologies used

The game uses the Twine engine and is coded in Harlowe. The output file is in HTML and contains the javascript code of the Twine game engine.

## How to play the game

Your objective in the game is to max out your health, family and self-actualization score to 100. You also have to reduce your stress to 0. If you manage to do that, you can check to see if you won a chance to go to Mars.

### How to increase health

You can increase your health by eating food that YOU made. If you eat from outside, then it can have negative side effects. Health can also be increased by first building a physique and then lifting heavier weights in the gym.

### How to increase self-actualization

Self-actualization is increased by going to school and learning computer science. You can also increase it by buying cooking or public speaking books. If you go to work at Mcdonalds and spend too much time there, your self-actualization goes down.

### How to increase family points

You can visit your folks or loved ones from your home and increase family points.

### How to decrease stress

Stress can be reduced by - going to therapy, spending time with the family, not eating fast food, going to the gym. Working too long or learning computer science for too long can increase your stress.

## How does it work

The game remembers the state of the player using variables for each skills and category. The points are always displayed on your right and are updated every second. Whenever your stress increases beyond a certain point, you will see a quick link to visit therapy. Throughout the game, you will see blue links. When these links are pressed, a macro is executed which executes some Harlowe code to change the state of the player.

## Lessons learned

I have understood fundamentally how some of my favorite games work - they are constantly monitoring the state of the application or the player. Another imporant concept that I came across is the "clock" in the game which. Using the clock, we can execute the same code over and over again as a means to update our state.

## Future features

- A way to cool down some of the links so that they are not spammed
- A better banking system to handle the money and debt that the user will take.
- A way to give out loans to users based on their credit score.
