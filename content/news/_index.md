---
title: "News"
type: "landing"
show_title: false
show_breadcrumb: false
backlinks: false

sections:
  # Page-only styling (just for this page)
  - block: "markdown"
    id: "news-card-style"
    content:
      title: ""
      text: |-
        <style>
          /* Scope to this page's cards only */
          #news-cards .section-title { font-size: 1.15rem; margin-bottom: .75rem; }
          #news-cards .feature-title { font-size: 1.0rem; line-height: 1.35; }
          #news-cards .feature-text { font-size: .92rem; line-height: 1.45; }
        </style>

  # Card/grid with icons (like your Academic Service section)
  - block: "features"
    id: "news-cards"
    content:
      title: "News & Milestones"
      items:
        - icon: trophy
          icon_pack: fas
          name: "Workshop Abstract Accepted — AMIA 2025 (NLP Workshop)"
          description: "Atlanta, GA • 2025-09-12"
        - icon: briefcase
          icon_pack: fas
          name: "Postdoctoral Researcher — CU Anschutz (DBMI)"
          description: "University of Colorado Anschutz Medical Campus • 2025-07-01"
        - icon: award
          icon_pack: fas
          name: "Ph.D. Completed — Computer Science"
          description: "Utah State University • 2024-12-01–12-31"
        - icon: book-open
          icon_pack: fas
          name: "Paper Accepted — ECML-PKDD 2024"
          description: "2024-08-22"
        - icon: book-open
          icon_pack: fas
          name: "Paper Accepted — PAKDD 2024"
          description: "2024-04-25"
        - icon: check-circle
          icon_pack: fas
          name: "Ph.D. Proposal Defense — Passed"
          description: "Utah State University • 2024-03-01"
        - icon: book-open
          icon_pack: fas
          name: "Paper Accepted — IJCNN 2023"
          description: "2023-06-18"
        - icon: book-open
          icon_pack: fas
          name: "Paper Accepted — IEEE Big Data 2022"
          description: "2022-12-17"
        - icon: book-open
          icon_pack: fas
          name: "Paper Accepted — IEEE Big Data 2021"
          description: "2021-12-15"
    design:
      columns: 3         # 3-up like your screenshot; change to 2 if you prefer larger cards
---
