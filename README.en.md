[简体中文](README.md) | English

# Wiki-GRx-Pipeline

![](pictures/7.png)

This repository provides a guidance for training Fourier Intelligence GRx series robot to walk on plane using Reinforcement Learning (RL) algorithms.

## Requirements

- Ubuntu 20.04
- NVIDIA GPU (Prefer GPU powerful than GTX 3060)
- NVIDIA Driver with CUDA higher than 11.0

## Pipeline

The pipeline of training Fourier Intelligence GRx series robot to walk on plane can be divided into the following steps:

（GRMini related content is in `mini` branch）

1. **Prepare** robot model:
    - **URDF**:
        - [Wiki-GRx-Models](https://github.com/FFTAI/Wiki-GRx-Models/tree/mini)
        - This repository provides the GRx series robot models in URDF format.

2. **Train** walking policy:
    - **Isaac Gym**:
        - [Wiki-GRx-Gym](https://github.com/FFTAI/Wiki-GRx-Models/tree/mini)
        - This repository provides the code for training walking policy for GRx in Isaac Gym.

3. **Deploy** on real robot 🤖:
    - [Wiki-GRx-Deploy](https://github.com/FFTAI/Wiki-GRx-Deploy/tree/mini)
    - This repository provides the code for deploying the walking policy on the real robot.

## 参考文档

Please refer to the document [Fourier-GRX](https://fourier-grx.github.io) for more details.

---

Thank you for your interest in the Fourier Intelligence GRx Robot Repositories.
We hope you find this resource helpful in your robotics projects!