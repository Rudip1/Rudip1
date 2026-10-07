## Hi, I'm Pravin Oli

**Robotics researcher in model-based control.** I like hybrid designs: a classical, well-understood controller
with a learned component on top, so the system adapts to data without giving up the guarantees of the
classical method. I enjoy the whole path from dynamics modelling and controller design through learning and
simulation to the real robot.

**Now:** PhD researcher at the Automation and Control Institute (ACIN), TU Wien: model-based control of
closed-chain mechanisms, model predictive control and skill-based robot programming, built on a C++ multibody
and control stack.

[![Email](https://img.shields.io/badge/Email-pravin.oli.08%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:pravin.oli.08@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pravin--oli-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pravin-oli)

---

### Projects

| project | what it is |
|---|---|
| [**CA-MCW**](https://github.com/Rudip1/CA-MCW) | Context-adaptive MPPI navigation: a perception-conditioned network re-weights interpretable Nav2 critics every cycle, while feasibility stays classical. MSc thesis; ranked first of 23 controllers, zero collisions. ROS 2 · Nav2 · PyTorch → ONNX → C++ |
| [**path-ilc**](https://github.com/Rudip1/path-ilc) | Path-parameter iterative learning control on a flexible-joint KUKA iiwa14 in MuJoCo, plus a learned layer that transfers corrections to unseen paths and compensates thermal drift. Tool error ≈34 mm → ≈1 mm |
| [**pomona-nexus**](https://github.com/Rudip1/pomona-nexus) | Agricultural field robot workspace: an AgileX Scout V2 that maps, navigates furrows and treats crop beds with UV-C. ROS 2 · Nav2 · Gazebo |
| [**vehicle-manipulator-task-priority**](https://github.com/Rudip1/vehicle-manipulator-task-priority) | Kinematic control of a mobile base and arm as one system via task-priority redundancy resolution |
| [**pekf-slam-icp**](https://github.com/Rudip1/pekf-slam-icp) | Pose-based EKF SLAM with ICP laser scan matching |
| [**lidar-exploration**](https://github.com/Rudip1/lidar-exploration) | Autonomous exploration with a 2D LiDAR: information-gain goal sampling, Dubins-RRT*, pure pursuit |
| [obj_manipulation](https://github.com/IFRoS-ELTE/obj_manipulation) *(team)* | Grasping unseen objects on an xArm6 + Scout: YOLOv8, SAM, Contact-GraspNet, MoveIt, dual-ROS Docker |

### Learning: [robotics-learning](https://github.com/Rudip1/robotics-learning)

Robotics from first principles: theory, C++ implementations and interactive notebooks, one module per subject:
[motion planning](https://github.com/Rudip1/learn-motion-planning) ·
[state estimation](https://github.com/Rudip1/learn-state-estimation) ·
[manipulator control](https://github.com/Rudip1/learn-manipulator-control) ·
[computer vision](https://github.com/Rudip1/learn-computer-vision) ·
[sensor fusion](https://github.com/Rudip1/learn-sensor-fusion)

### Technical reports

- *Context-Adaptive Multi-Critic Controller using Deep Learning-Based Cost Weighting in Autonomous Navigation*, MSc thesis, 2026 — [PDF](https://github.com/Rudip1/CA-MCW/blob/main/thesis/pravin_elteikthesis_en.pdf)
- *Path-Parameter ILC with a Learned Correction Layer for High-Accuracy Industrial Robots*, 2026 — [PDF](https://github.com/Rudip1/path-ilc/blob/main/technical_report/full_technical_report.pdf)
- *Kinematic Control of a Vehicle–Manipulator System Using Task-Priority Redundancy Resolution*, 2025 — [PDF](https://github.com/Rudip1/vehicle-manipulator-task-priority/blob/main/docs/Hands_On_Intervention_Report.pdf)
- *Pose-Based EKF SLAM Using ICP Laser Scan Matching*, 2025 — [PDF](https://github.com/Rudip1/pekf-slam-icp/blob/main/docs/Hands_on_Localization_Report.pdf)
- *Autonomous Exploration with a 2D LiDAR and Dubins-RRT\* Planning*, 2025 — [PDF](https://github.com/Rudip1/lidar-exploration/blob/main/docs/planning_followup.pdf)

### Education

- **PhD**, Automation and Control Institute (ACIN), TU Wien, Austria — 2026–
- **MSc Intelligent Field Robotic Systems (IFROS)**, Erasmus Mundus Joint Master (fully funded) —
  Eötvös Loránd University, Hungary, and University of Girona, Spain — 2024–2026
- **BEng Mechanical Engineering**, Tribhuvan University, Nepal — 2017–2022

### Toolbox

**Control:** MPC, MPPI, ILC, task-priority IK, flexible-joint and multibody modelling ·
**Learning:** PyTorch, ONNX, PPO ·
**Robotics:** ROS 2, Nav2, MoveIt, SLAM ·
**Simulation:** MuJoCo, Gazebo, Isaac Sim ·
**Code:** C++, Python, MATLAB/Simulink, Docker, LaTeX

![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1F6FEB)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
