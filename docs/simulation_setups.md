## Simulation Setups

### Overview
This document provides an overview of the simulation setups used for the project **"Mapping and Path Planning in Autonomous Navigation with ROS 2"**. The setups are designed to replicate realistic environments in the Gazebo simulation framework, enabling comprehensive testing of SLAM and path-planning algorithms.

---

### Simulation Environment
The simulation environment is built in Gazebo and consists of the following key components:
- **Robot Model**: TurtleBot3 (Burger variant) equipped with:
  - Simulated LIDAR sensor for 2D mapping and obstacle detection.
  - RGB-D camera for depth perception and environment visualization.
- **Static Elements**: Walls, furniture, and other obstacles representing a structured indoor environment.
- **Dynamic Elements**: Moving entities such as other robots or pedestrians to test real-time adaptability.

---

### Configurations
1. **Gazebo World Files**:
   - Custom `.world` files are created to define the environment layout, including:
     - Static obstacles (e.g., walls, furniture).
     - Dynamic elements (e.g., moving objects).
   - Examples: `indoor_test.world`, `dynamic_scenario.world`.

2. **Robot Setup**:
   - **TurtleBot3** model is configured with:
     - A simulated Hokuyo LIDAR sensor.
     - An RGB-D camera for visual mapping and depth data.
   - ROS 2 packages: `turtlebot3_simulations`, `nav2_bringup`.

3. **SLAM Algorithms**:
   - Implementations tested include GMapping and SLAM Toolbox.
   - Configurations tailored for performance optimization in simulation.

4. **Path Planning Algorithms**:
   - **Global Planners**: A* and Dijkstra algorithms.
   - **Local Planners**: Dynamic Window Approach (DWA) and Timed Elastic Bands (TEB).

---

### Test Scenarios
1. **Static Environment Testing**:
   - Objective: Evaluate SLAM performance and mapping accuracy in structured indoor layouts.
   - Scenario: TurtleBot3 navigates a room with predefined static obstacles.

2. **Dynamic Environment Testing**:
   - Objective: Test the adaptability of path planning in dynamic scenarios.
   - Scenario: TurtleBot3 avoids moving entities while navigating toward a goal.

3. **Mixed Scenarios**:
   - Objective: Assess the integration of SLAM and path-planning systems.
   - Scenario: A combination of static and dynamic elements in a multi-room environment.

---

### Metrics for Evaluation
The following metrics are used to evaluate the simulation setups:
- **Mapping Accuracy**: Quality and coverage of generated maps.
- **Path Smoothness**: Continuity and efficiency of navigation paths.
- **System Responsiveness**: Time taken to adapt to dynamic changes.
- **Computational Efficiency**: Resource usage during SLAM and path-planning operations.

---

### Challenges and Limitations
1. **Sensor Noise**: Simulated sensors may not fully replicate real-world imperfections.
2. **Dynamic Entity Behavior**: Simulated behaviors may differ from real-world dynamics.
3. **Resource Constraints**: High computational demands for complex simulations.

---

### References
1. ROS Documentation, "Gazebo Simulation Environment," [Online]. Available: [https://gazebosim.org/](https://gazebosim.org/).  
2. Open Robotics, "TurtleBot3," [Online]. Available: [https://www.turtlebot.com/](https://www.turtlebot.com/).  
3. ROS 2 Navigation Stack Documentation, [Online]. Available: [https://navigation.ros.org/](https://navigation.ros.org/).  
