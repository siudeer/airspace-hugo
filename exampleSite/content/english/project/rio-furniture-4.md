---
title: Jacques Cousteau
description: ''
image: images/portfolio/work4.jpg
bg_image: images/feature-bg.jpg
category: Bucks
information:
- label: Sex
  info: Male
- label: Age
  info: Juvenile
- label: Tracking Start Date
  info: 4/1/21

---
#### I’m Jacques Cousteau (collar 87630), a young buck who spends my days relaxing and doing water sports on Campus lake. Cowabunga!

``` {r test, echo = F}

library(htmlwidgets)
library(htmltools)
setwd("images/portfolio")

x <- list.files(pattern = "html")
x <- x[1]


htmlwidgets::sizingPolicy(browser.defaultWidth = 400, browser.defaultHeight = 400, viewer.fill = T)
htmltools::includeHTML((paste0(getwd(), "/", x)))

```
