# A\* Path Finding Algorithm Visualization

This project is a visualization of the A\* pathfinding algorithm using Pygame. The algorithm uses Euclidean distance as the heuristic to find the shortest path between a start and an end point on a grid, while navigating around barriers.

## Features

- Visual representation of the A\* pathfinding algorithm.
- Adjustable grid size.
- Ability to place start and end points.
- Ability to place barriers.
- Visualization of the pathfinding process.
- Reset and clear the grid for new searches.

## Installation

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install the required dependencies:
   ```bash
   pip install pygame
   ```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/LordZeusIsBack/astar-pathfinding-visualization.git
   ```
2. Navigate to the project directory:
   ```bash
   cd astar-pathfinding-visualization
   ```
3. Run the script:
   ```bash
   python astar_visualization.py
   ```

## How to Use

- **Left Click**:

  - Place the start point (orange).
  - Place the end point (turquoise).
  - Place barriers (black).

- **Right Click**:

  - Remove the start point.
  - Remove the end point.
  - Remove barriers.

- **Space Key**: Start the pathfinding algorithm.

- **C Key**: Clear the grid.

## Screenshots

![Start Screen](screenshots/start-screen.png)<br>
_This is the basic start screen_

![Pathfinding in Progress](screenshots/pathfinding-in-progress.png)<br>
_Here the algorithm is finding the path to the destination_

![Path Found](screenshots/path-found.png)<br>
_The shortest path was found by the algorithm and constructed on the pygame window_

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements and bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The Pygame community for their excellent resources and support.

## Contact

For any inquiries or feedback, please contact [anubhavsharma5645@gmail.com].
