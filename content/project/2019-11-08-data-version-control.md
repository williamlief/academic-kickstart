---
title: Data Version Control
date: '2019-11-08'
slug: data-version-control

summary: Package to track data versions in Git
subtitle: 'An r-package to automate data versioning for git integration'
tags:
  - Academic
lastmod: '2019-11-08T13:22:25-08:00'
---

This package came about from my frustration with trying to recreate old charts and tables while working on long term research projects. Because data files are not tracked in git, tracking my code meant either laboriously re-running old data cleaning scripts to restore data to its prior state or manually adding version stamps to data files and updating them in all relevent scripts whenever a data set was edited. This package automates the version control of data files by automatically adding prefixes to file names, and using git to save the current version at each point in time.

Note that this project is under current development and is currently in an alpha state. The user interface should remain stable, but at this stage of development I recommend forking the project and installing the package from a version that you control. 

Check out the [GitHub Repo](https://github.com/williamlief/liefTools) or 
Install using ` devtools::install_github("williamlief/DataVersionControl") ` 
