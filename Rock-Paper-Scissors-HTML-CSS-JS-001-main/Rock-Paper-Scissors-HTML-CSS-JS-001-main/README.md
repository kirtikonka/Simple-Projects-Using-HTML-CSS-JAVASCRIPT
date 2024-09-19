# lOGIC OF THE JS FILE

Hand Options: It defines images for rock, paper, and scissors.

Score Keeping: A variable SCORE tracks the user's wins.

Pick User Hand:

Hides the hand selection menu.
Shows the contest area.
Sets the user's chosen hand image based on selection.
Calls the pickComputerHand function to generate the computer's choice.
Pick Computer Hand:

Creates an array of "rock", "paper", and "scissors".
Randomly selects a hand for the computer.
Sets the computer's hand image based on the selection.
Calls the referee function to determine the winner.
Referee:

Compares the user's hand and computer's hand using a series of if-else statements.
Based on the comparison, it determines a win, lose, or tie scenario.
Calls setDecision to display the result on the screen.
Calls setScore to update the user's score if they win.
Restart Game:

Hides the contest area.
Shows the hand selection menu again for a new round.
Update Display Functions:

setDecision updates the text element showing the result (win, lose, or tie).
setScore updates the text element showing the user's current score.
