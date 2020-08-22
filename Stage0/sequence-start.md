# Interaction Sequences

## Startup Sequence

-describe-how-your-modules-interact-to-start

Initially User Interface module displays Menu Screen.
The player clicks on Play button on Menu Screen.
Then objects like Player,Paddle,Ball,Board,Score System get created.
They get assigned default positions.
Then game starts.

## Movement Initiation

-describe-how-modules-interact-to-make-the-ball-move.

Ball initially starts in middle and moves in random direction.
When player wants to move paddle, move() method is called.
When paddle detects it has collided with ball,direction of ball changes.
If ball hits either left or right wall, ball gets reset to middle position.

## One score

-describe-how-the-modules-interact-to-record-scores

Player 1 is on left and Player 2 is on right.
Board detects that either its left or right wall has collided with Ball.
If right wall has been collided with, Score System updates score for Player 1.
If left wall has been collided with, Score System updates score for Player 2.
