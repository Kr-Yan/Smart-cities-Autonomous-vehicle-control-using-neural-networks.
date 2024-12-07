# Smart-cities-Autonomous-vehicle-control-using-neural-networks.
## Team
Shashwat Singh, Sai Akshay Menta, Niranjan Satish, Shuwen Wang and Kairuo Yan


## Project Overview
This project is a car simulation system built in Unity that integrates a neural network and A* algorithm to guide vehicles efficiently from a starting point to a destination. The simulation emphasizes intelligent pathfinding, vehicle dynamics, and real-time decision-making. Vehicles navigate a grid-based environment while avoiding obstacles, using an optimized path determined by A* and further enhanced by neural network predictions.

---

## Features
- **Intelligent Navigation**: Vehicles autonomously navigate from a start to an end point using A* for pathfinding and a neural network for decision-making.
- **Dynamic Environments**: Simulated environments include grid-based maps with obstacles and waypoints.
- **Neural Network Control**: A neural network predicts vehicle speed and turning angle based on environmental and vehicle dynamics.
- **Performance Metrics**: Tracks metrics like travel time, stops, and path deviation for evaluation.
- **Visualization**: Real-time visualization of paths, waypoints, and vehicle movement.

---



## Setup & Installation
1. Clone this repository to your local machine:
   git clone "url".

2. Open the project in Unity (tested on Unity 2021.x and above).

3. Load the `MainScene` from the `Assets/Scenes` folder.

4. Run the simulation by pressing the Play button in Unity.

---

## How It Works
### Pathfinding
- The A* algorithm calculates the optimal path between the starting and ending points, considering obstacles and grid constraints.
- Path smoothing reduces sharp turns for a more realistic trajectory.

### Neural Network
- Inputs: Sensor data such as distances to obstacles, current speed, and waypoint information.
- Outputs: Target speed and turning angle to optimize navigation.
- Training: The network learns from simulated scenarios, using loss functions to minimize path deviation, enhance speed efficiency, and ensure smooth turning.

### Simulation
- Vehicles follow the A*-computed path while adapting in real-time using neural network predictions.
- Metrics like travel time and collisions are recorded for evaluation.

---

## Experiments
The neural network was trained and tested in various simulated scenarios:
- Different map configurations, including obstacle density and waypoint arrangements.
- Hyperparameter tuning for the neural network (e.g., learning rate, hidden layers).
- Performance metrics were visualized in plots to compare results across experiments.

---

## Results
- **Efficient Navigation**: Vehicles successfully reached destinations with minimal path deviation and optimized speeds.
- **Adaptive Behavior**: The neural network adapted to different environments, improving over multiple iterations.

---

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major contributions, open an issue to discuss the proposal.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


