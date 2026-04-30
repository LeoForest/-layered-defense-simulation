# -layered-defense-simulation
多层防御系统数值模拟代码，复现教材中资源分配、分裂弹头、不同防御策略等模型，生成各层防御势占比、剩余导弹比例等对比曲线图。

# 多层防御系统数值模拟

## 项目说明

本项目复现了某教材中关于多层防御系统的数值模拟结果，属于笔者某篇论文的一部分，包括：

- **第6章**：多阶段防御系统的资源分配与效能分析
- **第7章**：不同防御策略（随机分配 vs 均匀分配）的对比分析

> **注意**：代码中生成的图片编号（如 Figure_6_5.png）严格对应**参考文献**中的图表编号，与论文中的章节编号无关。

## 文件说明

- `Layered_Defense.ipynb` - 主程序 Jupyter Notebook
- `requirements.txt` - Python 依赖包列表

## 依赖安装

```bash
pip install -r requirements.txt
