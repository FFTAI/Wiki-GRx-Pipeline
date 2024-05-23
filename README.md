# Wiki-GRx-Pipeline

![](pictures/7.png)

This repository provides a guidance for training GRx to walk on rough terrain using NVIDIA's Isaac Gym, legged_gym and rsl_rl libraries from Legged Robotics @ ETH Zürich.

## Requirements

- Ubuntu 20.04
- Anaconda
- NVIDIA GPU (Prefer GPU powerful than GTX 3060)
- NVIDIA Driver with CUDA higher than 11.0
- Python 3.8
- Isaac Gym
- legged_gym
- rsl_rl

## Pipeline

The pipeline of training GRx to walk on rough terrain can be divided into the following steps:

1. Prepare robot model:
    - https://gitee.com/FourierIntelligence/wiki-grx-models
    - This repository provides the GRx series robot models in URDF format.

2. Prepare walking policy:
    - https://gitee.com/FourierIntelligence/wiki-grx-gym
    - This repository provides the code for training walking policy for GRx in Isaac Gym.

3. Verify in simulator with ODE physics engine:
    - https://gitee.com/FourierIntelligence/wiki-grx-webots
    - This repository provides the code for verifying the walking policy in the simulator with ODE physics engine.
    - Use Webots as the simulator.

4. Deploy on real robot:
    - https://gitee.com/FourierIntelligence/wiki-grx-deploy
    - This repository provides the code for deploying the walking policy on the real robot.

## Low-Level Controls

If you are interested in the low-level controls of Fourier Intelligence products,
you can refer to the following repositories:

- Fourier Intelligence Actuator (FSA):
    - https://gitee.com/FourierIntelligence/wiki-fsa
- Fourier Intelligence Encoder (FSE):
    - https://gitee.com/FourierIntelligence/wiki-fse
- Fourier Intelligence Dexterous Hand (FDH):
    - https://gitee.com/FourierIntelligence/wiki-fdh

## Model Conversion

If you are interested in converting the neural network models to jit models for deployment on the real robot in other languages,
you can refer to the following repository:

- Fourier Intelligence JIT Compiler:
    - https://gitee.com/FourierIntelligence/wiki-jit

---

## Order GRx Series Robot 🛒

If you are interested in buying Fourier Intelligence GRx series robot, please use the following link to contact:

- https://www.fftai.cn/order/

Buying one GRx series robot will be provided with more detailed development guidance and support from our engineers.

---

Thank you for your interest in the Fourier Intelligence GRx Robot Repositories.
We hope you find this resource helpful in your robotics projects!