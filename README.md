# Neural-Network-Sudoku-Solver
This is a work in progress. The goal is to train a neural network model to make logical inferences to achieve the task of completing a Sudoku puzzle. It was undertaken as a part of a graduate level Machine-Learning course at UNL. Part of the training set has been sourced from the UNL Sudoku solver website http://sudoku.unl.edu/SudokuSet/SudokuSetV5/.

The website uses Consistency algorithms in constrained systems to solve puzzles and ranks them based on the number of clues supplied etc. This solution uses a convolutional and dense neural network approach. Additional datasets used include '17 given puzzles' and 'Kaggle 1 million Sudoku puzzles'. Some approaches used in this solution have been adapted from here
 https://github.com/Kyubyong/sudoku and here https://www.kaggle.com/dithyrambe/neural-nets-as-sudoku-solvers.

Currently this performs extremely well on the test-set from Kaggle. However, it is not as effective at solving the test sets from '17 given puzzles' and 'UNL Sudoku' indicating a discrepancy between the type of puzzles encapsulated in the different repositories. Further investigation and optimization will be implemented in the future.
