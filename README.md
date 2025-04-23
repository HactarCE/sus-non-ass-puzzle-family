# sus-non-ass-puzzle-family
very scary, finitely generated, infinite non-associative puzzles

## how it works
- the puzzle is solved when the board is empty
- you can use `<` and `>` to start making a new board state to apply to the old one, to access different associations 
- each cell in the board can have four states (empty, `*`, `/`, or `\`)
- empty and `*` are like C2 (cyclic group with 2 elements), and the slashes are the special operations for this puzzle family
- when you layer two states on top of each other in the same cell, they multiply, with slashes having special rules about forwarding states up the board
- you can use `<` and `>` as parens in your expressions, and unclosed parens will show you the state you're constructing, which is placed on top of the previous board when closed
