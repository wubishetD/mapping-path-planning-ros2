# Project Plan

## Overview
This plan outlines the timeline, phases, and milestones for the project.

## Timeline
| **Phase**               | **Dates**            | **Description**                                                                                     |
|--------------------------|----------------------|-----------------------------------------------------------------------------------------------------|
| Phase 1: Research & Planning | 02.12.2024 - 22.12.2024 | Literature review, algorithm selection, and scenario definition.                                   |
| Phase 2: Simulation Setup    | 23.12.2024 - 29.12.2024 | Set up Gazebo, RViz, and robot configurations.                                                     |
| Phase 3: SLAM Implementation | 30.12.2024 - 12.01.2025 | Implement SLAM and test mapping accuracy.                                                          |
| Phase 4: Path Planning       | 13.01.2025 - 26.01.2025 | Implement and test path planning algorithms in static and dynamic environments.                    |
| Phase 5: Testing & Evaluation| 27.01.2025 - 09.02.2025 | Evaluate overall system performance.                                                               |
| Phase 6: Documentation       | 10.02.2025 - 21.02.2025 | Prepare the final report and presentation.                                                         |

## Milestones
- **Week 1-2**: Literature review and initial algorithm selection.
- **Week 3**: Simulation setup and basic environment validation.
- **Week 4-6**: SLAM implementation and mapping results.
- **Week 7-8**: Path planning and navigation testing.
- **Week 9-10**: Full system evaluation.
- **Week 11-12**: Final documentation and presentation.


# **Project Plan: Mapping and Path Planning in Autonomous Navigation with ROS 2**

## **Week 1–2 (2 Dec – 15 Dec 2024): Literature Review and ROS 2 Familiarization**
### Tasks:
1. Conduct a comprehensive **literature review** on:
   - State-of-the-art (SOTA) SLAM and path-planning algorithms.
   - Integration of mapping and path planning in ROS 2.
   - Challenges in autonomous navigation (e.g., dynamic environments).
2. Gain proficiency in **ROS 2**:
   - Learn ROS 2 concepts (nodes, topics, services, and actions).
   - Experiment with tutorials and examples using TurtleBot3 in simulation.
3. Explore **Gazebo simulation environment**:
   - Set up basic simulation scenarios with TurtleBot3.

### Deliverables:
- Summary of SOTA techniques and identified research gaps.
- Basic ROS 2 and Gazebo setup ready for further work.

---

## **Week 3–4 (16 Dec – 29 Dec 2024): Simulation Environment Development**
### Tasks:
1. Create a **Gazebo simulation environment**:
   - Add static obstacles like walls, furniture, and barriers.
   - Configure TurtleBot3 with LIDAR and RGB-D sensors.
2. Validate the environment:
   - Ensure TurtleBot3 can navigate within the static setup.
   - Test sensor outputs for accuracy and reliability.

### Deliverables:
- Functional Gazebo environment with static obstacles.
- Verified TurtleBot3 configuration (movement and sensors).

---

## **Week 5–6 (30 Dec 2024 – 12 Jan 2025): SLAM Algorithm Implementation**
### Tasks:
1. Implement **SLAM algorithms**:
   - Use GMapping and SLAM Toolbox to generate maps.
2. Test mapping in static environments:
   - Analyze metrics like map accuracy, coverage, and computational efficiency.
3. Document SLAM results and identify areas for improvement.

### Deliverables:
- SLAM-generated maps of static environments.
- Initial analysis of mapping performance.

---

## **Week 7–8 (13 Jan – 26 Jan 2025): Path Planning Implementation (Global)**
### Tasks:
1. Implement **global path-planning algorithms**:
   - Use A* and Dijkstra to compute paths based on SLAM-generated maps.
2. Test global planning in static environments:
   - Evaluate path quality, length, and smoothness.
3. Integrate global planners with SLAM maps.

### Deliverables:
- Global path-planning functionality tested in static environments.
- Preliminary performance metrics for path quality.

---

## **Week 9–10 (27 Jan – 9 Feb 2025): Dynamic Environment and Local Planning**
### Tasks:
1. Add **dynamic obstacles** to the Gazebo environment:
   - Introduce moving entities like robots or simulated humans.
2. Implement **local planners**:
   - Use Dynamic Window Approach (DWA) and Timed Elastic Bands (TEB) for real-time obstacle avoidance.
3. Combine SLAM, global planning, and local planning:
   - Test the complete pipeline in environments with dynamic obstacles.

### Deliverables:
- Dynamic Gazebo environment with moving obstacles.
- Integrated navigation pipeline tested for responsiveness and adaptability.

---

## **Week 11–12 (10 Feb – 23 Feb 2025): Optimization and Validation**
### Tasks:
1. Optimize SLAM and path-planning algorithms:
   - Fine-tune parameters for better performance in dynamic scenarios.
2. Validate the full system:
   - Perform comprehensive testing in varied environments.
   - Analyze metrics like map quality, path smoothness, and system responsiveness.
3. Document final results and insights.

### Deliverables:
- Optimized algorithms and validated system performance.
- Detailed analysis of results.

---

## **Week 13 (24 Feb – 1 Mar 2025): Report and Presentation Preparation**
### Tasks:
1. Draft the project report:
   - Include methodology, experiments, results, and conclusions.
   - Use visualizations like maps, graphs, and code snippets.
2. Create presentation slides and videos:
   - Demonstrate key findings and simulation outcomes.
3. Review all deliverables for completeness and clarity.

### Deliverables:
- Drafted report in IEEE format.
- Presentation slides and simulation videos.

---

## **Week 14 (2 Mar – 15 Mar 2025): Final Submission**
### Tasks:
1. Finalize and submit the project report.
2. Submit source code and documentation.
3. Conduct the final presentation.

### Deliverables:
- Final report in PDF format.
- Complete source code and simulation files.
- Presentation and videos showcasing results.

---

## **Key Milestones**
1. **Week 2**: Literature review and ROS 2/Gazebo basics completed.
2. **Week 4**: Gazebo simulation environment finalized.
3. **Week 6**: SLAM implementation with initial results.
4. **Week 8**: Global path planning integrated and tested.
5. **Week 10**: Dynamic environment setup and local planning completed.
6. **Week 12**: Full pipeline optimized and validated.
7. **Week 13**: Report and presentation prepared.
8. **Week 14**: Final submission and presentation conducted.
