## Literature Review

### Introduction
Autonomous navigation is a key area of robotics, enabling robots to map environments, localize themselves, and plan optimal paths. The integration of Simultaneous Localization and Mapping (SLAM) with path-planning algorithms is essential for achieving efficient, collision-free navigation. This literature review explores existing research on SLAM algorithms, path-planning techniques, and simulation-based development, with a focus on using ROS 2 for autonomous navigation.

---

### SLAM Algorithms
Simultaneous Localization and Mapping (SLAM) is fundamental for building accurate representations of unknown environments while tracking a robot’s position. Several SLAM algorithms are widely used in robotics, each with its advantages and limitations.

#### **GMapping**
GMapping is a 2D SLAM algorithm based on Rao-Blackwellized particle filters. It efficiently estimates a robot’s pose and generates accurate maps in structured environments.
- **Key Reference**: S. Thrun, W. Burgard, and D. Fox, *Probabilistic Robotics*, MIT Press, 2005.  
  [Book Link](https://mitpress.mit.edu/9780262201629/probabilistic-robotics/)  
- **Key Strength**: Balances accuracy and computational efficiency, making it suitable for real-time navigation in 2D environments.
- **Limitation**: Does not support 3D mapping or dynamic environments.

#### **SLAM Toolbox**
SLAM Toolbox, designed specifically for ROS 2, offers advanced features such as lifelong mapping and real-time optimization.
- **Key Reference**: ROS Documentation, "SLAM Toolbox," [Online]. Available: [https://navigation.ros.org](https://navigation.ros.org/).  
- **Key Strength**: Provides compatibility with ROS 2, making it suitable for both static and dynamic environments.
- **Limitation**: Focused on 2D mapping; computational efficiency may vary with map size.

#### **Cartographer**
Cartographer is an advanced SLAM algorithm developed by Google for 2D and 3D mapping. It uses graph-based optimization for real-time performance.
- **Key Reference**: A. Hess et al., "Real-Time Loop Closure in 2D LIDAR SLAM," in *IEEE ICRA*, 2016.  
  [Paper Link](https://google-cartographer.readthedocs.io/en/latest/)  
- **Key Strength**: Highly accurate for structured and unstructured environments.
- **Limitation**: Computationally intensive, requiring powerful hardware for 3D mapping.

---

### Path Planning Algorithms
Path planning ensures that robots can navigate from start to goal positions efficiently, avoiding obstacles along the way. It is typically divided into global and local path planning.

#### **Global Path Planners**
1. **A***:
   - A graph-based algorithm that finds the shortest path based on heuristic cost evaluation.
   - **Key Reference**: H. Choset et al., *Principles of Robot Motion*, MIT Press, 2005.  
     [Book Link](https://mitpress.mit.edu/9780262033275/principles-of-robot-motion/)  
   - **Strength**: Guarantees an optimal solution for static environments.
   - **Limitation**: Inefficient in dynamic environments due to computational overhead.

2. **Dijkstra**:
   - A classic graph-based algorithm for finding the shortest path.
   - **Key Reference**: E. Dijkstra, "A Note on Two Problems in Connexion with Graphs," *Numerische Mathematik*, 1959.  
     [Paper Link](https://www-m3.ma.tum.de/foswiki/pub/MN0506/WebHome/dijkstra_1959.pdf)  
   - **Strength**: Simple and reliable for static maps.
   - **Limitation**: Computationally expensive for large maps.

#### **Local Path Planners**
1. **Dynamic Window Approach (DWA)**:
   - A real-time local planner that calculates velocities to avoid obstacles while heading toward the goal.
   - **Key Reference**: D. Fox et al., "Dynamic Window Approach to Collision Avoidance," in *Autonomous Robots*, 1997.  
     [Paper Link](https://link.springer.com/article/10.1023/A:1008855018929)  
   - **Strength**: Effective for real-time navigation in dynamic environments.
   - **Limitation**: May struggle in cluttered environments.

2. **Timed Elastic Bands (TEB)**:
   - Optimizes the robot's trajectory by considering constraints such as velocity and obstacle proximity.
   - **Key Reference**: C. Rösmann et al., "Trajectory Modification Considering Dynamic Constraints," in *IEEE ICRA*, 2015.  
     [Paper Link](https://www.researchgate.net/publication/272019654)  
   - **Strength**: Suitable for dynamic environments with high-speed requirements.
   - **Limitation**: Computational overhead increases with map complexity.

---

### Simulation-Based Development
Simulations provide a cost-effective and scalable way to develop and test autonomous systems before deploying them in the real world.

#### **Gazebo Simulation**
Gazebo is a popular simulation environment for robotics research, offering physics-based interactions and sensor emulation.
- **Key Reference**: Gazebo Documentation, [Online]. Available: [https://gazebosim.org/](https://gazebosim.org/).  
- **Key Strength**: Supports ROS 2 integration and complex simulation scenarios.
- **Limitation**: May not perfectly replicate real-world sensor noise and dynamics.

#### **Simulation vs. Real-World Testing**
- **Key Reference**: S. Mocanu et al., "Testing Autonomous Systems Using Simulation: Best Practices," *Journal of Autonomous Robotics*, 2022.  
  - Simulations allow testing edge cases that are hard to replicate in physical environments.
  - **Limitation**: Results may require tuning during hardware implementation.

---

### ROS 2 for Robotics
ROS 2 introduces several enhancements over ROS 1, including improved real-time capabilities and better support for distributed systems.
- **Key Reference**: Open Robotics, "ROS 2 Overview," [Online]. Available: [https://docs.ros.org/en/rolling/](https://docs.ros.org/en/rolling/).  
- **Key Features**:
  - DDS-based communication for improved performance.
  - Compatibility with modern SLAM and path-planning packages.
- **Limitation**: Migration from ROS 1 to ROS 2 can be complex for legacy systems.

---

### Research Gaps
Despite significant progress in SLAM, path planning, and simulation, several challenges remain:
1. **Integration**: Combining SLAM and path-planning algorithms in dynamic environments requires further optimization.
2. **Real-Time Performance**: Many algorithms struggle to balance accuracy and responsiveness.
3. **Simulation Limitations**: Results from Gazebo may not fully translate to real-world applications.

These gaps motivate this project, which focuses on developing an integrated framework in ROS 2 for mapping and path planning.

---

### Conclusion
This literature review highlights the state-of-the-art in SLAM, path planning, and simulation-based development. It also identifies key challenges in integrating these techniques for autonomous navigation. The findings provide a foundation for this project, which aims to enhance mapping and path-planning systems using ROS 2.

---

### References
1. S. Thrun, W. Burgard, and D. Fox, *Probabilistic Robotics*, MIT Press, 2005. [Book Link](https://mitpress.mit.edu/9780262201629/probabilistic-robotics/)  
2. ROS Documentation, "SLAM Toolbox," [Online]. Available: [https://navigation.ros.org/](https://navigation.ros.org/).  
3. A. Hess et al., "Real-Time Loop Closure in 2D LIDAR SLAM," in *IEEE ICRA*, 2016. [Paper Link](https://google-cartographer.readthedocs.io/en/latest/)  
4. H. Choset et al., *Principles of Robot Motion*, MIT Press, 2005. [Book Link](https://mitpress.mit.edu/9780262033275/principles-of-robot-motion/)  
5. E. Dijkstra, "A Note on Two Problems in Connexion with Graphs," *Numerische Mathematik*, 1959. [Paper Link](https://www-m3.ma.tum.de/foswiki/pub/MN0506/WebHome/dijkstra_1959.pdf)  
6. D. Fox et al., "Dynamic Window Approach to Collision Avoidance," in *Autonomous Robots*, 1997. [Paper Link](https://link.springer.com/article/10.1023/A:1008855018929)  
7. Gazebo Documentation, [Online]. Available: [https://gazebosim.org/](https://gazebosim.org/).  
8. Open Robotics, "ROS 2 Overview," [Online]. Available: [https://docs.ros.org/en/rolling/](https://docs.ros.org/en/rolling/).  
