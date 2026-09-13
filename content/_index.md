---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/yachen-miao-cv.pdf
      headings:
        about: About
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: small # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: education
    content:
      title: Education
      text: |-
        <div class="theo-education">
          <strong>University of Liverpool</strong>
          <span>BSc Applied Mathematics, 2023-2027</span>
          <p>Year 2 Average: 93/100 | Ranked 1st | Willis Prize</p>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: research
    content:
      title: Research / Current Work
      text: |-
        <div class="theo-feature">
          <div>
            <p class="theo-eyebrow">Current focus</p>
            <h3>Distortion Risk Measures & Stochastic Dominance</h3>
            <p>Studying quantile representations, endpoint conditions, and extensions towards fractional stochastic dominance.</p>
          </div>
          <a class="theo-link" href="/research/current-work/">Read more</a>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: projects
    content:
      title: Selected Projects
      text: |-
        <div class="theo-grid">
          <article class="theo-card">
            <h3>Finite-Memory Sequence Models</h3>
            <p>Studying sequence models with finite memory, with attention to model complexity, generalisation, and reliable evaluation.</p>
            <div class="theo-tags"><span>Sequence Models</span><span>Learning Theory</span><span>Generalisation</span></div>
          </article>
          <article class="theo-card">
            <h3>FactorLab / Quant Research</h3>
            <p>Building and testing factor research workflows for quantitative finance, including signal validation and multiple testing concerns.</p>
            <div class="theo-tags"><span>Python</span><span>Factor Research</span><span>Quant Finance</span></div>
          </article>
          <article class="theo-card">
            <h3>Density Estimation with Masked Autoregressive Flows</h3>
            <p>Exploring flexible density estimation with normalising flows and autoregressive structure for high-dimensional modelling.</p>
            <div class="theo-tags"><span>Density Estimation</span><span>Normalising Flows</span><span>ML</span></div>
          </article>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: experience
    content:
      title: Experience
      text: |-
        <div class="theo-list">
          <div class="theo-list-item">
            <strong>Tianyidao Investment Management</strong>
            <span>Quant Research Intern</span>
            <p>Quantitative research work involving statistical modelling, factor analysis, and empirical validation.</p>
          </div>
          <div class="theo-list-item">
            <strong>University of Liverpool</strong>
            <span>Research Work</span>
            <p>Work on distortion risk measures, stochastic dominance, quantile representations, and endpoint conditions.</p>
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: awards
    content:
      title: Awards
      text: |-
        <div class="theo-grid theo-grid-compact">
          <div class="theo-card"><h3>Willis Prize in Mathematics</h3><p>University of Liverpool</p></div>
          <div class="theo-card"><h3>XJTLU Excellence Scholarship</h3><p>XJTLU</p></div>
          <div class="theo-card"><h3>Academic Merit Scholarship</h3><p>University of Liverpool</p></div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: interests
    content:
      title: Research Interests
      text: |-
        <div class="theo-notes">
          <span>Statistical Machine Learning</span>
          <span>Generalisation & Learning Theory</span>
          <span>Stochastic Processes</span>
          <span>Quantitative Finance</span>
          <span>Risk & Stochastic Dominance</span>
        </div>
    design:
      columns: '1'
---
