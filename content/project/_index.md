---
title: Selected Projects
cms_exclude: true
# type: landing
# View
# view: article-grid

# Optional cover image (relative to `assets/media/` folder).
# image:
#   caption: ''
#   filename: ''

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: projects
    content:
      title: Selected Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
---


