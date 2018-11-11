---
title: "Basic Concepts"
author: "Itamar Caspi"
date: '2019'
output:
  ioslides_presentation:
    css: style.css
    df_print: tibble
    highlight: espresso
    keep_md: yes
  beamer_presentation:
    highlight: espresso
    includes:
      in_header: preamble.txt
    df_print: kable
editor_options:
  chunk_output_type: inline
---



## R Markdown

This is an \alert{R Markdown} presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Slide with R Output


```r
head(cars)
```

```
## # A tibble: 6 x 2
##   speed  dist
## * <dbl> <dbl>
## 1     4     2
## 2     4    10
## 3     7     4
## 4     7    22
## 5     8    16
## 6     9    10
```

## Bias-Variance Tradeoff

$$y = ax+b+e$$
where $y$ is the response variable...

## Slide with Plot

![](beamer_files/figure-html/pressure-1.png)<!-- -->

## New Slide

