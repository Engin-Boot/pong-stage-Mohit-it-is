classDiagram
	PongGame --> PongGameUI
	PongGame --> ScoreCard
  PongGame --> BallMovement
  PongGame --> RacketMovement
	PongGameUI --> BallUI
  PongGameUI --> RacketUI
  ScoreCard-->Reward
  BallMovement-->BallCollisions
  RacketMovement-->RacketCollisions
  BallUI-->BallMovement
  RacketUI-->RacketMovement
  BallCollisions-->ScoreCard
  PongGame: -FirstPlayerName
  PongGame: -SecondPlayerName
  PongGame: +popupenterName()
  PongGame: +setName()
  PongGame: +reportCrash()

    class ScoreCard{
    -playeronescore
    -playertwoscore
    -No_of_rounds
    +updatescore()return winner
     }

    class BallMovement{
    +ball_position_x
    +ball_position_y
    -ball_speed
    +updateball()
    }

    class RacketMovement{
     +racket_position_left
     +racket_positon_right
     -racket_speed
     +updateracket()

    }
    
    class BallUI{
    +x_cordinnate
    +y_coordinate
    +size
    -color
    +updateballUI()  
    }

    class RacketUI{
    +x_coordinate
    +y_coordinate
    +size
    -color
    +updateracketUI()
    }
    
    class BallCollisions{
    +x_coordinate_window
    +y_coordiante_window
    +x_coordinate_ball
    +y_coordiante_ball
    +size
    -check_collision() 
    }
    class RacketCollisions{
    +LeftRacket
    +RightRacket
    +x_coordinate_window
    +y_coordiante_window
    +Racketsize
    -check_collision()
    }
    class Reward{
    +Winner
    +increamentcoins(Winner)  
    +show_stars()
    }
    class PongGameUI{
    -BakcGround_color
    -update_background()
    -setUIwithbackground()
    +setUIManually()
    }	
   
    
					
