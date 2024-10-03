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
          description: 가상화 및 클라우드 환경에 대해서 공부하고 있습니다. 주로 OpenStack 환경에 대해서 다룹니다.

        - title: Computer Science Student
          company: Chonbuk National University
          company_url: ''
          company_logo: univ
          location: Jeonju, South Korea
          date_start: '2022-03-01'
          date_end: ''
          description: 현재 컴퓨터공학과에 재학 중이며, 소프트웨어 개발과 연구에 집중하고 있습니다.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---