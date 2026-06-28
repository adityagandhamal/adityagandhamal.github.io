---
layout: archive
title: "Projects & Open-Source Contributions"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<style>
.proj-card { margin-bottom: 2.6em; padding-bottom: 2.6em; border-bottom: 1px solid #f0f0f0; }
.proj-card:last-child { border-bottom: none; }
.proj-header { display:flex; justify-content:space-between; align-items:baseline; flex-wrap:wrap; gap:4px; margin-bottom:4px; }
.proj-title { font-weight:700; font-size:1em; color:#1a1a1a; margin:0; }
.proj-date { font-size:0.82em; color:#888; white-space:nowrap; }
.proj-tag { display:inline-block; font-size:0.75em; padding:2px 8px; border-radius:10px; background:#eef2fb; color:#2a6ebb; font-weight:600; margin-right:5px; margin-bottom:8px; }
.proj-motivation { font-size:0.88em; color:#555; font-style:italic; margin:4px 0 6px 0; line-height:1.6; border-left:3px solid #d0d8e8; padding-left:10px; }
.proj-desc { font-size:0.88em; color:#333; margin:6px 0 10px 0; line-height:1.65; }
.proj-link { font-size:0.82em; color:#2a6ebb; text-decoration:none; font-weight:600; margin-right:14px; }
.proj-media { margin:12px 0 10px 0; }
.media-grid { display:grid; grid-template-columns:1fr 1fr; gap:8px; max-width:620px; }
.media-grid-item img { width:100%; height:180px; object-fit:contain; background:#f8f8f8; border-radius:5px; border:1px solid #e0e0e0; display:block; }
.media-grid-item video { width:100%; height:180px; object-fit:cover; border-radius:5px; border:1px solid #e0e0e0; display:block; }
.media-caption { font-size:0.78em; color:#777; margin-top:4px; }
.section-label { font-size:0.78em; font-weight:700; letter-spacing:0.1em; text-transform:uppercase; color:#2a6ebb; border-bottom:2px solid #2a6ebb; padding-bottom:4px; margin:0 0 1.6em 0; }
.pr-entry { margin-bottom:8px; font-size:0.88em; color:#333; line-height:1.6; }
.pr-badge { display:inline-block; font-size:0.75em; padding:1px 7px; border:1px solid #2a6ebb; border-radius:3px; color:#2a6ebb; text-decoration:none; font-weight:600; margin-left:6px; vertical-align:middle; }
</style>

<!-- ───────────────────────────── OSS ───────────────────────────── -->

<p class="section-label">Open-Source Contributions</p>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">Ivy — Unified ML Framework &nbsp;<span style="font-size:0.82em; font-weight:400; color:#888;">Unify (YC W23) · Top Contributor</span></p>
    <span class="proj-date">2023</span>
  </div>
  <span class="proj-tag">PyTorch</span><span class="proj-tag">TensorFlow</span><span class="proj-tag">JAX</span><span class="proj-tag">Transpilation</span>
  <p class="proj-desc">Contributed to Ivy, an open-source framework that unifies PyTorch, TensorFlow, PaddlePaddle, and NumPy under a single API for cross-framework code transpilation. Added transpilation features, resolved bugs, implemented and tested functional APIs, and maintained documentation across <strong>10+ merged pull requests</strong>. Recognized as a <strong>Top Contributor</strong>.</p>
  <a href="https://github.com/unifyai/ivy" class="proj-link">GitHub →</a>
  <a href="https://github.com/ivy-llc/ivy/pulls?q=adityagandhamal" class="proj-link">All PRs →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">PyTorch-RL</p>
    <span class="proj-date">2023</span>
  </div>
  <span class="proj-tag">Reinforcement Learning</span><span class="proj-tag">PyTorch</span><span class="proj-tag">Bug Fix</span><span class="proj-tag">Feature Extension</span>
  <div class="pr-entry">
    <strong>PR #682 — RewardScaling: standard_normal support</strong>
    <a href="https://github.com/pytorch/rl/pull/682" class="pr-badge">PR</a><br>
    Added a <code>standard_normal</code> kwarg to the <code>RewardScaling</code> transform, bringing parity with <code>ObservationNorm</code> and enabling normalized reward scaling without in-place tensor operations.
  </div>
  <div class="pr-entry">
    <strong>PR #637 — Fix step_mdp usage in data collector</strong>
    <a href="https://github.com/pytorch/rl/pull/637" class="pr-badge">PR</a><br>
    Fixed a bug where the data collector manually excluded keys instead of delegating to <code>step_mdp</code>'s built-in exclusion logic, which caused incorrect state transitions during rollout.
  </div>
  <a href="https://github.com/pytorch/rl" class="proj-link" style="margin-top:8px; display:inline-block;">GitHub →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">PyTorch-Vision</p>
    <span class="proj-date">2023</span>
  </div>
  <span class="proj-tag">Computer Vision</span><span class="proj-tag">PyTorch</span><span class="proj-tag">Bug Fix</span>
  <div class="pr-entry">
    <strong>PR #6675 — Validate reduction mode in loss functions</strong>
    <a href="https://github.com/pytorch/vision/pull/6675" class="pr-badge">PR</a><br>
    Resolved a silent failure where invalid strings (e.g. <code>"avg"</code>) were accepted as reduction modes in loss functions. Added <code>ValueError</code> with a descriptive message and updated tests to assert the error is raised correctly.
  </div>
  <a href="https://github.com/pytorch/vision" class="proj-link" style="margin-top:8px; display:inline-block;">GitHub →</a>
</div>

<!-- ───────────────────────────── Projects ───────────────────────── -->

<p class="section-label" style="margin-top:0.6em;">Projects</p>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">CLIPcam &nbsp;<code style="font-size:0.8em; background:#f4f4f4; padding:1px 7px; border-radius:3px; font-weight:400;">pip install clip-cam</code></p>
    <span class="proj-date">2025</span>
  </div>
  <span class="proj-tag">Python Package</span><span class="proj-tag">VLM Explainability</span><span class="proj-tag">CLIP</span>
  <p class="proj-motivation">As VLMs become widely adopted, understanding why a model attends to specific image regions for a given prompt is critical for debugging. CLIPcam addresses this gap by exposing the internal alignment between visual and textual embeddings through Grad-CAM-style heatmaps.</p>
  <p class="proj-desc">An open-source Python package for visualizing prompt-image feature alignment in ViT-based CLIP models. Supports custom fine-tuned checkpoints, multiple CLIP backbones, and easy integration into VLM workflows for interpretability and debugging.</p>
  <div class="proj-media">
    <img src="/images/projects/clipcam.png" alt="CLIPcam visualization" style="width:100%; max-width:600px; border-radius:6px; border:1px solid #e0e0e0;" onerror="this.style.display='none'">
    <p class="media-caption">Grad-CAM-style heatmaps showing prompt-image feature alignment in CLIP.</p>
  </div>
  <a href="https://github.com/adityagandhamal/clip_cam" class="proj-link">GitHub →</a>
  <a href="https://pypi.org/project/clip-cam/" class="proj-link">PyPI →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">Prompt Learning with CLIP for Open Vocabulary Segmentation</p>
    <span class="proj-date">2024</span>
  </div>
  <span class="proj-tag">Open-Vocabulary</span><span class="proj-tag">Prompt Learning</span><span class="proj-tag">Segmentation</span>
  <p class="proj-motivation">Fixed-text templates like "a photo of a [CLASS]" are brittle for open-vocabulary segmentation — they fail to capture context or generalise to unseen categories. Prompt learning replaces these with learnable vectors, enabling CLIP to adapt its textual representations to diverse domains.</p>
  <p class="proj-desc">Implemented prompt learning techniques for CAT-Seg (CVPR'24), integrating CLIP with Context Optimization (IJCV'22), Conditional Context Optimization (CVPR'22), and Textual-based Class-aware Prompting (CVPR'24); conducted ablation studies evaluating each variant against the MESS benchmark covering 20 multi-domain datasets.</p>
  <div class="proj-media">
    <div id="pl-show-proj" style="position:relative;width:100%;max-width:580px;height:260px;background:#f8f8f8;border-radius:6px;border:1px solid #e0e0e0;overflow:hidden;">
      <img src="/images/projects/prompr-learning-base-CATSeg-CVPR24.png" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:12px;opacity:1;transition:opacity 0.5s ease-in-out;">
      <img src="/images/projects/prompt-learning-CoOp-IJCV22.png" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:12px;opacity:0;transition:opacity 0.5s ease-in-out;">
      <img src="/images/projects/prompt-learning-CoCoOp-CVPR22.png" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:12px;opacity:0;transition:opacity 0.5s ease-in-out;">
      <img src="/images/projects/prompt-learning-TCP-CVPR24.png" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:12px;opacity:0;transition:opacity 0.5s ease-in-out;">
      <div id="pl-label-proj" style="position:absolute;bottom:0;left:0;right:0;background:rgba(20,20,20,0.62);padding:7px 14px;font-size:0.8em;color:#fff;font-weight:600;letter-spacing:0.01em;">Base: CAT-Seg (CVPR'24)</div>
    </div>
    <div id="pl-dots-proj" style="display:flex;gap:6px;margin-top:8px;">
      <span style="width:7px;height:7px;border-radius:50%;background:#2a6ebb;display:inline-block;transition:background 0.3s;"></span>
      <span style="width:7px;height:7px;border-radius:50%;background:#ccc;display:inline-block;transition:background 0.3s;"></span>
      <span style="width:7px;height:7px;border-radius:50%;background:#ccc;display:inline-block;transition:background 0.3s;"></span>
      <span style="width:7px;height:7px;border-radius:50%;background:#ccc;display:inline-block;transition:background 0.3s;"></span>
    </div>
    <script>
    (function() {
      var show = document.getElementById('pl-show-proj');
      var imgs = show.querySelectorAll('img');
      var label = document.getElementById('pl-label-proj');
      var dots = document.getElementById('pl-dots-proj').children;
      var caps = ["Base: CAT-Seg (CVPR'24)", "+ CoOp (IJCV'22)", "+ CoCoOp (CVPR'22)", "+ TCP (CVPR'24)"];
      var i = 0;
      setInterval(function() {
        imgs[i].style.opacity = '0';
        dots[i].style.background = '#ccc';
        i = (i + 1) % imgs.length;
        imgs[i].style.opacity = '1';
        dots[i].style.background = '#2a6ebb';
        label.textContent = caps[i];
      }, 2500);
    })();
    </script>
  </div>
  <a href="https://github.com/adityagandhamal/prompt-learning-ovss" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">Bias Mitigation for Fair Facial Attribute Classification (FAIR-Face)</p>
    <span class="proj-date">2024</span>
  </div>
  <span class="proj-tag">Fairness</span><span class="proj-tag">Adversarial Training</span><span class="proj-tag">ResNet</span>
  <p class="proj-motivation">Facial attribute classifiers often inherit spurious correlations from training data — for example, "Bald" predictions becoming entangled with "Male" — leading to systematically unfair predictions across demographic groups. Addressing this requires not just better data, but explicit training objectives that penalise bias.</p>
  <p class="proj-desc">Fine-tuned ResNet-50 on CelebA for multi-attribute facial classification. Identified spurious correlations in "Bald" and "Male" predictions and implemented adversarial training to reduce demographic bias by 20%, evaluated using Equalized Odds.</p>
  <div class="proj-media">
    <img src="/images/projects/fair-face.png" alt="FAIR-Face results" style="width:100%; max-width:600px; border-radius:6px; border:1px solid #e0e0e0;" onerror="this.style.display='none'">
    <p class="media-caption">A depiction of the CelebA dataset.</p>
  </div>
  <a href="https://github.com/adityagandhamal/fairness" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">Satellite Orbital Trajectory Forecasting (SatPO)</p>
    <span class="proj-date">2022</span>
  </div>
  <span class="proj-tag">Time-Series</span><span class="proj-tag">LSTM</span><span class="proj-tag">Satellite</span>
  <p class="proj-motivation">The growing population of Resident Space Objects (RSOs) in Low Earth Orbit dramatically increases collision risk — a cascading chain of collisions, known as Kessler Syndrome, could render entire orbital shells unusable. Reliable short-term trajectory forecasting is critical for proactive collision avoidance.</p>
  <p class="proj-desc">Developed an LSTM-based forecasting model trained on 18 days of telemetry data from a satellite in a 600-object dataset to predict its orbital trajectory for the next 7 days. Compared against an ARIMA baseline through trajectory visualisation.</p>
  <div class="proj-media">
    <div class="media-grid">
      <div class="media-grid-item">
        <video autoplay loop muted playsinline style="width:100%; height:180px; object-fit:cover; border-radius:5px; border:1px solid #e0e0e0;">
          <source src="/images/projects/satpo1.mp4" type="video/mp4">
        </video>
        <p class="media-caption">Satellite telemetry data.</p>
      </div>
      <div class="media-grid-item">
        <video autoplay loop muted playsinline style="width:100%; height:180px; object-fit:cover; border-radius:5px; border:1px solid #e0e0e0;">
          <source src="/images/projects/satpo2.mp4" type="video/mp4">
        </video>
        <p class="media-caption">LSTM-predicted 7-day orbital trajectory.</p>
      </div>
    </div>
  </div>
  <a href="https://github.com/adityagandhamal/satellite-position-estimation" class="proj-link">GitHub →</a>
</div>

<div class="proj-card">
  <div class="proj-header">
    <p class="proj-title">Road Lane Detection</p>
    <span class="proj-date">2021</span>
  </div>
  <span class="proj-tag">Computer Vision</span><span class="proj-tag">OpenCV</span><span class="proj-tag">Python</span>
  <p class="proj-motivation">Lane detection is a foundational component of autonomous driving pipelines — without reliable lane boundary identification, downstream path planning and driver-assist systems cannot operate safely. Classical computer vision techniques provide a lightweight, interpretable baseline before invoking deep learning.</p>
  <p class="proj-desc">Real-time lane detection pipeline for images and video using edge detection, Hough transforms, and region-of-interest masking. Demonstrated on Manhattan street footage and highway sequences.</p>
  <div class="proj-media">
    <img src="/images/projects/road-lane-1.gif" alt="Road lane detection demo" style="width:100%; max-width:600px; border-radius:6px; border:1px solid #e0e0e0;">
    <p class="media-caption">Real-time lane detection on Manhattan street footage.</p>
  </div>
  <a href="https://github.com/adityagandhamal/road-lane-detection" class="proj-link">GitHub →</a>
</div>
