# How to Automate Repeated Things in R

by [Jae Yeon Kim](https://jaeyk.github.io/)

File an [issue](https://github.com/dlab-berkeley/automating-workflows-in-R/issues) if you have problems, questions or suggestions.

## Overview

This workshop helps you to step up your R skills with functional programming. The `purrr` package provides easy-to-use tools to automate repeated things in your entire R workflow (e.g., wrangling, modeling, and visualization). The end result is cleaner, faster, more readable and extendable code. I highly recommend you to take this workshop (1) if you still write copy-and-paste code, (2) exclusively rely on for loops for automation, and (3) want to know about the joy and power of R functional programming.

## Learning objectives

1. How to use `purrr` to automate workflow in a cleaner, faster, and more extendable way [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/01_why_map.html)]

2. How to use `map2()` and `pmap()` to avoid writing nested loops. [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/02_more_inputs.html)]

3. How to use `map()` and `glue()` to automate creating multiple plots [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/03_map_glue.html)]

4. How to use `reduce()` to automate joining multiple dataframes [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/04_reduce_join.html)]

5. How to use `slowly()` and `future_` to make automation process either slower or faster [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/05_slower_faster.html)]

6. How to use `safely()` and `possibly()` to make error handling easier [[Notebook](https://rawcdn.githack.com/dlab-berkeley/R-functional-programming/1650e53a815d7c6e5449e035fd61a21b646b43d7/lecture_notes/06_make_error_handling_easier.html)]

## Prerequisites

- Some experience with writing functions in R

## Setup

Launch the [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/R-functional-programming/master?urlpath=rstudio). Please do so before attending the worskshop as it takes a while (especially, if you do it for the first time).

---

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
