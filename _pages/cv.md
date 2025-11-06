---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
---

<div style="text-align: right; margin-bottom: 2rem;">
  <a href="/cv_en/">English Version</a>
</div>

## 专业技能
- **编程语言：** 熟悉 Python、C++
- **深度学习框架：** 熟练使用 PyTorch 进行模型开发、训练与部署
- **大模型技术：** 熟悉 LLM/MLLM 架构（如 Qwen-VL 系列），具备 LoRA 微调、指令微调、推理部署及效果评估经验
- **多模态能力：** 掌握跨模态表征学习与融合方法，能设计端到端的多模态理解与生成系统
- **工程落地：** 熟悉 ComfyUI 等 AIGC 工具链，具备技术文档撰写、新模块快速复现与系统集成能力

---

## 科研经历

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>真假立辨：特征解耦增强的视觉语言模型用于扩散生成图像检测</strong>
  <em>一作｜投稿 CVPR 2026 CCF-A</em>
</div>
- 开创语义-噪声双路解耦架构，分层处理特征，显式解耦图像中的真实内容特征与生成器固有痕迹，提高 VLM 准确性
- 首创VLM语义推理检测范式，利用VLM强大预训练知识，辅以小样本-高效参数微调，极大提高识别准确性和鲁棒性
- 实现零样本跨模型强检测能力，仅用轻量 LoRA ，对已知与未知生成方式达到99%以上准确度，摆脱对特定生成器训练数据的依赖。跨数据集任务准确度优于 SOTA 10%
- 实验证明模型具有极强的鲁棒性，在图像质量下降一半时检测精度仅降低 0.3%

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>PR-CapsNet：面向图学习的伪黎曼胶囊网络</strong>
  <em>一作｜WSDM 2026, CCF-B</em>
</div>
- 提出首个在伪黎曼流形上运行的胶囊网络，通过自适应曲率动态路由机制融合多几何视角特征，解决异构图泛化难题
- 设计几何一致的分类器，在节点分类与图分类任务上平均超越 SOTA 模型 5.2%
- 在保持更高准确率的同时，模型 FLOPs 降低 3–5 倍，显著提升计算效率
- 核心创新：① 伪黎曼动态路由（处理测地线不连通）；② 自适应曲率学习；③ 伪黎曼空间投影分类器

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>基于自约束风格解耦的语义分割单样本无监督域适应</strong>
  <em>三作｜投稿 AAAI 2025, CCF-A</em>
</div>
- 提出轻量级风格解耦模块：在 ViT 特征后接入两个小型 CNN 编码器，分离语义与风格特征
- 设计多目标联合损失函数，协同优化语义一致性、风格重建与图像重绘质量，实现训练效率与生成质量的平衡
- 该模块可直接用于后续风格迁移或域适应任务，提升模型泛化能力

---

## 项目经历

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>异眼盯真: 基于昇腾全栈使能的细粒度多模态假新闻鉴定系统</strong>
  <em>队长｜2025 华为昇腾 AI 大赛 ｜2025.06~至今</em>
</div>
- 设计深浅双层协同推理架构，增强模型检测能力
- 运用二阶粗细粒度检测框架，实现多种伪造手段的识别
- 构建中文多模态数据集，让模型对中文语境适配，准确度超市面竞品40%

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>极端天气下无人驾驶船舶自动避让系统</strong>
  <em>队长｜2024 华为昇腾 AI 大赛 · 最具商业潜力奖｜2024.06~2024.12</em>
</div>
- 基于 MAPPO 强化学习算法训练避障策略网络，设计多目标奖励函数平衡安全性与路径效率
- 融合船舶动力学参数与 RL 决策模块，完成系统集成并在真实水域开展多轮极端天气测试，验证系统鲁棒性

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>基于昇腾平台的细胞检测软件</strong>
  <em>队长｜2023 华为昇腾 AI 大赛 · 广州金奖｜2023.06~2023.12</em>
</div>
- 设计端到端细胞检测系统，集成数据输入、预处理、推理与结果可视化全流程
- 基于 DiffusionDet 框架引入扩散机制，显著提升对微小肿瘤细胞的检测敏感度与抗干扰能力
- 使用私有+公开混合数据集训练，在真实临床样本中检测准确率较现有方法提升约 15%

---

## 荣誉证书

<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>2024 华为昇腾 AI 大赛（广州区）最具商业潜力奖</span>
  <strong>2024.10</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>广东工业大学校级奖学金（三等奖）</span>
  <strong>2024.09</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>2023 华为昇腾 AI 大赛（广州区）金奖</span>
  <strong>2023.10</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>第14届蓝桥杯 C/C++ 程序设计大赛（广东赛区）二等奖</span>
  <strong>2023.04</strong>
</div>