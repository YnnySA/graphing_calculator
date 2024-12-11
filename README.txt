GRAPHING CALCULATOR
==================

A simple interactive graphing calculator that allows users to plot multiple mathematical functions on the same coordinate system.

Features:
---------
- Plot multiple functions simultaneously
- Interactive input system
- Support for basic mathematical operations and numpy functions
- Grid display with x and y axes
- Auto-generated legend
- Resizable plotting window

How to Use:
-----------
How to Use:
-----------
1. Open graphing_calculator.ipynb in Jupyter Notebook:
   - Launch Jupyter Notebook
   - Navigate to the project directory
   - Click on graphing_calculator.ipynb to open

2. Run the notebook:
   - Either click "Run All" from the Cell menu
   - Or run each cell individually using Shift+Enter

3. When the input prompt appears, enter mathematical functions using 'x' as the variable
   Example: x**2 or np.sin(x)

4. Press Enter without any input to finish and display the graph

Note: Make sure all required packages (matplotlib, numpy) are installed in your Jupyter environment

Example Functions:
----------------
- x**2         (parabola)
- np.sin(x)    (sine wave)
- 2*x + 1      (linear function)
- x**3         (cubic function)
- np.cos(x)    (cosine wave)

Requirements:
------------
- Python 3.x
- matplotlib>=3.5.0
- numpy>=1.21.0

Installation:
------------
1. Install required packages:
   pip install -r requirements.txt

2. Run the program:
   graphing_calculator.ipynb

Notes:
------
- Valid functions must use 'x' as the variable
- numpy functions should be prefixed with 'np.'
- Invalid expressions will be caught and reported
