---
title: "LiDAR/Camera Fusion for 3D Object Detection"
collection: talks
type: "Talk"
permalink: /talks/2025-02-11-lidar-camera-fusion
venue: "Faculty Development Workshop on AI-Driven Autonomous Drones, Indian Institute of Science"
date: 2025-02-11
location: "Bangalore, India"
excerpt: "A survey of 3D data representations and SOTA LiDAR, camera, and fusion architectures for 3D object detection, with applications in autonomous driving."
---

<a href="https://docs.google.com/presentation/d/1T7zhQa3aTHLtuskoE2mhqakdr3n3g8GC/edit?usp=sharing" target="_blank" style="display:inline-block; margin-bottom:1.4em; font-size:0.85em; padding:6px 16px; border:1px solid #2a6ebb; border-radius:4px; color:#2a6ebb; text-decoration:none; font-weight:600;">&#128196; View Slides</a>

Covered **3D data representation techniques** (point-based, voxel-based, pillar-based, frustum-based, BEV) and delivered a literature review spanning:

- **LiDAR-based methods** — PointNet++, VoxelNet, PointPillars, SECOND
- **Camera-based methods** — FCOS3D, PETR, DETR3D
- **Multimodal fusion architectures** — MVX-Net, BEVFusion

Discussed real-world applications in autonomous driving and robotics, key challenges including sensor data sparsity and adverse weather robustness, and standard benchmarks — KITTI, Waymo, and nuScenes.

---

**Glimpses**

<div id="talk-show" style="position:relative;width:100%;max-width:580px;height:320px;background:#f8f8f8;border-radius:6px;border:1px solid #e0e0e0;overflow:hidden;margin-top:0.8em;">
  <img src="/images/talks/lidar-talk-1.jpg" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:8px;opacity:1;transition:opacity 0.5s ease-in-out;">
  <img src="/images/talks/lidar-talk-2.png" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain;padding:8px;opacity:0;transition:opacity 0.5s ease-in-out;">
</div>
<div id="talk-dots" style="display:flex;gap:6px;margin-top:7px;">
  <span style="width:7px;height:7px;border-radius:50%;background:#2a6ebb;display:inline-block;transition:background 0.3s;"></span>
  <span style="width:7px;height:7px;border-radius:50%;background:#ccc;display:inline-block;transition:background 0.3s;"></span>
</div>
<script>
(function() {
  var show = document.getElementById('talk-show');
  var imgs = show.querySelectorAll('img');
  var dots = document.getElementById('talk-dots').children;
  var i = 0;
  setInterval(function() {
    imgs[i].style.opacity = '0';
    dots[i].style.background = '#ccc';
    i = (i + 1) % imgs.length;
    imgs[i].style.opacity = '1';
    dots[i].style.background = '#2a6ebb';
  }, 2500);
})();
</script>
