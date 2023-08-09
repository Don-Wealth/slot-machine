# Slot Game

This is a simple slot game written in Python where players can deposit funds and play the game with a chance to win. The game simulates a slot machine with various symbols and allows players to place bets on different lines. The player's balance is tracked, and they can continue playing until they choose to quit or run out of funds. 

**Note:** ***I do not in anyway support gambling! This purely to get my self comfortable with python fundamental syntax***

## Table of contents

- [How-to-play](#How-to-play)
  - [Rules](#Rules)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [How-to-Run ](#How-to-Run)
  - [Requirements](#Requirements)
  - [Note](Note)
- [Author](#author)



## How-to-play

1. Run the Python script slot_game.py.

2. You will be prompted to deposit funds to start playing. Enter the amount you want to deposit. The deposited amount will be added to your balance.

3. The game will start by displaying your current balance. Press Enter to start playing or press 'q' to quit the game.

4. If you choose to continue playing, you will be asked to enter the number of lines you want to bet on. The lines represent the rows on the slot machine.

5. Next, you will be asked to specify the amount you want to bet on each line.

6. The slot machine will display the results of the spin, showing the symbols on each line.

7. If you win on any line, your winnings will be added to your balance.

8. The game will continue asking if you want to play another round or quit until you decide to quit or run out of funds.

### Rules

* The game has a maximum of 3 lines and allows bets between $1 and $100.

* The symbols and their corresponding values are predefined. The symbols "A", "B", "C", and "D" have different values.

* To win on a line, all symbols on that line must match.

* Your winnings are calculated based on the symbols matched and the bet amount.

### Screenshot

![](./screenshots.png)

### Links

- Solution URL: [ Github ](https://github.com/Don-Wealth/slot-machine)

## My process

### Step 1: Project Setup

1. Created a new directory for the project.
2. Initialized a Git repository to track changes.

### Step 2: Define Game Parameters

1. Defined constants for maximum lines, max and min bets, and symbol properties.
2. Created dictionaries to store symbol counts and values.

### Step 3: Implement Core Game Logic

1. Implemented the `check_winnings` function to calculate winnings based on symbol matches.
2. Developed the `get_slot_machine_spin` function to generate random slot machine spins.
3. Created the `print_slot_machine` function to display the slot machine grid.

### Step 4: User Interaction

1. Implemented the `deposit` function to allow users to deposit funds.
2. Created functions to get the number of lines to bet on and the bet amount.
3. Developed the `spin` function to execute the slot machine spin and determine winnings.

### Step 5: Main Game Loop

1. Implemented the main game loop using the `main` function.
2. Allowed users to play the game, spin the slot machine, and see results.
3. Checked for available funds and provided an option to quit the game.

### Step 6: Documenting and Testing

1. Added descriptive function and variable names.
2. Tested the game extensively to ensure all features work as intended.
3. Added error handling and user-friendly prompts.

### Step 7: Writing README

1. Started writing the README file to provide an overview of the project.
2. Documented the game rules, how to play, requirements, and instructions to run the game.
3. Included a section detailing the development process.

### Built with

- Python 3
- random module

### Note

This game is provided for educational purposes and entertainment. The probabilities of winning and losing are not representative of real-world gambling games.

Feel free to customize and extend the game as you see fit.

Enjoy playing the slot game!

### Requirements

* Python 3.x

### How-to-Run

* Ensure you have Python 3.x installed on your system.

* Open a terminal or command prompt.

* Navigate to the directory containing the slot_game.py file.

* Run the command: python slot_game.py.

* Follow the on-screen prompts to play the game.

## Author

- Website - [Modozie Chika](https://github.com/Don-Wealth)
- Twitter - [@DonWealth0001](https://twitter.com/DonWealth0001)


