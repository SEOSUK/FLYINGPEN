# Flying Pen
*Real-Time Contact-Aware Control for Aerial Manipulator via Normal Vector Estimation on Unstructured Surfaces*

**Project Period:** Jan. 2025 – Present

*Manuscript in preparation — IEEE Robotics and Automation Letters (RA-L).*

## 🔹 Overview

<div align="center">
  <img src="https://github.com/user-attachments/assets/b5701bbc-d4ff-4747-9418-96afbec797ca"
       alt="Flying Pen System Overview"
       width="900">
</div>

- **Contact Force Estimation:** Estimates the interaction wrench from momentum-observer residuals while adapting thrust effectiveness online.
- **Surface Normal Estimation:** Estimates the local surface normal from the contact wrench and contact-consistent motion information.
- **Surface Swiping Control:** Modulates tangential velocity in real time based on local surface-normal variation to maintain stable contact over unstructured surfaces.

## 🎥 Preliminary Experiment

### Early-Stage Demonstration

https://github.com/user-attachments/assets/69a10c2e-2a55-4dab-9d5c-9ec235f88d85

*Early-stage demonstration using an initial version of the Flying Pen framework.*

### Thrust Effectiveness Correction

https://github.com/user-attachments/assets/accd8cf2-8e62-4524-8cb4-f559fa3b9234

*Comparison between the raw momentum observer (MOB) and the η_T-updated MOB, showing improved alignment of the estimated force direction with the wall normal.*

## 🔹 Repository Structure

- [`firmware`](./firmware) — [`FLYINGPEN-FIRMWARE`](https://github.com/SEOSUK/FLYINGPEN-FIRMWARE), modified Crazyflie firmware for **real-world experiments, contact-force estimation, thrust-effectiveness adaptation, and contact-aware control**.
- [`ros2_interface`](./ros2_interface) — [`FLYINGPEN_ROS2-INTERFACE`](https://github.com/SEOSUK/FLYINGPEN_ROS2-INTERFACE), ROS 2 interface for **commanding, experiment control, and flight-data logging**.
- [`MuJoCo Simulation`](https://github.com/SEOSUK/mujoco_crazyflie) — MuJoCo-based environment for **simulation and validation of the Flying Pen algorithms**.

## 🔹 Previous Work

The initial surface-normal-estimation study was presented as a poster at **KRoC 2025**.

🔗 [KRoC 2025 — Normal Estimation](https://github.com/SEOSUK/DONE-KROC_Normal_Estimation)
