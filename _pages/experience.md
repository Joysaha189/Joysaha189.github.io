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
/* ====== Experience Timeline ====== */
.exp-timeline {
  margin: 0;
  padding: 0;
}

.exp-item {
  display: grid;
  grid-template-columns: 180px 1fr;
  column-gap: 16px;
  align-items: center;
  margin: 0 0 2.25rem 0;
  padding: 1.5rem;
  background: linear-gradient(135deg, #e0f2fe 0%, #bae6fd 100%);
  border-radius: 12px;
  border-left: 8px solid #0ea5e9;
  transition: all 0.3s ease;
}

.exp-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(14, 165, 233, 0.3);
  border-left-color: #0284c7;
}

/* ===== FIRST BOX (Graduate TA) ===== */
.exp-item:first-child {
  background: linear-gradient(135deg, #ecfeff 0%, #cffafe 100%);
  border-left-color: #0891b2;
}

/* Other boxes — unchanged */
.exp-item:nth-child(2) {
  background: linear-gradient(135deg, #ddd6fe 0%, #c4b5fd 100%);
  border-left-color: #8b5cf6;
}

.exp-item:nth-child(3) {
  background: linear-gradient(135deg, #dcfce7 0%, #bbf7d0 100%);
  border-left-color: #10b981;
}

.exp-item:nth-child(4) {
  background: linear-gradient(135deg, #fce7f3 0%, #fbcfe8 100%);
  border-left-color: #ec4899;
}

/* DATE */
.exp-date {
  font-weight: 700;
  line-height: 1.4;
  text-align: right;
  white-space: nowrap;
  font-size: 0.95rem;
  color: #2d3748;
}

/* First box date color */
.exp-item:first-child .exp-date {
  background: linear-gradient(135deg, #0891b2 0%, #0e7490 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* CONTENT */
.exp-content {
  color: #2d3748;
}

.exp-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.15rem;
  line-height: 1.35;
}

/* First box title */
.exp-item:first-child .exp-content h3 {
  background: linear-gradient(135deg, #0891b2 0%, #0e7490 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* Organization name */
.exp-content strong:first-of-type {
  font-weight: 700;
  font-size: 1.05rem;
  color: #1a202c;
}

/* First box organization */
.exp-item:first-child .exp-content strong:first-of-type {
  background: linear-gradient(135deg, #0f766e 0%, #115e59 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* First box text override */
.exp-item:first-child .exp-content,
.exp-item:first-child .exp-content li,
.exp-item:first-child .exp-content strong {
  color: #083344;
}

.exp-content .meta {
  margin: 0.35rem 0 0.1rem 0;
  font-size: 0.95rem;
  color: #4a5568;
}

.exp-item:first-child .meta {
  color: #155e75;
}

.exp-content ul {
  margin: 0.5rem 0 0 1rem;
}

.exp-content li {
  margin-bottom: 0.4rem;
}

/* Divider */
.exp-item + .exp-item {
  position: relative;
  margin-top: 2rem;
}

.exp-item + .exp-item::after {
  content: "";
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
  .exp-item {
    grid-template-columns: 150px 1fr;
  }
}

@media (max-width: 520px) {
  .exp-item {
    grid-template-columns: 1fr;
    align-items: start;
  }

  .exp-date {
    text-align: left;
    margin-bottom: 0.5rem;
    white-space: normal;
  }
}
</style>

<div class="exp-timeline">

  <!-- Graduate Teaching Assistant -->
  <div class="exp-item">
    <div class="exp-date">
      Aug 2024 – May 2025<br/>
      Aug 2025 – Present
    </div>
    <div class="exp-content">
      <h3>Graduate Teaching Assistant</h3>
      <strong>University at Albany, SUNY</strong> — NY, United States
      <div class="meta">Department of Electrical and Computer Engineering</div>
      <ul>
        <li>Supported undergraduate courses by assisting with grading, laboratory sessions, and student mentoring through office hours and tutorials.</li>
        <li><strong>Award:</strong> CNSE Excellence in Teaching (2025)</li>
        <li><strong>Courses Assisted:</strong>
          <ul>
            <li>IECE 371 — Signals and Systems (Fall 2024)</li>
            <li>IECE 300 — Introduction to Electronics (Fall 2024)</li>
            <li>IECE 310 — Engineering Electromagnetics (Spring 2025)</li>
            <li>IECE 442 — System Analysis and Design (Spring 2025)</li>
            <li>IECE 490/1 — Electrical System Design (Fall 2025)</li>
            <li>IECE 310 — Engineering Electromagnetics (Spring 2026)</li>
            <li>IECE 490/1 — Electrical System Design (Spring 2026)</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>

  <!-- Research Project Assistant -->
  <div class="exp-item">
    <div class="exp-date">May 2025 – Aug 2025</div>
    <div class="exp-content">
      <h3>Research Project Assistant</h3>
      <strong>The Research Foundation for SUNY</strong> — NY, United States
      <div class="meta">Department of Electrical and Computer Engineering</div>
      <ul>
        <li>
          Developed a sequential, instance-specific feature acquisition framework with dynamic group sizing to balance accuracy and cost; reduced feature usage and inference time while sustaining or improving classification. Evaluated on nine public datasets; extended toward a journal paper with initial results submitted to ICASSP 2026.
        </li>
      </ul>
    </div>
  </div>

  <!-- Part-Time Lecturer -->
  <div class="exp-item">
    <div class="exp-date">Jan 2024 – Aug 2024</div>
    <div class="exp-content">
      <h3>Part-Time Lecturer</h3>
      <strong>Presidency University</strong> — Dhaka, Bangladesh
      <div class="meta">Department of Electrical and Electronic Engineering</div>
      <ul>
        <li>
          Taught undergraduate Digital Electronics and Numerical Methods courses, including lectures, laboratories, assessments, and academic mentoring.
        </li>
        <li><strong>Courses Taught:</strong>
          <ul>
            <li>CSE-207 / EE-205 — Digital Electronics</li>
            <li>CSE-208 / EE-206 — Digital Electronics Laboratory (Spring &amp; Summer 2024)</li>
            <li>EE-211 / EEE-311 — Numerical Methods (Spring &amp; Summer 2024)</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>

  <!-- Adjunct Lecturer -->
  <div class="exp-item">
    <div class="exp-date">Feb 2024 – Jul 2024</div>
    <div class="exp-content">
      <h3>Adjunct Lecturer</h3>
      <strong>Bangladesh University of Textiles (BUTEX)</strong> — Dhaka, Bangladesh
      <div class="meta">Department of Textile Machinery Design and Maintenance</div>
      <ul>
        <li>
          Delivered lectures and supervised laboratories in electrical and electronic engineering, designed assessments, evaluated student performance, and provided academic support.
        </li>
        <li><strong>Courses Taught:</strong>
          <ul>
            <li>MDM 201 — Fundamentals of Electrical and Electronic Engineering (WPE, AE, TFD)</li>
            <li>MDM 202 — Fundamentals of Electrical and Electronic Engineering Laboratory (WPE, TFD)</li>
            <li>MDM 305 — Machine Control Engineering (TMDM)</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>

</div>
