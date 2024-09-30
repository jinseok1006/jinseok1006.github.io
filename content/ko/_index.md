---
# Leave the homepage title empty to use the site title
title:
date: 
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your profile text from `authors/admin/_index.md`?
      # text: |-
      #   👋 Hi, there! I'm **Alice**, a machine learning researcher at Netflix.
      #   {style="font-size: 1.2rem; color: #FFB76B;"}
      button:
        text: Download CV
        url: uploads/resume.pdf
  # - block: hero
  #   content:
  #     title: |
  #       Wowchemy
  #       Research Group
  #     image:
  #       filename: welcome.jpg
  #     text: |-
  #       <br>
  #       The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.

  - block: slider
    content:
      slides:
      - title: 👋 안녕하세요!
        content: 김진석의 포트폴리오 페이지입니다!
        align: center
        background:
          image:
            filename: working.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'

      - title: 클라우드 인프라
        content: 클라우드 인프라에 대해 학습하고 있습니다.
        align: left
        background:
          image:
            filename: datacenter.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'

      - title: 가상화 및 컨테이너
        content: 가상화와 컨테이너 기술에 대해 학습하고 있습니다.
        align: left
        background:
          image:
            filename: linux.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: 웹 개발
        content: React를 활용한 컴포넌트식 개발에 대해 학습하고 있습니다.
        align: left 
        background:
          image:
            filename: coding.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: features
    content:
      title: <span style="font-size:75%">관심분야</span>
      text: 저는 주로 다음과 같은 IT 분야에 관심을 가지고 공부하고 있습니다.<br><br><br>
      items:
        - name: 가상화
          icon: server
          icon_pack: fas
          description: 서버 가상화와 클라우드 환경에서의 효율적인 자원 관리
        - name: 컨테이너
          icon: docker
          icon_pack: fab
          description:  도커를 활용한 컨테이너 및 배포 간소화
        - name: 클라우드 인프라
          icon: cloud
          icon_pack: fas
          description:  AWS, Openstack 등의 클라우드 플랫폼을 사용한 인프라 관리 및 서비스 배포
        - name: 웹 개발
          icon: globe
          icon_pack: fas
          description: React를 이용한 컴포넌트 방식의 구조화된 웹페이지 작성
        - name: CI/CD
          icon: rotate
          icon_pack: fas
          description:  도커와 연계되는 지속적 통합 및 배포
        - name: 네트워크
          icon: network-wired
          icon_pack: fas
          description:  클라우드 환경에서 사용되는 다양한 네트워크 지식

  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: community/card
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: My subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
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

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: community/card
  #     columns: '2'


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact" cta_text="Contact me" %}}
    design:
      columns: '1'
---
