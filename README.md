# Golf-Code

In the game of golf, each hole has a par,

meaning, the average number of strokes a golfer is expected to make in order to sink the ball in the hole to complete the play.

Depending on how far above or below par your strokes are, there is a different nickname.

Your function will be passed par and strokes arguments.

 Return the correct string according to this table which lists the strokes in order of priority; 
 
top (highest) to bottom (lowest):


Strokes	Return

1	"Hole-in-one!"

<= par - 2	"Eagle"

par - 1	"Birdie"

par	"Par"

par + 1	"Bogey"

par + 2	"Double Bogey"

>= par + 3	"Go Home!"

par and strokes will always be numeric and positive. 
 We have added an array of all the names for your convenience.
golfScore(4, 1) should return the string Hole-in-one!
golfScore(4, 2) should return the string Eagle
golfScore(5, 2) should return the string Eagle
