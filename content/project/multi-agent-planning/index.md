---
title: Rigidity-Constrained Multi-Agent Priority Planning
summary: A planning algorithm for a network of agents which can localize using only distance measurements between each other
tags:
- Robotics
date: "2020-10-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

- icon: google-scholar
  icon_pack: ai
  name: Scholar
  url: https://scholar.google.com/citations?user=Ym3SpKgAAAAJ&hl=en

image:
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In many environments, such as underwater, it can be difficult to get reliable
localization using visual features. This could be due to the environment being highly repetitive or there being a general sparsity of features. In these situations the performance of traditional localization techniques tends to degrade and can give highly incorrect errors.

A key direction in my research is leveraging the use of inter-agent ranging, a
measurement which does not depend on environmental observation, to aid the
multi-robot localization task. However, there is a caveat, the quality of range-based localization varies based on the connectivity and spatial arrangement of the network of agents.

In this work I developed a planner which allowed for networks of agents to efficiently plan trajectories that allowed them to stay in configurations which were favorable for range-based localization. Read more about it <a href=""> here </a>
