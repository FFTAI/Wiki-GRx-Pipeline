[English](README.en.md) | 简体中文

# Wiki-GRx-Pipeline

![](pictures/developer_banner.png)

本仓库提供使用强化学习（Reinforcement Learning, RL）算法训练傅利叶智能 GRx 系列机器人实现平地行走的完整流程指南。

## 环境要求

- Ubuntu 20.04 / Ubuntu 22.04 系统
- NVIDIA GPU（建议GTX 3060以上性能）
- NVIDIA 显卡驱动（CUDA版本11.0以上）

## 实施流程

训练傅利叶智能 Fourier GRx 系列机器人平地地形行走能力的完整流程可分为以下步骤：

（GR2 相关内容请查看 `FourierGR2` 分支）

1. **准备**机器人模型
    - **URDF 模型**
        - [Wiki-GRx-URDF](https://github.com/FFTAI/wiki-grx-urdf/tree/FourierGR2)
        - 该仓库提供 Fourier GRx 系列机器人的 URDF 格式模型文件。

    - **MJCF 模型**
        - [Wiki-GRx-MJCF](https://github.com/FFTAI/wiki-grx-mjcf/tree/FourierGR2)
        - 该仓库提供 Fourier GRx 系列机器人的 MJCF 格式模型文件。

2. **训练**行走策略
    - **Isaac Gym 训练平台** ![nvidia.png](pictures/nvidia.png)
        - [Wiki-GRx-Gym](https://github.com/FFTAI/wiki-grx-gym/tree/FourierGR2)
        - 该仓库提供在 Isaac Gym 中训练 Fourier GRx 机器人行走策略的代码实现。

3. **验证**行走策略 ![mujoco.png](pictures/mujoco.png) / **部署**真实机器人🤖
    - [Wiki-GRx-Deploy](https://github.com/FFTAI/wiki-grx-deploy/tree/FourierGR2)
    - 该仓库提供在 Mujoco 中验证 Fourier GRx 机器人行走策略的代码实现。
    - 该仓库提供将训练好的策略部署到真实 Fourier GRx 机器人的代码实现。

## 参考文档

请参阅文档 [Fourier-GRX](https://fftai.github.io/fourier-grx-GR2/) 以获取更多详细信息。

---

感谢您对傅利叶智能 GR2 机器人项目的关注！
希望本资源能为您的机器人开发提供有力支持！