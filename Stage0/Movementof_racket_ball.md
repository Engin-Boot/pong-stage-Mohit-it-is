# Movement of racket and ball

## Feature

What part of the game does this module deliver?
This module handles the movement of racket and ball
Module is divided into 4 classes
"Racket Movement" which controls racket movement left and right and speed
"Ball Movement" which controls the movement of ball and speed
"Ball collision" Which handles the collision of ball with the wall and racket
"racket collision" which handles the collision of racket with the wall

## Acceptance Criteria

### Scenario: Starting the movement of ball

  Given User has started the game and graphical interface is loaded

  When the game is not crashed or exited by user

  Then start the movement of ball by invoking "ball movement" class

### Scenario: User press exit or game crashed while playing

  Given User has started the game and game is loaded successfully
  
  When User press exit or game freezes while playing
  
  Then Stop the game and exit
