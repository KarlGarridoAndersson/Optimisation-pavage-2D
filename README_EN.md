# Discrete Optimization of Geometric Compactness: 2D Tiling

This repository contains the research work and algorithmic implementation related to the study of the automatic assembly of connected blocks (polyominoes).

## Research Summary
This project tackles the **NP-complete** complexity of the tiling problem. The goal is to maximize the compactness of an assembly on a discrete grid using heuristic approaches based on vertex topology.

### Developed Heuristics
* **H1 (Greedy Approach)**: Selection and placement based on the maximum vertex order.
* **H2 (Structural Adaptation)**: Use of a vertex-to-vertex fit metric to optimize interlocking.
* **H3 (Local Reference)**: Local brute-force algorithm used as a baseline to evaluate the performance of the solutions.

## Performance Indicators
The success of the algorithms is measured through:
1. **Compactness index**: Analysis of the area-to-perimeter ratio of the envelope.
2. **Morphological similarity**: Comparison with theoretical optimal configurations.

## Repository Structure
* `/Notebook`: Source code for the merging logic and heuristic computations.
* `/article`: Full text of the publication detailing the mathematical model.
* `/guide utilisation`: Guide to understanding the different variables introduced in the notebook.
