# Interaction Sequences

## Startup Sequence

-describe-how-your-modules-interact-to-start

Initially Pong Menu module will display Menu screen.
The player clicks on "play" button on Menu Screen.
Then Pong Game Logic module will check if both players have joined.
If both have not joined, it will be waiting.
If both have joined, then game is started with game elements initialized with default positions.

## Movement Initiation

-describe-how-modules-interact-to-make-the-ball-move.

Ball initially starts in middle and moves in random direction.
When player wants to move paddle, move() method is called.
When paddle detects it has collided with ball,direction of ball changes.
If ball hits either left or right wall,score is updated.
Ball gets reset to middle position.

## One score

-describe-how-the-modules-interact-to-record-scores

Player 1 is on left and Player 2 is on right.
Board detects that either its left or right wall has collided with Ball.
If right wall has been collided with, Score System updates score for Player 1.
If left wall has been collided with, Score System updates score for Player 2.
