# MD-AMPC-PathTracking
Demo videos for the paper "Statistics-Aware Adaptive MPC Using Mahalanobis Distance for Path Tracking"

# Statistics-Aware Adaptive MPC Using Mahalanobis Distance for Path Tracking
## Abstract
Model Predictive Control (MPC) is widely applied to path tracking in
autonomous vehicles due to its ability to handle constraints and optimize
future trajectories. However, fixed weighting matrices in standard MPC
formulations often fail to adapt to varying error statistics, leading to
suboptimal performance in dynamic environments. This paper proposes an
adaptive MPC framework based on Mahalanobis Distance (MD-AMPC) that uses
the Mahalanobis Distance as a statistical measure to quantify
multidimensional state errors and their correlations, and dynamically
adjusts the quadratic cost weights. Simulations in CARLA demonstrate
improved tracking accuracy compared with a baseline standard MPC.

## Demonstration Videos

| Scenario | Description | Link |
|----------|-------------|------|
| Figure-eight trajectory | MD-AMPC vs. standard MPC tracking in CARLA (Town02) | [Watch](figure_eight_demo.mp4) |

## Simulation Setup
- **Simulator:** CARLA 0.9.11, Town02
- **Vehicle:** Tesla Model 3 (kinematic bicycle model)
- **Reference speed:** 5 m/s
- **Controllers:** Standard MPC, MD-AMPC

