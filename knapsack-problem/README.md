# Knapsack Problem

`MS Excel Solver`, `Scipy` and `PuLP` implementations of a sample Knapsack Problem 

### Problem Definition:

We need to plan for a hiking trip and take all the intems that can provide us the highest value for the hiking trip. However, we only have a knapsack (backpack) with a capacity of 5 kgs. Hence, we cannot take all the items and have to choose carefully. We need to choose items in such a way that the value is maximized and we do not exceed the 5kg capacity of the knapsack.

### Mathematical Formulation:
**Objective:**  
$
\max \sum \limits_{i=1}^{n} x_i \times V_i
$

**Subject to constraints:**  
$
\sum \limits_{i=1}^{n} x_i \times w_i  <= C
$

**Where:**   
$C$ is the total knapsack capacity  
$x_i \in \{0,1\}$ i.e. $x_i$ is a binary decision variable for each item available for selection (0 indicates do not select and 1 indicates selection)  
$V_i$ is the relative value of each item available for selection  
$w_i$ is the weight of each item that is available for selection
