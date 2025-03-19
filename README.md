# Dream Team

Integer Linear Programming (ILP)

Integer Linear Programming is a mathematical optimization technique that guarantees an optimal solution. You can use ILP to solve this problem as follows:
### Variables:
#### Let xixi be a binary variable:
  ##### xi=1xi=1 if player ii is selected.
  ##### xi=0xi=0 otherwise.

### Objective:
#### Maximize the total score:
  ##### Maximize ∑i=1nScorei⋅xiMaximize i=1∑nScorei⋅xi

• Constraints:
1.	Select exactly 11 players:
##### ∑i=1nxi=11i=1∑nxi=11
2.	Stay within the budget:
##### ∑i=1nCosti⋅xi≤ai=1∑nCosti⋅xi≤a
3.	Binary variables:
##### xi∈{0,1}∀ixi∈{0,1}∀i

Advantages of ILP
##### Guaranteed Optimality: ILP solvers use advanced algorithms (e.g., branch-and-bound) to find the exact optimal solution.
##### Flexibility: You can easily add or modify constraints (e.g., minimum number of batsmen, bowlers, etc.).
##### Scalability: Modern ILP solvers can handle large datasets efficiently.


