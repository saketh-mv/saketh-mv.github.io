---
layout: page
title: Research and Projects 
permalink: /projects/
# description: A collection of my cool projects.
nav: true
nav_order: 3
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">
  <div class="container">
    <h2>Research</h2>
    <!-- Project 1 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/3dgs.png" alt="Gaussian Splatting" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>ActiveInitSplat | Gaussian Splatting with active image selection</h3>
        <p class="project-subtitle">Graduate Student Researcher under professor Tara Javidi <a href="https://arxiv.org/abs/2503.06859" class="project-paper">[Paper]</a></p>
        <p class="project-description">
          •  Developed a novel active image selection framework for Gaussian Splatting (3DGS), leveraging density and occupancy based criteria using blackbox optimization to ensure diverse viewpoint coverage.
        </p>
        <p class="project-description">
          • Achieved significant performance improvements in real-time 3D scene rendering, surpassing passive selection baselines, by achieving increased LPIPS, SSIM, and PSNR metrics by almost 5% with fewer training images
        </p>
      </div>
    </div>
    <!-- Project 2 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/mot.gif" alt="Multi-object tracking" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Multi-Object Tracking</h3>
        <p class="project-subtitle">Graduate Student Researcher under professor Nikolay Atanasov</p>
        <p class="project-description">
          • Engineered an advanced KF-based multi-object tracking (MOT) system, leveraging probabilistic data association(PDAKF) for superior tracking accuracy, increasing HOTA and MOTA metrics by almost 10%.
        </p>
        <p class="project-description">
          • Integrating ReID features(Neural Features) into the tracking pipeline, inspired by StrongSORT, to improve robustness in real-time tracking under occlusions and cluttered scenes.
        </p>
      </div>
    </div>
    <!-- Project 3 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/semantics.gif" alt="Semantic Odometry" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>VLM-Based Semantic Odometry </h3>
        <p class="project-subtitle">Graduate Student Researcher under professor Nikolay Atanasov</p>
        <p class="project-description">
            • Developed an end-to-end(E2E) odometry pipeline using foundation models (TinyCLIP) to extract semantic-spatial embeddings from RGB images, fused with FastSAM masks for precise localization on NVIDIA Jetson Nano
        </p>
        <p class="project-description">
            • Fine-tuned the VLM on domain-specific race track data (e.g., cones, barriers) and optimized inference via TensorRT, achieving 20% higher accuracy than geometric baselines (FPFH) at 10Hz
        </p>
      </div>
    </div>
    <h2>Techincal Projects</h2>
    <!-- Project 1 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/tiara.gif" alt="Mesh Generation" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Text-to-3D Mesh Generation</h3>
        <p class="project-subtitle">CSE 252D: Advanced Computer Vision<a href="https://drive.google.com/file/d/1nhhBTaKQcUYS6MWLehpMoR1DqQR40ikt/view?usp=sharing" class="project-report">[Report]</a></p>
        <p class="project-description">
          Enhanced the Gaussian Dreamer framework for Text-to-3D with stable diffusion Foundation Model for better 2D diffusion replacing Stable diffusion with MV Dream and Score Distillation Sampling to Variational Score Distillation for improved loss. 
        </p>
          <p class="project-description">
          Employed SuGaR for efficient mesh extraction, achieving faster generation times and superior model quality across views.
        </p>
      </div>
    </div>
    <!-- Project 2 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/ece_285.png" alt="Multimodel Image generation" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Multimodal Edge-to-RGB Image Translation</h3>
        <p class="project-subtitle">ECE 285: Intro to Visual Learning <a href="https://drive.google.com/file/d/1jL64gvW_CLYag41Dofts2-F_s6b5ICf_/view?usp=sharing" class="project-report">[Report]</a></p>
        <p class="project-description">
         Designed an encoder-decoder architecture using cVAE and GAN to convert edge images into realistic RGB images, enhancing scene interpretation.
        </p>
          <p class="project-description">
          Improved output diversity and realism by incorporating latent space sampling and multimodal learning, achieving high-quality image generation with better adaptability in dynamic environments
        </p>
      </div>
    </div>
    <!-- Project 3 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/hqdefault.jpg" alt="Roomba" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Designing Roomba prototype</h3>
        <p class="project-description">
         • Developed an integrated real-time motion planning and navigation system for an autonomous robot (Roomba) using the Qualcomm RB5 platform, incorporating a LiDAR and camera for environmental sensing.
        </p>
          <p class="project-description">
            • Designed and implemented path planning algorithms (A*, RRT) and integrated SLAM techniques (EKF, ICP) for precise localization and mapping, with real-time Pose graph optimization and Loop closure constraints        
            </p>
      </div>
    </div>
    <!-- Project 3 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="assets/img/franka.jpg" alt="Roomba" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Robot Arm Simulation and Perception</h3>
        <p class="project-subtitle">ECE 276C: Robot Manipulation and Control<a href="https://drive.google.com/file/d/1O71ETYHTFYyidcvZDhlkCrnxSK1pXF7Y/view?usp=sharing" class="project-report">[Report]</a></p>
        <p class="project-description">
            • Simulated a Franka Panda 7-DOF robotic arm on an omnidirectional mobile base in PyBullet, integrating an end-effector mounted camera for real-time object tracking, motion estimation, and visual feedback control.
        </p>
          <p class="project-description">
            • Developed an enhanced RRT* algorithm for mobile base path planning while maintaining manipulator reachability and designed a combined motion planning for efficient reaching behaviors.       
            </p>
      </div>
    </div>
        <!-- Project 4 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/6dpose.png" alt="Pose estimation" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>6D Object Pose Estimation</h3>
        <p class="project-description">
         Developed an end-to-end pipeline for estimating the 6D pose of objects from RGBD input using PointNet architecture, and using Roboflow for data annotation
        </p>
          <p class="project-description">
          Applied advanced point cloud processing techniques such as Farthest Point Sampling to refine object pose accuracy, achieving 80% accuracy within 5° error.
        </p>
      </div>
    </div>
        <!-- Project 5 -->
    <div class="row project-item align-items-center">
      <div class="col-md-4">
        <img src="/assets/img/ifogsim.png" alt="ifogsim" class="img-fluid rounded">
      </div>
      <div class="col-md-8">
        <h3>Computing framework for Autonomous Vehicles</h3>
        <p class="project-subtitle">Presented in IEEE ROBIO-2023 <a href="https://ieeexplore.ieee.org/document/10355008" class="project-report">[PDF]</a></p>
        <p class="project-description">
         Aimed to emphasize and examine the outcomes of computer simulation(mainly energy consumption and data transmission) using fog nodes and iFogsim as a framework in a dynamic bandwidth environment.
        </p>
          <p class="project-description">
         Established groundwork for SDN for optimization and interchanging between star and mesh topology as needed.
        </p>
      </div>
    </div>

  </div>
</div>

<style>
.project-item {
  margin-bottom: 3rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid #eee;
}

.project-item:last-child {
  border-bottom: none;
}

.project-subtitle {
  color: #6c757d;
  margin-bottom: 1rem;
  font-size: 1rem;
}

.project-link {
  color: #0d6efd;
  text-decoration: none;
  margin-left: 0.5rem;
}

.project-link:hover {
  text-decoration: underline;
}

.project-description {
  margin-bottom: 0;
  line-height: 1.6;
}

h2 {
  margin-bottom: 2rem;
  /* color: #343a40; */
}

h3 {
  margin-bottom: 0.5rem;
  /* color: #495057; */
}

.img-fluid {
  max-width: 100%;
  height: auto;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.rounded {
  border-radius: 0.25rem;
}
</style>