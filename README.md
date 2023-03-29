# World Cup - CS50 Problem Set

This is the solution for the World Cup problem set in CS50 course. The aim of this problem set is to create a program that simulates a sports tournament, where teams play against each other and progress through the tournament brackets. In this program, the tournament brackets are constructed randomly, and the user can enter the number of teams they want to participate in the tournament.

Getting Started

To use this program, you need to have a working installation of Python 3.7 or higher. You can clone this repository to your local machine and run the program using the following command:

Copy code
python3 world_cup.py
Usage

When you run the program, you will be prompted to enter the number of teams that will participate in the tournament. Once you enter a valid number, the program will simulate the tournament and display the results on the console. The program will display the name of the winner and the runner-up, as well as the list of all teams with their respective scores.

Implementation Details

This program is implemented in Python and uses object-oriented programming concepts to model the tournament and teams. The tournament is represented by a Tournament class, which contains the list of teams and the tournament brackets. The teams are represented by a Team class, which contains the name and the score of the team.

The program uses the following algorithm to simulate the tournament:

Shuffle the list of teams randomly.
Divide the teams into pairs and assign them to the first round of the brackets.
For each round, simulate the matches between the teams and update their scores.
Move the winners to the next round of the brackets.
Repeat steps 3 and 4 until there is only one team left, which is the winner of the tournament.
Acknowledgments

This program is inspired by the World Cup problem set in the CS50 course. The implementation details are based on the lectures and materials provided by the course. The program is developed and maintained by Ebite Samuel, and is licensed under the MIT License.
