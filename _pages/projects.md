---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# 1. FEM
*Numerical investigation of linear advection equation with SUPG method.* [Report](http://Xu-Duan.github.io/files/Numerical%20investigation%20of%20linear%20advection%20equation%20with%20SUPG%20method.pdf)
* Solved the linear advection equation with adaptive mesh refinement using deal.II on a Linux system.
* Utilized parallel computing with multiple processors accessing shared memory techniques in deal.II to assemble the global matrix and accelerate computation.

## 2D result
![2D result](http://Xu-Duan.github.io/images/solution-5-2d.png)

## 3D result
![3D result](http://Xu-Duan.github.io/images/solution-2-3d.png)

---

# 2. Shallow water wave simulation
Numerical modeling of water wave evolution in shallow and variable-depth terrain using Finite Volume Method in Fortran. [Report](http://Xu-Duan.github.io/files/CFD.pdf)
* Developed a Fortran program to numerically solve fully nonlinear Boussinesq Wave Model from scratch.
* Applied the Monotonic Upstream-centered Scheme for Conservation Law (MUSCL) for spatial discretizing and utilized the third-order Strong Stability-Preserving (SSP) Runge-Kutta scheme for time integration.

![Time step](http://Xu-Duan.github.io/images/timeStep.png)

---

# 3. Fluid model using Lattice Boltzmann Method (LBM)
Numerical investigation of a fluid domain activated by a waving plate using Lattice Boltzmann Method (LBM) 
![LBM](http://Xu-Duan.github.io/images/LBM-project.gif)

---

# 4. Image reconstruction using convex optimization
Delved into the realm of dictionary learning models and optimization algorithms to address the challenges of grayscale and color image processing. Our primary focus was on two key aspects: dictionary learning and descent methods. [Report](http://Xu-Duan.github.io/files/optimization.pdf)
![Image Comparison](http://Xu-Duan.github.io/images/Optimization.png)

---

# 5. Controller Design
*Control System Design for an Underwater Vehicle*
* Developed a Simulink model for simulating an underwater vehicle, incorporating a 4-DOF dynamic model of the ROV, along with a propulsion system model and a voltage allocation module.
* Designed a Proportional Integral Differential (PID) control system to correct deviations between the robot's actual depth and heading, achieving 18.50% and 31.57% overshoot, with settling time of 5.13s and 12.84s for depth and heading, respectively.

![depth](http://Xu-Duan.github.io/images/response-depth.png) ![heading](http://Xu-Duan.github.io/images/response-direction.png)

# 6. Wind Speed Prediction
*Wind Speed Prediction with Neural Networks	and Signal Decomposition Techniques* [Report](http://Xu-Duan.github.io/files/Wind-Prediction.pdf)
* Conducted short-term wind speed forecasting using a Long Short-Term Memory (LSTM) neural network based on historical wind speed data.
* Employed signal processing techniques to preprocess raw wind speed data for improved model accuracy.
