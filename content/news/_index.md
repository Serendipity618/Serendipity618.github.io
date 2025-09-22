---
title: "News"
type: "landing"
show_title: false
show_breadcrumb: false
backlinks: false

sections:
  # 1) Page-scoped CSS (only affects #news block below)
  - block: "markdown"
    id: "news-style"
    content:
      title: ""
      text: |-
        <style>
          /* Smaller text, comfy spacing, only on this page's #news block */
          #news .section-title{font-size:1.05rem;margin:0 0 .6rem 0;line-height:1.25;}
          #news .article-style, #news .markdown-body{font-size:.9rem;line-height:1.55;}
          #news ul{margin:0;padding-left:1.1rem;}
          #news li{margin:.6rem 0;}
          #news strong{font-weight:600;}
        </style>

  # 2) Actual News content
  - block: "markdown"
    id: "news"
    content:
      title: "News & Milestones"
      text: |-
        - 🏆 **2025-09-12** — *Workshop Abstract Accepted — AMIA 2025 (NLP Workshop)* — _Atlanta, GA_
        - 💼 **2025-07-01** — *Postdoctoral Researcher — CU Anschutz (DBMI)* — _University of Colorado Anschutz Medical Campus_
        - 🎓 **2024-12-01–12-31** — *Ph.D. Completed — Computer Science* — _Utah State University_
        - 📖 **2024-08-22** — *Paper Accepted — ECML-PKDD 2024*
        - 📖 **2024-04-25** — *Paper Accepted — PAKDD 2024*
        - ✅ **2024-03-01** — *Ph.D. Proposal Defense — Passed* — _Utah State University_
        - 📖 **2023-06-18** — *Paper Accepted — IJCNN 2023*
        - 📖 **2022-12-17** — *Paper Accepted — IEEE Big Data 2022*
        - 📖 **2021-12-15** — *Paper Accepted — IEEE Big Data 2021*
    design:
      columns: 1
---
