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
  border-radius: 12px;
  border-left: 8px solid transparent;
  transition: all 0.3s ease;
  color: #000; /* default black text */
}

.edu-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

/* ====== First item (Ph.D.) greenish gradient ===== */
.edu-item:first-child {
  background: linear-gradient(135deg, #d1fae5 0%, #6ee7b7 100%);
  border-left-color: #10b981;
}

.edu-item:first-child:hover {
  border-left-color: #059669;
}

/* Gradient text for first box: degree, university, date */
.edu-item:first-child .edu-date,
.edu-item:first-child .edu-content h3,
.edu-item:first-child .edu-content strong.grad {
  background: linear-gradient(135deg, #10b981 0%, #059669 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== Second item (B.Sc.) soft blue gradient ===== */
.edu-item:nth-child(2) {
  background: linear-gradient(135deg, #e0f2fe 0%, #bae6fd 100%);
  border-left-color: #3b82f6;
}

.edu-item:nth-child(2):hover {
  border-left-color: #1e40af;
}

/* Gradient text for second box: only degree, university, date */
.edu-item:nth-child(2) .edu-date,
.edu-item:nth-child(2) .edu-content h3,
.edu-item:nth-child(2) .edu-content strong.grad {
  background: linear-gradient(135deg, #3b82f6 0%, #1e40af 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== General Text ===== */
.edu-content {
  color: #000; /* all text black */
}

.edu-content ul {
  margin: 0.5rem 0 0 1rem;
}

.edu-content li {
  margin-bottom: 0.4rem;
}

/* Bold black for all labels (Major, GPA, Advisor, Research, Honors, Undergraduate Thesis) */
.edu-content li strong {
  font-weight: 700;
  color: #000;
}

/* Thesis name link in black and underlined */
.edu-content strong.thesis-title + a {
  font-weight: 600;
  color: #000;
  text-decoration: underline;
  margin-left: 0.25rem;
}

/* PDF and Slides links keep original colors */
.thesis-links a.pdf {
  color: #1f6feb; /* blue */
  text-decoration: none;
}

.thesis-links a.slides {
  color: #d97706; /* orange */
  text-decoration: none;
}

.thesis-links a.pdf:hover,
.thesis-links a.slides:hover {
  text-decoration: underline;
}

/* Divider line */
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
  background: linear-gradient(90deg, transparent, #0ea5e9, transparent);
  opacity: 0.3;
}

/* Responsive */
@media (max-width: 720px) {
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
      <strong class="grad">University at Albany, SUNY</strong>
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
      <strong class="grad">Bangladesh University of Engineering and Technology (BUET)</strong>
      <ul>
        <li><strong>Major:</strong> Communication and Signal Processing</li>
        <li><strong>GPA:</strong> 3.61 / 4.00</li>
        <li>
          <strong class="thesis-title">Undergraduate Thesis:</strong>
          <a href="https://github.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data" target="_blank" rel="noopener">
            Implementation-Friendly Convolutional Neural Network for Sign Language Recognition Using WiFi CSI Data
          </a>
          <span class="thesis-links">
            [<a class="pdf"
               href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data/main/Deliverables/UG_Thesis_1706189.pdf"
               target="_blank" rel="noopener">PDF</a>]
            [<a class="slides"
               href="https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Joysaha189/Implementation-Friendly-CNN-For-Sign-Language-Recognition-Using-Wi-Fi-CSI-Data/main/Deliverables/Thesis-Presentation.pdf"
               target="_blank" rel="noopener">Slides</a>]
          </span>
        </li>
        <li><strong>Honors:</strong> Dean's List (2022)</li>
      </ul>
    </div>
  </div>
</div>
