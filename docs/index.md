---
knit: bookdown::render_book
site: bookdown::bookdown_site
title: "Introduction to Data Science with R and Tidyverse"
author: "Lukas Jürgensmeier, based on materials from Data Science in a Box by Mine Çetinkaya-Rundel"
description: "Data Science in a Box contains the materials required to teach (or learn from) the course described above, all of which are freely-available and open-source."
date: "2024-02-15"
github-repo: https://github.com/coding-intro/R_Intro_2024_02
cover-image: dsbox.png
url: 'https\://datasciencebox.org/'
documentclass: book
link-citations: yes
---

# Welcome {.unnumbered}

Welcome to the course website for

**Introduction to Data Science with R and Tidyverse**

offered for GRADE Brain and other GRADE Centers at Goethe University in February 2024.
This website serves as the central repository for all course materials.
Here, you will find all slides, lecture materials, and links to your online development environment.

## Course Objective

Most academic fields require proficiency in at least one data-centered analysis tool.
For many, the R programming language has become the tool of choice.
However, the first steps in coding can be intimidating and discouraging---especially if you have never worked with a programming language before.
This course aims at providing a results-oriented, applied, and hands-on introduction to the most important parts of a Data Science project in R.
We will not only introduce the libraries and frameworks necessary for your analysis, but also focus on teaching you the implementation and application of those tools with small examples that you can work on yourself.

Our goal is to show you the scope of possibilities within R and leave you with the impression that you can confidently implement your own empirical projects in R.
We will focus on the Tidyverse ecosystem, a consistent and intuitive framework for building your data analysis from start to finish.
After the successful completion of this course, you know how to apply the basic Tidyverse tools for common Data Science tasks in R---primarily data wrangling, data visualization, and results communication.

## Course Description

We aim this course at beginners who are either entirely new to R as a programming language and/or want to learn about the Tidyverse ecosystem.
The course covers four primary areas of the typical data science process and introduces the respective `tidyverse` tools:

-   Plotting with `ggplot2`
-   Data wrangling with `dplyr`
-   Communicating your results with R Markdown
-   Regressions with `tidymodels`

We will not cover statistical or theoretical concepts in this course, as the focus will lie on applied coding.

## Methods

We will *let you eat cake first*.
What does that mean?
Many programming courses start with the absolute basics --- variable types, syntax, loops, etc.
Those are important but quite dull in the beginning.
Instead of monotonously walking you through those, we follow a different teaching philosophy.

Each topic will start with a very friendly and sometimes a bit complicated *cake*.
And you will dive right into it by executing and adapting the code for that "data science cake."

For example, we will show you an advanced visualization right at the beginning of the course and focus on what is possible eventually.
While this might appear intimidating at first (*"how should I ever be able to code that from scratch?"*), we will walk you through the steps and introduce the methods to get there during the course.

The course will alternate between short introductions to a concept or method and small do-it-yourself coding exercises.
In between the three sessions, you are encouraged to work on provided exercises that further deepen your understanding.

## Conditions

This course is a beginner-friendly course.
You do not need prior coding experience.
But you are also more than welcome to participate if you are an experienced R user but want to learn more about the Tidyverse.

You will need a [Posit Cloud](https://posit.cloud/) (formerly RStudio Cloud) account.
Posit Cloud is a very convenient online integrated Development Environment, where we provide you with all the necessary code to follow the course and work with small application exercises on your own.

By avoiding to install RStudio locally during the course, we can start right away with the more critical course content.
If you already have set up a local installation of RStudio, you are, of course, more than welcome to use that instead.
In this case, download the source files linked in the respective application exercises.
Note that you won't need to set anything up if you use Posit Cloud.

Since we do not want to waste precious time on the technical setup, we will use the Posit Cloud as a simple---and already set up---development environment.
We will send out detailed instructions and an invitation link in advance.

## Course Organization

We will meet on February 16th and 23rd 2024 from 09:00 -- 12:30 in Seminarhaus, room 5.106 on Campus Westend ([see map](https://www.wiwi.uni-frankfurt.de/fileadmin/user_upload/dateien_pruefungsamt/Pruefungsorganisation/Lageplan_Campus_Westend.pdf)).
Here is a rough timetable, depending on our progress we may change this up a little:

DAY 1 (Feb. 16th)

| Part            | Time           |
|-----------------|----------------|
| Workshop Part 1 | 09:00 -- 10:30 |
| *Coffee Break*  | 10:30 -- 11:00 |
| Workshop Part 2 | 11:00 -- 12:30 |

DAY 2 (Feb. 23rd)

| Part            | Time           |
|-----------------|----------------|
| Workshop Part 3 | 09:00 -- 10:30 |
| *Coffee Break*  | 10:30 -- 11:00 |
| Workshop Part 4 | 11:00 -- 12:30 |

We want you to *make your hands dirty* --- that means we want you to code!
Just following along fancy slides won't magically transfer the skill of coding to you.
But you actively engaging with the course content in your development environment will more likely do just that.

That's why we need you to prepare accordingly:

Please create a [Posit Cloud](https://posit.cloud/) (formerly RStudio Cloud) account before the first class.
We have sent you a link to access all exercises on Posit Cloud.
Since we want you to start coding very early on in the first class, please ensure that you can access those course materials on Posit Cloud before our first meeting.

If you have any questions, please reach out to one of us through the e-mail addresses on the bottom of this page.

## Schedule

This workshop alternates between lecture-style presentations and application exercises.
In those hands-on exercises, you will actively try out the discussed tools in small groups and with suppport from the teachers.
We aim to adhere to the following schedule.
Depending on our progress, we may discuss some parts a bit earlier or later during the course.

| Part | Title                              | Type                 |
|------|------------------------------------|----------------------|
| 1    | Welcome                            | Lecture              |
| 1    | First data visualization: UN Votes | Application Exercise |
| 1    | Meet the programming toolkit       | Lecture              |
| 1    | The Bechdel Test + R Markdown      | Application Exercise |
| 2    | Data and visualization             | Lecture              |
| 2    | Visualizing data with ggplot2      | Lecture              |
| 2    | Visualizing categorical data       | Lecture              |
| 2    | StarWars + Dataviz                 | Application Exercise |
| 3    | Tidy data                          | Lecture              |
| 3    | Grammar of data wrangling          | Lecture              |
| 3    | Working with a single data frame   | Lecture              |
| 3    | Hotels + Data wrangling            | Application Exercise |
| 4    | Working with multiple data frames  | Lecture              |
| 4    | Data types                         | Lecture              |
| 4    | Importing data                     | Lecture              |
| 4    | Nobels + Sales + Data import       | Application Exercise |
| 4    | Fitting and interpreting models    | Lecture              |

## Readings

The course is self-contained, and you will most likely get all the necessary information for the application exercises from the slides.
If you want to read more about given topics, we provide links to chapters in open source Data Science/Tidyverse/R textbooks.
You will find the links on the following pages right beside the link to each chapter's slides.

::: reading
We suggest two textbook references:

-   **R4DS**: Wickham, H., Grolemund, G. (2017), "R for Data Science: Import, Tidy, Transform, Visualize, and Model Data", available at [r4ds.had.co.nz](https://r4ds.had.co.nz/)
-   **IMS**: Çetinkaya-Rundel, M., Hardin, J. (2022), "Introduction to Modern Statistics", available at [openintro-ims.netlify.app](https://openintro-ims.netlify.app/)
:::

## Trainers

Feel free to reach out to us by e-mail if you have any questions before, during, or after the course:

-   **Matteo Fina**, M.Sc., PhD Student at GSEFM in Economics, [send me an e-mail](mailto:matteo.fina@its.uni-frankfurt.de)

-   **Jan Bischoff**, Business and Economics Student, R/Python Teacher and Course Designer at [TechAcademy e.V.](#0), [send me an e-mail](mailto:jan.bischoff@tech-academy.io)

## License {.unnumbered}

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" alt="Creative Commons License" style="border-width:0"/></a><br />This online work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International</a>.
Visit [here](https://github.com/rstudio-education/datascience-box/blob/master/LICENSE.md) for more information about the license.

## Acknowledgements {.unnumbered}

The course is built upon material from [datasciencebox.org](https://datasciencebox.org/) by Mine Çetinkaya-Rundel.

We acknowledge generous financial support for teaching this course through a DigiTeLL grant (project "Coding Intro").

Thanks to the #rstats education community who have made numerous suggestions for this resource, Lee Suddaby and Zeno Kujawa, for converting the homework assignments to learnr tutorials and [Müge Çetinkaya](http://muge.fr/) for the hex logo!

This website is built with [bookdown](https://bookdown.org/), the lovely icons by [icons8](http://icons8.com/), and none of this would be possible without the [tidyverse](https://tidyverse.org/).
