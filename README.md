# Contagion-Simulation-Project

This project is inspired by this <a href="https://www.washingtonpost.com/graphics/2020/world/corona-simulator/">Washington Post’s article that simulated infectiousness</a> with 2D cells in a graphical visualization. 

In the simulation, 2D cells are in one of three states: vulnerable (grey), infected (red), or immune (green). As the cells move around, if a vulnerable cell comes into contact with an infected cell, they become infected. After a set recovery period is over, that cell then becomes immune. The simulation ends when no cells are infected.

To simulate different situations, variables can be changed. Such as:
1. The total number of cells
2. The number of cells that start in each state at the beginning of the simulation
3. The recovery period time
4. The size of the cell
5. The speed of the cells
6. The bounds for the width and height that the simulation takes place in
