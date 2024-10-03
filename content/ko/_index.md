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
        - title: SQL Developer 자격증
          certificate_url: 
          date_end: ''
          date_start: '2024-09-20'
          description: 데이터베이스 관리 및 SQL 쿼리에 대한 능력을 입증하는 SQL 개발자 자격증 시험에 합격했습니다.
          icon: kdata
          organization: 한국데이터산업진흥원
          organization_url: https://www.dataq.or.kr
          url: ''

        - title: 2위, 컴퓨터인공지능학부 Hakcing Contest
          certificate_url: 
          date_end: ''
          date_start: '2023-12-21'
          description: CTF 기반의 대회에서 웹 해킹, OllyDbg를 활용한 역공학, 스테가노그래피 등의 기법등을 학습하고 활용했습니다.
          icon: univ
          organization: 전북대학교 컴퓨터인공지능학부
          organization_url: https://csai.jbnu.ac.kr
          url: ''

        - title: 1위, IT지능정보공학과 프로그래밍 경진대회 (1학년 부문)
          certificate_url: 
          date_end: ''
          date_start: '2022-09-29'
          description: 프로그래밍 경진대회에서 1위를 차지하여 문제 해결 및 알고리즘 설계 능력을 선보였습니다.
          icon: univ
          organization: 전북대학교 IT지능정보공학과
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
