# -Connect-Four-game-in-C
"Connect Four' game written in C language, but the size of the board is not fixed and the player can change the size of the board as well as the length of the winning line. The winning line, instead of being a line of tiles in the same colour, now must be a palindrom, comprised of numbers "1" and "2".

INSTRUCTION

The game parameters ROWS, COLUMNS, and LENGTH are defined using symbolic constants, which can be defined using the -D option of the compiler.

The default values of these constants are provided in the code:

WIERSZE is set to 8,
KOLUMNY is set to 8,
DLUGOSC is set to 5.

In the program loop:
- the current state of the board is displayed along with the player who is to make a move;
- a player's command is read;
- if a move command is read, it is executed;
- if the command to end the game is read, the program ends.

The loop ends when:
the program receives the command to end the game, or
one of the players wins.
If one of the players wins, the program displays the final state of the board and indicates who won.

INPUT FORMAT

The player commands are provided as input to the program. The program does not accept invalid input.

The only character in a move command is the name of the column where the player wants to place a pawn. Columns are named using consecutive lowercase letters, starting with a.

A move command is valid if the indicated column has a free space.

The only character in an end game command is a period.

OUTPUT FORMAT

The program outputs a sequence of board diagrams. After each diagram, a line indicates which player is to make a move or who has won.

Each square on the board is represented by a character:
- "-" if the square is empty;
- 1 if the square contains a pawn belonging to the first player;
- 2 if the square contains a pawn belonging to the second player.
A space precedes each character representing a square.
The square descriptions are grouped into rows, ordered from top to bottom. The squares in a row are ordered by column, starting with column a.

After the last row of squares, a line with the names of the columns is provided. Each name is preceded by a space.

Information about who is to make a move is provided in a line indicating the player's name, 1 or 2, followed by a colon.

Information about who has won is provided in a line indicating the player's name, 1 or 2, followed by an exclamation mark.
