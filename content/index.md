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
        - title: 협업 문의 환영합니다!
          content: '문의 주시면 일정 맞춰 빠르게 연락드리겠습니다!'
          align: left
          background:
            image:
              filename: web.jpg
              filters: { brightness: 0.7 }
            position: center
            color: '#555'
        - title: Build. Measure. Improve
          content: '데이터를 바탕으로 서비스를 지속적으로 개선합니다.'
          align: right
          background:
            image:
              filename: trip.jpg
              filters: { brightness: 0.5 }
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/
    design:
      is_fullscreen: False
      loop: true
      interval: 5000
      slide_height: '380px'
---