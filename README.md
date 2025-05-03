# Bipolar DC Power Flow Methods

This repository contains the MATLAB implementation files accompanying the paper:

**Title:** Formulation and Solution of the Power Flow Problem in Bipolar DC Distribution Networks with Unbalanced Constant Power Loads

**Summary:**  
This paper presents a comprehensive study on the formulation and solution of the power flow problem in bipolar DC distribution networks with unbalanced constant power loads. Using the nodal voltage method, a unified nonlinear model is proposed that captures both monopolar and bipolar configurations, including the voltage coupling between conductors, under the assumption of a solidly grounded neutral.  

Seven iterative algorithms are implemented and compared, including:
- Three Newton-Raphson-based formulations  
- Four quasi-Newton methods with constant Jacobian approximations  

The models were validated on two benchmark systems:
- 21-bus network  
- 85-bus network  

**Key findings:**  
- Newton-based methods offer quadratic convergence and high accuracy.  
- Quasi-Newton methods significantly reduce computational time, making them better suited for large-scale systems.  
- The study highlights the trade-off between convergence speed and computational efficiency.

---

## Repository Contents

This repository provides:
- **Seven MATLAB script files**, each implementing one of the proposed power flow algorithms.
- Example test cases for the 21-bus and 85-bus networks.
- A short usage guide for running the scripts.
