# Game user interface

## Feature

What part of the game does this module deliver?
This module is used for the development of the User interface
of the game
The module is divided into three classes
"PongGameUI" which controls Background color and background theme
"RacketUI" Which controls racket theme
"BallUI" Which controls ball theme

## Acceptance Criteria

### Scenario: loading of the pong game user interface

  Given the game has started and user has enterd name

  When user clicked start the game

  Then load the user interface of game

### Scenario: if Game crashed while loading or user exits the game

  Given user has enterd name and user interface is loading
  
  When user interrupts in between by clicking exit or game freezes
  
  Then stop loading phase of user interface and exit the game
