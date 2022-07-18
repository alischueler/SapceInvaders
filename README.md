# SapceInvaders
A game developed when taking Fundamentals of Computer Science 1 at Northeastern University Summer of 2019 using Dr. Racket.
The game is easily played using the left and right arrows to switch the direction the spaceship at the bottom is moving, but speed cannot be changedy. The space bar is used to shoot bullets at the "invaders" - 4 rows of 9 evenly spaced blocks at the top of the screen. A random group of invaders incremetly fires bullets to the bottom of the screen. 
The game ends if 
1. One of the bullets from the invaders hits the spaceship
2. The spaceship is able to shoot bullets at all of the invaders

The restrictions are that
1. At any given time there can only be three spaceship bullets in the battle
2. At any given time there can only be ten invader bullets in the battle
3. The spaceship travels in a steady direction - left or right. The ship changes direction when the user clicks the left or right arrow key.

To Start the Program:  
start the program from the terminal $ racket SpaceInvaders.rkt
or open the program file with DrRacket, and click Run
