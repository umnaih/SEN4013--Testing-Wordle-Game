# SEN4013--Testing-Wordle-Game
This project was prepared for SEN4013 Software Verification and Validation to test the Wordle Game. you can find the **Wordle Game - CMP2004 Project** in the following repository : https://github.com/umnaih/Wordle-game

## Project Overview

In this project, we have tested the game that we had previously created which is an interactive Wordle Game using Java. The Wordle Game presents players with a grid of letters, and their goal is to create valid words using these letters. Players have five chances to guess the word correctly and earn points.

### Gameplay Features

- Players can interact with the game in four different modes: 
  1. Single-player using the keyboard.
  2. Single-player using drag and drop.
  3. Two players using the keyboard.
  4. Two players using drag and drop.

- The game provides feedback to players based on their guesses:
  1. If a letter is in the word and in the correct place, the grid background for that letter turns green.
  2. If a letter is in the word but not in the correct place, the grid background for that letter turns yellow.
  3. If a letter is not in the word, the grid background for that letter turns gray.

- Players compete to achieve the highest score within the given chances.

- The game is not only fun and engaging but also helps improve vocabulary, word-building skills, spelling, and concentration.

## Project Structure

The project consists of 11 Java files and 4 text files. Here is an overview of the key components:

1. **Source.java**: Main method to start the game.
2. **WelcomePage.java**: Allows users to choose their preferred mode (keyboard or drag and drop).
3. **Player.java**: Let users select the number of players (1 or 2).
4. **PlayerParent.java**: Keeps track of user information.
5. **WordBase.java**: Reads words from "Words.txt" and selects a target word.
6. **Keyboard.java**: Handles gameplay with keyboard input.
7. **DragAndDrop.java**: Manages gameplay with drag and drop input.
8. **AnimationPanel.java**: Displays a 2D animation upon winning.
9. **AnimationFrame.java**: Creates the AnimationPanel frame.
10. **Statistics.java**: Shows user statistics and playing time.
11. **Checks.java**: Checks if the user entered the target word correctly.

### Text Files

1. **Words.txt**: Contains a list of 1000 words used to randomly select the target word.
2. **HighestScore.txt**: Keeps track of the highest score achieved.
3. **PlayCount.txt**: Records the number of players who have played the game.
4. **WinCount.txt**: Tracks the number of times a user has won the game.

## Testing

The project includes extensive testing, including## Functional Testing

## Functional Testing
1. Combinatorial Testing (Pairwise Approach)
2. Equivalence Class
3. Test Cases Table
4. Finite State Machines (3)
5. Case Effect Graphs (3)

## Structural Testing
1. Control Flow Graphs (4) with Their Test Cases
   
Feel free to explore the code in the following repository: https://github.com/umnaih/Wordle-game, test cases, and results to gain a deeper understanding of how this Wordle Game works.

Have fun playing the Wordle Game and improving your word skills!
