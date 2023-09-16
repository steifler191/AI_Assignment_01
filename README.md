# AI_Assignment_01

This repository contains code and related materials for AI Assignment 01.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Introduction
From a given array which is treated as a state .So, we have to find the neighbour state and check the wheather it is a goal state or not.
If not We check another neighbour state in Search ALgorithms .

I use the Search Algorithms:
1) Breadth First Search
2) Depth First Search
3) Iterative Deepening Depth First Search
4) Uniform Cost Search
5) Greedy First Search
6) A* Search


   A* is the Best Search Coming out the ALL the above .

   For Neighbour Search swapping two Adjacent number cost = 1

   basically we have to find the ALgorithm from the mention above which is the best for finding the optimal path .

   1)For Breadth First Search -- We have to use the queue as a fringe
   2)Depth First Search --- we have stack as a fringe
   3)Iterative Deepening Dept First Search -- we use stack but also the variable which use MAx depth to store and we tried it to minimise it.
   4)uniform Cost Search -- we use the priority queue as a fringe which cost biased.
   5)Greedy First Search --- we use the priority queue as a fringe which heuristic biased which is defined as number of elments not in there respective place in its sorted version.
   6)A* Search -- also uses priority queue but the combination of the UCS and Greedy first search .
   7)Hill climbing -- uses only a heuristic function .

   Then we see the Average length of the path of various Search we use.
   


### Prerequisites
can opened in the VSCode or any another platform in which .pynb file can be opened.


## Contributing
you can highlight the mistake in implementing the queue.


## Acknowledgments
I Thank to Dr. Yashaswi Verma For providing the Knowledge of the Above Algorithms because of which i was able to implement the code in python.

