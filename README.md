# Tic-Tac-Toe

Tic-Tac-Toe is a simple Tic Tac Toe Game built using React JS.



## Roadmap of Future Improvements

#### Highlight the three squares when someone wins.

We have used checkForWinner to declare the winner. We can get the three squares or the line that caused the win easily by modifying the return value of this function and add styles to highlight the three squares. 


#### Display a message about the result being a draw as no one wins

If the board is full (no next move can be taken) and there is no winner, we can say that the result is a draw. To get whether the current move results in a draw, we need to revise the checkForWinner function.
