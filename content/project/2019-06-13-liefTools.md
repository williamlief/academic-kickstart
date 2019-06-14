---
title: 'liefTools'
date: '2019-06-13'
slug: liefTools
summary: Handy functions for data analysis 
subtitle: 'An r-package to streamline common data exploration tasks'
tags:
  - Academic
lastmod: '2019-06-13T12:29:50-07:00'
---

This is an r-package I have developed to contain a collection of helpful functions that I find useful for data analysis. Most of these functions are very simple, but save me from having to type out the same five lines of code over and over again. As some examples:

* `summarize_mean` takes a dataset and returns the mean value of every variable in it. The function also allows an optional grouping parameter, and will return a wide tibble with one row per variable and one column per group level.
* `g_sample` takes a random sample of groups within a grouped tibble, instead of a random sample of rows within each group.
* `balance_panel` takes panel data, and removes all the units that are missing observations. 

The package is fully documented in R, see the help index for a full list of functions. Note that this package will change frequently, and I make no promises about preserving backwards compatibility. If you're interested in using any of the tools, I suggest forking the repository and maintaining your own version. 

Install using ` devtools::install_github("williamlief/liefTools") ` or check out the [GitHub Repo](https://github.com/williamlief/liefTools). 