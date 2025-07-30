[简体中文](README.md) | English

# Wiki-GRx-Pipeline

![](pictures/developer_banner.png)

This repository provides a guidance for training Fourier Intelligence GRx series robot to walk on plane using Reinforcement Learning (RL) algorithms.

## Requirements

- Ubuntu 20.04 / Ubuntu 22.04
- NVIDIA GPU (Prefer GPU powerful than GTX 3060)
- NVIDIA Driver with CUDA higher than 11.0

## Pipeline

The pipeline of training Fourier Intelligence GRx series robot to walk on plane can be divided into the following steps:

（GR2 related content is in `FourierGR2` branch）

1. **Prepare** robot model
    - **URDF Model**
        - [Wiki-GRx-URDF](https://github.com/FFTAI/wiki-grx-urdf/tree/FourierGR2)
        - This repository provides the GRx series robot models in URDF format.

    - **MJCF Model**
        - [Wiki-GRx-MJCF](https://github.com/FFTAI/wiki-grx-mjcf/tree/FourierGR2)
        - This repository provides the GRx series robot models in MJCF format.

2. **Train** walking policy
    - **Isaac Gym** ![nvidia.png](pictures/nvidia.png)
        - [Wiki-GRx-Gym](https://github.com/FFTAI/Wiki-GRx-Models/tree/FourierGR2)
        - This repository provides the code for training walking policy for Fourier GRx in Isaac Gym.

3. **Validate** walking policy
    - **MUJOCO** ![mujoco.png](pictures/mujoco.png)
        - [Wiki-GRx-Mujoco](https://github.com/FFTAI/wiki-grx-mujoco/tree/FourierGR2)
        - This repository provides the code for validating walking policy for Fourier GRx in Mujoco.

4. **Deploy** on real robot 🤖
    - [Wiki-GRx-Deploy](https://github.com/FFTAI/Wiki-GRx-Deploy/tree/FourierGR2)
    - This repository provides the code for deploying the walking policy on the Fourier GRx real robot.

## 参考文档

Please refer to the document [Fourier-GRX](https://fourier-grx-GR2.github.io) for more details.

---

Thank you for your interest in Fourier's GR2 robot project!
We hope this resource will provide strong support for your robotics development!
