---
layout: single
title: " "
permalink: /projects/
type: pages
author_profile: true
header:
  overlay: false
---

<style>
body {
  max-width: 1100px;
}

.intro-text {
  margin-bottom: 2rem;
  color: #4a5568;
  font-size: 1.05rem;
}

/* ====== Project items with colored boxes ====== */
.project-item {
  padding: 1.5rem;
  margin-bottom: 2rem;
  background: linear-gradient(135deg, #e0f2fe 0%, #bae6fd 100%);
  border-radius: 12px;
  border-left: 8px solid #0ea5e9;
  transition: all 0.3s ease;
}

.project-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(14, 165, 233, 0.3);
  border-left-color: #0284c7;
}

/* Different colors for each project */
.project-item:nth-child(2) {
  background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%);
  border-left-color: #f59e0b;
}

.project-item:nth-child(2):hover {
  border-left-color: #d97706;
  box-shadow: 0 8px 20px rgba(245, 158, 11, 0.3);
}

.project-item:nth-child(3) {
  background: linear-gradient(135deg, #ddd6fe 0%, #c4b5fd 100%);
  border-left-color: #8b5cf6;
}

.project-item:nth-child(3):hover {
  border-left-color: #7c3aed;
  box-shadow: 0 8px 20px rgba(139, 92, 246, 0.3);
}

.project-item:nth-child(4) {
  background: linear-gradient(135deg, #dcfce7 0%, #bbf7d0 100%);
  border-left-color: #10b981;
}

.project-item:nth-child(4):hover {
  border-left-color: #059669;
  box-shadow: 0 8px 20px rgba(16, 185, 129, 0.3);
}

.project-item:nth-child(5) {
  background: linear-gradient(135deg, #fce7f3 0%, #fbcfe8 100%);
  border-left-color: #ec4899;
}

.project-item:nth-child(5):hover {
  border-left-color: #db2777;
  box-shadow: 0 8px 20px rgba(236, 72, 153, 0.3);
}

.project-item:nth-child(6) {
  background: linear-gradient(135deg, #ffedd5 0%, #fed7aa 100%);
  border-left-color: #f97316;
}

.project-item:nth-child(6):hover {
  border-left-color: #ea580c;
  box-shadow: 0 8px 20px rgba(249, 115, 22, 0.3);
}

.project-item:nth-child(7) {
  background: linear-gradient(135deg, #dbeafe 0%, #bfdbfe 100%);
  border-left-color: #3b82f6;
}

.project-item:nth-child(7):hover {
  border-left-color: #2563eb;
  box-shadow: 0 8px 20px rgba(59, 130, 246, 0.3);
}

.project-item:nth-child(8) {
  background: linear-gradient(135deg, #fae8ff 0%, #f5d0fe 100%);
  border-left-color: #d946ef;
}

.project-item:nth-child(8):hover {
  border-left-color: #c026d3;
  box-shadow: 0 8px 20px rgba(217, 70, 239, 0.3);
}

.project-item:nth-child(9) {
  background: linear-gradient(135deg, #f0fdfa 0%, #ccfbf1 100%);
  border-left-color: #14b8a6;
}

.project-item:nth-child(9):hover {
  border-left-color: #0d9488;
  box-shadow: 0 8px 20px rgba(20, 184, 166, 0.3);
}

.project-item:nth-child(10) {
  background: linear-gradient(135deg, #fef2f2 0%, #fecaca 100%);
  border-left-color: #ef4444;
}

.project-item:nth-child(10):hover {
  border-left-color: #dc2626;
  box-shadow: 0 8px 20px rgba(239, 68, 68, 0.3);
}

.project-item:nth-child(11) {
  background: linear-gradient(135deg, #f5f3ff 0%, #ede9fe 100%);
  border-left-color: #a78bfa;
}

.project-item:nth-child(11):hover {
  border-left-color: #8b5cf6;
  box-shadow: 0 8px 20px rgba(167, 139, 250, 0.3);
}

.project-item:nth-child(12) {
  background: linear-gradient(135deg, #ecfdf5 0%, #d1fae5 100%);
  border-left-color: #34d399;
}

.project-item:nth-child(12):hover {
  border-left-color: #10b981;
  box-shadow: 0 8px 20px rgba(52, 211, 153, 0.3);
}

.project-item:nth-child(13) {
  background: linear-gradient(135deg, #fff7ed 0%, #ffedd5 100%);
  border-left-color: #fb923c;
}

.project-item:nth-child(13):hover {
  border-left-color: #f97316;
  box-shadow: 0 8px 20px rgba(251, 146, 60, 0.3);
}

/* ====== Project header line ====== */
.project-header {
  font-size: 1.1rem;
  font-weight: 700;
  margin-bottom: 0.75rem;
  color: #1a202c;
}

.project-header a.project-link {
  text-decoration: none;
  color: #1f6feb;
  transition: color 0.2s ease;
}

.project-header a.project-link:hover {
  text-decoration: underline;
  color: #0969da;
}

/* Project links */
.project-links {
  display: inline-block;
  margin-left: 8px;
}

.project-links a.pdf {
  color: #1f6feb;
  font-weight: 600;
  text-decoration: none;
  margin-left: 4px;
  padding: 0.2rem 0.4rem;
  border-radius: 4px;
  background: rgba(31, 111, 235, 0.1);
  transition: all 0.2s ease;
}

.project-links a.slides,
.project-links a.poster {
  color: #d97706;
  font-weight: 600;
  text-decoration: none;
  margin-left: 4px;
  padding: 0.2rem 0.4rem;
  border-radius: 4px;
  background: rgba(217, 119, 6, 0.1);
  transition: all 0.2s ease;
}

.project-links a.pdf:hover {
  background: rgba(31, 111, 235, 0.2);
  transform: translateY(-2px);
}

.project-links a.slides:hover,
.project-links a.poster:hover {
  background: rgba(217, 119, 6, 0.2);
  transform: translateY(-2px);
}

/* Separator removed - using colored boxes instead */
.project-separator {
  display: none;
}

/* Description spacing */
.project-desc {
  margin-top: 0.5rem;
  color: #2d3748;
  line-height: 1.6;
}

/* Keywords styling */
.project-keywords {
  margin-top: 0.75rem;
  font-style: italic;
  color: #4a5568;
  font-size: 0.95rem;
}

.project-keywords strong {
  font-weight: 600;
  font-style: normal;
}

@media (max-width: 768px) {
  .project-item {
    padding: 1rem;
  }
}
</style>

<p class="intro-text">
Below is a curated list of academic, research, and technical projects spanning machine learning, signal processing, control systems, IoT, and power systems.
</p>

<!-- Project 1 -->
<div class="project-item">
<div class="project-header">
1. <a class="project-link" href="https://github.com/Joysaha189/CSI-Based-Sign-Language-Recognition-Using-CNN-GRU-Architecture-Enhanced-with-Attention" target="_blank" rel="noopener">CSI-Based Sign Language Recognition Using CNN-GRU Architecture Enhanced with Attention</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/CSI-Based-Sign-Language-Recognition-Using-CNN-GRU-Architecture-Enhanced-with-Attention/main/Deliverables/DL_Project%20Report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/CSI-Based-Sign-Language-Recognition-Using-CNN-GRU-Architecture-Enhanced-with-Attention/main/Deliverables/Project%20Presentation.pdf"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Developed a WiFi CSI-based sign language recognition framework using CNN-GRU with attention to capture spatiotemporal features.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> CSI, Deep Learning, Human Activity Recognition
</p>
</div>

<!-- Project 2 -->
<div class="project-item">
<div class="project-header">
2. <a class="project-link" href="https://github.com/Joysaha189/Neural-Networks-Investigating-Effects-of-Layer-Depth-Neuron-Count-and-Activation-Functions" target="_blank" rel="noopener">Neural Networks: Investigating Effects of Layer Depth, Neuron Count, and Activation Functions</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Neural-Networks-Investigating-Effects-of-Layer-Depth-Neuron-Count-and-Activation-Functions/main/Deliverables/CSI_536_Final_Project_Report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Neural-Networks-Investigating-Effects-of-Layer-Depth-Neuron-Count-and-Activation-Functions/main/Deliverables/Final_Presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Conducted systematic experiments to analyze how architectural choices influence model performance, convergence behavior, and generalization.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Deep Learning, Neural Network Design
</p>
</div>

<!-- Project 3 -->
<div class="project-item">
<div class="project-header">
3. <a class="project-link" href="https://github.com/Joysaha189/Comparative-Analysis-of-Ada-Hessian-and-1st-Order-Optimizers-for-CSI-Based-Sign-Language-Recognition" target="_blank" rel="noopener">Comparative Analysis of AdaHessian and First-Order Optimizers for CSI-Based Sign Language Recognition</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Comparative-Analysis-of-Ada-Hessian-and-1st-Order-Optimizers-for-CSI-Based-Sign-Language-Recognition/main/Deliverables/Project%20Report-Joy.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="poster"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Comparative-Analysis-of-Ada-Hessian-and-1st-Order-Optimizers-for-CSI-Based-Sign-Language-Recognition/main/Deliverables/Joy_Showcase_poster.pdf"
    target="_blank" rel="noopener">Poster</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Performed a comparative study of second-order (AdaHessian) and first-order optimizers, evaluating accuracy, convergence speed, and stability.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Optimization, Deep Learning
</p>
</div>

<!-- Project 4 -->
<div class="project-item">
<div class="project-header">
4. <a class="project-link" href="https://github.com/Joysaha189/Social-Distance-Monitoring-in-Covid19-Situation" target="_blank" rel="noopener">Social Distance Monitoring in COVID-19 Situation</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Social-Distance-Monitoring-in-Covid19-Situation/main/Files/EEE-312%20Project%20Report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Social-Distance-Monitoring-in-Covid19-Situation/main/Files/EEE-312%20Project%20Presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Built a vision-based system to monitor interpersonal distance in public spaces and flag violations using real-time object detection.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Computer Vision, Public Health
</p>
</div>

<!-- Project 5 -->
<div class="project-item">
<div class="project-header">
5. <a class="project-link" href="https://github.com/Joysaha189/IoT-Based-Remote-Heart-Rate-Monitoring-System" target="_blank" rel="noopener">IoT-Based Remote Heart Rate Monitoring System</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/IoT-Based-Remote-Heart-Rate-Monitoring-System/main/Files/Project%20Report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/IoT-Based-Remote-Heart-Rate-Monitoring-System/main/Files/Project%20Presentation.pdf"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Designed an IoT-enabled system for real-time heart-rate acquisition, visualization, and remote health monitoring.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> IoT, Biomedical Signal Processing
</p>
</div>

<!-- Project 6 -->
<div class="project-item">
<div class="project-header">
6. <a class="project-link" href="https://github.com/Joysaha189/IoT-Based-Environment-Monitor-System" target="_blank" rel="noopener">IoT-Based Environment Monitoring System</a>
<span class="project-links">
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/IoT-Based-Environment-Monitor-System/main/Project%20Presentation.pdf"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Developed a sensor-based IoT platform to monitor environmental parameters such as temperature, humidity, and air quality.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> IoT, Sensors
</p>
</div>

<!-- Project 7 -->
<div class="project-item">
<div class="project-header">
7. <a class="project-link" href="https://github.com/Joysaha189/Password-Based-Door-Lock-System" target="_blank" rel="noopener">Password-Based Door Lock System</a>
<span class="project-links">
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Password-Based-Door-Lock-System/main/EEE%20304-%20Project%20Presentation.pdf"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Implemented a microcontroller-based secure door lock system using keypad authentication and access control logic.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Embedded Systems, Security
</p>
</div>

<!-- Project 8 -->
<div class="project-item">
<div class="project-header">
8. <a class="project-link" href="https://github.com/Joysaha189/TDM-PCM-System-Development-in-Proteus" target="_blank" rel="noopener">TDM-PCM System Development in Proteus</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/TDM-PCM-System-Development-in-Proteus/main/Deliverables/EEE-310-project-report-group-13.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/TDM-PCM-System-Development-in-Proteus/main/Deliverables/eee-310-project-presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Simulated a full TDM-PCM communication chain in Proteus, including sampling, quantization, encoding, and reconstruction stages.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Digital Communication, Simulation
</p>
</div>

<!-- Project 9 -->
<div class="project-item">
<div class="project-header">
9. <a class="project-link" href="https://github.com/Joysaha189/Elevator-With-3-Floors" target="_blank" rel="noopener">Elevator With 3 Floors</a>
<span class="project-links">
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Elevator-With-3-Floors/main/Files/Group08_EEE318_Project_Presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Designed and implemented a three-floor elevator control system focusing on request handling, prioritization logic, and safe operation.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Digital Logic, Control Systems
</p>
</div>

<!-- Project 10 -->
<div class="project-item">
<div class="project-header">
10. <a class="project-link" href="https://github.com/Joysaha189/INVESTIGATING-THE-EFFECT-OF-HVDC-CONNECTION-AND-LARGE-INDUSTRIAL-LOADS-IN-IEEE-39-BUS-NETWORK" target="_blank" rel="noopener">Investigating the Effect of HVDC Connection and Large Industrial Loads in IEEE-39 Bus Network</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/INVESTIGATING-THE-EFFECT-OF-HVDC-CONNECTION-AND-LARGE-INDUSTRIAL-LOADS-IN-IEEE-39-BUS-NETWORK/main/Deliverables/EEE306-project-report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/INVESTIGATING-THE-EFFECT-OF-HVDC-CONNECTION-AND-LARGE-INDUSTRIAL-LOADS-IN-IEEE-39-BUS-NETWORK/main/Deliverables/Project-Presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Analyzed the impact of HVDC integration and high-power industrial loads on stability and power flow in the IEEE-39 bus test system.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Power Systems, Smart Grid
</p>
</div>

<!-- Project 11 -->
<div class="project-item">
<div class="project-header">
11. <a class="project-link" href="https://github.com/Joysaha189/Electrical-Service-Design-for-A-Six-Story-Residential-Building" target="_blank" rel="noopener">Electrical Service Design for a Six-Story Residential Building</a>
<span class="project-links">
[<a class="pdf"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Electrical-Service-Design-for-A-Six-Story-Residential-Building/main/Deliverables/Project%20Report.pdf"
    target="_blank" rel="noopener">Report</a>]
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Electrical-Service-Design-for-A-Six-Story-Residential-Building/main/Deliverables/Final%20Presentation.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Developed a complete electrical service layout covering load estimation, panel selection, protection coordination, and safety standards.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Power Distribution, Electrical Design
</p>
</div>

<!-- Project 12 -->
<div class="project-item">
<div class="project-header">
12. <a class="project-link" href="https://github.com/Joysaha189/Laboratory-Variable-DC-Power-Supply" target="_blank" rel="noopener">Laboratory Variable DC Power Supply</a>
<span class="project-links">
[<a class="slides"
    href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Laboratory-Variable-DC-Power-Supply/main/Deliverables/Group03_EEE316_ProjectDemonstration.pptx"
    target="_blank" rel="noopener">Slides</a>]
</span>
</div>
<div class="project-separator"></div>
<p class="project-desc">
Built a laboratory DC power supply with variable voltage and current outputs for educational and experimental purposes.
</p>
<p class="project-keywords">
<strong>Keywords:</strong> Electronics, Power Supply, Laboratory
</p>
</div>
