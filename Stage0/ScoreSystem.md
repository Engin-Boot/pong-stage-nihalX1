# User Interface

## Feature

This module explains all the changes based on the SoreSystem.

## Acceptance Criteria

### Scenario: Score system updates score when one of the players scores

Given the game is started and the system conditions are working fine

When the ball hits left or right wall.

Then Score system updates score for the Player on opposite side of wall.

### Scenario: Score system checks for Winner when player scores

Given the game is started and the system conditions are working fine

When the players scores.

Then score system updates score.
If that Player has got 5 points, he is winner.
