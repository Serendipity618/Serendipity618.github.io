---
title: "News"
type: "landing"
show_title: false
show_breadcrumb: false
backlinks: false

sections:
  # Page-only style (affects just this page)
  - block: "markdown"
    id: "news-styles"
    content:
      title: ""
      text: |-
        <style>
          /* Scope styles to this section only */
          #news-timeline { font-size: 0.92rem; }
          #news-timeline .section-title { font-size: 1.05rem; margin: 0 0 .6rem 0; line-height: 1.25; }
          /* In case any body/description sneaks in, hide it */
          #news-timeline .card-text, #news-timeline .article-style { display: none; }
        </style>

  # Timeline (Experience block)
  - block: "experience"
    id: "news-timeline"
    content:
      title: "News & Milestones"
      date_format: "Jan 2006"
      items:
        - title: "Workshop Abstract Accepted — AMIA 2025 (NLP Workshop)"
          company: "Atlanta, GA"
          date_start: "2025-09-12"
          icon: "trophy"
          icon_pack: "fas"

        - title: "Postdoctoral Researcher — CU Anschutz (DBMI)"
          company: "University of Colorado Anschutz Medical Campus"
          date_start: "2025-07-01"
          icon: "briefcase"
          icon_pack: "fas"

        - title: "Ph.D. Completed — Computer Science"
          company: "Utah State University"
          date_start: "2024-12-01"
          date_end: "2024-12-31"
          icon: "award"
          icon_pack: "fas"

        - title: "Paper Accepted — ECML-PKDD 2024"
          company: ""
          date_start: "2024-08-22"
          icon: "book-open"
          icon_pack: "fas"

        - title: "Paper Accepted — PAKDD 2024"
          company: ""
          date_start: "2024-04-25"
          icon: "book-open"
          icon_pack: "fas"

        - title: "Ph.D. Proposal Defense — Passed"
          company: "Utah State University"
          date_start: "2024-03-01"
          icon: "check-circle"
          icon_pack: "fas"

        - title: "Paper Accepted — IJCNN 2023"
          company: ""
          date_start: "2023-06-18"
          icon: "book-open"
          icon_pack: "fas"

        - title: "Paper Accepted — IEEE Big Data 2022"
          company: ""
          date_start: "2022-12-17"
          icon: "book-open"
          icon_pack: "fas"

        - title: "Paper Accepted — IEEE Big Data 2021"
          company: ""
          date_start: "2021-12-15"
          icon: "book-open"
          icon_pack: "fas"
    design:
      columns: 1
---
