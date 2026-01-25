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
/* ====== Education Timeline (Left dates, centered alignment, no dot) ====== */
.edu-timeline {
  margin: 0;
  padding: 0;
}

/* Two-column grid: [date] [content] */
.edu-item {
  display: grid;
  grid-template-columns: 180px 1fr;
  column-gap: 16px;
  align-items: center;
  margin: 0 0 2.25rem 0;
  color: inherit;
}

/* DATE (left) */
.edu-date {
  font-weight: 700;
  color: inherit;
  line-height: 1.4;
  text-align: right;
  padding-right: 4px;
  white-space: nowrap;
}

/* CONTENT (right) */
.edu-content {
  color: inherit;
}

.edu-content h3 {
  margin: 0 0 0.25rem 0;
  font-size: 1.05rem;
  line-height: 1.35;
}

.edu-content strong {
  font-weight: 600;
}

.edu-content ul {
  margin: 0.5rem 0 0 1rem;
}

/* Subtle divider between entries */
.edu-item + .edu-item {
  position: relative;
}
.edu-item + .edu-item::after {
  content: "";
  display: block;
  margin-left: calc(180px + 16px);
  margin-top: 1.5rem;
  height: 1px;
  background: currentColor;
  opacity: 0.12;
}

/* ====== Responsive ====== */
@media (max-width: 720px) {
  .edu-item {
    grid-template-columns: 150px 1fr;
  }
  .edu-item + .edu-item::after {
    margin-left: calc(150px + 16px);
  }
}

@media (max-width: 520px) {
  .edu-item {
    grid-template-columns: 1fr;
    align-items: start;
  }
  .edu-date {
    text-align: left;
    margin-bottom: 0.25rem;
    white-space: normal;
  }
  .edu-item + .edu-item::after {
    margin-left: 0;
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
        <li><strong>Research Focus:</strong> Dynamic feature grouping; costly feature acquisition</li>
        <li><strong>Advisor:</strong> Prof. Daphney-Stavourla Zois</li>
        <li><strong>GPA:</strong> 4.00 / 4.00</li>
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
        <li><strong>Undergraduate Thesis:</strong>
          <a href="https://github.com/Joysaha189">
            Implementation-Friendly Convolutional Neural Network for Sign Language Recognition Using WiFi CSI Data
          </a>
        </li>
        <li><strong>Honors:</strong> Dean’s List (2022)</li>
      </ul>
    </div>
  </div>

</div>
