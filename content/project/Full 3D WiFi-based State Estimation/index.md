---
title: Fully 3D WiFi-based MAV State Estimation
summary: We take ubiquitous WiFi to achieve fully 3D MAV state estimation.
tags:
- State Estimation
date: "2020-06-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image by Shengkai Zhang
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

We take ubiquitous WiFi to extract absolute-relative drift-free environmental sensing features. Inspiring from visual-based state estimators, we view WiFi access points (APs) as environmental features whose geometrical relationship to the vehicle is established by WiFi signals. The PHY information of WiFi holds the cues of MAV positions and attitudes as well as APs' positions. Compare to the visual cues from images captured by camera, APs are few but persistent, even out of sight (behind walls) while visual features are rich but changeable with the field of view.
