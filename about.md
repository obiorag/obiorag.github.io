---
layout: page
title: ""
permalink: /about/
author_profile: true
classes: wide
---

<style>
.about-grid {
  display: grid;
  gap: 1.5rem;
  max-width: 900px;
  margin: auto;
}

.degree {
  position: relative;
  padding: 1.2rem 1.5rem;
  border-radius: 12px;
  background: linear-gradient(
    135deg,
    rgba(255,255,255,0.65),
    rgba(245,245,245,0.85)
  );
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  backdrop-filter: blur(6px);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.degree::before {
  content: "";
  position: absolute;
  left: 0;
  top: 12%;
  height: 76%;
  width: 4px;
  background: linear-gradient(to bottom, #444, #aaa);
  border-radius: 2px;
}

.degree:hover {
  transform: translateY(-4px);
  box-shadow: 0 18px 40px rgba(0,0,0,0.12);
}

.degree h3 {
  margin: 0 0 0.3rem 0;
  font-weight: 600;
  letter-spacing: 0.03em;
}

.meta {
  font-size: 0.85rem;
  opacity: 0.7;
}

.keywords {
  margin-top: 0.3rem;
  font-size: 0.9rem;
  font-style: italic;
  opacity: 0.85;
}

.interests {
  margin-top: 2.5rem;
  text-align: center;
  font-size: 0.9rem;
  letter-spacing: 0.15em;
  opacity: 0.7;
}
</style>


<div class="about-grid">

<div class="degree">
<h3>Ph.D. Mathematics — Purdue</h3>
<div class="meta">Peijun Li · Isaac Harris · 2021–Present</div>
<div class="keywords">PDEs · Inverse Scattering · Wave Propagation</div>
<div class="meta">Founder, Math History Seminar</div>
</div>

<div class="degree">
<h3>M.S. Applied Mathematics — NJIT</h3>
<div class="meta">Christina Frederick</div>
<div class="keywords">Underwater Acoustics · FEM · Domain Decomposition</div>
</div>

<div class="degree">
<h3>B.A. Mathematics, Minor in Philosophy — Rutgers</h3>
<div class="keywords">Logic · Modern & Continental Philosophy</div>
</div>

</div>

<div class="interests">
Writing · Poetry · Jogging · History & Philosophy of Science
</div>




