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
    id: skills
    content:
      text: |
        <div class="custom-buttons-container">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSebXAd24FmFQMkuKa-fyjRTdjL-TAO5jmKyusAQ5xukQo7i7A/viewform?pli=1" class="custom-inquiry-button">
            <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
            </svg>
            강의, 연수, 컨설팅 문의
          </a>
          <a href="https://blog.naver.com/ehk516" class="custom-view-work-button">
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
          <a href="https://www.instagram.com/eunhyokyung/" class="custom-view-work-button" target="_blank" rel="noopener noreferrer">
            <svg fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
            </svg>
            [인스타그램] 교육 현장 기록
          </a>
          </a>
          <a href="https://www.youtube.com/@%EB%AF%B8%EB%94%94%EC%96%B4%EA%B5%90%EC%9C%A1-114?sub_confirmation=1" class="custom-view-work-button" target="_blank" rel="noopener noreferrer">
            <svg fill="currentColor" viewBox="0 0 24 24">
              <path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/>
            </svg>
            [유튜브] 교육 콘텐츠 • 미디어교육
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
  
  # Contact Section with YouTube Video
  - block: markdown
    id: contact-wrapper
    content:
      text: |
        <div class="contact-section-wrapper">
          <div class="contact-video">
            <a href="https://www.youtube.com/watch?v=c1UFt-Hkaow&t=5126s" target="_blank" rel="noopener noreferrer" class="youtube-thumbnail-link">
              <div class="youtube-thumbnail">
                <img src="/media/authors/youtube_tn.png" alt="2020 병영독서활성화 지원사업 온라인 워크숍" class="youtube-thumbnail-image">
                <div class="youtube-play-button">
                  <svg viewBox="0 0 68 48" width="68" height="48">
                    <path d="M66.52,7.74c-0.78-2.93-2.49-5.41-5.42-6.19C55.79,.13,34,0,34,0S12.21,.13,6.9,1.55 C3.97,2.33,2.27,4.81,1.48,7.74C0.06,13.05,0,24,0,24s0.06,10.95,1.48,16.26c0.78,2.93,2.49,5.41,5.42,6.19 C12.21,47.87,34,48,34,48s21.79-0.13,27.1-1.55c2.93-0.78,4.64-3.26,5.42-6.19C67.94,34.95,68,24,68,24S67.94,13.05,66.52,7.74z" fill="#f00"></path>
                    <path d="M 45,24 27,14 27,34" fill="#fff"></path>
                  </svg>
                </div>
              </div>
            </a>
            <p class="youtube-caption">[강의 샘플] 시범강의(병영독서)</p>
          </div>
          <div class="contact-content">
            <div class="contact-info-content">
              <h2>강의·연수·컨설팅 문의</h2>
              <p>공교육·기업·공공기관 대상<br>
              미디어·AI 리터러시 교육 강의·연수·컨설팅 문의, 언제나 환영합니다!</p>
              <div class="contact-email">
                <strong>이메일:</strong>
                <a href="mailto:ehk516@hanmail.net">ehk516@hanmail.net</a>
              </div>
              <a href="mailto:ehk516@hanmail.net" class="contact-button">
                <svg fill="none" stroke="currentColor" viewBox="0 0 24 24" style="width: 1.25rem; height: 1.25rem;">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"></path>
                </svg>
                이메일 보내기
              </a>
            </div>
          </div>
        </div>
    design:
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "2rem", "4rem", "2rem"]
  
  # CTA Card
  # - block: cta-card
  #   content:
  #     title: "Open to Opportunities"
  #     text: |-
  #       I'm currently looking for **senior engineering** or **tech lead** roles.
        
  #       Let's connect and discuss how I can help your team.
  #     button:
  #       text: 'Download Resume'
  #       url: uploads/resume.pdf
  #       new_tab: true
  #   design:
  #     card:
  #       # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
  #       css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
  #       text_color: dark
  #     background:
  #       color:
  #         light: "#f5f5f5"
  #         dark: "#08080c"
  #     spacing:
  #       padding: ["4rem", "0", "6rem", "0"]
---
