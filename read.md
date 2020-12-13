# Feature Tasks and Requirements

[x]Your job is to render out chess boards with red and blue queens on them.

[x]We’re keeping it really basic here so the only pieces are queens and each queen is represented by a blue or red square.

[x]Chess board is an 8 by 8 grid of alternating black and white squares. The queens are red and blue squares.

[x]Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

# Implementation Notes

[x]Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)


[x]should have add_red method that accepts a row and column as input which colors corresponding cell.

[x]should have add_blue method that accepts a row and column as input which colors corresponding cell.

[x]should have render method that displays the chess board on screen with red and blue shown in correct locations

[x]should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

# User Acceptance Tests
[x]queens on same row should be “under attack”

[x]queens on same column should be “under attack”

[x]queens on same diagonal should be “under attack”

[x]queens with any other coordinates should NOT be “under attack”

[x]NOTE: Include assert statements directly in your notebook verifying the behavior above.

# Stretch Goal
[]Enlarge the chessboard to allow for pixel art drawn pieces. 16x16 ought to be enough.

[]Add more attacking queens.

[]Add opacity to cell colors.

https://github.com/MsDiala/chess-board/pull/1
