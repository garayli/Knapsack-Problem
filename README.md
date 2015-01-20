# Knapsack-Problem

A code finds an optimal solution of Knapsack problem

Approach used : Tabu Search Algorithm,Greedy algorithm

Description of approach used :

First,greedy algorithm is used for getting initial solution.By dividing profit array by weight array, appropriate fraction array was got. The one having maximum fraction number is selected as a solution vector. The weight and fitness (profit) of solution vector is computed. For getting better solutions (we call them decision vectors), we begin change/ mutate them by an algorithm. So that, after mutation, if there is any improvement in fitness value, check in tabu list, take it as an optimal value, add to tabu and move to the another neighbour. Else, go back, and mutate/ change other gene of decision vector,check in tabu list,compute fitness.

All relevant parameters and their settings:

Tabu length = 20


