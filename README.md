<h1 align="center">Enes Erisen</h1>

<p align="center">
  <strong>MSc Autonomy Technologies · Robotics, Sensor Fusion and Control</strong>
</p>

<p align="center">
  ROS 2 · Camera/LiDAR/Radar Data · State Estimation · Engineering Software
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&amp;logo=c&amp;logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&amp;logo=cplusplus&amp;logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/MATLAB-EF6C00?style=flat-square" alt="MATLAB" />
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&amp;logo=ros&amp;logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&amp;logo=cmake&amp;logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" />
</p>

---

I am an MSc student in Autonomy Technologies at FAU with a BSc in Electrical and Electronics Engineering from Atilim University. My primary portfolio focuses on robotics, autonomous systems, sensor data, control, embedded systems and reproducible engineering software.

I am targeting robotics, autonomy and Robot Deployment Engineer roles. The evidence below comes from deterministic simulation, synthetic data and public datasets; planned work and validation limits are labelled explicitly.

**Currently building:** [Autonomous Sensor Fusion Lab](https://github.com/seneserisen/autonomous-sensor-fusion-lab) and [FaultNav ROS 2](https://github.com/seneserisen/ros2-autonomous-mobile-robot).

## Selected engineering projects

| Project | What is implemented | Status and boundary |
| --- | --- | --- |
| [Autonomous Sensor Fusion Lab](https://github.com/seneserisen/autonomous-sensor-fusion-lab) | Deterministic nuScenes table traversal, timestamp diagnostics, calibrated sensor-to-ego/global transforms, cross-time LiDAR/radar camera projection, bird's-eye visualization and synthetic CI fixtures. | **Active, v0.1 foundation.** A real nuScenes mini run is still pending; no detection, tracking or physical sensor validation is claimed. |
| [FaultNav ROS 2](https://github.com/seneserisen/ros2-autonomous-mobile-robot) | Exact differential-drive motion, quantised encoder and seeded IMU simulation, fault injection, encoder-derived odometry, ROS 2 odometry/TF, reports and automated tests. | **Active.** Controlled software simulation only; EKF, physics simulation, SLAM, Nav2 and hardware work remain future milestones. |
| [Automatic Control Laboratory](https://github.com/seneserisen/automatic-control-lab-projects) | Five nonlinear/state-space control studies, LQR, observers, saturation and anti-windup, independent Python references and portable C99 runtimes. | **Maintained.** MATLAB, Python and C software validation; no hardware or production-controller claim. |
| [Industrial Quality Anomaly Monitor](https://github.com/seneserisen/industrial-quality-anomaly-monitor) | Deterministic synthetic manufacturing data, global and machine-aware robust baselines, Isolation Forest, a shared-dataset comparison runner, reports, Docker and tests. | **Active.** Synthetic comparison evidence, not real-factory performance. |
| **Power Electronics Manufacturing** | A tested Python shear-curve workflow covering preprocessing, features, batch validation, review-oriented outlier evidence, capability gates and two-parameter Weibull analysis. | **Maintained, private repository.** Generic/synthetic data only; no proprietary or production validation evidence. |

## Engineering foundations in development

- **Embedded BMS and CAN Simulator** — specification and milestone plan only. The intended C++ battery model, protection state machine and virtual CAN workflow do not yet have an executable foundation.
- **Radar / ISAR Classification Pipeline** — specification and milestone plan only. Dataset processing, baselines and evaluation are not yet implemented.

## Technical evidence

| Area | Demonstrated tools and methods |
| --- | --- |
| **Robotics and autonomy** | Python, ROS 2 interfaces, differential-drive modelling, sensor/fault simulation, odometry, TF and deterministic scenarios |
| **Autonomous-driving data** | nuScenes devkit, camera/LiDAR/radar calibration, coordinate transforms, timestamp diagnostics, projection and bird's-eye visualization |
| **Control and embedded foundations** | MATLAB, state-space methods, LQR, observers, numerical integration, saturation, anti-windup, portable fixed-size C99 and CMake/CTest |
| **Manufacturing analytics** | NumPy, pandas, scikit-learn, robust statistics, Isolation Forest, curve analysis, process diagnostics and Weibull modelling |
| **Engineering workflow** | pytest, Ruff, GitHub Actions, Docker, reproducible CLIs and reviewable CSV/JSON/SVG/PNG artifacts |

## How I work

- Separate ground truth, measurements, estimates and evaluation data.
- Record units, coordinate frames, timestamps and assumptions explicitly.
- Use deterministic scenarios and tests before publishing measurements.
- Keep failure handling and rejected data visible instead of silently cleaning it away.
- Distinguish software evidence from real-world validation.

---

<p align="center">
  <strong>Engineering evidence should be measurable, testable and reproducible.</strong><br />
  <a href="https://github.com/seneserisen">github.com/seneserisen</a>
</p>
