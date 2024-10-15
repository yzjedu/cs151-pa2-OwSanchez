# Initial Design Document
#### PLEASE! PLEASE! PLEASE! READ the [README.md](README.md) File carefully

1. Prompt user to input number of sticks between 10 and 100
- Error check if input is under 10 or over 100.
2. Prompt user 1 to pick how many sticks they want to pick up (1-3)
- Do the same for user 2
- Error check for values less than 1 or greater than 3
3. Code program to roll a random number from 1-3
- (This is the computer playing against the 2 users)
- Output the amount of sticks the program picked up
4. Loop this process until amount of sticks is equal to 1
- Whoevers turn it is to pick up the stick is the loser
- Output who lost the game
- Keep track who and how many times a player lost the game
5. Prompt user to play game again
- If user plays again, loop this process
- If user chooses to end game. Output the amount of losses each player has
- Error check for any other decision.