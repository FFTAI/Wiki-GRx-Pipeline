[English](README.en.md) | 简体中文

# Wiki-GRx-Pipeline

![](pictures/7.png)

本仓库提供使用强化学习（Reinforcement Learning, RL）算法训练傅利叶智能GRx系列机器人实现平地行走的完整流程指南。

## 环境要求

- Ubuntu 20.04 / 22.04 系统
- Miniconda 环境
- NVIDIA GPU（建议GTX 3060以上性能）
- NVIDIA显卡驱动（CUDA版本11.0以上）

## 实施流程

训练傅利叶智能GRx系列机器人复杂地形行走能力的完整流程可分为以下步骤：

1. **准备**机器人模型：
    - **URDF模型**：
        - [Wiki-GRx-Models](https://github.com/FFTAI/wiki-grx-models)
        - 该仓库提供GRx系列机器人的URDF格式模型文件。

2. **训练**行走策略：
    - **Isaac Gym训练平台**：
        - [Wiki-GRx-Gym](https://github.com/FFTAI/wiki-grx-gym)
        - 该仓库提供在Isaac Gym中训练GRx机器人行走策略的代码实现。

3. **真实机器人部署**🤖：
    - [Wiki-GRx-Deploy](https://github.com/FFTAI/wiki-grx-deploy)
    - 该仓库提供将训练好的策略部署到真实GRx机器人的代码实现。

---

感谢您对傅利叶智能GRx机器人开源项目的关注！希望本资源能为您的机器人开发提供有力支持！