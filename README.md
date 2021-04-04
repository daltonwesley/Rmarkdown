# Rmarkdown
title: "LifeExpect"
author: "Dalton Shepherd"
date: "2021.04.04"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

```{r cars}
summary(LifeExpect)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(LifeExpect)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
