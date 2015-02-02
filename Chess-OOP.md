### Convert your chessboard to OOP
#### Create a Board class
1. Your __init__ method should initialize the board and the pieces dictionary as Board attributes, and a taken pieces list.
2. You should have a print method that prints the board.
3. You should have a check_move method that takes a position (a list) and a move (another list) and returns True or False
depending on whether the move is acceptable or not.
4. A move method that checks if the move is valid, moves the piece if is, updates the taken list if necessary, and prints
the updated board. 

```
class Board:
  
  def __init__(self):
    self.board = ...
    self.pieces = 
    self.taken = []
    
  def print(self):

  def check_move(self, pos, move):
  
  def move(self, pos, move):
  ```
