# Hi, I'm Priestly 👋

**Robotics Software Engineer | ROS 2 · Python · Gazebo · Linux**  
*M.S. in Robotics — Colorado School of Mines*

I build and evaluate robotics software, with a focus on **autonomous systems, sensor reliability, and evidence-based testing**. My background spans software engineering, machine learning, autonomous drone research, and Linux-based systems troubleshooting.

I care about a practical question: **How can we tell when a robot's behavior is actually supported by trustworthy evidence?**

## Selected projects

### 🛑 [Stop Evidence Monitor (SEM)](https://github.com/priestly-ops/stop-evidence-monitor)
An observation-only ROS 2 research prototype that checks whether a stop request has supporting command and motion evidence.

- Evaluates normal-stop, misrouted-stop, and missing-LiDAR scenarios in a controlled Gazebo setup.
- In [20 repeated simulation trials](https://github.com/priestly-ops/stop-evidence-monitor/blob/main/evidence/m4_repeat20/summary.json) (60 scenario observations), each scenario returned its predefined expected status.
- Explicitly documents an [unresolved correlated-sensor spoofing failure](https://github.com/priestly-ops/stop-evidence-monitor/blob/main/docs/known-failures.md).

*Research prototype only; not a safety-certified stop system or a hardware-validated reliability claim.*

### 🔬 [COLDSTART](https://github.com/priestly-ops/COLDSTART)
A robotics anomaly-detection research framework studying how much healthy commissioning data is needed to evaluate detectors under scarce-data conditions.

- Focuses on leakage-safe experiments, calibration, false-alarm constraints, and reproducible comparisons.
- Research and cross-dataset validation are ongoing; no deployment certification is claimed.

## What I work with

`Python` · `ROS 2` · `Gazebo` · `Linux` · `Git` · Robotics Simulation · Sensor Integration · System Debugging · Machine Learning

## Currently exploring

- Robot localization, navigation, and sensor consistency
- Fault detection and trustworthy behavior under uncertain observations
- Reproducible robotics experiments and practical reliability engineering

## Let's connect

I'm interested in **robotics software engineering, system integration, research collaboration, and open-source robotics**.

[LinkedIn](https://www.linkedin.com/in/priestly-mlengineer/) · [GitHub projects](https://github.com/priestly-ops?tab=repositories)
