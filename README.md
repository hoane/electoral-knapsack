Python Jupyter notebook which solves for the minimum number of votes required to flip the national electoral result.

Takes as input a list of states with the state vote margin and electoral vote allocation for each.
Outputs the list of states to flip and the sum of votes required to flip them.

This problem is a version of the [knapsack problem](https://en.wikipedia.org/wiki/Knapsack_problem).
The solution here uses dynamic programming to solve the problem in `O(nk)`, where `n` is the number of states and `k` is the electoral vote margin.
