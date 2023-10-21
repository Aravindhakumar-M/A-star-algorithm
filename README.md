# RRT-Star Algorithm:

This repository contains Python code for the RRT* (Rapidly-exploring Random Tree Star) algorithm. The RRT* algorithm is a motion planning algorithm used to find feasible paths for a robot or agent in a given environment while avoiding obstacles. This implementation uses the Pygame library for visualization and provides a basic example of how the algorithm works.

## Prerequisites:
**Before running the code, make sure you have the following installed:**

Python 3.x,
Pygame library.
**You can install Pygame using pip:**
```bash
pip install pygame
```

## Getting Started:

Clone the repository or download the code to your local machine.
Navigate to the directory containing the code.
Running the Code
To run the RRT* algorithm, follow these steps:

## Execute the rrt_star.py script:

```bash
python3 rrt_star.py
```
You will be prompted to enter the size of obstacles and the number of obstacles in the environment.

A Pygame window will appear, displaying the start and goal positions as well as randomly generated obstacles. The RRT* algorithm will attempt to find a path from the start to the goal while avoiding obstacles.

Once the algorithm has completed, the optimal path will be displayed in pink.

## Code Structure:
The code is divided into two parts:

## **rrt_star.py:**
This script contains the main implementation of the RRT* algorithm. It includes functions for node expansion, rewiring, and path visualization.

## **lineIntersect.py:**
This script contains helper functions for checking intersection between line segments.

## **Customizing the Environment:**
You can customize the environment by adjusting the parameters in the rrt_star.py script. For example, you can change the size and number of obstacles, the start and goal positions, and the number of iterations (NUMNODES) the algorithm should run.

## Customize the environment here
`size = int(input("Enter the size of the obstacles : "))`

`n = int(input("Enter the no of obstacles : "))`

## Define start and goal positions
`start = Node(0.0, 0.0)`

`goal = Node(630.0, 470.0)`

## Number of iterations for the RRT* algorithm
`NUMNODES = 2000`

**License:**
This code is provided under the MIT License. You are free to use and modify it for your own projects.

**Acknowledgments:**
This code is based on the RRT* algorithm and Pygame library. Special thanks to the developers of Pygame for providing a convenient way to visualize the algorithm's execution.

Feel free to explore and modify the code to suit your needs. Happy coding!
