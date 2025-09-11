---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# 1. Numerical investigation of hydraulic forces induced by drillstring whirling and rotation dynamics
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 1;">
    Comprehensive computational fluid dynamics (CFD) simulations were conducted with the finite volume method (FVM) to estimate the hydraulic forces on drillstrings under diverse conditions. Coupled lateral-torsional movements of a drill pipe were reconstructed and approximated as the moving boundaries of the CFD model. With the hybrid/dynamic mesh, the proposed CFD model can effectively calculate the real-time annulus fluid velocity field and hydraulic forces with improved accuracy. The simulations span a wide range of drilling scenarios, exploring different drillstring whirling and rotational frequencies, with varying flow rates of Newtonian and non-Newtonian fluids in 2D and 3D domains.
  </div>
  <div style="flex: 1;">
    <img src="http://Xu-Duan.github.io/images/OMAE20252.png" alt="2D result">
    <img src="http://Xu-Duan.github.io/images/OMAE20251.png" alt="3D result">
  </div>
</div>

---
# 2. Coupled managed pressure and temperature drilling in geothermal and HPHT wells
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 1;">
    This paper introduces an integrated MPD-MTD control framework based on improved reduced drift-flux model (RDFM) that incorporates temperature dynamics, interface mass transfer, and a new lumped pressure dynamics model to describe geothermal and HPHT drilling. The proposed MPD-MTD control strategy utilizes MPD choke adjustments, flow rate modulation, and mud cooling to simultaneously regulate downhole pressure and temperature. 
    <img src="http://Xu-Duan.github.io/images/SGW2025Diagram1.png" alt="2D result">
  </div>
  <div style="flex: 1;">
    
    <img src="http://Xu-Duan.github.io/images/SGW2025Diagram2.png" alt="3D result">
  </div>
</div>

---
# 3. FEM
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 1;">
    <p><em>Numerical investigation of linear advection equation with SUPG method.</em> <a href="http://Xu-Duan.github.io/files/Numerical%20investigation%20of%20linear%20advection%20equation%20with%20SUPG%20method.pdf">Report</a></p>
    <ul>
      <li>Solved the linear advection equation with adaptive mesh refinement using deal.II and FEniCS on a Linux system.</li>
      <li>Conducted numerical experiments in 1D 2D and 3D domains.</li>
      <li>Utilized parallel computing with multiple processors accessing shared memory techniques to assemble the global matrix and accelerate computation.</li>
      <li>Compare the results and convergence rates from SUPG, Standard Galerkin, and Upwind methods.</li>
    </ul>
    <img src="http://Xu-Duan.github.io/images/solution-5-2d.png" alt="2D result">
  </div>
  <div style="flex: 1;">
    <img src="http://Xu-Duan.github.io/images/convergence_rate.png" alt="2D result">
    <img src="http://Xu-Duan.github.io/images/N20.png" alt="3D result">
  </div>
</div>

---

# 4. Shallow water wave simulation
Numerical modeling of water wave evolution in shallow and variable-depth terrain using Finite Volume Method in Fortran. [Report](http://Xu-Duan.github.io/files/CFD.pdf)
* Developed a Fortran program to numerically solve fully nonlinear Boussinesq Wave Model from scratch.
* Applied the Monotonic Upstream-centered Scheme for Conservation Law (MUSCL) for spatial discretizing and utilized the third-order Strong Stability-Preserving (SSP) Runge-Kutta scheme for time integration.

![Time step](http://Xu-Duan.github.io/images/timeStep.png)

---

# 5. Fluid model using Lattice Boltzmann Method (LBM)
Numerical investigation of a fluid domain activated by a waving plate using Lattice Boltzmann Method (LBM) 
![LBM](http://Xu-Duan.github.io/images/LBM-project.gif)

---

# 6. Image reconstruction using convex optimization
Delved into the realm of dictionary learning models and optimization algorithms to address the challenges of grayscale and color image processing. Our primary focus was on two key aspects: dictionary learning and descent methods. [Report](http://Xu-Duan.github.io/files/optimization.pdf)
![Image Comparison](http://Xu-Duan.github.io/images/Optimization.png)

---

# 7. Controller Design
*Control System Design for an Underwater Vehicle*
* Developed a Simulink model for simulating an underwater vehicle, incorporating a 4-DOF dynamic model of the ROV, along with a propulsion system model and a voltage allocation module.
* Designed a Proportional Integral Differential (PID) control system to correct deviations between the robot's actual depth and heading, achieving 18.50% and 31.57% overshoot, with settling time of 5.13s and 12.84s for depth and heading, respectively.

![depth](http://Xu-Duan.github.io/images/response-depth.png) ![heading](http://Xu-Duan.github.io/images/response-direction.png)