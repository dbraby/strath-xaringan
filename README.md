# strath_xaringan
CSS theme for r/xaringan in Strath Colours

To download this repo into R, use the following code

```

devtools::install_github("dbraby/strath_xaringan")

```
...and inserting the code below into to the YAML front-matter
```
---
title: "Title here"
subtitle: "Sub-title here"
author: "Your Name"
date: "University of Strathclyde </br> `r Sys.Date()`"
output:
  xaringan::moon_reader:
    css: ["strath.css", "strath-fonts.css"]
    nature:
      beforeInit: "https://www.danielbraby.com/strath_xaringan.js"
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
      ratio: "16:9"
---
```
