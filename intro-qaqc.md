---
title: "Introduction to quality assurance and quality control"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- Why is managing data quality important?
- What is the role of data quality assurance and quality control in the data lifecycle?
- How do you address data quality in work?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Describe the role of quality assurance and quality control in the data life cycle
- Recognize common issues that occur with human- and sensor-collected datasets
- Explain resources available at the USGS to support data quality
- Reflect on processes that you use to address data quality

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

Quality assurance and quality control are both components of the data life cycle. Quality assurance focuses on preventing errors by taking steps during and before data are acquired or collected, while quality control evaluates data to determine whether they are correct, complete, and consistent.

::: callout

We use the USGS model of the data life cycle, but there are various models of data life cycles.

:::

Data collected by USGS hydrologists on freshwater water quality is likely to undergo both quality assurance and quality control. For this type of data, quality assurance steps could include:

- training in standard field methods
- designing data templates
- backing up datasets

Quality control steps could include:

- evaluating a dataset for missing values
- checking for issues with data that is out of range
- flagging errors

::: discussion

In 1-2 sentences, describe a dataset that you work on or that you are familiar with. Then, list 4-5 data quality issues that could arise while working with this data.

:::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Quality assurance vs. quality control?

Review a USGS resource, such as the [Data Management webpage](https://www.usgs.gov/data-management/manage-quality). Differentiate between quality assurance and quality control by sorting tasks (from McCord et al. 2021) under the header of one or another activity.

- document errors
- develop data management plan
- record metadata
- review data
- check calculations using data
- track methods

:::::::::::::::::::::::: solution 
 
| QA    | QC |
| -------- | ------- |
| develop data management plan  | document errors    |
| record metadata | review data     |
| track methods    | check calculations using data    |

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints 

- Managing data quality supports scientific research, data releases, and communication
- Quality assurance focuses on preventing errors by taking steps during and before data are acquired or collected, while quality control evaluates data to determine whether they are correct, complete, and consistent
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
