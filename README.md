# Artificial Intelligence Nanodegree
# Diagonal Sudoku Solver
## by Egor Ermilov

### Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: We identify all the units containing naked twins (2 boxes with identical sets of 2 candidates). Then we eliminate the twin values from the peers. Eliminating these values makes the Sudoku easier to solve. In other words we reduce the search space by making local constraints. 

### Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: We created two new constraints (digits 1-9 must appear only once in the diagonals) by simply adding new units. The strategies did not change.

### Install

This project requires **Python 3**.

### Code

* `solution.py` - You'll fill this in as part of your solution.
* `solution_test.py` - Do not modify this. You can test your solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing your solution.
* `visualize.py` - Do not modify this. This is code for visualizing your solution.


