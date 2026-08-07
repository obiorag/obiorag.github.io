---
layout: page
title: ""
permalink: /experiences/
author_profile: true
classes: wide
---

<!-- Heading Grid -->
<div style="max-width: 900px; margin: auto; padding-bottom: 1rem;">
  <h1 style="margin-bottom: 0.2rem; font-size: 2.2rem; font-weight: 700; color: #222;">Experiences</h1>
  <p style="color: #666; margin-top: 0; font-size: 1.05rem;">A timeline of research, industry engineering, and academic instruction.</p>
</div>

<style>
/* Modern Timeline Layout */
.timeline {
  max-width: 900px;
  margin: 1.5rem auto 3.5rem auto;
  position: relative;
  padding-left: 1.5rem;
  border-left: 2px solid #ebeeef;
}

.timeline-item {
  position: relative;
  margin-bottom: 2rem;
}

.timeline-item::before {
  content: "";
  position: absolute;
  left: calc(-1.5rem - 6px);
  top: 0.35rem;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #007BA7;
  border: 2px solid #fff;
  box-shadow: 0 0 0 2px rgba(0, 123, 167, 0.25);
}

.timeline-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.timeline-title {
  font-size: 1.05rem;
  font-weight: 600;
  color: #222;
  margin: 0;
}

.timeline-date {
  font-size: 0.88rem;
  color: #666;
  font-weight: 500;
  white-space: normal;
}

.timeline-org {
  color: #007BA7;
  font-weight: 600;
}

/* Teaching & Mentoring Clean Layout */
.section-title {
  max-width: 900px;
  margin: 3rem auto 1.5rem auto;
  font-size: 1.4rem;
  font-weight: 700;
  color: #222;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.4rem;
}

.teaching-container {
  max-width: 900px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.teaching-card {
  padding: 1.2rem 1.5rem;
  border-radius: 8px;
  background: #fafafa;
  border: 1px solid #f0f0f0;
}

.teaching-card.instructor {
  border-left: 4px solid #007BA7;
  background: linear-gradient(to right, #f4fafd, #fafafa);
}

.teaching-card.ta {
  border-left: 4px solid #555;
}

.teaching-card.mentoring {
  border-left: 4px solid #aaa;
}

.card-role {
  font-size: 1.05rem;
  font-weight: 600;
  color: #222;
  margin-bottom: 0.8rem;
}

.course-list {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}

.course-item {
  background: #fff;
  padding: 0.75rem 1rem;
  border-radius: 6px;
  border: 1px solid #ebeeef;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.course-info {
  display: flex;
  align-items: baseline;
  gap: 0.5rem;
}

.course-code {
  font-weight: 600;
  color: #333;
  font-size: 0.95rem;
}

.course-name {
  font-size: 0.9rem;
  color: #555;
}

.course-term {
  font-size: 0.8rem;
  font-weight: 500;
  color: #666;
  background: #f0f0f0;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
}

.mentor-project {
  font-size: 0.88rem;
  color: #666;
  margin-top: 0.1rem;
}

@media (max-width: 600px) {
  .timeline-header, .course-item {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.2rem;
  }
}
</style>

<!-- Section 1: Employment & Research -->
<div class="section-title">
  <i class="fas fa-briefcase" style="color: #007BA7; margin-right: 0.3rem;"></i> Employment & Research
</div>

<div class="timeline">
  
  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">Purdue University</span> &mdash; Graduate Research Assistant</div>
      <div class="timeline-date">2023 – 2024, 2025 – Present</div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">MIT Lincoln Laboratory</span> &mdash; Summer Research Intern</div>
      <div class="timeline-date">May 2023 – Oct 2023</div>
    </div>
    <div style="font-size: 0.88rem; color: #666; margin-top: 0.2rem;">Group 36 &middot; Integrated Missile Defense Technology</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">MIT Lincoln Laboratory</span> &mdash; Summer Research Intern</div>
      <div class="timeline-date">May 2022 – Aug 2022</div>
    </div>
    <div style="font-size: 0.88rem; color: #666; margin-top: 0.2rem;">Group 37 &middot; Advanced Undersea Systems & Technology</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">NJIT</span> &mdash; Research Assistant & Graduate Researcher</div>
      <div class="timeline-date">July 2020 – May 2021</div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">Accel Learning</span> &mdash; Mathematics Instructor</div>
      <div class="timeline-date">Sep 2020 – Dec 2020</div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-header">
      <div class="timeline-title"><span class="timeline-org">Mathnasium</span> &mdash; Mathematics Instructor & Tutor</div>
      <div class="timeline-date">Sep 2018 – Jan 2019</div>
    </div>
  </div>

</div>

<!-- Section 2: Teaching & Mentoring -->
<div class="section-title">
  <i class="fas fa-graduation-cap" style="color: #555; margin-right: 0.3rem;"></i> Teaching & Mentoring
</div>

<div class="teaching-container">

  <!-- Instructor Card -->
  <div class="teaching-card instructor">
    <div class="card-role">Instructor of Record</div>
    <div class="course-list">
      <div class="course-item">
        <div class="course-info">
          <span class="course-code">MA 16020</span>
          <span class="course-name">Applied Calculus II</span>
        </div>
        <span class="course-term" style="background: #e2f0f7; color: #007BA7;">Fall 2025</span>
      </div>
    </div>
  </div>

  <!-- TA Card -->
  <div class="teaching-card ta">
    <div class="card-role">Graduate Teaching Assistant</div>
    <div class="course-list">
      
      <div class="course-item">
        <div class="course-info">
          <span class="course-code">MA 511</span>
          <span class="course-name">Linear Algebra</span>
        </div>
        <span class="course-term">Spring 2023</span>
      </div>

      <div class="course-item">
        <div class="course-info">
          <span class="course-code">MA 251</span>
          <span class="course-name">Multivariable Calculus</span>
        </div>
        <span class="course-term">Fall 2022</span>
      </div>

      <div class="course-item">
        <div class="course-info">
          <span class="course-code">MA 162</span>
          <span class="course-name">Calculus II</span>
        </div>
        <span class="course-term">Spring 2022</span>
      </div>

      <div class="course-item">
        <div class="course-info">
          <span class="course-code">MA 161</span>
          <span class="course-name">Calculus I</span>
        </div>
        <span class="course-term">Fall 2021</span>
      </div>

    </div>
  </div>

  <!-- Mentoring Card -->
  <div class="teaching-card mentoring">
    <div class="card-role">Mentoring & Academic Service</div>
    <div class="course-list">
      
      <div class="course-item">
        <div>
          <div class="course-code">Purdue Math Directed Reading Program</div>
          <div class="mentor-project">Project Focus: Computational Topology</div>
        </div>
        <span class="course-term">Spring 2025</span>
      </div>

      <div class="course-item">
        <div class="course-info">
          <span class="course-code">AMC / AIME Examination Mentoring</span>
        </div>
        <span class="course-term">2020</span>
      </div>

    </div>
  </div>

</div>

