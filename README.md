# MPC

(1) For MPC solutions, please refer to the following materials:
1. The MPC.pdf document given above
2. For OSQP solver:https://osqp.org/docs/examples/mpc.html#matlab，This python uses Sparse QP Formulation
3.https://zhuanlan.zhihu.com/p/141871796  Condensed QP Formulation

(2) The Hierarchical-MPC project is developed based on ROS. This simulation can use the simulation environment under the f110_simulator project. The usage is as follows:

1. Compile the Hierarchical-MPC and f110_simulator in the workspace
2. Start the simulation environment: roslaunch f110_simulator simulator.launch
3.  Start the control algorithm: roslaunch hmpc_auto_race hmpc.launch
![Screenshot from 2022-03-27 14-24-32](https://user-images.githubusercontent.com/21233498/160269500-62d0ed35-5f60-4fd5-8946-5fcf2872a7a1.png)

(3) The MPCC project is still under development
