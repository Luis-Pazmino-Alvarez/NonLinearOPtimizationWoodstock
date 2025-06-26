# Optimization of Furniture Production – Woodstock Co.
This project models and solves a linear programming problem using the graphical method to help Woodstock Co. determine the optimal mix of tables and chairs that maximizes profit under resource constraints.

Problem Description
Woodstock Co. produces chairs and tables. Each product requires a certain amount of labor and wood, and the company seeks to maximize profits given limited resources. The key elements of the problem are:

Chairs

Profit: $20 each

Requires 2 hours of labor and 4 units of wood

Tables

Profit: $30 each

Requires 3 hours of labor and 5 units of wood

Constraints

Maximum of 120 hours of labor available

Maximum of 200 units of wood available

Objective
Maximize the total profit:

java
Copiar
Editar
Maximize Z = 20x + 30y
Subject to:

scss
Copiar
Editar
2x + 3y ≤ 120  (labor constraint)
4x + 5y ≤ 200  (wood constraint)
x, y ≥ 0       (non-negativity)
Solution Approach
The problem is solved graphically.

Feasible region is plotted based on constraints.

Corner points (vertices) of the feasible region are identified.

The profit function is evaluated at each vertex to find the optimal solution.

Tools Used
Python

Matplotlib

NumPy

Output
Graph showing constraints and feasible region

Optimal production mix

Maximum profit

📝 License Distributed under the GNU GPL 3.0 License.

📬 Contact

Created by Luis Pazmino Alvarez, consultant in finance, economics, and predictive modeling. Connect with me on LinkedIn https://www.linkedin.com/in/luis-pazmino-702838248/.
