# Supply-Network-Optimize-Price-Optimize-Location

Our project is based on a mathematical optimization model problem available on www.gurobi.com. We chose to translate gurobi code for "Supply Network Design I" into pyomo. The original problem and gurobi code is available at : https://www.gurobi.com/jupyter_models/supply-network-design/?fbclid=IwAR0WdxrqEs0zeFJqYd9V9j-K_N1HdXpJ_YQ8CvvFJyHYTynFfxaoAjRez0A. The purpose of this problem is to satisfy all customer demand while minimize the shipping cost.

In addition to code translation, we extend further to address the optimal location to set up a factory in order to serve the demand of the product based on the associated costs. In this part, we also use pyomo to help find the optimal solution. Finally, we introduce two methods, Newton and Nelder-Mead, to solve for a optimal product price to achieve maximum profit.

Our project is devided into 3 main parts:
1. Part 1: Translate gurobi code for "Supply Network Design I" into Pyomo.
2. Part 2: Optimize locations using Pyomo.
3. Part 3: Optimize price to get maximize profit. 

### Techniques applied

Techniques applied in this project are mainly (not in order):

Pyomo Model

Optimization (minimization: using Pyomo, Newton Method, and Nelder-Mead )

Mathematical programming
