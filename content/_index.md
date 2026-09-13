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
---
