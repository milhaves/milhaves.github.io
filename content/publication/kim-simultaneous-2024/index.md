---
title: Simultaneous Tracking and Balancing Control of Two-Wheeled Inverted Pendulum
  with Roll-joint using Dynamic Variance MPPI
authors:
- Taehyun Kim
- Jechan Jeon
- Myo-Taeg Lim
- Yisoo Lee
- Yonghwan Oh
date: '2024-11-01'
publishDate: '2025-09-21T00:13:10.042839Z'
publication_types:
- paper-conference
publication: '*2024 IEEE-RAS 23rd International Conference on Humanoid Robots (Humanoids)*'
doi: 10.1109/Humanoids58906.2024.10769962
abstract: The Two-Wheeled Inverted Pendulum with Rolljoint (TWIP-R) model and Dynamic
  Variance Model Predictive Path Integral (DV-MPPI) controller are proposed to simultaneously
  solve tracking and balancing problems. The TWIP-R model’s additional roll joint
  allows it to better handle centrifugal forces, offering superior performance in
  high-speed curved driving compared to the traditional TWIP model. Similar to the
  TWIP model, the TWIP-R model also cannot achieve position tracking without additional
  kinematic control due to the linearization process. Therefore, controlling the TWIP-R
  can be achieved using Model Predictive Path Integral (MPPI), which is capable of
  handling nonlinear control. However, MPPI often suffers from chattering issues due
  to the use of Gaussian random noise, leading to control instability. DV-MPPI controller
  dynamically adjusts random noise variance based on real-time state errors, reducing
  chattering and improving stability. By controlling the TWIP-R using DV-MPPI, we
  simultaneously solved the tracking and balancing problems without any additional
  kinematic tracking control, achieving smooth output. Experimental results show our
  approach is effective, demonstrating the TWIP-R model’s superior performance in
  balancing and tracking and the benefits of the DV-MPPI.
tags:
- Dynamics
- Humanoid robots
- Kinematics
- Noise
- Predictive models
- Real-time systems
- Stability analysis
- Testing
- Tracking
- Trajectory
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10769962
---
