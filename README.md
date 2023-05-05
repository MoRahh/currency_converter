# Maze Solver with Python and Curses
This is a Python program that uses the curses library to display a maze and finds a path from the starting point to the ending point in the maze. The program uses a breadth-first search algorithm to find the path.

# Requirements
Python 3.x
curses library (usually pre-installed on Unix-based systems)

# Usage
To run the program, navigate to the directory containing the maze.py file and run the following command:
python main.py
The program will display the maze and the path taken to solve it.

# How it works
The program reads in a maze represented as a list of lists, where each element in the list represents a cell in the maze. The '#' character represents a wall, the Empty one represents an open space, 'O' represents the starting point, and 'X' represents the ending point.

The program then uses a breadth-first search algorithm to find the shortest path from the starting point to the ending point. During the search, the program displays the maze and the current path being taken in the maze using the 'print_maze' function and the 'curses' library.

The 'wrapper' function from the 'curses' library is used to initialize the 'curses' library and set up the screen for displaying the maze.

# Credits
This program was created by MoRahh.