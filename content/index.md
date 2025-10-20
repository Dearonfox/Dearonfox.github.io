---
title: My page
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              filename: computer.png
              filters: { brightness: 0.7 }
            position: right
            color: '#666'
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            image:
              filename: web.jpg
              filters: { brightness: 0.7 }
            position: center
            color: '#555'
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
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
      is_fullscreen: true
      loop: true
      interval: 5000
      
---