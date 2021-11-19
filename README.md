# midterm

**Sudoku**

Sudoku is a common puzzle in which the aim is to assign a single number between 1 and $$k^2$$ to each cell in a k2×k2 matrix which is divided into k×k equal blocks. A number can appear once in each row, once in each column, and once within each of the k×k blocks. The standard version of the puzzle is a 9×9 matrix (k=3).

Considering the standard version, each puzzle consists of a matrix in which some cells have been already filled with a number between 1 and 9 (an example of such a puzzle at the initial state is shown in Figure 1). The goal is to fill the remaining cells with numbers so that the mentioned rules are met.

There are 6.67×1021 possible combinations for an empty Sudoku board. It is clear that this number is reduced as the pre-filled cells serve as constraints. There is a unique solution for a proper Sudoku puzzle and a sequence of logical deductions are required to reach that solution (the unique solution for the sudoku puzzle example is shown in Figure 2). This project aims to find the solution for a sudoku puzzle through an algorithmic approach that can be implemented step by step in Python. 

`5	0	0	0	0	1	0	0	8`

`0	0	0	0	0	0	6	0	0`

`0	0	0	0	6	2	5	7	0`

`0	9	0	2	0	5	1	0	0`

`0	0	4	0	1	0	3	0	0`

`0	0	8	3	0	9	0	2	0`

`0	7	6	9	8	0	0	0	0`

`0	0	5	0	0	0	0	0	0`

`8	0	0	1	0	0	0	0	3`

**Figure 1.** The initial state of a Sudoku puzzle


`5	6	2	7	3	1	9	4	8`

`7	4	1	5	9	8	6	3	2`

`9	8	3	4	6	2	5	7	1`

`3	9	7	2	4	5	1	8	6`

`2	5	4	8	1	6	3	9	7`

`6	1	8	3	7	9	4	2	5`

`1	7	6	9	8	3	2	5	4`

`4	3	5	6	2	7	8	1	9`

`8	2	9	1	5	4	7	6	3`

**Figure 2.** The final answer of the Sudoku puzzle



**References**

Chae, R. H., & Regan, A. C. (2021). An analysis of Harmony Search for solving Sudoku puzzles. Soft Computing Letters, 3, 100017.

Kendall, G., Parkes, A., & Spoerer, K. (2008). A survey of NP-complete puzzles. ICGA Journal, 31(1), 13-34.

Eppstein, D., (2005). Nonrepetitive Paths and Cycles in Graphs with Application to Sudoku. Available at: https://arxiv.org/pdf/cs/0507053.pdf
