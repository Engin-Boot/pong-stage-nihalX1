# Paddle

## Feature

This module explains all the changes based on the Paddle.

## Acceptance Criteria

### Scenario: Move() method is executed when Player wants to move paddle

Given the game is started and the system conditions are working fine

When the player wants to move paddle

Then move() method of paddle is executed for that Player.

### Scenario: Paddle checks if collision has occured when ball updates position

Given the game is started and the system conditions are working fine

When the position of the ball is updated.

Then paddle checks if it has collided with Ball.
