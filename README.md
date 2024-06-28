# Multi-Purpose-Project
Upon starting the program, users are greeted with a welcome message and presented with two primary options:

1. Perform Calculations
2. Play a Casino Game
Users input their choice to proceed to the respective section of the program.

Calculation Options :-
If the user selects the calculation option (entering 1), they are presented with four further choices:

Simple Interest Calculation: Users can calculate the simple interest based on the principal amount, rate of interest, and time period in years.
Compound Interest Calculation: This option allows users to compute the compound interest given the principal amount, rate of interest, and time period in years.
Temperature Conversion: Users can convert temperatures between Celsius and Fahrenheit.
Multiplication Table: This feature prints the multiplication table for a given number up to 10.
Each option leads the user through the necessary inputs, performs the calculations, and displays the results. After displaying the results, users are given the choice to return to the main menu or exit the program.

Casino Game :-
If the user chooses to play the casino game (entering 2), they are taken to a simple number guessing game with the following rules:

The user enters their name and initial balance.
They place a bet on a number between 1 and 10.
A random number is generated, and if the user's guess matches the random number, they win 10 times the bet amount. If not, they lose the bet amount.
The game continues until the user decides to stop or runs out of money.
The game provides feedback after each round, showing the winning number, the user's balance, and the option to play again or exit.

Implementation Details :-
Main Menu and Input Handling: The main menu prompts the user for input and directs them to the appropriate section based on their choice.
Calculation Functions: Each calculation task is encapsulated in a separate case within a switch statement, ensuring modular handling of different calculations.
Casino Game Logic: The game uses a random number generator (Random class) to simulate the number guessing game and maintains the user's balance throughout the session.
Screen Clearing: The clearScreen() method is a placeholder for clearing the console screen, improving readability and user experience.
Code Structure
The code is structured with nested switch statements to handle the different functionalities and inputs. This modular approach allows for easy addition or modification of features in the future.
