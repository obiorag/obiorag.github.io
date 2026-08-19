---
layout: page
title: ""
permalink: /about/
author_profile: true
classes: wide
---

<style>
/* =========================================================
   ABOUT PAGE
   ========================================================= */

.about-page {
  --accent: #007BA7;
  --ink: #222;
  --muted: #777;
  --light: #f5f7f8;
  --line: #dfe4e7;

  max-width: 980px;
  margin: 0 auto;
}

/* ---------- Header ---------- */

.about-header {
  position: relative;
  padding: 14px 0 58px;
  margin-bottom: 52px;
  border-bottom: 1px solid var(--line);
}

.about-eyebrow {
  font-size: 0.82rem;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  color: var(--accent);
  margin-bottom: 15px;
}

.about-header h1 {
  margin: 0;
  font-size: 2.7rem;
  font-weight: 400;
  letter-spacing: -0.025em;
  line-height: 1.2;
}

.about-header::after {
  content: "";
  display: block;
  width: 85px;
  height: 3px;
  background: var(--accent);
  margin-top: 28px;
}

/* ---------- Biography ---------- */

.biography {
  max-width: 820px;
  margin-bottom: 78px;
}

.biography p {
  margin: 0 0 22px;
  font-size: 1.14rem;
  line-height: 1.85;
  color: #444;
}

.biography p:last-child {
  margin-bottom: 0;
}

.biography strong {
  color: var(--ink);
  font-weight: 600;
}

/* ---------- Section headings ---------- */

.section-heading {
  display: flex;
  align-items: baseline;
  gap: 17px;
  margin-bottom: 34px;
}

.section-number {
  font-family: Georgia, serif;
  font-size: 1rem;
  color: var(--accent);
}

.section-heading h2 {
  margin: 0;
  font-size: 0.95rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  color: #444;
}

/* ---------- Education ---------- */

.education {
  margin-bottom: 82px;
}

.degree {
  position: relative;
  display: grid;
  grid-template-columns: 1fr;
  padding: 30px 34px 32px 36px;
  margin-bottom: 16px;
  background: var(--light);
  border-left: 4px solid var(--accent);
  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.degree:hover {
  transform: translateX(5px);
  box-shadow: 0 9px 28px rgba(0,0,0,0.06);
}

.degree h3 {
  margin: 0 0 9px;
  font-size: 1.25rem;
  font-weight: 400;
  line-height: 1.5;
  color: var(--ink);
}

.meta {
  font-size: 0.98rem;
  line-height: 1.65;
  color: #666;
  margin-bottom: 2px;
}

.meta strong {
  color: #444;
  font-weight: 600;
}

.keywords {
  margin-top: 9px;
  font-size: 0.96rem;
  line-height: 1.6;
  font-style: italic;
  color: #777;
}

/* ---------- Interests ---------- */

.interests {
  margin-bottom: 40px;
}

.interests-title {
  font-size: 0.95rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  color: #444;
  margin-bottom: 22px;
}

.interest-list {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.interest-tag {
  display: inline-block;
  padding: 8px 15px;
  font-size: 0.9rem;
  color: #555;
  background: #f5f7f8;
  border: 1px solid #dfe4e7;
  border-radius: 3px;
  transition:
    background 0.18s ease,
    color 0.18s ease,
    border-color 0.18s ease,
    transform 0.18s ease;
}

.interest-tag:hover {
  background: var(--accent);
  border-color: var(--accent);
  color: white;
  transform: translateY(-1px);
}

/* ---------- Mobile ---------- */

@media (max-width: 600px) {

  .about-header {
    padding-bottom: 45px;
  }

  .about-header h1 {
    font-size: 2.1rem;
  }

  .biography p {
    font-size: 1.04rem;
    line-height: 1.75;
  }

  .degree {
    padding: 25px 25px 27px 27px;
  }

  .degree h3 {
    font-size: 1.1rem;
  }

  .meta,
  .keywords {
    font-size: 0.9rem;
  }
}
</style>


<div class="about-page">

  <!-- HEADER -->

  <div class="about-header">
    <div class="about-eyebrow">About · Background · Interests</div>
    <h1>About Me</h1>
  </div>


  <!-- BIOGRAPHY -->

  <section class="biography">

    <p>
      I am a Mathematics Ph.D. candidate at <strong>Purdue University</strong>
      specializing in partial differential equations (PDEs) and inverse wave
      scattering. My research focuses on developing rigorous mathematical
      frameworks and computational sampling methods to reconstruct hidden
      geometries from elastic and flexural wave data.
    </p>

    <p>
      Prior to Purdue, I earned my M.S. in Applied Mathematics from NJIT,
      focusing on underwater acoustics and finite element methods. Outside
      of core technical research, I also founded the
      <strong>Math History Seminar</strong> at Purdue.
    </p>

  </section>


  <!-- EDUCATION -->

  <section class="education">

    <div class="section-heading">
      <span class="section-number">01</span>
      <h2>Education &amp; Research</h2>
    </div>


    <div class="degree">

      <h3>
        Ph.D. Mathematics — Purdue University
      </h3>

      <div class="meta">
        <strong>Advisors:</strong>
        Peijun Li &amp; Isaac Harris
        · 2021–Present
      </div>

      <div class="meta">
        Founder, Math History Seminar
      </div>

      <div class="keywords">
        Research: PDEs · Inverse Scattering · Wave Propagation
      </div>

    </div>


    <div class="degree">

      <h3>
        M.S. Applied Mathematics — NJIT
      </h3>

      <div class="meta">
        <strong>Advisor:</strong>
        Christina Frederick
        · 2019–2021
      </div>

      <div class="keywords">
        Research: Underwater Acoustics · FEM · Domain Decomposition
      </div>

    </div>


    <div class="degree">

      <h3>
        B.A. Mathematics — Rutgers University
      </h3>

      <div class="meta">
        Minor in Philosophy
      </div>

      <div class="keywords">
        Focus: Mathematical Logic · Modern &amp; Continental Philosophy
      </div>

    </div>

  </section>


  <!-- INTERESTS -->

  <section class="interests">

    <div class="section-heading">
      <span class="section-number">02</span>
      <h2>Interests &amp; Pursuits</h2>
    </div>

    <div class="interest-list">
      <span class="interest-tag">Writing</span>
      <span class="interest-tag">Poetry</span>
      <span class="interest-tag">Jogging</span>
      <span class="interest-tag">History &amp; Philosophy of Science</span>
    </div>

  </section>

</div>




