---
title: Network Localization for COVID-19 Contact Tracing
summary: Tested different localization algorithms to perform COVID-19 Contact Tracing
tags:
- Robotics
date: "2020-10-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""


image:
  caption: Figure by Lilly Clark
  focal_point: Smart

links:
- icon: google-scholar
  icon_pack: ai
  name: Scholar
  url: https://scholar.google.com/citations?user=Ym3SpKgAAAAJ&hl=en


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

Most modern day phones are equipped with hardware that allows for Bluetooth
Low-Energy (BLE) communication with other phones. This can also be used to get a
rough distance between two phones, something which many teams have tried to use
to get contact tracing information. However, this approach has proven
challenging, with the measurements being highly noisy and there being a good
chance of two phones not having a measurement despite being within sensing range
of each other.

To try to combat these challenges, the contact tracing problem can be considered
a sensor network localization problem. This is a long-studied class of
algorithms which attempt to localize members of a network using only pairwise
distance measurements between network members. Modeling contact tracing as a
network localization problem serves two distinct benefits. First, this allows
for multiple measurements to be used to try to estimate the distance between
phones, combatting the effects of noisy data. Secondly, this allows for the
distance between two phones to be estimated even if there is no corresponding
distance measurement between these two devices.

In this collaboration I worked with <a
href="https://sites.google.com/usc.edu/lillyclark">Lilly Clark </a> to test out
a number of sensor network localization approaches for contact tracing. See our
results and read more about it <a href=""> here</a>!
