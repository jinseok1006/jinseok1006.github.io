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
      - title: 👋 Hello!
        content: Welcome to Jinseok Kim's Portfolio Page!
        align: justify
        background:
          image:
            filename: working.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'

      - title: Cloud Infrastructure
        content:  I want to deepen my knowledge in cloud infrastructure to build efficient and scalable systems.
        align: justify
        background:
          image:
            filename: datacenter.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'

      - title: Virtualization & Container
        content: I aim to realize efficient resource management and deployment automation through virtualization and container technologies.
        align: justify
        background:
          image:
            filename: linux.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: Web Development
        content:  I aspire to develop innovative web solutions that provide the best user experience by utilizing the latest technologies in web development.
        align: justify 
        background:
          image:
            filename: coding.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: DevOps and Automation
        content: I aim to maximize the efficiency of software development and operations processes by leveraging DevOps tools and automation pipelines.
        align: justify
        background:
          image:
            filename: devops.jpg
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
      title: <span style="font-size:75%">Interest</span>
      text: I am primarily interested in and studying the following IT fields.<br><br><br>
      items:
        - name: Virtualization
          icon: server
          icon_pack: fas
          description: Efficient resource management in server virtualization and cloud environments
        - name: Containers
          icon: docker
          icon_pack: fab
          description: Simplifying containerization and deployment using Docker
        - name: Cloud Infrastructure
          icon: cloud
          icon_pack: fas
          description: Managing infrastructure and deploying services using cloud platforms like AWS and OpenStack
        - name: Web Development
          icon: globe
          icon_pack: fas
          description: Developing structured web pages using a component-based approach with React
        - name: CI/CD
          icon: rotate
          icon_pack: fas
          description: Continuous integration and deployment connected with Docker
        - name: Networking
          icon: network-wired
          icon_pack: fas
          description: Various networking knowledge used in cloud environments


  
  - block: collection
    content:
      title: Projects
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - post
      offset: 0
      order: desc
      page_type: post
    design:
      view: community/card
      columns: '2'

  - block: accomplishments
    content:
      title: Accomplishments
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: SQL Developer Certification
          certificate_url: 
          date_end: ''
          date_start: '2024-09-20'
          description: I passed the SQL Developer certification exam, demonstrating my abilities in database management and SQL queries.
          icon: kdata
          organization: Korea Data Industry Agency
          organization_url: https://www.dataq.or.kr
          url: ''

        - title: 2nd Place, Computer AI Department Hacking Contest
          certificate_url: 
          date_end: ''
          date_start: '2023-12-21'
          description: I learned and applied techniques such as web hacking, reverse engineering with OllyDbg, and steganography in a CTF-based competition.
          icon: univ
          organization: Chonbuk National University Computer AI Department
          organization_url: https://csai.jbnu.ac.kr
          url: ''

        - title: 1st Place, IT Intelligent Information Engineering Programming Contest (Freshman Division)
          certificate_url: 
          date_end: ''
          date_start: '2022-09-29'
          description: I secured first place in a programming contest, showcasing my problem-solving and algorithm design skills.
          icon: univ
          organization: Chonbuk National University IT Intelligent Information Engineering Department
          organization_url: https://it.jbnu.ac.kr
          url: ''

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
