---
title: Positions
type: landing

banner:
  caption: ''
  image: 'skill.jpg'

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: skill.jpg
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: 'custom-height'
  - block: experience
    content:
      title: Positions
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern
          company: Operating Systems Research Lab
          company_url: ''
          company_logo: univ
          location: Jeonju, South Korea
          date_start: '2024-03-02'
          date_end: ''
          description: Conducting research in operating systems, contributing to projects on performance optimization and system architecture.

        - title: Computer Science Student
          company: Chonbuk National University
          company_url: ''
          company_logo: univ
          location: Jeonju, South Korea
          date_start: '2022-03-01'
          date_end: ''
          description: Currently enrolled in the Computer Science Department, focusing on software development and research.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---