# Neural-Network-Sudoku-Solver
This project is a work in progress.The goal is to train a neural network model to make logical inferences to achieve the task of completing a Sudoku puzzle. It was undertaken as a part of the CSE 878 course at UNL and a part of the training set has been 
sourced from the UNL Sudoku solver website http://sudoku.unl.edu/SudokuSet/SudokuSetV5/.
The website uses Consistency algorithms in constrained systems to solve the puzzles and ranks them based on the number of clues suppllied etc.We use a convolutional and dense neural network approach for comparison with the above. Additional datasets include '17 given puzzles' and 'Kaggle 1 million Sudoku puzzles'.Some of the approaches have been adapted from here
https://github.com/Kyubyong/sudoku and here https://www.kaggle.com/dithyrambe/neural-nets-as-sudoku-solvers.
NN consistently performs well on the Kaggle trainset and randomly sampled '17 given...' and 'UNL Sudoku' datasets as well. But performs poorly on the hold out set that were sampled from the more difficult compilations in '17-given and 'UNL Sudoku'.Further optimization is being worked on for the future.
