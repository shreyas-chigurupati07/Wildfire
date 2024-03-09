# Wildfire

## Project Overview

This project evaluates the performance of combinatorial and sampling-based planning algorithms in a simulation where a firetruck navigates through a field of obstacles to extinguish fires, contending with an adversarial Wumpus setting new fires.

## Problem Statement

The objective is to implement and compare two motion planning algorithms: a combinatorial search algorithm (A*) and a Probabilistic RoadMap (PRM) planner. The simulation measures their effectiveness in guiding a firetruck to extinguish fires in a dynamic and challenging environment.

## Implementation Details

- **Environment:** A 250-meter square field with tetromino-shaped obstacles, where fires spread and new ones ignite over time.
- **Firetruck:** A Mercedes Unimog with standard Ackerman steering, utilizing PRM for navigation and fire extinguishing tasks.
- **Wumpus:** An adversarial entity using A* for movement, responsible for igniting fires within the simulation.

## Results

The project includes a detailed analysis of the algorithms' performance based on metrics such as the intact-to-total ratio, extinguished-to-total ratio, and burned-to-total ratio, alongside computation time comparisons.

### Combinatorial Planner A-Star
https://github.com/shreyas-chigurupati07/Wildfire/assets/84034817/298880a8-5fae-4987-8a80-6680d5c2011f



### Sampling Based PRM
https://github.com/shreyas-chigurupati07/Wildfire/assets/84034817/0252bbf0-3b89-487a-93a8-6f2aba2d589a


## Dependencies

- Python
- Matplotlib
- NumPy


## References

- Steven M. LaValle. Planning Algorithms. Cambridge University Press, May 2006.
