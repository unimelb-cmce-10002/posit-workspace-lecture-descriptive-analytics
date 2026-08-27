# Posit Workspace: Descriptive Analytics (RFM & Segmentation)

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![lifecycle](https://img.shields.io/badge/version-2026.S2-red.svg)]()

## What this repo does

This repository contains instructor materials for lecture 9 on Descriptive Analytics (RFM & Data-Driven Segmentation) using CDNOW purchase data.

Our weapons of choice are:

* Rule-based segmentation using RFM (Recency, Frequency, Monetary) metrics
* Data-driven segmentation using K-Means clustering

## Repository Contents

* `_notes/`: Instructor notes and reference notebooks:
  * `lecture_07_instructor.qmd`: Quarto notebook with complete instructor solutions and notes for RFM calculations, rule-based segmentation, and K-Means clustering.
  * `lecture_07_student.qmd`: Reference student notebook version.
  * `lecture_07_inclass.qmd`: Template for the in-class activity.
* `lecture_07_inclass.qmd`: Main Quarto notebook for student in-class exercises.
* `data/cdnow_purchases.csv`: Transaction data for CDNOW customer purchases.
* `project.Rproj`: RStudio project file.

## How to Build this repo

If you have R and RStudio/Quarto installed, navigate your terminal to this directory or open `project.Rproj` in RStudio.

### Installing Missing R packages

To ensure all required R libraries are installed, open R and run:

```r
install.packages(c("tidyverse", "lubridate", "recipes", "factoextra", "broom", "kableExtra"))
```

