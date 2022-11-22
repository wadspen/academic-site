---
title: Using Mixture Distributions in Collaborative Forecasting of COVID-19
summary: Iowa State department of statistics 75th anniversary celebration
tags:
  - COVID-19
  - Forecasting
date: '2022-09-2T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'Image credit: [**ISU-Statistics**](https://www.stat.iastate.edu/event/2022/75th-anniversary-celebration)'
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_poster: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Poster (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: "content/presentations/75th_anniversary_poster.pdf"
---

The COVID-19 Forecast Hub was established in 2020 as a collaborative
effort to forecast the coronavirus pandemic. Dozens of teams have been
involved, each submitting weekly probabilistic forecasts of the spread of
the virus. From the weekly forecasts, a single ensemble forecast is
constructed and shared with the CDC for use in public reports. In order to
assess the various forecasts against one another and to construct from
them an ensemble forecast, each submitted forecast must share a
common format. Each forecast is submitted as a set of 23 quantiles and
their corresponding values.

Other collaborative forecast projects use different formats for
representation such as binned probabilities used in the CDC’s annual flu
forecasting competition. Other formats include parametric distributions
and sample distributions.
Introduction

We propose that collaborative forecast projects utilize a
discrete mixture distribution format as a preferable alternative to
the four mentioned above.
