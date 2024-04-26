# CHEME 4/5800 Enumerate Network Paths Project
Template repository for the enumerate network path problem.

## Description
One of the exciting challenges in chemical pathway design is to assemble possible multiple-step chemical reaction pathways that connect a starting compound, e.g., Glucose, and a target compound, e.g., 1,3-propanediol. Design and implement a program to enumerate all possible pathways connecting a source compound and a target compound given a specified list of chemical reactions. Explore networks of increasing complexity. A potential approach would be to use linear programming to compute a minimum cost path, then remove edges from that path one at a time and, in combination, rerun the computation to generate a new path. Alternatively, routes could be calculated using heuristic pathfinding approaches such as Ant Colony Optimization (ACO).
* Example reaction data is included in the [e_coli_core.json file](data/e_coli_core.json), which was taken from the [Core E. Coli model of Palsson and coworkers](https://systemsbiology.ucsd.edu/Downloads/EcoliCore). Use the reaction network to develop your pathway prediction approach.
