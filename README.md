# GameofLife

Imagine an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two
possible states, live or dead. Every cell interacts with its eight neighbors, which are the cells that are
directly horizontally, vertically, or diagonally adjacent.
At each step in time (tick), the following transitions occur:
1. Any live cell with fewer than two live neighbors dies, as if by loneliness.
2. Any live cell with more than three live neighbors dies, as if by overcrowding.
3. Any live cell with two or three live neighbors lives, unchanged, to the next generation.
4. Any dead cell with exactly three live neighbors comes to life.

**Solution:**

In the java program first we take input for N,M which are rows and column using grid. Then we take values for those pixels.

After taking the input we display the input by user and call nextgeneration() function which will display the next generation cell.

Inside next generation function we create future grid.

In next generation function we run loops for all the pixels and check using the loop from -1 to 1 (Neighbours) how many alive cells are presenet.

Once we have number of alive cells we can check if that cell will live or not.

To check this we use three if condition based on three condition given

Output is displayed as the future generation.
