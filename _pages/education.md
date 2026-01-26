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
body {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  min-height: 100vh;
}

/* ====== Education Timeline (Left dates, centered alignment, no dot) ====== */
.edu-timeline {
  margin: 0;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 16px;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
}

/* Two-column grid: [date] [content] */
.edu-item {
  display: grid;
  grid-template-columns: 180px 1fr;
  column-gap: 16px;
  align-items: center;
  margin: 0 0 2.25rem 0;
  padding: 1.5rem;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 12px;
  border-left: 5px solid #667eea;
  transition: all 0.3s ease;
}

.edu-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
  border-left-color: #764ba2;
}

.edu-item:first-child {
  background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
  border-left-color: #ff6b6b;
}

.edu-item:first-child:hover {
  border-left-color: #ee5a24;
}

/* DATE (left) */
.edu-date {
  font-weight: 700;
  color: #2d3748;
  line-height: 1.4;
  text-align: right;
  padding-right: 4px;
  white-space: nowrap;
  font-size: 0.95rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.edu-item:first-child .edu-date {
  background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

/* CONTENT (right) */
.edu-content {
  color: #2d3748;
}

.edu-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.15rem;
  line-height: 1.35;
  color: #1a202c;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.edu-item:first-child .edu-content h3 {
  background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
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

/* Subtle divider between entries */
.edu-item + .edu-item {
  position: relative;
  margin-top: 2rem;
}

.edu-item + .edu-item::after {
  content: "";
  display: block;
  position: absolute;
  top: -1rem;
  left: calc(180px + 16px + 1.5rem);
  right: 1.5rem;
  height: 2px;
  background: linear-gradient(90deg, transparent, #667eea, transparent);
  opacity: 0.3;
}

/* ====== Thesis link colors ====== */
.thesis-links {
  display: inline-block;
  margin-top: 0.25rem;
}

.thesis-links a {
  font-weight: 600;
  text-decoration: none;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
  transition: all 0.2s ease;
  display: inline-block;
}

.thesis-links a.pdf {
  color: #1f6feb;
  background: rgba(31, 111, 235, 0.1);
}

.thesis-links a.pdf:hover {
  background: rgba(31, 111, 235, 0.2);
  transform: translateY(-2px);
}

.thesis-links a.slides {
  color: #d97706;
  background: rgba(217, 119, 6, 0.1);
}

.thesis-links a.slides:hover {
  background: rgba(217, 119, 6, 0.2);
  transform: translateY(-2px);
}

/* ====== Responsive ====== */
@media (max-width: 720px) {
  .edu-timeline {
    padding: 1.5rem;
  }
  
  .edu-item {
    grid-template-columns: 150px 1fr;
  }
  
  .edu-item + .edu-item::after {
    left: calc(150px + 16px + 1.5rem);
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
  
  .edu-item + .edu-item::after {
    left: 1.5rem;
  }
}
</style>

<div class="edu-timeline">
  <!-- Ph.D. -->
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
  
  <!-- B.Sc. -->
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
