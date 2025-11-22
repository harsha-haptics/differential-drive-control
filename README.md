# Differential Drive Control – Jacobian-Based Cartesian Feedback

This repository contains the simulation and documentation for a differential-drive mobile robot
controlled using Jacobian-based Cartesian feedback.

## 📄 Files Included

- `differential_drive.pdf` – Full document explaining the control method.
- `mobile_robot.py` – Python simulation of the closed-loop controller.
- `fig-1.png`, `fig-2.png` – Figures used in the documentation.

## 🚀 Description

The simulation implements:
- PD feedback in Cartesian space  
- Jacobian pseudoinverse mapping to wheel velocities  
- Ideal motor model  
- Dead-reckoning for pose reconstruction  
- Sinusoidal reference trajectory  

## 📚 How to Run the Code

```bash
python mobile_robot.py
