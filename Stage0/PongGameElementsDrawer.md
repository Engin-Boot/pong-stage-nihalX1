# Pong Game Elements Drawer

## Feature

This module explains all the changes based on rendering game elements.

## Acceptance Criteria

### Scenario: the Ball is re-drawn when ball position is updated

Given the game is started and the system conditions are working fine

When the ball position moves using the move function

Then UI renders ball with the new position.

### Scenario: the Paddle is re-drawn when paddle position is updated

Given the game is started and the system conditions are working fine

When the paddle position moves via  move function

Then the paddle position is updated in the UI

### Scenario: the Score Board is re-drawn when a player scores

Given the game is started and the system conditions are working fine

When the ball collides with the left wall or right wall

Then The Score Board is updated based on the player who scored.
Score system is also updated.

### Scenario: On game start, game elements are drawn with their default positions

Given: We have a working game

When: When both players join and the game starts.

Then: The ball,paddle, board,initial score get initialized.
Then they are rendered.

### Scenario: On winning, the winner is displayed

Given: We have a working game

When: When player scores 5 goals.

Then: He is displayed as the winner.
