---
layout: single
title: ""
permalink: /education/
author_profile: true
---



<style>
/* ====== Education Timeline (Left-aligned dates, bold) ====== */
.edu-timeline {
  position: relative;
  margin: 0;
  padding: 0;
}

/* One entry in the timeline */
.edu-item {
  position: relative;
  display: grid;
  grid-template-columns: 160px 16px 1fr; /* left: date | middle: dot space | right: content */
  column-gap: 16px;
  align-items: start;
  margin-bottom: 2.25rem; /* space between entries */
}

/* DATE (timeline label on the left) */
.edu-date {
  font-weight: 700;         /* strong format */
  color: #333;              /* readable, dark gray */
  line-height: 1.4;
  text-align: right;        /* align date near the dot */
  padding-right: 4px;
  white-space: nowrap;      /* keeps the date on one line where possible */
}

/* DOT (small visual cue instead of a long vertical line) */
.edu-dot {
  position: relative;
  width: 16px;
  height: 16px;
}

.edu-dot::before {
  content: "";
  position: absolute;
  top: 0.35rem;             /* vertically centers dot relative to first content line */
  left: 50%;
  transform: translateX(-50%);
  width: 8px;
  height: 8px;
  background: #555;
  border-radius: 50%;
}

/* CONTENT (degree, university, bullets) */
.edu-content h3 {
  margin: 0 0 0.25rem 0;
  font-size: 1.05rem;
  line-height: 1.3;
}

.edu-content strong {
  font-weight: 600;
}

.edu-content ul {
  margin: 0.5rem 0 0 1rem;
}

/* A gentle divider between entries (optional; not a vertical line) */
.edu-item + .edu-item::after {
  content: "";
  display: block;
  margin-left: 176px;       /* aligns under content start (160 + 16) */
  margin-top: 1.5rem;
  height: 1px;
  background: #eee;
}

/* ====== Responsive tweaks ====== */
@media (max-width: 640px) {
  .edu-item {
    grid-template-columns: 120px 16px 1fr;
  }
  .edu-item + .edu-item::after {
    margin-left: 136px;
  }
}

@media (max-width: 480px) {
  .edu-item {
    grid-template-columns: 1fr;     /* stack on very small screens */
  }
  .edu-date {
    text-align: left;
    margin-bottom: 0.25rem;
  }
  .edu-dot {
    display: none;                  /* hide dot on tiny screens if you prefer */
  }
  .edu-item + .edu-item::after {
    margin-left: 0;
  }
}
</style>

<div class="edu-timeline">

  <!-- Ph.D. -->
  <div class="edu-item">
    <div class="edu-date"><strong>Aug 2024 – Present</strong></div>
    <div class="edu-dot" aria-hidden="true"></div>
    <div class="edu-content">
      <h3>Ph.D. in Electrical and Computer Engineering</h3>
      <strong>University at Albany, SUNY</strong>
      <ul>
        <li><strong>Research Focus:</strong> Dynamic feature grouping; costly feature acquisition</li>
        <li><strong>Advisor:</strong> Prof. Daphney‑Stavourla Zois</li>
      </ul>
    </div>
  </div>

  <!-- B.Sc. -->
  <div class="edu-item">
    <div class="edu-date"><strong>Mar 2018 – May 2023</strong></div>
    <div class="edu-dot" aria-hidden="true"></div>
    <div class="edu-content">
      <h3>B.Sc. in Electrical and Electronic Engineering</h3>
      <strong>Bangladesh University of Engineering and Technology (BUET)</strong>
      <ul>
        <li><strong>Major:</strong> Communication and Signal Processing</li>
        <li><strong>GPA:</strong> 3.61 / 4.00</li>
        <li><strong>Undergraduate Thesis:</strong>
          <a href="https://github.com/Joysaha189">
            Implementation‑Friendly Convolutional Neural Network for Sign Language Recognition Using WiFi CSI Data
          </a>
        </li>
        <li><strong>Honors:</strong> Dean’s List (2022)</li>
      </ul>
    </div>
  </div>

</div>

