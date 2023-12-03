# AI Algorithms Implementation

This repository contains Python implementations of various Search-based AI algorithms, Constraint Satisfaction Problem (CSP) implementation, and Adversarial Search algorithms. These implementations were developed as part of an AI course.

## Contents

- [Search-based AI Algorithms](#search-based-ai-algorithms)
- [Constraint Satisfaction Problem](#constraint-satisfaction-problem)
- [Adversarial Search](#adversarial-search)
- [Usage](#usage)


## Search-based AI Algorithms

The repository includes implementations of various search algorithms, such as:

- Breadth-First Search
- Depth-First Search
- A* Search
- Greedy Best-First Search
- Uniform Cost Search

Each algorithm is designed to solve different types of problems by exploring the state space efficiently.

### Implementation Details

The repository includes implementations of various search algorithms, each tailored to solve different types of problems:

#### Breadth-First Search
- Explores all nodes at the current depth before moving on to the next level.
- Useful for finding the shortest path in unweighted graphs.

#### Depth-First Search
- Explores as far as possible along each branch before backtracking.
- Suitable for solutions where exploration depth is crucial.

#### A* Search
- Utilizes a heuristic to estimate the cost from the current state to the goal.
- Balances the cost of reaching the goal and the cost taken to get there.

#### Greedy Best-First Search
- Chooses the path that looks most promising according to a heuristic.
- May not guarantee an optimal solution.

#### Uniform Cost Search
- Expands the least-cost node in the search frontier.
- Guarantees an optimal solution in terms of cost.

## Constraint Satisfaction Problem

The Constraint Satisfaction Problem (CSP) implementation in this repository addresses problems where variables must be assigned values subject to constraints. This is a powerful paradigm for representing and solving problems in AI.


## Adversarial Search

Adversarial Search algorithms, such as Minimax and Alpha-Beta Pruning, are implemented for decision-making in competitive environments, especially in games.



## Usage

To use any of the implemented algorithms, simply clone the repository and open the .ipynb file in Google Colaboratory

