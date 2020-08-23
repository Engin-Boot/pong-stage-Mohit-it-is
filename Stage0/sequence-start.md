# Interaction Sequences

## Startup Sequence

As the user run the application the very first module "Start Game"
runs which consists  
of function "enter-name" which will take name as the input and invoke
"set name" for  
setting the name Then "Start Game" button will appear by
clicking the button user can  
start the game "report-crash and "exit" function
will look for related events

## Movement Initiation

* As the user clicks start game the "Game-ui" module will start now  
the user interface of the game will load
* "Ball-UI" class is called where the size position and speed of  
of the ball is defined
* "Racket-UI" class is called where the size and position of  
racket is defined
* "Movement-module" will interact with "Game-UI" module to take the  
position and size of the ball
* "update-ball" function will move the ball continuously  
* "Ball-collisions class will handle the collision of the ball with  
the racket and the wall
* "Ball-collision class will update the number of rounds if ball passes  
the racket

## One score

-describe-how-the-modules-interact-to-record-scores
