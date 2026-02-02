# YOLOv8人头检测模型在算能TPU上的部署完整教程

## 📋 项目概述
本项目完整记录了YOLOv8人头检测模型从训练到在算能TPU（BM1688芯片）上部署的全过程。包含模型转换、量化优化、部署代码和实际测试结果。

## 🚀 快速开始

### 环境要求
```bash
# 基础环境
Python 3.8+
Ubuntu 20.04/22.04
算能TPU设备（BM1684/BM1688）

# Python依赖
pip install ultralytics onnx numpy opencv-python
pip install sophon-sail  # 算能SAIL推理库
