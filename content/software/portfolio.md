---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

title: Projects

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Middleware
      tag: middleware
    - name: Smart Spaces
      tag: spaces
    - name: Active
      tag: active
    - name: IoT
      tag: iot
    - name: QoS
      tag: qos
    - name: SOA
      tag: soa

design:
  columns: '1'
  view: Card
  flip_alt_rows: false
  background: {}
  spacing: {padding: [10, 0, 5, 0]}
---