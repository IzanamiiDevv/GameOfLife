# The Game of Life

The Game of Life, also known simply as **Life**, is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game,meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves. It is Turing complete and can simulate a universal constructor or any other Turing machine.

## Rules

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead (or populated and unpopulated, respectively). Every cell interacts with its eight neighbors, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

- Any live cell with fewer than two live neighbors dies, as if by underpopulation.
- Any live cell with two or three live neighbors lives on to the next generation.
- Any live cell with more than three live neighbors dies, as if by overpopulation.
- Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed, live or dead; births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick.[nb 1] Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.

## Examples of patterns
Many different types of patterns occur in the Game of Life, which are classified according to their behaviour. Common pattern types include: still lifes, which do not change from one generation to the next; oscillators, which return to their initial state after a finite number of generations; and spaceships, which translate themselves across the grid.

The earliest interesting patterns in the Game of Life were discovered without the use of computers. The simplest still lifes and oscillators were discovered while tracking the fates of various small starting configurations using graph paper, blackboards, and physical game boards, such as those used in Go. During this early research, Conway discovered that the R-pentomino failed to stabilize in a small number of generations. In fact, it takes 1103 generations to stabilize, by which time it has a population of 116 and has generated six escaping gliders; these were the first spaceships ever discovered.

Frequently occurring examples (in that they emerge frequently from a random starting configuration of cells) of the three aforementioned pattern types are shown below, with live cells shown in black and dead cells in white. Period refers to the number of ticks a pattern must iterate through before returning to its initial configuration.

<table border="1">
    <tr>
        <th colspan="2">Still Lifes</th>
        <th colspan="2">Oscillators</th>
        <th colspan="2">Spaceships</th>
    </tr>
    <tr>
        <td>Block</td>
        <td>
            <img src="./assets/StillLifes/Game_of_life_block_with_border.svg">
        </td>
        <td>Blinker<br/>(period 2)</td>
        <td>
            <img src="./assets/Oscillators/Game_of_life_blinker.gif">
        </td>
    </tr>
    <tr>
        <td>Bee Hive</td>
        <td>
            <img src="./assets/StillLifes/Game_of_life_beehive.svg">
        </td>
        <td>Toad<br/>(period 2)</td>
        <td>
            <img src="./assets/Oscillators/Game_of_life_toad.gif">
        </td>
    </tr>
    <tr>
        <td>Loaf</td>
        <td>
            <img src="./assets/StillLifes/Game_of_life_loaf.svg">
        </td>
        <td>Beacon<br/>(period 2)</td>
        <td>
            <img src="./assets/Oscillators/Game_of_life_beacon.gif">
        </td>
    </tr>
    <tr>
        <td>Boat</td>
        <td>
            <img src="./assets/StillLifes/Game_of_life_boat.svg">
        </td>
        <td>Pulsar<br/>(period 3)</td>
        <td>
            <img src="./assets/Oscillators/Game_of_life_pulsar.gif">
        </td>
    </tr>
    <tr>
        <td>Tub</td>
        <td>
            <img src="./assets/StillLifes/Game_of_life_flower.svg">
        </td>
        <td>Pentadecathlon<br/>(period 15)</td>
        <td>
            <img src="./assets/Oscillators/I-Column.gif">
        </td>
    </tr>
</table>

for more info click <a href="https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life">here</a>
