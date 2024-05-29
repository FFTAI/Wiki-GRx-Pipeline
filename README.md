# Wiki-GRx-Pipeline

[Gitee README.md](README.gitee.md)

![](pictures/7.png)

This repository provides a guidance for training Fourier Intelligence GRx series robot to walk on rough terrain using Reinforcement Learning (RL) algorithms.

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

The pipeline of training Fourier Intelligence GRx series robot to walk on rough terrain can be divided into the following steps:

1. **Prepare** robot model:
    - [Wiki-GRx-Models](https://github.com/FFTAI/wiki-grx-models)
    - This repository provides the GRx series robot models in URDF format.

2. **Train** walking policy:
    - **Isaac Gym**:
        - [Wiki-GRx-Gym](https://github.com/FFTAI/wiki-grx-gym)
        - This repository provides the code for training walking policy for GRx in Isaac Gym.

3. **Verify** in simulator with ODE physics engine:
    - **Webots**:
        - [Wiki-GRx-Webots](https://github.com/FFTAI/wiki-grx-webots)
        - This repository provides the code for verifying the walking policy in the Webots simulator with ODE physics engine.
    - **Gazebo**:
        - [Wiki-GRx-Gazebo](https://github.com/FFTAI/wiki-grx-gazebo)
        - This repository provides the code for verifying the walking policy in the Gazebo simulator with ODE physics engine.

4. **Deploy** on real robot 🤖:
    - [Wiki-GRx-Deploy](https://github.com/FFTAI/wiki-grx-deploy)
    - This repository provides the code for deploying the walking policy on the real robot.

## Low-Level Controls

If you are interested in the low-level controls of Fourier Intelligence products,
you can refer to the following repositories:

- Fourier Intelligence Actuator (FSA):
    - [Wiki-FSA](https://github.com/FFTAI/wiki-fsa)
- Fourier Intelligence Encoder (FSE):
    - [Wiki-FSE](https://github.com/FFTAI/wiki-fse)
- Fourier Intelligence Dexterous Hand (FDH):
    - [Wiki-FDH](https://github.com/FFTAI/wiki-fdh)

## Model Conversion

If you are interested in converting the neural network models to jit models for deployment on the real robot in other languages,
you can refer to the following repository:

- Fourier Intelligence JIT Compiler:
    - [Wiki-JIT](https://github.com/FFTAI/wiki-jit)

---

## Order GRx Series Robot 🛒

If you are interested in buying Fourier Intelligence GRx series robot, please use the following link to contact:

- https://www.fftai.cn/order/

Buying one GRx series robot will be provided with more detailed development guidance and support from our engineers.

---

Thank you for your interest in the Fourier Intelligence GRx Robot Repositories.
We hope you find this resource helpful in your robotics projects!