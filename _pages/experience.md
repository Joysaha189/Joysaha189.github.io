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
  border-radius: 12px;
  border-left: 8px solid transparent;
  transition: all 0.3s ease;
}

.exp-item:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

/* ====== First Box (Graduate TA) ===== */
.exp-item:first-child {
  background: linear-gradient(135deg, #ecfeff 0%, #cffafe 100%);
  border-left-color: #0891b2;
}

.exp-item:first-child .exp-date,
.exp-item:first-child .exp-content h3,
.exp-item:first-child .exp-content strong:first-of-type,
.exp-item:first-child .meta {
  background: linear-gradient(135deg, #0891b2 0%, #0e7490 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== Second Box (Research Project Assistant) ===== */
.exp-item:nth-child(2) {
  background: linear-gradient(135deg, #ddd6fe 0%, #c4b5fd 100%);
  border-left-color: #8b5cf6;
}

.exp-item:nth-child(2) .exp-date,
.exp-item:nth-child(2) .exp-content h3,
.exp-item:nth-child(2) .exp-content strong:first-of-type,
.exp-item:nth-child(2) .meta {
  background: linear-gradient(135deg, #7c3aed 0%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== Third Box (Part-Time Lecturer) ===== */
.exp-item:nth-child(3) {
  background: linear-gradient(135deg, #dcfce7 0%, #bbf7d0 100%);
  border-left-color: #10b981;
}

.exp-item:nth-child(3) .exp-date,
.exp-item:nth-child(3) .exp-content h3,
.exp-item:nth-child(3) .exp-content strong:first-of-type,
.exp-item:nth-child(3) .meta {
  background: linear-gradient(135deg, #10b981 0%, #059669 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== Fourth Box (Adjunct Lecturer) - NEW ORANGE ===== */
.exp-item:nth-child(4) {
  background: linear-gradient(135deg, #fff7ed 0%, #ffe4b5 100%);
  border-left-color: #f97316;
}

.exp-item:nth-child(4) .exp-date,
.exp-item:nth-child(4) .exp-content h3,
.exp-item:nth-child(4) .exp-content strong:first-of-type,
.exp-item:nth-child(4) .meta {
  background: linear-gradient(135deg, #f97316 0%, #ea580c 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* ====== General Text ===== */
.exp-content {
  color: #2d3748; /* default black for normal text */
}

.exp-content ul li {
  color: #2d3748; /* list items default black */
}

/* DATE */
.exp-date {
  font-weight: 700;
  line-height: 1.4;
  text-align: right;
  white-space: nowrap;
  font-size: 0.95rem;
}

/* CONTENT TITLE */
.exp-content h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1.15rem;
  line-height: 1.35;
}

/* Organization */
.exp-content strong:first-of-type {
  font-weight: 700;
  font-size: 1.05rem;
}

/* Department / Meta */
.exp-content .meta {
  margin: 0.35rem 0 0.1rem 0;
  font-size: 0.95rem;
}

/* Nested Lists (Courses) keep color effect */
.exp-content li strong {
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
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
