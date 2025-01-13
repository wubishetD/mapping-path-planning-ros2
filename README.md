
# Autonomous Intelligent Systems Project

<!-- PROJECT LOGO -->
<img src="resources/images/FRA-UAS_Logo_rgb.jpg" width="150"/>

<h3 align="center">MAP-2: Mapping and Path Planning in Autonomous Navigation with ROS 2</h3>

<p align="center">
    <br>
   This project focuses on mapping and path planning for autonomous navigation using ROS 2. It enables robots to map their environment and autonomously plan optimal paths for navigation, ensuring efficient and safe movement in dynamic environments.
    <br>
    <br>
    <br>
    <strong>MAP-2 Group Members:</strong>
</p>

<div align="center">

| **Name**                    | **Matriculation Number** |
|-----------------------------|--------------------------|
| Wubishet Yibabie Damtie     |       1324950            |
| Khaled Nabil Mounir Kandil  |       1364635            |


</div>


---
## Feature Overview

This project explores the implementation of **Mapping and Path Planning in Autonomous Navigation** using ROS 2. At this stage, the features below represent **planned objectives** 

*   [ ] **Mapping (SLAM)**: Explore SLAM (Simultaneous Localization and Mapping) algorithms like **Cartographer**, **GMapping**, or **SLAM Toolbox** to generate maps of the environment.
*   [ ] **Path Planning**: Investigate path planning algorithms such as **A***, **Dijkstra**, or **RRT** for efficient and dynamic navigation.
*   [ ] **Simulation**: Set up simulations using **Gazebo** with pre-built environments to test mapping and path planning capabilities.
*   [ ] **Visualization**: Use **RViz** to display robot state, maps, and navigation paths in real time.
*   [ ] **Performance Evaluation**: Define metrics to evaluate mapping accuracy, path efficiency, and re-planning latency.
*   [ ] **Documentation**: Provide detailed guides for setting up and running the project.

---
## Table of Contents
1. [Project Overview](#project-overview)
2. [Quick Links](#quick-links)
3. [System Architecture](#system-architecture)
4. [Installation and Setup](#installation-and-setup)
5. [Directory Structure](#directory-structure)
6. [How to Use This Repository](#how-to-use-this-repository)
7. [Results and Visuals](#results-and-visuals)
8. [Future Work](#future-work)
9. [FAQ](#faq)
10. [License](#license)


---

## Project Overview
- **Title**: Mapping and Path Planning in Autonomous Navigation with ROS 2
- **Approach**: Simulation-based
- **Timeline**: 02.12.2024 - 21.02.2025
- **Tools**: ROS 2, Gazebo, RViz, TurtleBot3, Cartographer, A*, RRT.

### Objectives:
1. Develop a mapping system using **SLAM algorithms**.
2. Implement **path planning algorithms** for goal-driven navigation.
3. Evaluate system performance in simulated environments of varying complexity.

---

## Quick Links
1. [Project Plan](./docs/project_plan.md)  
   - Includes detailed milestones, phases, and timeline.
2. [Project Proposal](./docs/project_proposal.md)  
   - Includes title, summary, context, objectives, methodology, challenges, timeline, deliverables, references, and conclusion.
2. [Deliverables](./docs/deliverables.md)  
   - Lists deliverables for each phase of the project.
3. [Simulation Scenarios](./docs/simulation_scenarios.md)  
   - Details on test environments for SLAM and path planning algorithms.
4. [Algorithm Choices](./docs/algorithm_choices.md)  
   - Explains the rationale for SLAM and path planning algorithm selection.
5. [Performance Metrics](./docs/performance_metrics.md)  
   - Defines evaluation criteria for mapping, navigation, and overall system performance.
6. [Final Report](./docs/final_report.md)  
   - Links to the final project report (to be completed).
7. [Presentation Slides](./docs/presentation_slides.md)  
   - Links to the final presentation slides (to be completed).




---
## System Architecture

The project consists of three core components:
1. **SLAM (Mapping)**: For creating maps of the environment in real time.
2. **Path Planning**: For determining optimal paths from the robot's current position to a goal.
3. **Navigation**: For executing planned paths and re-planning dynamically if necessary.

<!-- ![System Architecture](./resources/images/system_architecture.png) -->

The diagram for the system architecture will be added soon.

---


## Installation and Setup
To set up the project on your machine, follow the steps in the [Installation Guide](./docs/installation.md).

---

## Directory Structure

The directory structure for the **Mapping and Path Planning in Autonomous Navigation with ROS 2** project is organized as shown for clarity, scalability, and ease of use. 

```bash
📂 mapping-path-planning-ros2/
├── 📂 docs/
│   ├── project_plan.md
│   ├── ...
├── 📂 resources/
│   ├── 📂 images/
│   │   ├── FRA-UAS_Logo_rgb.jpg
│   │   ├── system_architecture.png
│   ├── 📂 config/
│   ├── 📂 datasets/
├── 📂 results/
├── 📂 simulations/
├── 📂 src/
├── README.md
├── LICENSE
```

This directory structure is continuously updated as the project progresses. For the most up-to-date structure, see the [Project Directory Structure](./docs/project_structure.md).

---

## How to Use This Repository
- **Setup Instructions**: Refer to the [Installation Guide](./docs/installation.md) for ROS 2 and Gazebo setup.
- **Codebase**: ROS 2 packages for mapping and navigation are located in the `src/` directory.
- **Simulations**: Pre-configured Gazebo worlds are available in the `simulations/` directory.



---
## Results and Visuals



---
## Future Work



---
## FAQ



---
## License
This project is licensed under a custom educational license. See the [LICENSE](./LICENSE) file for full terms and conditions.