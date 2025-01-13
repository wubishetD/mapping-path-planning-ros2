## **Project Plan: Mapping and Path Planning in Autonomous Navigation with ROS 2**

### Overview
This plan outlines the timeline, phases, and milestones for the project.

### Timeline
| **Phase**                | **Dates**            | **Description**                                                                                     |
|---------------------------|----------------------|-----------------------------------------------------------------------------------------------------|
| Phase 1: Research & Familiarization | 02.12.2024 - 22.12.2024 | Conduct literature review, study state-of-the-art algorithms, and familiarize with ROS 2 and Gazebo. |
| Phase 2: Experimentation & Setup    | 23.12.2024 - 05.01.2025 | Experiment with TurtleBot3 in Gazebo and set up the basic simulation environment.                    |
| Phase 3: SLAM Implementation        | 06.01.2025 - 19.01.2025 | Implement SLAM algorithms, generate maps, and test mapping accuracy in static environments.          |
| Phase 4: Path Planning              | 20.01.2025 - 02.02.2025 | Implement and test global and local path planning algorithms in static and dynamic environments.     |
| Phase 5: Full System Testing        | 03.02.2025 - 16.02.2025 | Integrate SLAM and path planning; test the complete system in dynamic scenarios and optimize results. |
| Phase 6: Documentation & Submission | 17.02.2025 - 15.03.2025 | Prepare and finalize the report, presentation, and source code for submission.                       |

### Milestones
- **Week 1-3**: Literature review, ROS 2/Gazebo familiarization, and research on algorithms.
- **Week 4-5**: Basic Gazebo environment setup and experimentation.
- **Week 6-7**: SLAM implementation and static environment mapping results.
- **Week 8-9**: Path planning integration and testing.
- **Week 10-11**: Full system evaluation in dynamic scenarios.
- **Week 12-14**: Final report, presentation preparation, and submission.


### **Week 1–3 (2 Dec – 22 Dec 2024): Literature Review and ROS 2 Familiarization**
#### Tasks:
1. Conduct an in-depth **literature review**:
   - State-of-the-art (SOTA) SLAM algorithms and path-planning techniques.
   - Challenges in integrating mapping and path planning in autonomous navigation.
   - Existing solutions and gaps in ROS 2-based implementations.
2. Learn **ROS 2 basics**:
   - Work through tutorials covering nodes, topics, services, and actions.
   - Experiment with sample packages and simulation examples using TurtleBot3.
3. Explore **Gazebo simulation environment**:
   - Learn the basics of creating and configuring environments.

#### Deliverables:
- Comprehensive summary of SOTA techniques and identified gaps.
- Familiarity with ROS 2 and basic operations using TurtleBot3 in simulation.
- Basic understanding of Gazebo for creating environments.

---

### **Week 4–5 (23 Dec 2024 – 5 Jan 2025): Experimentation and Simulation Setup**
#### Tasks:
1. Perform **experimentation** with:
   - TurtleBot3 movement in Gazebo.
   - Configuration of LIDAR and RGB-D sensors in simulations.
2. Develop a simple **Gazebo simulation environment**:
   - Static obstacles (walls, barriers, etc.).
   - Test TurtleBot3 sensor outputs and navigation.
3. Implement **basic SLAM algorithms** (e.g., GMapping):
   - Generate simple maps of the environment.
   - Analyze initial SLAM results for accuracy and feasibility.

#### Deliverables:
- Functional simple simulation environment in Gazebo.
- Initial SLAM-generated maps.
- Documentation of experimentation results and findings.

---

### **Week 6–7 (6 Jan – 19 Jan 2025): SLAM Algorithm Implementation**
#### Tasks:
1. Complete implementation of **SLAM algorithms**:
   - Use advanced SLAM techniques like SLAM Toolbox.
   - Generate detailed maps of the simulation environment.
2. Test SLAM in static environments:
   - Evaluate map accuracy, coverage, and computational efficiency.
3. Document SLAM results and address any issues.

#### Deliverables:
- SLAM-generated maps of static environments.
- Analysis of SLAM performance metrics.

---

### **Week 8–9 (20 Jan – 2 Feb 2025): Path Planning Implementation (Global)**
#### Tasks:
1. Implement **global path-planning algorithms**:
   - A* and Dijkstra for optimal route planning.
2. Integrate global path planners with SLAM-generated maps.
3. Test global path planning in static environments:
   - Analyze path quality, length, and smoothness.

#### Deliverables:
- Global path-planning functionality tested in static environments.
- Preliminary performance metrics for path quality and navigation.

---

### **Week 10–11 (3 Feb – 16 Feb 2025): Dynamic Environment and Local Planning**
#### Tasks:
1. Extend the Gazebo simulation with **dynamic obstacles**:
   - Introduce moving entities (e.g., other robots, humans).
2. Implement **local path-planning algorithms**:
   - Use Dynamic Window Approach (DWA) and Timed Elastic Bands (TEB).
3. Combine SLAM, global planning, and local planning:
   - Test the complete pipeline in dynamic environments.

#### Deliverables:
- Dynamic simulation environment with moving obstacles.
- Integrated navigation pipeline tested for responsiveness and adaptability.

---

### **Week 12 (17 Feb – 23 Feb 2025): Optimization and Validation**
#### Tasks:
1. Optimize the navigation pipeline:
   - Fine-tune SLAM and path-planning parameters for improved performance.
2. Validate the full system:
   - Test in a variety of scenarios (static and dynamic).
   - Evaluate key metrics like map quality, path smoothness, and system responsiveness.
3. Document final results.

#### Deliverables:
- Optimized and validated navigation pipeline.
- Test results and analysis.

---

### **Week 13 (24 Feb – 1 Mar 2025): Report and Presentation Preparation**
#### Tasks:
1. Draft the project report:
   - Methodology, experiments, results, and conclusions.
   - Include visualizations such as maps, graphs, and screenshots.
2. Prepare presentation slides and videos:
   - Demonstrate key findings and simulation outcomes.
3. Review and refine all deliverables.

#### Deliverables:
- Drafted report in IEEE format.
- Presentation slides and simulation videos.

---

### **Week 14 (2 Mar – 15 Mar 2025): Final Submission**
#### Tasks:
1. Finalize and submit the project report.
2. Submit source code and other documentation.
3. Conduct the final presentation.

#### Deliverables:
- Final report in PDF format.
- Complete source code and simulation files.
- Presentation and videos showcasing project outcomes.

---

### **Key Milestones**
1. **Week 3**: Literature review and ROS 2 familiarization completed.
2. **Week 5**: Basic Gazebo environment and SLAM experimentation completed.
3. **Week 7**: SLAM implementation with detailed maps completed.
4. **Week 9**: Global path planning integrated and tested.
5. **Week 11**: Dynamic environment and local planning implemented.
6. **Week 12**: Full pipeline optimized and validated.
7. **Week 13**: Report and presentation prepared.
8. **Week 14**: Final submission and presentation conducted.


