---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section-title {
  font-size: 0.8em;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #2a6ebb;
  border-bottom: 2px solid #2a6ebb;
  padding-bottom: 4px;
  margin: 2em 0 1em 0;
}
.cv-entry {
  margin-bottom: 1.4em;
}
.cv-entry-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 4px;
}
.cv-role {
  font-weight: 700;
  font-size: 0.97em;
  color: #1a1a1a;
}
.cv-date {
  font-size: 0.85em;
  color: #666;
  white-space: nowrap;
}
.cv-org {
  font-style: italic;
  font-size: 0.88em;
  color: #444;
  margin: 2px 0 6px 0;
}
.cv-bullets {
  margin: 0;
  padding-left: 1.2em;
  font-size: 0.88em;
  color: #333;
  line-height: 1.65;
}
.cv-skill-row {
  display: flex;
  gap: 8px;
  margin-bottom: 6px;
  font-size: 0.88em;
  flex-wrap: wrap;
  align-items: baseline;
}
.cv-skill-label {
  font-weight: 700;
  color: #1a1a1a;
  white-space: nowrap;
  min-width: 130px;
}
</style>

<p style="margin-top:0;"><a href="/files/CV_detail.pdf" style="font-size:0.88em; padding:5px 14px; border:1px solid #2a6ebb; border-radius:4px; color:#2a6ebb; text-decoration:none; font-weight:600;">⬇ Download PDF</a></p>

<div class="cv-section-title">Education</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Bachelor of Engineering — Electronics and Telecommunication</span>
    <span class="cv-date">Aug 2019 – Jun 2023</span>
  </div>
  <div class="cv-org">Savitribai Phule Pune University</div>
  <ul class="cv-bullets">
    <li>Relevant Coursework: Signal Processing, Control Systems, Digital Communication, Data Structures, OOP, Cloud Computing, DBMS, Data Mining</li>
  </ul>
</div>

<div class="cv-section-title">Research &amp; Professional Experience</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Research Fellow &mdash; <a href="https://www.sarvam.ai/" style="font-weight:400; color:#2a6ebb;">Sarvam AI</a></span>
    <span class="cv-date">Jun 2025 – Present</span>
  </div>
  <div class="cv-org">Bangalore</div>
  <ul class="cv-bullets">
    <li>Built large-scale data generation pipelines for pre-training and SFT (150TB+, 260M+ images) for Sarvam Vision (3B-parameter VLM, 22 Indian languages), achieving SOTA on olmOCR-Bench and OmniDocBench.</li>
    <li>Converted curated datasets to WebDataset (WebDS) for NVIDIA NeMo Framework; maintained internal Indic OCR benchmarks with RL-reward-based evaluation metrics; integrated frontier VLMs via vLLM distributed inference.</li>
    <li>Leading an applied research project for GoI (MoSPI) — GIS + satellite + Gemma-31B + Grounding DINO pipeline to prioritize regions for the national Urban Frame Survey.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Pre-Doctoral Researcher &mdash; <a href="https://www.linkedin.com/company/artificial-intelligence-and-robotics-laboratory/" style="font-weight:400; color:#2a6ebb;">AIRL, Indian Institute of Science</a></span>
    <span class="cv-date">Aug 2024 – May 2025</span>
  </div>
  <div class="cv-org">Bangalore &nbsp;·&nbsp; Advisor: <a href="https://aero.iisc.ac.in/people/sureshsundaram/">Dr. Suresh Sundaram</a></div>
  <ul class="cv-bullets">
    <li>Conducted research on open-vocabulary learning, multi-modal alignment, and domain generalization in VLMs.</li>
    <li>Adapted CLIP for open-vocabulary segmentation using Optimal Transport, Masked Image Modelling, and PeFT (LoRA, Prompt Learning); built multimodal benchmarks (EO-IR / Sim-2-Real / aerial-ground / BEV) for open-world evaluation.</li>
    <li>Developed <a href="https://pypi.org/project/clip-cam/">CLIPcam</a> (PyPI) for CLIP explainability; delivered a talk on 3D Vision at a Faculty Development Program.</li>
    <li>2 papers at CVPR Workshops 2025 · 1 paper accepted at IROS 2026 · 2 journal papers under review (TMLR, IEEE TAI)</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Deep Learning and Image Processing Intern &mdash; <a href="https://galaxeye.space/" style="font-weight:400; color:#2a6ebb;">GalaxEye Space</a></span>
    <span class="cv-date">Apr 2024 – Jul 2024</span>
  </div>
  <div class="cv-org">Bangalore</div>
  <ul class="cv-bullets">
    <li>Built a SAR-optical coregistration algorithm (Mutual Information + Powell Optimization), C++-deployed on Jetson aboard <a href="https://www.isro.gov.in/POEM_4_Payloads_spadex.html">ISRO's POEM-4 mission</a>, cutting runtime ~62% (40s → 15s).</li>
    <li>Diagnosed SAR distortion via Lucas-Kanade Optical Flow; built an image-warping autoencoder to model and rectify misalignment.</li>
    <li>Developed SAR-EO fusion architecture (Knowledge Distillation + Contrastive Learning) as PoC for OptoSAR Satellite Launch — Mission Drishti.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Computer Vision Intern — AI for Healthcare &mdash; <span style="font-weight:400;">Indian Institute of Science</span></span>
    <span class="cv-date">Nov 2023 – Feb 2024</span>
  </div>
  <div class="cv-org">Bangalore &nbsp;·&nbsp; Advisor: <a href="https://aero.iisc.ac.in/people/radhakantpadhi/">Dr. Radhakant Padhi</a></div>
  <ul class="cv-bullets">
    <li>Worked on automation of drug delivery systems (Artificial Pancreas) under the guidance of <a href="https://aero.iisc.ac.in/people/radhakantpadhi/">Dr. Radhakant Padhi</a>.</li>
    <li>Built a meal-detection pipeline (SAM + ResNet50 + fuzzy matching) for carbohydrate estimation, achieving 91% accuracy.</li>
    <li>Presented findings to a clinical panel from Ramaiah Hospital and Madras Diabetes Research Foundation.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Open Source Developer — ML &mdash; <span style="font-weight:400;"><a href="https://github.com/unifyai/ivy" style="color:#2a6ebb;">Unify (YC W23)</a></span></span>
    <span class="cv-date">Mar 2023 – Oct 2023</span>
  </div>
  <div class="cv-org">Remote</div>
  <ul class="cv-bullets">
    <li>Contributed to Ivy, Unify's cross-framework ML transpilation framework.</li>
    <li>Created/reviewed PRs (functional APIs, transpilation utilities, bug fixes) across PyTorch, TensorFlow, JAX, NumPy backends.</li>
    <li>Recognized as a <strong>Top Contributor</strong>.</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Research Intern — NLP &mdash; <span style="font-weight:400;">NIT Kurukshetra</span></span>
    <span class="cv-date">Mar 2022 – Aug 2022</span>
  </div>
  <div class="cv-org">Remote &nbsp;·&nbsp; Advisor: <a href="https://sites.google.com/view/nitkkrsarikajain/home?authuser=0">Dr. Sarika Jain</a></div>
  <ul class="cv-bullets">
    <li>Worked on Link Prediction on legal documents under the supervision of <a href="https://sites.google.com/view/nitkkrsarikajain/home?authuser=0">Dr. Sarika Jain</a>.</li>
    <li>Built a Legal Knowledge Graph from Supreme Court filings, framing citation prediction and case similarity as link-prediction tasks.</li>
    <li>Benchmarked GraphSAGE, GAT, GCN vs. RGCN; GCN improved AUC ~40% (case similarity) and ~10% (citation prediction).</li>
  </ul>
</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">Project Intern — Computer Vision &mdash; <span style="font-weight:400;">Indian Army</span></span>
    <span class="cv-date">Mar 2021 – Aug 2021</span>
  </div>
  <div class="cv-org">Pune &nbsp;·&nbsp; Mentor: Col. (Dr.) K. Joshil Raj</div>
  <ul class="cv-bullets">
    <li>Devised satellite imagery feature extraction techniques for road network identification, supporting urban planning and border surveillance, under Col. (Dr.) K. Joshil Raj.</li>
    <li>Curated annotated satellite imagery datasets and developed U-Net segmentation models for road-network extraction, achieving 0.78 / 0.73 IoU on urban / border roads.</li>
    <li>Developed an interactive GUI enabling Army personnel to experiment with the models.</li>
  </ul>
</div>

<div class="cv-section-title">Publications</div>

{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign cat_posts = site.publications | where: "category", category[0] %}
    {% if cat_posts.size > 0 %}
<p style="font-weight:700; font-size:0.84em; color:#444; margin:1em 0 0.4em; text-transform:uppercase; letter-spacing:0.05em;">{{ category[1].title }}</p>
<ul style="margin-top:0;">{% for post in site.publications reversed %}{% if post.category == category[0] %}{% include archive-single-cv.html %}{% endif %}{% endfor %}</ul>
    {% endif %}
  {% endfor %}
{% endif %}

<div class="cv-section-title">Talks</div>

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

<div class="cv-section-title">Skills</div>

<div style="margin-bottom: 1em;">
  <div class="cv-skill-row"><span class="cv-skill-label">Languages</span><span>Python, Bash/Shell</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">VLMs</span><span>CLIP, Qwen, Gemma, PaliGemma, InternVL, PaddleOCR-VL</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">Training &amp; Fine-Tuning</span><span>Nvidia DGX Cloud Lepton, Yotta, SLURM, GCP, LoRA, Prompt Learning, Masked Image Modeling, Knowledge Distillation, Contrastive Learning, Context Optimization</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">Inference &amp; Deploy</span><span>vLLM, Docker</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">Data &amp; Pipelines</span><span>WebDataset (WebDS), Data Labelling &amp; Deduplication, Pre-Training Data Curation, Synthetic Data Generation, YouTube Data API v3, Google Cloud Storage</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">Sensor Data</span><span>RGB-SAR, RGB-IR, Multispectral Satellite Imagery (Cartosat)</span></div>
  <div class="cv-skill-row"><span class="cv-skill-label">Frameworks &amp; Tools</span><span>PyTorch, HuggingFace Transformers, Detectron2, TensorFlow, OpenCV, Git</span></div>
</div>

<div class="cv-section-title">Achievements</div>

<ul class="cv-bullets" style="margin-left:0; padding-left:1.2em;">
  <li>2× Awardee of the <strong>KIAC Fellowship</strong> (Kotak-IISc AI-ML Centre)</li>
  <li>Co-registration algorithm deployed aboard <a href="https://www.isro.gov.in/POEM_4_Payloads_spadex.html">ISRO's POEM-4 Mission</a> — <a href="https://x.com/GalaxEye/status/1873977161142448443">GLX-SQ payload</a> by GalaxEye Space</li>
  <li>Contributed to <strong>Sarvam Vision</strong> — India's first sovereign VLM, achieving SOTA on Indic OCR and global document understanding benchmarks</li>
</ul>

<div class="cv-section-title">Volunteering</div>

<div class="cv-entry">
  <div class="cv-entry-header">
    <span class="cv-role">AI/ML Co-Lead &mdash; Google Developer Student Clubs</span>
    <span class="cv-date">Aug 2021 – Jul 2022</span>
  </div>
  <div class="cv-org">Pune</div>
  <ul class="cv-bullets">
    <li>Organized hackathons and workshops; conducted hands-on sessions on TensorFlow and Git/GitHub reaching 150+ students.</li>
  </ul>
</div>
