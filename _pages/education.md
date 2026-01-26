---
layout: single
title: " "
permalink: /education/
type: pages
author_profile: true
header:
  overlay: false
---
<style>
/* ====== Education Timeline ====== */
.edu-timeline {
  margin: 0;
  padding: 0;
}

.edu-item {
  display: grid;
  grid-template-columns: 180px 1fr;
  column-gap: 16px;
  align-items: center;
  margin: 0 0 2.25rem 0;
  padding: 1.5rem;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 12px;
  border-left: 8px solid #667eea;
  transition: all 0.3s ease;
}

.edu-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
  border-left-color: #764ba2;
}

/* ===== PhD (first item) ===== */
.edu-item:first-child {
  background: linear-gradient(135deg, #e0f2fe 0%, #bae6fd 100%);
  border-left-color: #0284c7;
}

.edu-item:first-child:hover {
  border-left-color: #0369a1;
}

/* DATE */
.edu-date {
  font-weight: 700;
  line-height: 1.4;
  text-align: right;
  white-space: nowrap;
  font-size: 0.95rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.edu-item:first-child .edu-date {
  background: linear-gradient(135deg, #0284c7 0%, #0369a1 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* CONTENT */
.edu-content {
  color: #2d3748;
}

.edu-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.15rem;
  line-height: 1.35;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.edu-item:first-child .edu-content h3 {
  background: linear-gradient(135deg, #0284c7 0%, #0369a1 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* University name */
.edu-content strong:first-of-type {
  font-weight: 700;
  font-size: 1.05rem;
  background: linear-gradient(135deg, #10b981 0%, #059669 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.edu-item:first-child .edu-content strong:first-of-type {
  background: linear-gradient(135deg, #16a34a 0%, #15803d 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.edu-content strong {
  font-weight: 600;
  color: #4a5568;
}

.edu-content ul {
  margin: 0.5rem 0 0 1rem;
}

.edu-content li {
  margin-bottom: 0.4rem;
  color: #2d3748;
}

/* Divider */
.edu-item + .edu-item {
  position: relative;
  margin-top: 2rem;
}

.edu-item + .edu-item::after {
  content: "";
  position: absolute;
  top: -1rem;
  left: calc(180px + 16px + 1.5rem);
  right: 1.5rem;
  height: 2px;
  background: linear-gradient(90deg, transparent, #667eea, transparent);
  opacity: 0.3;
}

/* ===== Thesis links — PURE BLACK ===== */
.thesis-links {
  display: inline-block;
  margin-top: 0.25rem;
}

.thesis-links a,
.thesis-links a.pdf,
.thesis-links a.slides {
  font-weight: 600;
  text-decoration: none;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
  color: #000000;
  background: transparent;
}

.thesis-links a:hover,
.thesis-links a.pdf:hover,
.thesis-links a.slides:hover {
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 720px) {
  .edu-item {
    grid-template-columns: 150px 1fr;
  }
}

@media (max-width: 520px) {
  .edu-item {
    grid-template-columns: 1fr;
    align-items: start;
  }

  .edu-date {
    text-align: left;
    margin-bottom: 0.5rem;
    white-space: normal;
  }
}
</style>

<div class="edu-timeline">

  <!-- PhD -->
  <div class="edu-item">
    <div class="edu-date">Aug 2024 – Present</div>
    <div class="edu-content">
      <h3>Ph.D. in Electrical and Computer Engineering</h3>
      <strong>University at Albany, SUNY</strong>
      <ul>
        <li><strong>Major:</strong> Signal Processing and Communications</li>
        <li><strong>GPA:</strong> 4.00 / 4.00</li>
        <li><strong>Research Focus:</strong> Dynamic feature grouping; costly feature acquisition</li>
        <li><strong>Advisor:</strong> Prof. Daphney-Stavourla Zois</li>
      </ul>
    </div>
  </div>

  <!-- BSc -->
  <div class="edu-item">
    <div class="edu-date">Mar 2018 – May 2023</div>
    <div class="edu-content">
      <h3>B.Sc. in Electrical and Electronic Engineering</h3>
      <strong>Bangladesh University of Engineering and Technology (BUET)</strong>
      <ul>
        <li><strong>Major:</strong> Communication and Signal Processing</li>
        <li><strong>GPA:</strong> 3.61 / 4.00</li>
        <li>
          <strong>Undergraduate Thesis:</strong>
          <a href="https://github.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data">
            Implementation-Friendly Convolutional Neural Network for Sign Language Recognition Using WiFi CSI Data
          </a>
          <span class="thesis-links">
            [
            <a class="pdf"
               href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data/main/Deliverables/UG_Thesis_1706189.pdf"
               target="_blank" rel="noopener">PDF</a>
            ]
            [
            <a class="slides"
               href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data/main/Deliverables/Thesis-Presentation.pdf"
               target="_blank" rel="noopener">Slides</a>
            ]
          </span>
        </li>
        <li><strong>Honors:</strong> Dean's List (2022)</li>
      </ul>
    </div>
  </div>

</div>
