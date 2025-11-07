---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---
<div style="text-align: right; margin-bottom: 2rem;">
  <a href="/cv_cn/">中文</a>
</div>

## Technical Skills
- **Programming Languages:** Proficient in Python and C++
- **Deep Learning Frameworks:** Extensive experience with PyTorch for model development, training, and deployment
- **Large Model Technologies:** Familiar with LLM/MLLM architectures (e.g., Qwen-VL series); experienced in LoRA fine-tuning, instruction tuning, inference deployment, and performance evaluation
- **Multimodal Capabilities:** Skilled in cross-modal representation learning and fusion methods; capable of designing end-to-end multimodal understanding and generation systems
- **Engineering & Deployment:** Proficient with AIGC toolchains such as ComfyUI; experienced in technical documentation, rapid prototyping of new modules, and system integration

---

## Research Experience

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>Discerning the Real from the Synthetic: Feature-Disentangled Vision-Language Models for Diffusion-Generated Image Detection</strong>
  <em>First Author | Submitted to CVPR 2026 (CCF-A)</em>
</div>
- Proposed a novel semantic-noise dual-path disentanglement architecture that hierarchically processes features to explicitly separate authentic content from generator-specific artifacts, significantly enhancing VLM accuracy.
- Pioneered a VLM-based semantic reasoning paradigm for synthetic image detection, leveraging the rich pre-trained knowledge of VLMs combined with few-shot, parameter-efficient fine-tuning to achieve high accuracy and robustness.
- Achieved strong zero-shot cross-generator detection performance: using only lightweight LoRA, attained >99% accuracy on both known and unseen generation methods, eliminating dependence on generator-specific training data. Outperformed state-of-the-art (SOTA) methods by 10% in cross-dataset evaluations.
- Demonstrated exceptional robustness: detection accuracy dropped by only 0.3% even when image quality was degraded by 50%.

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>PR-CapsNet: Pseudo-Riemannian Capsule Networks for Graph Representation Learning</strong>
  <em>First Author | Accepted to WSDM 2026 (CCF-B)</em>
</div>
- Introduced the first capsule network operating on pseudo-Riemannian manifolds, employing an adaptive-curvature dynamic routing mechanism to integrate multi-geometric perspectives and address generalization challenges in heterogeneous graphs.
- Designed a geometrically consistent classifier that outperforms SOTA models by 5.2% on average in both node and graph classification tasks.
- Achieved 3–5× lower FLOPs than existing methods while maintaining higher accuracy, substantially improving computational efficiency.
- Core innovations: (1) Pseudo-Riemannian dynamic routing (handles geodesic discontinuities); (2) Adaptive curvature learning; (3) Projection-based classifier in pseudo-Riemannian space.

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>Self-Constrained Style Disentanglement for One-Shot Unsupervised Domain Adaptation in Semantic Segmentation</strong>
  <em>Third Author | Submitted to AAAI 2025 (CCF-A)</em>
</div>
- Developed a lightweight style-disentanglement module: two compact CNN encoders appended to ViT features to decouple semantic and stylistic representations.
- Designed a multi-objective joint loss function that jointly optimizes semantic consistency, style reconstruction, and image re-rendering quality, balancing training efficiency and generation fidelity.
- The module is plug-and-play for downstream tasks such as style transfer or domain adaptation, enhancing model generalization.

---

## Project Experience

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>EagleEye: Fine-Grained Multimodal Fake News Detection System Powered by Huawei Ascend Full-Stack AI</strong>
  <em>Team Lead | Huawei Ascend AI Innovation Contest 2025 | Jun 2025 – Present</em>
</div>
- Designed a shallow-deep collaborative reasoning architecture to enhance detection capability.
- Implemented a two-stage coarse-to-fine detection framework capable of identifying diverse forgery techniques.
- Constructed a Chinese multimodal dataset tailored to local linguistic and cultural contexts, achieving 40% higher accuracy than commercial competitors.

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>Autonomous Collision Avoidance System for Unmanned Vessels in Extreme Weather</strong>
  <em>Team Lead | Huawei Ascend AI Innovation Contest 2024 – “Most Commercially Promising Award” | Jun 2024 – Dec 2024</em>
</div>
- Trained an obstacle-avoidance policy network using MAPPO reinforcement learning, with a multi-objective reward function balancing safety and path efficiency.
- Integrated vessel dynamics parameters with the RL decision module; conducted multiple rounds of real-world water trials under extreme weather conditions, validating system robustness.

<br>

<div style="display: flex; justify-content: space-between; align-items: baseline;">
  <strong>Ascend-Powered Cell Detection Software</strong>
  <em>Team Lead | Huawei Ascend AI Innovation Contest 2023 – Guangzhou Gold Award | Jun 2023 – Dec 2023</em>
</div>
- Developed an end-to-end cell detection system encompassing data input, preprocessing, inference, and result visualization.
- Enhanced the DiffusionDet framework with diffusion mechanisms, significantly improving sensitivity to tiny tumor cells and robustness against noise.
- Trained on a hybrid dataset (private + public); achieved ~15% higher detection accuracy than existing methods on real clinical samples.

---

## Honors & Certifications

<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>Huawei Ascend AI Innovation Contest 2024 (Guangzhou) – Most Commercially Promising Award</span>
  <strong>Oct 2024</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>Guangdong University of Technology – University-Level Scholarship (Third Class)</span>
  <strong>Sep 2024</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>Huawei Ascend AI Innovation Contest 2023 (Guangzhou) – Gold Award</span>
  <strong>Oct 2023</strong>
</div>
<div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 8px;">
  <span>14th Blue Bridge Cup – C/C++ Programming Contest (Guangdong Province) – Second Prize</span>
  <strong>Apr 2023</strong>
</div>