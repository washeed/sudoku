# sudoku
Sudoku Solver using Hill climbing algorithm
The Hill Climb Sudoku Solver is an intelligent program designed to solve Sudoku puzzles efficiently. Sudoku is a popular logic-based puzzle where a 9x9 grid must be filled with digits from 1 to 9, following certain rules. The goal is to fill in the empty cells so that each row, column, and 3x3 sub-grid contains all the numbers from 1 to 9 without any repetitions.

The Hill Climb algorithm used in this Sudoku solver is a heuristic search algorithm that aims to find an optimal solution by iteratively improving the current solution. It starts with an initial candidate solution and evaluates its fitness based on a heuristic, which in this case, is the number of correct digits placed on the Sudoku board.

The solver begins by randomly populating the empty cells of the Sudoku grid while adhering to the Sudoku rules. Then, it evaluates the fitness of the current configuration. If the fitness improves, the solver continues exploring the neighboring solutions by making small changes, such as swapping two digits or moving a digit to a different cell. This process is repeated iteratively, always selecting the best neighbor that improves the fitness, until no further improvement is possible or the puzzle is solved.

In each iteration, the solver examines the neighboring solutions, calculates their fitness, and selects the one with the highest fitness as the next candidate solution. This approach allows the solver to "climb" towards a more optimal solution by gradually improving the arrangement of digits on the Sudoku grid.

However, it's important to note that the Hill Climb algorithm is not guaranteed to find the optimal solution for all Sudoku puzzles. It may get stuck in local maxima, where further exploration does not improve the fitness. To mitigate this, additional techniques such as random restarts or incorporating other search algorithms can be employed.

Overall, the Hill Climb Sudoku Solver provides an efficient approach to solve Sudoku puzzles by iteratively improving the candidate solution based on the heuristic evaluation of fitness. It serves as a valuable tool for enthusiasts and individuals looking to challenge themselves with Sudoku puzzles.
