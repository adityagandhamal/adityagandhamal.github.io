---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<style>
.proj-card {
  margin-bottom: 2em;
  padding-bottom: 2em;
  border-bottom: 1px solid #f0f0f0;
}
.proj-card:last-child { border-bottom: none; }
.proj-title {
  font-weight: 700;
  font-size: 1em;
  color: #1a1a1a;
  margin: 0 0 4px 0;
}
.proj-tag {
  display: inline-block;
  font-size: 0.75em;
  padding: 2px 8px;
  border-radius: 10px;
  background: #eef2fb;
  color: #2a6ebb;
  font-weight: 600;
  margin-right: 5px;
  margin-bottom: 6px;
}
.proj-desc {
  font-size: 0.88em;
  color: #333;
  margin: 6px 0 10px 0;
  line-height: 1.65;
}
.proj-link {
  font-size: 0.82em;
  color: #2a6ebb;
  text-decoration: none;
  font-weight: 600;
  margin-right: 14px;
}
</style>

<div class="proj-card">
  <p class="proj-title">CLIPcam &nbsp;<code style="font-size:0.8em; background:#f4f4f4; padding:1px 7px; border-radius:3px; font-weight:400;">pip install clip-cam</code></p>
  <span class="proj-tag">Python Package</span><span class="proj-tag">VLM Explainability</span><span class="proj-tag">CLIP</span>
  <p class="proj-desc">An open-source Python package for visualizing prompt-image feature alignment in ViT-based CLIP models. Supports custom fine-tuned checkpoints, multiple CLIP backbones, and easy integration into VLM workflows for interpretability and debugging.</p>
  <a href="https://github.com/adityagandhamal/clip_cam" class="proj-link">GitHub →</a>
  <a href="https://pypi.org/project/clip-cam/" class="proj-link">PyPI →</a>
</div>

<div class="proj-card">
  <p class="proj-title">Prompt Learning with CLIP for Open Vocabulary Segmentation</p>
  <span class="proj-tag">Open-Vocabulary</span><span class="proj-tag">Prompt Learning</span><span class="proj-tag">Segmentation</span>
  <p class="proj-desc">Implemented and ablated prompt learning techniques for CAT-Seg (CVPR'24), integrating CLIP with Context Optimization (CoOp, IJCV'22), Conditional Context Optimization (CoCoOp, CVPR'22), and Textual-based Class-aware Prompting (CVPR'24). Conducted ablation studies evaluating each variant against the MESS benchmark across 20 multi-domain datasets.</p>
  <a href="https://github.com/adityagandhamal/prompt-learning-ovss" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <p class="proj-title">Bias Mitigation for Fair Facial Attribute Classification (FAIR-Face)</p>
  <span class="proj-tag">Fairness</span><span class="proj-tag">Adversarial Training</span><span class="proj-tag">ResNet</span>
  <p class="proj-desc">Fine-tuned ResNet-50 on CelebA for facial attribute classification while mitigating spurious correlations in "Bald" and "Male" attribute predictions. Implemented adversarial training to reduce demographic bias by 20%, evaluated using Equalized Odds.</p>
  <a href="https://github.com/adityagandhamal" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <p class="proj-title">Satellite Orbital Trajectory Forecasting (SatPO)</p>
  <span class="proj-tag">Time-Series</span><span class="proj-tag">LSTM</span><span class="proj-tag">Satellite</span>
  <p class="proj-desc">Developed an LSTM-based time-series forecasting model trained on 18 days of telemetry data to predict satellite orbital trajectories for the next 7 days. Validated performance through comparative analysis and trajectory visualization.</p>
  <a href="https://github.com/adityagandhamal" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <p class="proj-title">Ivy — Unified ML Framework &nbsp;<span style="font-size:0.82em; font-weight:400; color:#888;">Unify (YC W23) · Top Contributor</span></p>
  <span class="proj-tag">Open Source</span><span class="proj-tag">PyTorch</span><span class="proj-tag">TensorFlow</span><span class="proj-tag">JAX</span>
  <p class="proj-desc">Contributed to Ivy, an open-source framework unifying PyTorch, TensorFlow, PaddlePaddle, and NumPy for cross-framework code transpilation. Added transpilation features, resolved bugs, implemented and tested functional APIs, and maintained documentation across 10+ merged pull requests. Recognized as a Top Contributor.</p>
  <a href="https://github.com/unifyai/ivy" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <p class="proj-title">PyTorch-RL</p>
  <span class="proj-tag">Open Source</span><span class="proj-tag">Reinforcement Learning</span><span class="proj-tag">PyTorch</span>
  <p class="proj-desc">Added normalisation methods for reward function scaling in <code>RewardScaling</code>. Fixed redundant use of <code>step_mdp</code> in the data collector, rectifying incorrect state transitions during rollout.</p>
  <a href="https://github.com/pytorch/rl" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <p class="proj-title">PyTorch-Vision</p>
  <span class="proj-tag">Open Source</span><span class="proj-tag">Computer Vision</span><span class="proj-tag">PyTorch</span>
  <p class="proj-desc">Resolved a core validation bug where invalid strings were silently accepted as loss reduction modes. Implemented <code>ValueError</code> handling across relevant loss functions and updated associated tests.</p>
  <a href="https://github.com/pytorch/vision" class="proj-link">GitHub →</a>
</div>
