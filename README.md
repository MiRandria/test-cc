# Complexity Analysis of Rice Cooker Simulator

## 1. Calculation of Complexity for the Original Code:

Suppose the total number of user actions is represented by NN.

The complexity of the while loop can be expressed as O(N), where NN is the total number of iterations of the while loop. Each iteration includes displaying the menu, user input, and executing an action based on the user's choice.

The general formula for the complexity of the while loop is:

```bash
Complexity=Total number of iterations×(Complexity per iteration)```

In this case:

    - The total number of iterations (NN) depends on the number of user actions.
    - The complexity per iteration primarily depends on the execution time of operations inside the loop (displaying the menu, user input, and executing an action).


 ## 2. Calculation of Complexity after Refactoring:

After refactoring, the temporal complexity of your program may still be primarily determined by the number of user actions, as the interactive nature of the program likely hasn't changed. If the refactoring optimized certain parts of the code but didn't fundamentally alter the algorithmic logic, the complexity would generally remain of the order O(N)O(N), where NN represents the number of user actions.

It's essential to note that algorithmic complexity is often more relevant for algorithms dealing with datasets or specific problems rather than interactive programs. In the case of an interactive program, complexity is often more related to how the user interacts with the program rather than a specific input dataset.
