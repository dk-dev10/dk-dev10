### Hi there 👋

<!--
**dk-dev10/dk-dev10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


name: 📅 Isometric commit calendar
category: github
description: |
  This plugin displays an isometric view of a user commit calendar along with a few additional statistics like current streak and average number of commit per day.
examples:
  +full year calendar: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg
  half year calendar: https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg
index: 0
supports:
  - user
scopes:
  - public_access
inputs:

  plugin_isocalendar:
    description: |
      Enable isocalendar plugin
    type: boolean
    default: no

  plugin_isocalendar_duration:
    description: |
      Time range

      - `half-year`: 180 days
      - `full-year`: 1 year
    type: string
    default: half-year
    values:
      - half-year
      - full-year
