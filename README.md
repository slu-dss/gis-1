# gis-1 <img src="/img/logo.png" align="right" />
[![](https://img.shields.io/badge/seminar-%20mapping%20in%20R-brightgreen.svg)](https://github.com/slu-dss/gis-1/)
[![](https://img.shields.io/badge/lesson%20status-under%20development-red.svg)](https://github.com/slu-dss/gis-1/)
[![](https://img.shields.io/github/release/slu-dss/gis-1.svg?label=version)](https://github.com/slu-dss/gis-1/releases)
[![](https://img.shields.io/github/last-commit/slu-dss/gis-1.svg)](https://github.com/slu-dss/gis-1/commits/master)

## Lesson Overview
This repository contains the first lesson for the Mapping in R seminar. This lesson introduces some basics of working with spatial data.

### Objectives
At the end of this lesson, participants should be able to:

1. Import spatial data into `R`
2. Create basic web maps using `leaflet`
3. Convert point data stored in a `.csv` to `sf` objects
4. Explore spatial data using the `mapview` package as well as `View()`

### Lesson Resources
* The [`notebook/`](/notebook) directory contains the materials for this lesson.

### Extra Resources
* [R for Data Science](https://r4ds.had.co.nz/)
* [Geocomputation with R](https://geocompr.robinlovelace.net)

## Lesson Quick Start
### Install Software
The packages we'll need for today can be installed using:

```r
install.packages(c("tidyverse", "here", "knitr", "leaflet",
                   "mapview", "rmarkdown", "sf", "usethis"))
```

### Access Lesson
You can download this lesson to your Desktop easily using `usethis`:

```r
usethis::use_course("https://github.com/slu-dss/gis-1/archive/master.zip")
```

By using `usethis::use_course`, all of the lesson materials will be downloaded to your computer, automatically extracted, and saved to your desktop. You can then open the `.Rproj` file to get started.

## Contributor Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## About the SLU DSS
### Mapping in `R`
This seminar series introduces the basics of working with spatial data in `R`, including data wrangling and basic map production.

### About the SLU Data Science Seminar
The [SLU Data Science Seminar](https://slu-dss.githb.io) (DSS) is a collaborative, interdisciplinary group at Saint Louis University focused on building researchers’ data science skills using open source software. We currently host seminars focused on the programming language R. The SLU DSS is co-organized by [Christina Gacia, Ph.D.](mailto:christina.garcia@slu.edu), [Kelly Lovejoy, Ph.D.](mailto:kelly.lovejoy@slu.edu), and [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). You can keep up with us here on GitHub, on our [website](https://slu-dss.githb.io), and on [Twitter](https://twitter.com/SLUDSS).

### About Saint Louis University <img src="/img/sluLogo.png" align="right" />
Founded in 1818, [Saint Louis University](http://www.slu.edu) is one of the nation’s oldest and most prestigious Catholic institutions. Rooted in Jesuit values and its pioneering history as the first university west of the Mississippi River, SLU offers nearly 13,000 students a rigorous, transformative education of the whole person. At the core of the University’s diverse community of scholars is SLU’s service-focused mission, which challenges and prepares students to make the world a better, more just place.
