# Rock-paper-scissors-with-AI

Welcome to my Rock, Paper, Scissors challenge project repository! In this project, I've created a Python program that plays Rock, Paper, Scissors against four different bots. The objective was to build a program that wins at least 60% of the games against each of these bots.

## Getting Started

To use and test the project, follow these steps:

1. Clone this repository to your local machine.

```bash
git clone https://github.com/amey-narwadkar-4869/Rock-paper-scissors-with-AI.git
```

2. Navigate to the project directory.

```bash
cd rock-paper-scissors-challenge
```

3. Ensure you have Python 3.x installed.

4. Open the `RPS.py` file in your favorite code editor. This is where the core logic for the player function resides. You can customize this function to improve your game strategy.

5. Use the `main.py` file to test your code during development. It imports the game function and bots from `RPS_game.py`. You can simulate matches between your player and the bots using the `play` function.

```python
# Example: Play 1000 games between player and quincy, and display results.
play(player, quincy, 1000, verbose=True)
```

6. Run your code from the command line or your code editor to see how well your player performs against the bots.

## Project Details

In the `RPS.py` file, you have a function called `player`. This function takes an argument that is a string describing the last move of the opponent ("R", "P", or "S"). The function should return a string representing the next move for your player to make ("R", "P", or "S").

- The player function will receive an empty string as an argument for the first game in a match since there is no previous play.

- You can also use the optional second argument, `opponent_history`, which is a list of the opponent's previous moves. This can be useful if you want to implement more advanced strategies.

- To defeat all four opponents, your program may need to have multiple strategies that adapt depending on the plays of the opponent.

## Testing

Unit tests for this project are available in `test_module.py`. You can run these tests by uncommenting the last line in `main.py`. These tests will help ensure that your player function is working correctly.

## Contribution

Feel free to contribute to this project by improving the player's strategy, optimizing the code, or adding new features. Fork the repository, make your changes, and submit a pull request. I'd love to see how others approach this challenge!

## License

This project is licensed under the MIT License.
## Acknowledgments

This project was completed as part of a coding challenge and serves as a fun way to practice Python programming and strategy development. Thanks to the creators of the challenge for providing the starter code.

Have fun playing Rock, Paper, Scissors!
