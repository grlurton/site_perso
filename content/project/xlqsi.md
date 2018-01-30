+++
title = "XLQSI - Excel tool for laboratory quality improvement"
date = 2017-09-29T01:40:08-08:00
draft = false

# Tags: can be used for filtering projects.
tags = ["tools","laboratory","continuous quality improvement","consultancy"]

# Project summary to display on homepage.
summary = "An Excel based tool to help Continuous Quality Improvement for laboratories."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

The need for an Excel tool to collect data related to the continuous quality strengthening of laboratories was first raised by the Laboratory Systems
Strengthening team in [ITech](https://www.go2itech.org/). In order to use the [Laboratory Quality Stepwise Implementation tool (LQSI)](https://extranet.who.int/lqsi/) developed by the World Health Organization in and the Dutch Royal Tropical Institute (KIT), field teams needed a tool that would be easy to use, adaptable to specific conditions or local regulations in the field, and that would allow a better follow-up of laboratories progresses and results.

As part of a short term consultancy for ITech, I developped an Excel based and Python enriched workbook, to help for the collection of the highly dimensional of LQSI tool. Using the *xlwings* package and add-in for advanced data manipulation in Excel, the tool allows the user to:

* Adapt the generic checklist to local norms and conditions
* Directly import data from electronic equipment registries
* Enter data in a simplified list, with completude checks and progression bars to help with the multipliciy of indicators
* Visualize the results of a mentoring session
* Visualize the progression of laboratories in time

## More details

Documentation: [html](https://grlurton.github.io/xlqsi/html/) , [pdf](https://github.com/grlurton/xlqsi/raw/master/docs/latex/XLQSI.pdf)

Full project: [Github](https://github.com/grlurton/xlqsi)
