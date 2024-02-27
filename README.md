## Random Dice Game

This simple C# console application implements a random dice game. The game prompts the user to roll a dice and aims to roll a number greater than a randomly generated target number. Below is a breakdown of how the game works:

### How to Run the Game
To run the game, simply compile and execute the provided code in a C# environment.

### Game Flow
1. The game starts by asking the player if they would like to play. If the player enters 'Y' (case insensitive), the game proceeds; otherwise, it exits.
2. Inside the game loop, a target number is randomly generated between 1 and 5 (inclusive). The player's goal is to roll a dice and get a number higher than this target.
3. The player rolls the dice, and the result is displayed.
4. Based on the result compared to the target number, the game informs the player whether they win or lose.
5. After each round, the player is asked if they want to play again. If they choose 'Y', the game continues; otherwise, it exits.

### Code Structure
- **Main Method**: The entry point of the application. It initializes a `Random` object and checks if the player wants to play.
- **ShouldPlay Method**: Responsible for checking if the player wants to play again.
- **PlayGame Method**: Controls the main game loop. It generates a target number, rolls the dice, determines the outcome, and asks if the player wants to play again.
- **GetTarget Method**: Generates a random target number.
- **RollDice Method**: Simulates rolling a dice and returns the result.
- **WinOrLose Method**: Determines if the player wins or loses based on the comparison of the roll with the target.

### Note
This code provides a basic structure for a simple dice game and can be expanded upon or modified to add more features, complexity, or user interactions. Enjoy playing!# Random-Dice-Game
