---
layout: page
permalink: /research/
author_profile: true
classes: wide
title: ""
---

<style>
/* =========================================================
   RESEARCH PAGE
   ========================================================= */

.research-page {
  --accent: #007BA7;
  --accent-dark: #005f82;
  --ink: #222;
  --muted: #777;
  --light: #f5f7f8;
  --line: #dfe4e7;

  max-width: 980px;
  margin: 0 auto;
}

/* ---------- Intro ---------- */

.research-header {
  position: relative;
  padding: 10px 0 48px;
  margin-bottom: 42px;
  border-bottom: 1px solid var(--line);
}

.research-header::after {
  content: "";
  display: block;
  width: 70px;
  height: 3px;
  background: var(--accent);
  margin-top: 24px;
}

.research-eyebrow {
  font-size: 0.72rem;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  color: var(--accent);
  margin-bottom: 12px;
}

.research-header h1 {
  margin: 0;
  font-size: 2.15rem;
  font-weight: 400;
  letter-spacing: -0.02em;
}

.research-header p {
  max-width: 650px;
  margin: 14px 0 0;
  color: var(--muted);
  font-size: 0.95rem;
  line-height: 1.7;
}

/* ---------- Sections ---------- */

.research-section {
  margin-bottom: 72px;
}

.section-heading {
  display: flex;
  align-items: baseline;
  gap: 14px;
  margin-bottom: 30px;
}

.section-number {
  font-family: Georgia, serif;
  font-size: 0.82rem;
  color: var(--accent);
}

.section-heading h2 {
  margin: 0;
  font-size: 0.82rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  color: #444;
}

/* ---------- Publications ---------- */

.publication {
  position: relative;
  display: grid;
  grid-template-columns: 70px 1fr;
  gap: 20px;
  padding: 27px 0 31px;
  border-top: 1px solid var(--line);
}

.publication:last-child {
  border-bottom: 1px solid var(--line);
}

.pub-number {
  font-family: Georgia, serif;
  font-size: 2.15rem;
  color: #d5dadd;
  line-height: 1;
  transition: color 0.2s ease;
}

.publication:hover .pub-number {
  color: var(--accent);
}

.pub-content {
  min-width: 0;
}

.pub-title {
  font-size: 1.08rem;
  line-height: 1.5;
  font-weight: 400;
  margin-bottom: 8px;
  color: var(--ink);
}

.pub-authors {
  font-size: 0.88rem;
  color: #666;
  line-height: 1.6;
}

.pub-authors a {
  color: var(--accent);
  text-decoration: none;
}

.pub-authors a:hover {
  text-decoration: underline;
}

.pub-meta {
  margin-top: 7px;
  font-size: 0.84rem;
  color: var(--muted);
}

.pub-links {
  display: flex;
  gap: 7px;
  margin-top: 13px;
  flex-wrap: wrap;
}

.pub-links a {
  display: inline-block;
  padding: 4px 10px;
  border: 1px solid #ccd5d9;
  border-radius: 3px;
  color: #666;
  text-decoration: none;
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  transition:
    background 0.18s ease,
    color 0.18s ease,
    border-color 0.18s ease,
    transform 0.18s ease;
}

.pub-links a:hover {
  background: var(--accent);
  border-color: var(--accent);
  color: white;
  transform: translateY(-1px);
}

/* ---------- Expository Notes ---------- */

.note-card {
  position: relative;
  padding: 28px 30px;
  background: var(--light);
  border-left: 3px solid var(--accent);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.note-card:hover {
  transform: translateX(4px);
  box-shadow: 0 7px 24px rgba(0,0,0,0.06);
}

.note-title {
  font-size: 1.08rem;
  font-weight: 400;
  margin-bottom: 7px;
}

.note-author {
  font-size: 0.86rem;
  color: var(--muted);
}

.note-links {
  margin-top: 16px;
}

.note-links a {
  color: var(--accent);
  font-size: 0.74rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  text-decoration: none;
  margin-right: 18px;
}

.note-links a::after {
  content: " ↗";
  font-size: 0.8em;
}

.note-links a:hover {
  text-decoration: underline;
}

/* ---------- Talks ---------- */

.talk-list {
  position: relative;
  margin-left: 10px;
  padding-left: 30px;
  border-left: 1px solid #ccd5d9;
}

.talk {
  position: relative;
  padding: 0 0 30px;
}

.talk:last-child {
  padding-bottom: 0;
}

.talk::before {
  content: "";
  position: absolute;
  left: -35px;
  top: 5px;
  width: 9px;
  height: 9px;
  border: 2px solid var(--accent);
  background: white;
  border-radius: 50%;
  transition: background 0.2s ease;
}

.talk:hover::before {
  background: var(--accent);
}

.talk-date {
  font-size: 0.69rem;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: var(--accent);
  margin-bottom: 5px;
}

.talk-title {
  font-size: 1rem;
  line-height: 1.45;
  color: var(--ink);
}

.talk-location {
  display: inline-block;
  margin-top: 3px;
  font-size: 0.82rem;
  color: var(--muted);
}

.talk-detail {
  margin-top: 5px;
  font-size: 0.82rem;
  color: #777;
  line-height: 1.55;
}

.talk-slides {
  display: inline-block;
  margin-top: 8px;
  color: var(--accent);
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  text-decoration: none;
}

.talk-slides:hover {
  text-decoration: underline;
}

/* ---------- Mobile ---------- */

@media (max-width: 600px) {

  .research-header h1 {
    font-size: 1.75rem;
  }

  .publication {
    grid-template-columns: 42px 1fr;
    gap: 12px;
  }

  .pub-number {
    font-size: 1.6rem;
  }

  .pub-title {
    font-size: 1rem;
  }

  .note-card {
    padding: 22px;
  }

  .talk-list {
    margin-left: 5px;
    padding-left: 24px;
  }

  .talk::before {
    left: -29px;
  }
}
</style>


<div class="research-page">

  <!-- HEADER -->

  <div class="research-header">
    <div class="research-eyebrow">Research · Publications · Talks</div>
    <h1>Research &amp; Scholarship</h1>
    <p>
      Research in inverse problems, inverse scattering, and computational
      methods for partial differential equations.
    </p>
  </div>


  <!-- PUBLICATIONS -->

  <section class="research-section">

    <div class="section-heading">
      <span class="section-number">01</span>
      <h2>Publications &amp; Preprints</h2>
    </div>


    <div class="publication">

      <div class="pub-number">01</div>

      <div class="pub-content">

        <div class="pub-title">
          Novel implementation of the extended sampling method for inverse biharmonic scattering
        </div>

        <div class="pub-authors">
          <a href="https://sites.google.com/site/isaacpurduemath/home">I. Harris</a>
          and <span>G. Ozochiawaeze</span>
        </div>

        <div class="pub-meta">
          Preprint · 2026
        </div>

        <div class="pub-links">
          <a href="https://arxiv.org/abs/2605.12367">arXiv</a>
        </div>

      </div>
    </div>


    <div class="publication">

      <div class="pub-number">02</div>

      <div class="pub-content">

        <div class="pub-title">
          Factorization method for the biharmonic scattering problem for an absorbing penetrable scatterer
        </div>

        <div class="pub-authors">
          <a href="https://rafaelcejaayala.com">R. Ceja Ayala</a>,
          <a href="https://sites.google.com/site/isaacpurduemath/home">I. Harris</a>,
          and <span>G. Ozochiawaeze</span>
        </div>

        <div class="pub-meta">
          <em>Communications on Analysis and Computation</em>,
          Volume 9 (2026), pp. 16–39
        </div>

        <div class="pub-links">
          <a href="https://www.aimsciences.org/article/doi/10.3934/cac.2026010">DOI</a>
          <a href="https://arxiv.org/abs/2511.05711">arXiv</a>
        </div>

      </div>
    </div>


    <div class="publication">

      <div class="pub-number">03</div>

      <div class="pub-content">

        <div class="pub-title">
          Sampling methods for the inverse cavity scattering problem of biharmonic waves
        </div>

        <div class="pub-authors">
          <a href="https://sites.google.com/site/isaacpurduemath/home">I. Harris</a>,
          <a href="https://www.math.purdue.edu/~lipeijun/">P. Li</a>,
          and <span>G. Ozochiawaeze</span>
        </div>

        <div class="pub-meta">
          <em>Inverse Problems</em>,
          Volume 42 (2026), Article 015002
        </div>

        <div class="pub-links">
          <a href="https://iopscience.iop.org/article/10.1088/1361-6420/ae2ef8">DOI</a>
          <a href="https://arxiv.org/abs/2509.02773">arXiv</a>
        </div>

      </div>
    </div>

  </section>


  <!-- NOTES -->

  <section class="research-section">

    <div class="section-heading">
      <span class="section-number">02</span>
      <h2>Expository Notes</h2>
    </div>

    <div class="note-card">

      <div class="note-title">
        Direct Imaging Methods for Inverse Obstacle Scattering
      </div>

      <div class="note-author">
        G. Ozochiawaeze
      </div>

      <div class="note-links">
        <a href="/files/Direct_Imaging_Methods.pdf">PDF</a>
        <a href="https://arxiv.org/abs/2311.16962">arXiv</a>
      </div>

    </div>

  </section>


  <!-- TALKS -->

  <section class="research-section">

    <div class="section-heading">
      <span class="section-number">03</span>
      <h2>Selected Invited Talks</h2>
    </div>

    <div class="talk-list">


      <div class="talk">
        <div class="talk-date">June 2026</div>
        <div class="talk-title">
          WAVES Conference
        </div>
        <div class="talk-location">
          Montreal, Canada
        </div>
        <div class="talk-detail">
          Minisymposium:
          <em>Inverse Problems in Wave Scattering: Theory and Computation</em>
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Feb 2026</div>
        <div class="talk-title">
          Baby Inverse Problems (BIP) Seminar
        </div>
        <div class="talk-location">
          Online
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Nov 2025</div>
        <div class="talk-title">
          SIAM Conference on Analysis of PDEs (PD25)
        </div>
        <div class="talk-location">
          Pittsburgh, PA
        </div>
        <div class="talk-detail">
          Minisymposium MS47:
          <em>Inverse Problems for PDEs: Inverse Scattering and Non-scattering</em>
        </div>
        <a class="talk-slides" href="/files/FM_Present.pdf">
          View slides
        </a>
      </div>


      <div class="talk">
        <div class="talk-date">Nov 2025</div>
        <div class="talk-title">
          Purdue Graduate Research Day
        </div>
        <div class="talk-location">
          West Lafayette, IN
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Nov 2025</div>
        <div class="talk-title">
          Purdue CCAM Lunch Seminar
        </div>
        <div class="talk-location">
          West Lafayette, IN
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Feb 2025</div>
        <div class="talk-title">
          Purdue CCAM Lunch Seminar
        </div>
        <div class="talk-location">
          West Lafayette, IN
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Nov 2024</div>
        <div class="talk-title">
          Purdue Graduate Research Day
        </div>
        <div class="talk-location">
          West Lafayette, IN
        </div>
      </div>


      <div class="talk">
        <div class="talk-date">Apr 2024</div>
        <div class="talk-title">
          Purdue SIAM Student Chapter Conference
        </div>
        <div class="talk-location">
          West Lafayette, IN
        </div>
      </div>


    </div>

  </section>

</div>
:::










