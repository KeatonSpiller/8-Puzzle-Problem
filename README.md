# 8-Puzzle-Problem
Greedy Best First Search and A* Algorithm's with heuristics manhattan and # of misplaced tiles
* Requirements
* Python Version 3.10 or higher
1. Load libraries numpy, pandas, random

2. Initalize the hyper parameters

to the same initial puzzle number and goal number
(initial_puzzle1,puzzle_goal1) | (initial_puzzle2,puzzle_goal2) |(initial_puzzle3,puzzle_goal3) |(initial_puzzle4,puzzle_goal4) |(initial_puzzle5,puzzle_goal5) 
initial_puzzle = starting puzzle, make sure to match with goal puzzle number 1|2|3|...7
puzzle_goal = ending puzzle, make sure to match with inital puzzle number 1|2|3|...7

ex. for puzzle 3        
initial_puzzle = initial_puzzle3 # Set Which Puzzle I want to solve
goal = puzzle_goal3              # Set Which goal I want to solve

Then choose the type of heuristic with the type of algorithm
# Choose the Heuristic and the algorithm to solve
heuristic = "Manhattan" # Misplaced | Manhattan | Both 
algorithm = "A_Star" # Greedy | A_Star
*Puzzle 4 and 5 are the hard puzzles and this doesn't find the solutions on some combinations (*in an hour)

3. Run the Code block and see the best solution path found to solve the puzzle
