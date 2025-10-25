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
  - block: markdown
    id: news
    content:
      title: ""
      text: |
        <div style="
          display: grid;
          grid-template-columns: 1fr 2fr;
          gap: 2rem;
          align-items: start;
        ">

          <!-- 왼쪽 타이틀 영역 -->
          <div style="color:#fff; font-size: clamp(2rem, 1.2vw + 1.5rem, 3rem); font-weight:600; line-height:1.2;">
            <div>Notifications &</div>
            <div>News</div>
          </div>

          <!-- 오른쪽 카드 영역 -->
          <div style="
            background-color:#2f3339;
            border-radius:12px;
            padding:2rem;
            color:#fff;
            box-shadow:0 12px 24px rgba(0,0,0,0.5);
            max-width: 100%;
          ">

            <!-- 카드 상단 이미지 -->
            <img
              src="/media/hawaii.jpg"
              alt="ICCV 2025 Hawaii"
              style="
                width:100%;
                height:auto;
                border-radius:4px;
                margin-bottom:1.5rem;
                display:block;
              "
            />

            <!-- 카드 헤드라인 -->
            <h3 style="
              color:#1d4ed8;  /* 파란 강조색 */
              font-size:1.25rem;
              font-weight:700;
              line-height:1.4;
              text-transform:uppercase;
              margin:0 0 1rem 0;
            ">
              CONGRATULATIONS TO SEO-YEON CHOI (STUDENT RESEARCHER)
              ON TWO PAPERS ACCEPTED TO ICCV 2025 WORKSHOPS!
            </h3>

            <!-- 카드 본문 -->
            <p style="
              color:#d1d5db;
              font-size:1rem;
              line-height:1.6;
              margin:0;
            ">
              We are thrilled to announce that our undergraduate researcher,
              Seo-Yeon Choi (최서연), has achieved a remarkable accomplishment —
              two papers have been accepted to workshops at ICCV 2025.
            </p>

          </div><!-- /card -->

        </div><!-- /grid -->
    design:
      columns: '1'
---