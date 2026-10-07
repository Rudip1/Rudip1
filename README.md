## Pravin Oli

PhD researcher in robot control at the Automation and Control Institute (ACIN), TU Wien.

I work on model-based control of robots: multibody modelling, optimal control and their real-time
implementation, with learned components where a model alone is not enough. My background runs from mechanical
engineering through mobile robotics and perception to control of industrial and parallel robots.

[![Email](https://img.shields.io/badge/pravin.oli.08%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:pravin.oli.08@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pravin--oli-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pravin-oli)

### Current work

PhD at ACIN, TU Wien (2026–), on skill-based control of industrial robots: a robot skill is specified as an
optimal-control problem and executed by a model predictive controller together with a constraint layer at drive
rate. Alongside the thesis I am building:

- a multibody dynamics library (C++ and Python) for serial, parallel and closed-chain mechanisms, validated
  against Pinocchio, MuJoCo and Drake;
- a real-time controller framework in C++ that runs the same controller in simulation and on Beckhoff TwinCAT;
- a MuJoCo digital twin of a linear-delta parallel robot, with MPC (acados, CasADi) and deployment through
  MATLAB/Simulink to TwinCAT.

This code is not public yet.

### Selected projects

| project | |
|---|---|
| [CA-MCW](https://github.com/Rudip1/CA-MCW) | Context-adaptive MPPI navigation: a small network re-weights the interpretable Nav2 critics each control cycle; feasibility checking stays classical. MSc thesis. |
| [path-ilc](https://github.com/Rudip1/path-ilc) | Path-parameter iterative learning control on a flexible-joint KUKA iiwa14 model in MuJoCo, with a learned layer for unseen paths and thermal drift. |
| [pomona-nexus](https://github.com/Rudip1/pomona-nexus) | ROS 2 workspace for an agricultural field robot: mapping, row navigation and UV-C treatment. |
| [vehicle-manipulator-task-priority](https://github.com/Rudip1/vehicle-manipulator-task-priority) | Mobile base and arm controlled as one kinematic system with task-priority redundancy resolution. |
| [pekf-slam-icp](https://github.com/Rudip1/pekf-slam-icp) | Pose-based EKF SLAM with ICP scan matching. |
| [lidar-exploration](https://github.com/Rudip1/lidar-exploration) | Autonomous exploration with a 2D LiDAR, information-gain goals and Dubins-RRT*. |

[**robotics-learning**](https://github.com/Rudip1/robotics-learning): course-style modules (theory, C++,
notebooks) on motion planning, state estimation, manipulator control, computer vision and sensor fusion.

### Technical reports

- Context-Adaptive Multi-Critic Controller using Deep Learning-Based Cost Weighting in Autonomous Navigation. MSc thesis, 2026. [PDF](https://github.com/Rudip1/CA-MCW/blob/main/thesis/pravin_elteikthesis_en.pdf)
- Path-Parameter ILC with a Learned Correction Layer for High-Accuracy Industrial Robots, 2026. [PDF](https://github.com/Rudip1/path-ilc/blob/main/technical_report/full_technical_report.pdf)
- Kinematic Control of a Vehicle–Manipulator System Using Task-Priority Redundancy Resolution, 2025. [PDF](https://github.com/Rudip1/vehicle-manipulator-task-priority/blob/main/docs/Hands_On_Intervention_Report.pdf)
- Pose-Based EKF SLAM Using ICP Laser Scan Matching, 2025. [PDF](https://github.com/Rudip1/pekf-slam-icp/blob/main/docs/Hands_on_Localization_Report.pdf)
- Autonomous Exploration with a 2D LiDAR and Dubins-RRT* Planning, 2025. [PDF](https://github.com/Rudip1/lidar-exploration/blob/main/docs/planning_followup.pdf)

### Skills

| area | |
|---|---|
| Modelling | rigid multibody dynamics (recursive algorithms, closed-chain constraints, reduced models), serial and parallel kinematics, flexible joints · Pinocchio, MuJoCo, Drake, SymPy, CasADi, Simscape |
| Control and optimisation | MPC and optimal control (acados, CasADi, IPOPT, qpOASES), MPPI, iterative learning control, computed-torque and impedance control, task-priority control, trajectory generation |
| Planning | graph search, sampling-based planners, Dubins paths, DWA, behaviour trees · MoveIt 2, Nav2 |
| Estimation and perception | Kalman and particle filters, EKF-SLAM, ICP, GNSS, point clouds, multi-view geometry · OpenCV |
| Learning | PyTorch, ONNX export to C++, PPO |
| Real-time and deployment | C++17, C99, real-time coding rules · Beckhoff TwinCAT 3, MATLAB/Simulink code generation · ROS 2, Docker |
| Engineering practice | CMake, GoogleTest, CI, sanitizers, Python, MATLAB, LaTeX, Git |

### Background

- **PhD**, Automation and Control Institute (ACIN), TU Wien, Austria. 2026–
- **MSc Intelligent Field Robotic Systems**, Erasmus Mundus Joint Master: Eötvös Loránd University, Hungary,
  and University of Girona, Spain. 2024–2026. Probabilistic robotics, manipulation, autonomous systems,
  multi-view geometry, 3D sensing and sensor fusion, deep learning. Thesis in industrial collaboration with
  European Knowledge Centre, Budapest.
- **BEng Mechanical Engineering**, Tribhuvan University, Nepal. 2017–2022. Robotics competitions: 1st place,
  TechFest IIT Bombay 2020.
- Research assistant at Kathmandu University and Tribhuvan University (2022–2023); lecturer at CTEVT, Nepal
  (2023–2024).

Languages: English (C1), Nepali (native), Hindi/Urdu, Spanish (A2), German (A1, learning).
