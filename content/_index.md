---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: true
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a research assistant in Institute for Artificial Intelligence, Peking University. My current work involves multi-agent reinforcement learning and AI safety project management.

        I’m interested in the practical application of advanced ML models in intelligent monitoring systems that help reduce human intervention and improve operational efficiency.
        
        Please reach out to collaborate 😃
    design:
      columns: '0'

---
