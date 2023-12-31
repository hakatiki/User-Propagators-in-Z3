# User-Propagators-in-Z3

## Installation

To install the Z3 package, run the following command in your terminal:

```bash
pip install z3
```

## Introduction
This document is part of our course on Advanced Verification Techniques. We aimed to develop a User Propagator, delving into the Z3 framework—a powerful tool for theorem proving and solving complex constraint satisfaction problems. The primary goal is to gain a practical understanding of Z3's operation and its application in various algorithmic challenges.

## Experiments with Z3
We started by experimenting with different algorithms within the Z3 framework. This phase was crucial in understanding the framework's versatility and robustness in diverse contexts. These initial steps were foundational in gaining experience before we embarked on creating the User Propagator.

<table>
  <tr>
    <td>
      <img src="/plots/graph_coloring_z3_peternson_3_coloring_graph_colored.png" width="300" alt="Graph Coloring - Peterson 3 Coloring">
      <br>
      <center><i>Figure 1: Graph coloring example using Z3</i></center>
    </td>
    <td>
      <img src="/plots/dodecahedral_graph_hamilton_cylcle.png" width="300" alt="Hamiltonian cycle in graph">
      <br>
      <center><i>Figure 2: Finding Hamiltonian cycle in graphs using Z3</i></center>
    </td>
  </tr>
</table>

## Focus on User Propagator
The core of this document revolves around the exploration of the User Propagator functionality in Z3. This feature allows for advanced problem-solving by enabling custom propagation strategies, which is a significant advancement over the basic capabilities of Z3.

## Advanced Problem-Solving
With the User Propagator, we tackled complex problems like the N-Queens challenge and Sudoku puzzles. This step opened new avenues for addressing intricate problems with enhanced efficiency.

<center>
<table>
  <tr>
    <td>
      <img src="/plots/8-queen.png" width="400" alt="N-Queens Solution">
      <br>
      <i>Figure 3: Solution to the N-Queens problem using Z3 User Propagators</i>
    </td>
  </tr>
</table>
</center>

<table>
  <tr>
    <td>
      <img src="/plots/sudoku_puzzle.png" width="250" alt="Sudoku puzzle">
      <br>
      <center><i>Figure 5: Sudoku puzzle</i></center>
    </td>
    <td>
      <img src="/plots/sudoku_solution.png" width="250" alt="Sudoku Solution">
      <br>
      <center><i>Figure 6: Sudoku solution using Z3 User Propagators</i></center>
    </td>
  </tr>
</table>

## Conclusion
Our journey through the Z3 framework and the creation of a User Propagator was enriching and enlightening. We successfully applied Z3 to a variety of algorithmic scenarios, demonstrating its power and adaptability.

---

