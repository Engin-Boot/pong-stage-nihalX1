# Class Diagram

classDiagram
    UI ..> Paddle
    UI ..> Ball
    UI ..> Player
    UI ..> Board

    Player --> Paddle
    Paddle ..> Ball
    ScoreSystem --> Player
    Board ..> Ball

    class Board{
        -String color
        -int length
        -int breadth
        +is_collided_leftwall(Ball)
        +is_collided_rightwall(Ball)
    }
    class Ball{
        -String color
        -int radius
        -int x_coor
        -int y_coor
        +change_direction(int x, int y)
    }
    class Paddle{
        -int length
        -int thickness
        -int x_coor
        -int y_coor
        +move(int y_coor)
        +is_collided(Ball)
    }
    class Player{
        -String name
        -int score
        +isWinner()

    }
    class ScoreSystem{
        -Player p1
        -Player p2
        +updateScore(Player player1, Player player2, Board board)
        +getScorePlayer(Player)
        +checkWinner(Player p1, Player p2)
    }
    class UI{
        +drawPaddle(Paddle paddle)
        +drawBall(Ball ball)
        +drawScoreBoard(Player player1, Player player2)
        +displayWinner(Player player1, Player player2)
        +drawBoard(Board)
        +drawMenuScreen()
        +initializePositions(Board, Paddle, Ball)
    }

                    

