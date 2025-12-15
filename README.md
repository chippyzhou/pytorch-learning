# 📘 My PyTorch Learning Journey

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-success)

> 这是一个用于记录我学习 PyTorch 深度学习框架的仓库。
> 这里存放了我的**学习笔记**、**代码练习**以及**遇到的 Bug 解决方案**。

---

## 📅 学习日志 (Update Log)

| 日期 | 学习主题 | 核心知识点 / 备注 | 对应文件 |
| :--- | :--- | :--- | :--- |
| 2025.12.13 | **Day 01: Tensor&Autograd** | PyTorch 安装, Conda 环境, Tensor 的创建与基本运算 | [12.13-12.15_notes.md](./notes/12.13-12.15_notes.md) |
| 2025.12.14 | **Day 02: 自动求导 (Autograd)** | `requires_grad`, 计算图, `.backward()` 原理 | [02_autograd.ipynb](./notes/autograd.md) |
| 2025.12.15 | **Day 03: 线性回归** | 手动实现梯度下降 vs 使用 `nn.Linear` | [03_linear_regression.py](./code/03_lr.py) |
| ... | ... | ... | ... |

*(在此处添加新的行以更新日志)*

---

## 📂 仓库结构 (Structure)

```text
.
├── 📂 code/               # 所有的练习代码
│   ├── 01_tensor_basic.py
│   └── utils.py
├── 📂 notes/              # 详细的 Markdown 笔记
│   ├── autograd_theory.md
│   └── loss_functions.md
├── 📂 assets/             # 存放笔记中的图片
├── requirements.txt       # 依赖包列表
└── README.md              # 项目主页
```

## 🛠️ 快速开始 (Getting Started)

如果你想运行本仓库的代码，请确保安装了以下环境：

1.  **克隆仓库**
    ```bash
    git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)
    cd 你的仓库名
    ```

2.  **安装依赖**
    ```bash
    pip install torch torchvision numpy matplotlib
    ```

## 📝 待办事项 (To-Do List)

- [x] 完成 Tensor 基础学习
- [ ] 搞懂反向传播原理
- [ ] 实现一个简单的 CNN (卷积神经网络)
- [ ] 复现一个经典的论文模型 (如 ResNet)

---
*Last updated: 2025-12-14*
