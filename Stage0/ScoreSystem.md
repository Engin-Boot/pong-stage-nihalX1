# User Interface

## Feature

This module explains all the changes based on the SoreSystem.

## Acceptance Criteria

### Scenario: Score system updates score when one of the players scores.

Given the game is started and the system conditions are working fine

When one of the players scores.

Then Score system updates score for that Player.

### Scenario: the User Interface is updated  for paddle position

Given the game is started and the system conditions are working fine

When the paddle position moves via  move function

Then the paddle position is updated in the UI

### Scenario: the UI is updated for the Score Board

Given the game is started and the system conditions are working fine

When the ball collides with the left wall or right wall

Then The Score Board is updated based on the player who scored.
UI Score system is also updated.

### Scenario: When the game loads initially, main menu screen is displayed

Given: We have a working game

When: When we load up the game

Then: Display the menu screen

### Scenario: On pressing play button, game elements get drawn

Given: We have a working game

When: When we click on the play button

Then: The ball,paddle,initial score get initialized with default positions.
Then they are rendered.

### Scenario: On winning, the winner is displayed

Given: We have a working game

When: When player scores 5 goals.

Then: He is displayed as the winner.
