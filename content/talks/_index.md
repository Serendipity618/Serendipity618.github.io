---
title: "Talks"
type: "landing"

# Hide the huge page H1 and breadcrumbs (use block title instead)
show_title: false
show_breadcrumb: false

sections:
  - block: "collection"
    id: "talks"
    content:
      title: "Recent & Upcoming Talks"   # smaller heading like Projects
      filters:
        folders: ["talks"]               # pull items from content/event/*
        # optional:
        # exclude_featured: false
        # publication_type: []
      sort_by: "Date"
      sort_ascending: false
    design:
      view: "article-grid"               # same card grid as Projects
      columns: 2
---
