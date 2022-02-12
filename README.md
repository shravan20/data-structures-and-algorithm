# Data-Structures-&-Algorithms
Repo contains the development explanation and code for Data Structure and Algorithm


This repository contains JavaScript based examples of many popular algorithms and data structures. Each algorithm and data structure has its own separate README with related explanations and links for further reading.


### Data Structure Operations Cheatsheet

```ruby
╔═══════════════╦═══════════════════════════════════════════════╦═══════════════════════════════════════════════╦════════════╗
║               ║          Average Case Time Complexity         ║           Worst Case Time Complexity          ║   Space    ║
║     Data      ║                                               ║                                               ║ Complexity ║
║   Structure   ╠═════════════╦══════════╦═══════════╦══════════╬═════════════╦══════════╦═══════════╦══════════╬════════════╣
║      Name     ║  Accessing  ║  Search  ║ Insertion ║ Deletion ║  Accessing  ║  Search  ║ Insertion ║ Deletion ║ Worst Case ║
║               ║ nth element ║          ║           ║          ║ nth element ║          ║           ║          ║            ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║     Arrays    ║     O(1)    ║   O(n)   ║    O(n)   ║   O(n)   ║     O(1)    ║   O(n)   ║    O(n)   ║   O(n)   ║    O(n)    ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║     Stacks    ║     O(n)    ║   O(n)   ║    O(1)   ║   O(1)   ║     O(n)    ║   O(n)   ║    O(1)   ║   O(1)   ║    O(n)    ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║     Queues    ║     O(n)    ║   O(n)   ║    O(1)   ║   O(1)   ║     O(n)    ║   O(n)   ║    O(1)   ║   O(1)   ║    O(n)    ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║  Binary Trees ║     O(n)    ║   O(n)   ║    O(n)   ║   O(n)   ║     O(n)    ║   O(n)   ║    O(n)   ║   O(n)   ║    O(n)    ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║    Binary     ║   O(log n)  ║ O(log n) ║  O(log n) ║ O(log n) ║     O(n)    ║   O(n)   ║    O(n)   ║   O(n)   ║    O(n)    ║
║  Search Trees ║             ║          ║           ║          ║             ║          ║           ║          ║            ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║    Balanced   ║             ║          ║           ║          ║             ║          ║           ║          ║            ║
║     Binary    ║   O(log n)  ║ O(log n) ║  O(log n) ║ O(log n) ║   O(log n)  ║ O(log n) ║  O(log n) ║ O(log n) ║  O(log n)  ║
║ Search Trees  ║             ║          ║           ║          ║             ║          ║           ║          ║            ║
╠═══════════════╬═════════════╬══════════╬═══════════╬══════════╬═════════════╬══════════╬═══════════╬══════════╬════════════╣
║  Hash Tables  ║     N/A     ║   O(1)   ║    O(1)   ║   O(1)   ║     N/A     ║   O(n)   ║    O(n)   ║   O(n)   ║    O(n)    ║
╚═══════════════╩═════════════╩══════════╩═══════════╩══════════╩═════════════╩══════════╩═══════════╩══════════╩════════════╝
```
### Search & Sort Algorithms Operations Cheatsheet

![](https://he-s3.s3.amazonaws.com/media/uploads/c950295.png)



<details> 
<summary>Different types of Algorithmic Approaches:</summary>

1. **Brute Force Algorithm**: To device an optimal solution first we need to get a solution at least and then try to optimise it. Every problem can be solved by brute force approach although generally not with appreciable space and time complexity.

2. **Recursive Algorithm**: An approach where an algorithm calls itself again and again until a base condition is achieved whereas iterative algorithm uses loops. Every recursive problem can be solved as an iterative solution and vice versa.

3. **Divide & Conquer Algorithm**: It works on a top-down approach and is preferred for a large problems, where basically you divide the problems into several sub problems. Conquer/Solve each sub problem and combine each sub-problem to get the required result. This algorithm divides the problems into subproblems and then solve each of them and then combine them to form the solution of the given problems.

4. **Dynamic Programming Algorithm**:  It is a bottom-up approach, where we solve all possible small problems then combine them to obtain solutions for bigger problems. Particularly helpful when the number of copying subproblems is exponentially large, and closely related to Optimization problem.
This is a technique for solving optimization problems by breaking them into smaller sub-problems and storing sub-solutionso that the correspinding sub-problem can be solved only once.  Its simply means remembering the past and apply it to future corresponding results and hence this algorithm is quite efficient in terms of time complexity. It is a good methodology for optimization problems that seek the maximal/minimal solutio with restriction as it searches through all possible sub problems and never recomputes the conclusion to any sub problem.

5. **Greedy Algorithm**: In greedy approach, at each step, a decision is made to choose the local optimum, without thinking about the future consequences. It is usually used to solve the optimization problem. An optimization problem is one in which we are given a set of input values, which are required either to be maximized or minimized (known as objective), i.e. some constraints/conditions. This approach doesn't always guarantee the optimal solution however generally produces a solution that is very close in value to the optimal.

6. **Backtracking Algorithm**: In any backtracking problems, the algorithm tries to find a path to the feasible solution which has some intermediary checkpoints. In case they don’t lead to the feasible solution, the problem can backtrack from the checkpoints and take another path in search of the solution.

7. **Branch and Bound Algorithm**: It is an algorithm design paradigm which is generally used for solving combinatorial problems. These problems are typically exponential in terms of time complexity and may require exploring all the possible permutations in worst case. 
</details>
