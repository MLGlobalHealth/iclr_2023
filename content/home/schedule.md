---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank # See https://wowchemy.com/docs/page-builder/
headless: true # This file represents a page section.
weight: 40 # Order that this section will appear.
title: Schedule
subtitle: ''
design:
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ['20px', '0', '20px', '0']
  columns: '1'
  css_class: fullscreen
---

{style="padding-top: 5rem"}

{{< table path="schedule.csv" header="true" >}}
