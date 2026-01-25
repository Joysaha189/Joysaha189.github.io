
---
layout: single
title: " "
permalink: /experience/
type: pages
author_profile: true
header:
  overlay: false
---

<style>
/* ====== Experience Timeline (Left dates, two-column grid, subtle divider) ====== */
.exp-timeline {
  margin: 0;
  padding: 0;
}

/* Two-column grid: [date] [content] */
.exp-item {
  display: grid;
  grid-template-columns: 180px 1fr;
  column-gap: 16px;
  align-items: center;
  margin: 0 0 2.25rem 0;
  color: inherit;
}

/* DATE (left) */
.exp-date {
  font-weight: 700;
  color: inherit;
  line-height: 1.4;
  text-align: right;
  padding-right: 4px;
  white-space: nowrap;
}

/* CONTENT (right) */
.exp-content {
  color: inherit;
}

.exp-content h3 {
  margin: 0 0 0.25rem 0;
  font-size: 1.05rem;
  line-height: 1.35;
}

.exp-content strong { font-weight: 600; }

.exp-content .meta {
  margin: 0.35rem 0 0.1rem 0;
  font-size: 0.95rem;
  opacity: 0.9;
}

.exp-content ul { margin: 0.5rem 0 0 1rem; }

/* Subtle divider between entries */
.exp-item + .exp-item { position: relative; }
.exp-item + .exp-item::after {
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
  .exp-item { grid-template-columns: 150px 1fr; }
  .exp-item + .exp-item::after { margin-left: calc(150px + 16px); }
}
@media (max-width: 520px) {
  .exp-item { grid-template-columns: 1fr; align-items: start; }
  .exp-date { text-align: left; margin-bottom: 0.25rem; white-space: normal; }
  .exp-item + .exp-item::after { margin-left: 0; }
}
</style>

<div class="exp-timeline">

  <!-- Graduate Teaching Assistant -->
  <div class="exp-item">
    <div class="exp-date">Aug 2024 – Present</div>
    <div class="exp-content">
      <h3>Graduate Teaching Assistant</h3>
      <strong>University at Albany, SUNY</strong> — NY, United States
      <div class="meta">Department of Electrical and Computer Engineering</div>
      <!-- Optional responsibilities
      <ul>
        <li>Assisted in ECE coursework and labs; graded assignments.</li>
        <li>Held office hours; supported <em>Signal Processing</em> and <em>Communications</em> courses.</li>
      </ul> -->
    </div>
  </div>

  <!-- Research Project Assistant -->
  <div class="exp-item">
    <div class="exp-date">May 2025 – Aug 2025</div>
    <div class="exp-content">
      <h3>Research Project Assistant</h3>
      <strong>The Research Foundation for SUNY</strong> — NY, United States
      <div class="meta">Department of Electrical and Computer Engineering</div>
      <!-- Optional responsibilities
      <ul>
        <li>Supported research on dynamic feature grouping and costly feature acquisition.</li>
      </ul> -->
    </div>
  </div>

  <!-- Part‑Time Lecturer -->
  <div class="exp-item">
    <div class="exp-date">Jan 2024 – Aug 2024</div>
    <div class="exp-content">
      <h3>Part‑Time Lecturer</h3>
      <strong>Presidency University</strong> — Dhaka, Bangladesh
      <div class="meta">Department of Electrical and Electronic Engineering</div>
      <!-- Optional responsibilities
      <ul>
        <li>Delivered lectures; designed assessments and labs.</li>
      </ul> -->
    </div>
  </div>

  <!-- Adjunct Lecturer -->
  <div class="exp-item">
    <div class="exp-date">Feb 2024 – Jul 2024</div>
    <div class="exp-content">
      <h3>Adjunct Lecturer</h3>
      <strong>Bangladesh University of Textiles</strong> — Dhaka, Bangladesh
      <div class="meta">Department of Textile Machinery Design and Maintenance</div>
      <!-- Optional responsibilities
      <ul>
        <li>Taught core courses and advised student projects.</li>
      </ul> -->
    </div>
  </div>

</div>
