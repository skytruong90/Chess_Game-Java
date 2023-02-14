## My Plan:
1. Define a class for the chess board, which contains an 8x8 array to represent the squares on the board. Each square can hold a chess piece object, or be empty.
2. Define a class for the chess pieces, which includes their type (e.g. pawn, bishop, knight), color (white or black), and their current position on the board.
3. Define a class for each type of chess piece (e.g. Pawn, Bishop, Knight), which inherits from the chess piece class and contains methods for moving the piece.
4. Define a class for the game itself, which initializes the chess board and sets up the starting positions of the pieces.

Note: In the game class, implement a loop that takes input from the user to move pieces. The input should be in the form of the starting and ending positions of the piece, and the game should check whether the move is legal before executing it.

Implement methods to check for various conditions that would end the game, such as checkmate or stalemate.

Finally, display the board after each move, and continue the game until it is over.
