---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

design:
  # Default section spacing
  spacing: '0'

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "교육자"
      show_status: true
      show_scroll_indicator: false
      typewriter:
        enable: true
        prefix: ""
        strings:
          - "Media"
          - "AI Literacy"
        type_speed: 100
        delete_speed: 80
        pause_time: 3000
      cta_buttons: []
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  
  # Custom Buttons Section
  - block: markdown
    id: custom-buttons
    content:
      text: |
        <div class="custom-buttons-container">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSebXAd24FmFQMkuKa-fyjRTdjL-TAO5jmKyusAQ5xukQo7i7A/viewform?pli=1" class="custom-inquiry-button">
            <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
            </svg>
            강의, 연수, 컨설팅 문의
          </a>
          <a href="#projects" class="custom-view-work-button">
            <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
            </svg>
            [블로그] 교육·강의 소개 (공교육·기업·공공기관)
          </a>
          <a href="https://search.naver.com/search.naver?where=nexearch&sm=top_hty&fbm=1&ie=utf8&query=%EC%9D%80%ED%9A%A8%EA%B2%BD" class="custom-view-work-button" target="_blank" rel="noopener noreferrer">
            <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"></path>
            </svg>
            [네이버] 교육자 공식 프로필
          </a>
        </div>
    design:
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["0", "0", "2rem", "0"]
  
  # Filterable Portfolio - Alpine.js powered project filtering
  - block: portfolio
    id: projects
    content:
      title: "대표 도서"
      subtitle: "은효경의 대표 도서 4선"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: 미디어
          tag: 미디어
        - name: 리터러시
          tag: 리터러시
        - name: 동화
          tag: 동화
      default_button_index: 0
      # Archive link auto-shown if more projects exist than 'count' above
      # archive:
      #   enable: false  # Set to false to explicitly hide
      #   text: "Browse All"  # Customize text
      #   link: "/work/"  # Custom URL
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: 경력사항
      date_format: 2006년 1월
      items:
        - title: 미디어 강사
          company: 경기도교육청 미디어교육센터
          company_url: ''
          company_logo: ''
          location: 경기도
          date_start: '2024-04-01'
          date_end: ''
          description: |2-
            * 미디어 리터러시 교육 강의 및 연수 진행
        - title: 통일교육위원
          company: 통일부
          company_url: ''
          company_logo: ''
          location: 서울
          date_start: '2022-05-01'
          date_end: ''
          description: |2-
            * 통일교육 정책 자문 및 교육 프로그램 개발
        - title: 도서선정위원회 위원
          company: 한국도서관협회 병영독서활성화 지원 사업
          company_url: ''
          company_logo: ''
          location: 서울
          date_start: '2022-05-01'
          date_end: '2022-05-31'
          description: |2-
            * 병영독서활성화를 위한 도서 선정 업무
        - title: 기자
          company: 소년한국일보
          company_url: ''
          company_logo: ''
          location: 서울
          date_start: '2018-03-01'
          date_end: '2019-12-31'
          description: |2-
            * 청소년 미디어 관련 기사 취재 및 작성
        - title: 자문위원
          company: 대통령직속 민주평화통일자문회의
          company_url: ''
          company_logo: ''
          location: 서울
          date_start: '2019-09-01'
          date_end: '2019-09-30'
          description: |2-
            * 통일 정책 자문 활동
        - title: 미디어강사
          company: 한국언론진흥재단
          company_url: ''
          company_logo: ''
          location: 서울
          date_start: '2007-01-01'
          date_end: ''
          description: |2-
            * 미디어 리터러시 교육 강의 및 연수 진행
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Recent Blog Posts
  # - block: collection
  #   id: blog
  #   content:
  #     title: Recent Posts
  #     subtitle: 'Thoughts on web development, tech, and more'
  #     text: ''
  #     filters:
  #       folders:
  #         - blog
  #       exclude_featured: false
  #     count: 3
  #     order: desc
  #   design:
  #     view: card
  #     columns: 3
  #     background:
  #       color:
  #         light: "#f5f5f5"
  #         dark: "#08080c"
  #     spacing:
  #       padding: ["4rem", "0", "4rem", "0"]
  
  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something amazing together"
      text: |-
        I'm always interested in hearing about new projects and opportunities.
        Whether you're looking to hire, collaborate, or just want to say hi, feel free to reach out!
      email: alex@example.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # CTA Card
  - block: cta-card
    content:
      title: "Open to Opportunities"
      text: |-
        I'm currently looking for **senior engineering** or **tech lead** roles.
        
        Let's connect and discuss how I can help your team.
      button:
        text: 'Download Resume'
        url: uploads/resume.pdf
        new_tab: true
    design:
      card:
        # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
