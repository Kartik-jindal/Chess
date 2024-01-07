# Chess Game

This repository contains a simple implementation of a chess game in Python using the `python-chess` library. The game can be played either in single-player mode against another human player or in a player versus AI mode.

## How to Play

### Single Player Mode

In this mode, you can play against another human player. The game prompts you to input your moves in the standard chess format (e.g., 'e2e4'). The game continues until it reaches a checkmate, stalemate, insufficient material for checkmate, or other draw conditions.

To play the game, run the `play_chess()` function in the provided Python script. Follow the on-screen prompts to enter your moves.

### Player versus AI Mode

If you want to play against an AI opponent, you can switch to AI mode. The AI makes random legal moves during its turn. The game continues until it reaches a checkmate, stalemate, insufficient material for checkmate, or other draw conditions.

To play against the AI, run the `play_chess()` function in the provided Python script. Follow the on-screen prompts to enter your moves during your turn, and the AI will respond with its moves during its turn.

## Game Over Conditions

The game can end in various ways, and the result is displayed at the end. Possible outcomes include checkmate, stalemate, insufficient material for checkmate, draws due to the 75-move rule, fivefold repetition, variant-specific rules, or a general game result.

Feel free to explore and enjoy the game!

# Author
Kartik Jindal

Contact: kartikjindal2003@example.com
