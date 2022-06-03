# GRAPH-COLORING-IN-SUDOKU-SOLVER-GAME
DESCRIPTION:

   Sudoku Graph consists of graph with 81 vertices/nodes. Each cell in the Sudoku can be seen as a vertices/node of the graph. Each node/cell has an edge to every other node/cell in its respective column, row, and grid 
 
   Chromatic Number minimum number of colors needed to color a proper coloring of a graph

   Sudoku can be solved by Graph Coloring with a Chromatic Number, G = 9
 
REQUIREMENTS:

   The code is written for python 3.6.10, but should work for other version with some modifications.

   pip install -r requirements.txt

PYTHON SCRIPT OVERVIEW:

   graph.py - It create nodes and vertices of the graph
   sudoku_connections.py - It manages graph and connect all the nodes in SUDOKU Grid format
   main.py – It will show input and output grid (SUDOKU form)

RUN:

   python graph.py
   python sudoku_connections.py
   python main.py
   
