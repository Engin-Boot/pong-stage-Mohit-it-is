# The taste of success

Your game is trending! The installations are encouraging!

## In-app Purchase

Marketing wants to introduce an in-app purchase:

- Harder paddles, that will bounce the ball faster -
makes it harder for opponents!

## Deliverables

- "Mode" variable and "set-mode" method will store the  
  information if the game is purchased.
- if game is purchased it will run in advanced mode.

## Making the Game hard

### Scenario: When racket is still

  Given: the ball is moving and racket is still
  
  when: ball collides with racket it
  
  Then: ball moves back with 1.2 times speed
  
### Scenario: When racket is moving

  Given: The ball and racket both are moving
  
  When: ball collides with ball
  
  Then: ball moves with (racket + ball) speed

### Stage 1 class Diagram

![mermaid-diagram-20200906162359](https://user-images.githubusercontent.com/68475914/92324240-86a7f380-f05d-11ea-9ee0-428fbeb2fb4e.png)
