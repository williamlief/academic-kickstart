
---
title: 'Teacher Evaluation Database'
date: '2019-06-13'
slug: evaluationDB
summary: District Level Teacher Evaluation Reports
subtitle: 'A database of teacher evaluation reports'
tags:
  - Academic
---

Teacher evaluations were a hugely controversial school reform tool of the early 2010s. The issue has personal significance, as I worked for New York City designing and implementing student growth  models for their Advance Teacher Evaluation system. A decade later, its not clear what impact these evaluations have had, outside of isolated cases like Washington D.C. Work by [Kraft and Gilmour](https://journals.sagepub.com/doi/pdf/10.3102/0013189X17718797) has focused on state level variation in evaluations and I follow up on their work by looking at district level variation in evaluation implementation within states. 

As an example, here's the distribution of teacher evaluation results across Ohio's school districts in 2014. Each school district is represented by a bar with width proportional to their size, and bars are arranged so that those districts with the most teacheres rated below effective are on the left. From this figure we can see that there is a huge amount of variability within the state in how the evaluation mandate was interpreted and implemented. 
![distribution of teacher evaluations in Ohio by school district](/project/teacher-evaluation-database/2019-06-13-teacher-evaluation-database_files/Ohio_evaluation.jpg)

This project is a compilation of publicly available teacher evaluation reports for US school districts. Detailed notes with the sources of all data are part of the [github repostiory](https://github.com/williamlief/evaluationDB), as is all code used to clean and process the data. In the repository you won't find teacher names and evaluation scores, but you will find the count of teachers receiving each rating in a district. It is not at all clear that evaluation reports are comparable across districts or states, and results cannot be directly compared across districts. Districts with more teachers rated 'ineffective' may have worse teachers or they may simply have been more willing to engage with the evaluation tools. Similarly, districts that report all of their teachers are 'highly effective' may in fact be phenomenal, or they may have had administrators who decided that they did not want to meaningfully participate in the evaluation system.

All data for this project is currently kept privately until I am ready for a public release of the data. If you are interested in getting involved please contact me. 
