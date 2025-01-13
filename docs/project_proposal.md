## Mapping and Path Planning in Autonomous Navigation with ROS 2


| **Name**                       | **Matriculation No.** | **Role**      |
|--------------------------------|-----------------------|---------------|
| Khaled Nabil Mounir Kandil     | 1364635               | Team Member   |
| Wubishet Yibabie Damtie        | 1324950               | Team Member   |
|                                |                       |               |
| **Project Group**              | MAP-2                 |               |
| **Submission Date**            | Fri, 21-Mar-2025      |               |
| **Supervisor**                 | Prof. Dr. Peter Nauth |               |


---

### Abstract

Autonomous navigation systems must operate effectively in dynamic and structured environments, requiring precise mapping and adaptive path-planning capabilities. This project explores the integration of advanced SLAM algorithms and path-planning techniques using ROS 2 to address challenges in mapping accuracy, real-time obstacle avoidance, and computational efficiency. A simulation framework is developed in Gazebo to evaluate performance metrics such as map quality, path smoothness, and system responsiveness.  

These efforts contribute directly to advancing mapping and path planning in autonomous navigation with ROS 2, which are core aspects of autonomous intelligent systems (AIS).

---

### Introduction

Robust autonomous navigation enables robots to execute complex tasks in dynamic environments. Mapping involves constructing spatial representations of the surroundings, while path planning ensures efficient, collision-free motion. These processes are foundational to autonomous navigation and essential for adaptability and efficiency in real-world scenarios. However, challenges such as high computational demands and the need for real-time decision-making hinder optimal performance.  

Simulation-based approaches are particularly effective for such research due to their cost-efficiency, scalability, and ability to provide reproducible results. Simulated environments like Gazebo allow testing of multiple scenarios, including static and dynamic obstacles, without the logistical challenges of real-world setups. However, they may not fully replicate real-world sensor noise or environmental uncertainties, which could limit the generalizability of results.  

This project leverages ROS 2, a powerful middleware for robotics applications, to implement and optimize mapping and path-planning techniques. By addressing challenges such as dynamic obstacles, computational efficiency, and real-time adaptability, the project aims to improve system performance. The chosen methods align directly with the project title: **“Mapping and path planning in autonomous navigation with ROS 2.”**

---

### Research Objectives

1. Analyze the state-of-the-art (SOTA) in SLAM and path planning to identify limitations and potential improvements.  
2. Develop an integrated framework using ROS 2 for mapping and path planning in simulation environments.  
3. Evaluate the performance of SLAM and path-planning algorithms under various conditions, including dynamic and static obstacles.  
4. Address trade-offs between computational efficiency, mapping accuracy, and system responsiveness.  

---

### Methodology

#### Simulation Environment:
- Scenarios built in Gazebo replicate realistic challenges, combining static elements (e.g., walls, furniture) and dynamic obstacles (e.g., moving entities).  
- The TurtleBot3, equipped with simulated LIDAR and RGB-D sensors, is the primary testing platform.  

#### Mapping:
- SLAM algorithms (e.g., GMapping, SLAM Toolbox) construct spatial representations of the environment.  
- Key metrics: map accuracy, coverage, and computational efficiency.  

#### Path Planning:
- **Global Planners:** A* and Dijkstra compute optimal routes in static environments.  
- **Local Planners:** Dynamic Window Approach (DWA) and Timed Elastic Bands (TEB) ensure real-time obstacle avoidance and adaptability.  

---

### Validation and Optimization

#### Iterative Testing:
- Test SLAM algorithms independently in static environments.  
- Introduce dynamic obstacles after achieving stable SLAM results.  
- Test path planning separately using predefined maps before integrating with SLAM.  

#### Performance Metrics:
- Map quality, path length, smoothness, and system responsiveness.  

Comparative analysis is performed against established benchmarks.  

---

### Anticipated Challenges

1. **Computational demands of real-time SLAM and path planning integration.**  
   - Mitigation: Use modular testing to focus on individual components before full integration. Optimize computational parameters incrementally.  

2. **Balancing trade-offs between mapping accuracy and system responsiveness.**  
   - Mitigation: Prioritize metrics based on the application context (e.g., favor responsiveness for dynamic obstacles).  

3. **Managing interactions with dynamic obstacles while maintaining system efficiency and safety.**  
   - Mitigation: Gradually increase environment complexity in simulation tests.  

---

### Project Plan

| **Phase**                 | **Date**             | **Description**                                                                                     |
|---------------------------|----------------------|-----------------------------------------------------------------------------------------------------|
| Research & Familiarization| Week 1–3            | Conduct literature review, study SOTA algorithms, and familiarize with ROS 2 and Gazebo.            |
| Experimentation & Setup   | Week 4–5            | Experiment with TurtleBot3 in Gazebo and set up the basic simulation environment.                   |
| SLAM Implementation       | Week 6–7            | Implement SLAM algorithms, generate maps, and test mapping accuracy in static environments.         |
| Path Planning             | Week 8–9            | Implement and test global and local path-planning algorithms in static and dynamic environments.    |
| Full System Testing       | Week 10–11          | Integrate SLAM and path planning; test the complete system in dynamic scenarios and optimize results.|
| Documentation & Submission| Week 12–14          | Prepare and finalize the report, presentation, and source code for submission.                      |

---

### Key Deliverables

- **Report:** Comprehensive documentation of methodology, results, and conclusions, aligned with the mapping and path planning theme.  
- **Source Code:** ROS 2 implementation of SLAM and path-planning algorithms.  
- **Presentation:** Overview of research findings, supported by metrics and visualizations.  
- **Videos:** Demonstration of simulation scenarios and outcomes.  

---

### References

1. S. Thrun, W. Burgard, and D. Fox, *Probabilistic Robotics.* Cambridge, MA: MIT Press, 2005.  
2. ROS 2 Documentation. Available: [https://docs.ros.org/](https://docs.ros.org/).  
3. R. Siegwart et al., *Introduction to Autonomous Mobile Robots,* 2nd ed., MIT Press, 2011.  

---

### Conclusion

This project aims to enhance the integration of mapping and path planning techniques in autonomous navigation using ROS 2. By addressing challenges in accuracy, adaptability, and computational efficiency, the results will contribute to the development of more intelligent and efficient AIS. The insights gained will pave the way for advanced autonomous navigation systems capable of navigating complex, dynamic environments.

---
### Topic Proposal (TopicProp)

The detailed topic proposal for the project can be accessed via the following SharePoint link:

[Topic Proposal - Mapping and Path Planning in ROS 2](https://studfrauasde-my.sharepoint.com/:w:/g/personal/uas0021736_stud_fra-uas_de/EehqviL0XFpOky5aAc4fmacBXk6AICHUFNyeEWEnEq7j5g?e=8lFmM3)
