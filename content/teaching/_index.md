---
title: Teaching
type: landing

# The following blocks support this option: pages, featured, experience, accomplishments, contact, blank, tag_cloud, portfolio
sections:
  - block: portfolio
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
        kinds:
          - page
      buttons:
        - name: All
          tag: '*'
        - name: Workshops
          tag: workshop
        - name: Lectures
          tag: lecture
        - name: Tutorials
          tag: tutorial
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    sort_by: 'Date'
    sort_ascending: false
---