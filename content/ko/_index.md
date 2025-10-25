---
title: My page
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Welcome to Myblog
          content: '제 공간에 오신것을 환영합니다.'
          align: center
          background:
            image:
              filename: computer.png
              filters: { brightness: 0.7 }
            position: right
            color: '#666'
        - title: Build. Measure. Improve
          content: '데이터를 바탕으로 서비스를 지속적으로 개선합니다.'
          align: right
          background:
            image:
              filename: trip.jpg
              filters: { brightness: 0.5 }
            position: center
            color: '#333'
        - title: 협업 문의 환영합니다!
          content: |
            <p style="color:#fff !important;">
              문의 주시면 일정 맞춰 빠르게 연락드리겠습니다!
            </p>

            <a class="btn" href="/contact/" style="background:#fff;border-color:#fff;color:#111;opacity:1">연락하기</a>
          background:
            image:
              filename: web.jpg
              filters: { brightness: 0.7 }
            position: center
            color: '#555'
    design:
      is_fullscreen: false
      loop: true
      interval: 5000
      slide_height: '450px'
  - block: features
    content:
      title: My Experience
      subtitle: ""
      items:
        - icon: react
          icon_pack: fab
          name: React
          description: SPA & Hooks
        - icon: js
          icon_pack: fab
          name: JavaScript
          description: ES6+ / TypeScript
        - icon: python
          icon_pack: fab
          name: Python
          description: Data & Scripting
        - icon: code
          icon_pack: fas
          name: C++
          description: Algorithm
        - icon: database
          icon_pack: fas
          name: SQL / NoSQL
          description: Schema & Query
        - icon: "😄"
          icon_pack: emoji
          name: Positivity
          description: 100%
    design:
      columns: 4
  - block: collection
    content:
      id: news
      title: Notifications & News
      subtitle: ""
      text: ""
      count: 5         # 최대 몇 개의 글(뉴스 항목) 보여줄지
      offset: 0        # 건너뛸 개수. 0이면 최신부터
      order: desc      # 최신순
      filters:
        folders:
          - post       # 너가 쓸 폴더. 없으면 먼저 만들면 됨: content/post/...
          # 필요하면 이런 것도 가능:
          # - notification
          # - event
    design:
      view: community/custom_card
      columns: '2'
---