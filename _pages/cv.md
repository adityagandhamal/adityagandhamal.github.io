---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Electronics and Telecommunication, Savitribai Phule Pune University, 2023
  * Relevant Coursework: Signal Processing, Control Systems, Digital Communication, Data Structures, OOP, Cloud Computing, Database Management Systems, Data Mining

Work Experience
======
* **Research Fellow** — Sarvam AI, Bangalore *(June 2025 – Present)*
  * Large-scale data generation for pre-training and SFT of Sarvam Vision (3B-parameter VLM, 22 Indian languages) at 150TB+ and 260M+ images
  * Designed data sourcing/labelling strategies using frontier models; built WebDataset (WebDS) pipelines for Nvidia NeMo Framework
  * Own the Indic evaluation and benchmarking pipeline; integrated VLMs (Qwen, Gemma, InternVL, PaddleOCR-VL) with vLLM-based distributed inference
  * Leading applied research project for GoI (MoSPI): geospatial pipeline integrating GIS, Gemma4-31B, Segment Any Change (NeurIPS '26), and Grounding DINO for Urban Frame Survey prioritization

* **Pre-Doctoral Researcher** — AI and Robotics Lab, Indian Institute of Science, Bangalore *(Aug 2024 – May 2025)*
  * Research on open-vocabulary learning, multi-modal alignment, and domain generalization in VLMs under Dr. Suresh Sundaram
  * Developed cost aggregation architectures using Optimal Transport and Masked Image Modelling with LoRA, CoOp, and CoCoOp
  * Built multimodal benchmarks for segmentation across EO-IR/Sim-2-Real, aerial-to-ground perspectives (drone, BEV, ground vehicles)
  * Developed CLIPcam (PyPI); delivered 3D Vision talk at IISc Faculty Development Program
  * 2 papers at CVPR Workshops 2025; 1 under review at IROS 2026; 2 journal papers under review (TMLR, IEEE TAI)

* **Deep Learning and Image Processing Intern** — GalaxEye Space, Bangalore *(April 2024 – July 2024)*
  * SAR-Optical coregistration and data fusion for drone-based SAR platform; failure-case analysis using Lucas-Kanade Optical Flow
  * Contributed to GLX-SQ payload (ISRO POEM-4): implemented coregistration in Python then ported to C++ for Jetson edge deployment, achieving ~62% runtime reduction (40s → 15s)
  * Designed SAR-EO fusion architecture on SpaceNet-6 using Knowledge Distillation and Contrastive Learning

* **Computer Vision Intern – AI for Healthcare** — Indian Institute of Science, Bangalore *(Nov 2023 – Feb 2024)*
  * Automated drug delivery system (Artificial Pancreas) under Dr. Radhakant Padhi
  * Carbohydrate estimation from food images: SAM + ResNet50 + fuzzy-matching pipeline, achieving 91% accuracy
  * Presented findings to doctors from Ramaiah Hospital and Madras Diabetes Research Foundation

* **Open Source Developer – Machine Learning** — Unify (YC W23), Remote *(March 2023 – Oct 2023)*
  * Contributed to Ivy (cross-framework ML interoperability); functional API implementations, bug fixes, documentation across PyTorch, TensorFlow, JAX, NumPy
  * Recognized as Top Contributor

* **Research Intern – NLP** — NIT Kurukshetra, Remote *(March 2022 – Aug 2022)*
  * Link Prediction on legal documents under Dr. Sarika Jain; built Legal Knowledge Graph from Indian Supreme Court filings using NER
  * Benchmarked GraphSAGE, GAT, GCN vs. RGCN; GCN improved baseline AUC by ~40% on Case Similarity and ~10% on Citation Prediction

* **Project Intern – Computer Vision** — Indian Army, Pune *(March 2021 – Aug 2021)*
  * Satellite imagery road network identification for urban planning and border surveillance under Col. (Dr.) K. Joshil Raj
  * U-NET (ResNet34 backbone) achieving IoU of 0.78/0.73 for urban/border roads; built interactive GUI for Army personnel

Skills
======
* **Languages**: Python, Bash/Shell
* **Vision-Language Models**: CLIP, Qwen, Gemma, PaliGemma, InternVL, PaddleOCR-VL
* **Training Infra & Fine-Tuning**: Nvidia DGX Cloud Lepton, Yotta, GCP, LoRA, Prompt Learning, Masked Image Modeling, Knowledge Distillation, Contrastive Learning, Context Optimization
* **Inference & Deployment**: vLLM, Docker, SLURM
* **Data & Pipelines**: WebDataset (WebDS), Data Labelling, Pre-Training Data Curation, Synthetic Data Generation, YouTube Data API v3, Google Cloud Storage
* **Multi-Modal Sensor Data**: RGB-SAR, RGB-IR, Multispectral Satellite Imagery (Cartosat)
* **Frameworks & Tools**: PyTorch, HuggingFace Transformers, Detectron2, TensorFlow, OpenCV, Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Achievements
======
* 2× Awardee of the KIAC Fellowship (Kotak-IISc AI-ML Centre)
* Algorithm deployed on ISRO's POEM-4 Mission aboard the GLX-SQ payload (GalaxEye Space)
* Contributed to Sarvam Vision — India's first sovereign Vision-Language Model, achieving state-of-the-art on Indic OCR and global document understanding benchmarks

Volunteering
======
* **AI/ML Co-Lead** — Google Developer Student Clubs, Pune *(Aug 2021 – July 2022)*
  * Organized hackathons, workshops, and hands-on sessions on TensorFlow and Git/GitHub; reached 150+ students
