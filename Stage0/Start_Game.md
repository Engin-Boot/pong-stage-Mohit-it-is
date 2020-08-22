# Start Game

## Feature

What part of the game does this module deliver?
This module represents starting phase of game which
Provides start menu to enter name of the players
Provides "set-name" function to set name of players
Provides "Report-crash" function to report crash and exit

## Acceptance Criteria

### Scenario: To run the game

  Given I have a working device which supports Pong game

  When I Run the game by tapping or clicking

  Then Start menu appears where users can enter their name
  
### Scenario: set Valid names of players

  Given Users have entered their name and press "enter-game"
  
  When I check the names and names are not empty
  
  Then start the Pong game
  
### Scenario: if Game Crashed in loading phase

  Given I have started the game by tapping or clicking the icon
  
  When the screen freezes and start menu is not appearing
  
  Then Exit the game and popup "report-crash"
