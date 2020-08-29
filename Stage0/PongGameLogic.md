# Pong Game Logic

## Feature

This module explains all the changes based on the Pong Game Logic.

## Acceptance Criteria

### Scenario: Check if both players joined

Given: We have a working game

When: When we click on play button on menu screen.

Then: Check if both players have joined.

### Scenario: Starting the game

Given We have a working game

When both players have joined the game.

Then game starts.

### Scenario: Initialize game elements positions

Given: We have a working game

When: When the game starts

Then: Initialize default positions for game elements and draw them.

### Scenario: Reset game elements positions

Given: The game is started and system conditions are working fine.

When: When one of the players score.

Then: Reset game elements positions to their default values.

### Scenario: Change direction of ball

Given: The game is started and system conditions are working fine.

When: When paddle detects collision with ball.

Then: The direction of ball is changed.

### Scenario: Score system updates score when one of the players scores

Given: The game is started and system conditions are working fine.

When: When one of the players score.

Then: Score system updates score for the Player on opposite side of wall.

### Scenario: Score system checks for Winner when player scores

Given the game is started and the system conditions are working fine

When the players scores.

Then score system is made to update score.
If that Player has got 5 points, he is winner.

### Scenario: Board checks if it has collided with ball when position of Ball changes

Given the game is started and the system conditions are working fine

When the position of ball changes.

Then Board is made to check if its right or left wall has collided with the Ball.
