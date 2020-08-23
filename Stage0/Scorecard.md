# Scorecard and winner module

## Feature

What part of the game does this module deliver?

This module keeps track of scorecard and shows winner
name and the number of reward points he wins

"Scorecard" class keeps track of rounds or user
"winner" class keeps track of reward points and total reward points
of user

## Acceptance Criteria

### Scenario: User completes all rounds of the game

  Given the user is playing the game and game is not exited

  When user finishes all the rounds

  Then show the scorecard "the number of rounds he won" and reward points

### Scenario: User exits or game crashed just after completion of all rounds

  Given the user completes all rounds of the game
  
  When user press exit or game freezes for 10 seconds
  
  Then Exit the game and reset values in scorecard
