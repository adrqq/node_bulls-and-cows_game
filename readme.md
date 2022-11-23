# The "Bulls & Cows" game

[PLAY IT]() in Sandbox terminal.
Just make fork press continue without an account then open a new terminal and type the command npm run play or node src/app.js

**Rules**

- the program randomly generates a number of 4 different digits
- and asks a player to guess
- the player enters a number of 4 different digits
- the program check the entered number (if it has exactly 4 different digits)
- then computer compares a try with the generated number and shows a result of 'bulls' and 'cows'
- `bull` - guessed digit is on its place (index)
- `cow` - guessed digit exists in the number but the place (index) is wrong
- the game ends when the numbers is found

## Example

Computer makes `1234`, user prints `1345`. The result is one `bull` (guessed
digit `1` is on it's place) and 2 `cows` (digits `3` and `4` are present but on
wrong places).
