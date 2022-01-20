# R Fundamentals for Public Policy

This course aims to introduce and demonstrate how fun and exciting data analysis with R could be. Mastering computational tools and techniques not only enable social scientists to collect, wrangle, analyze, and interpret data with less pain and more fun, but it also let them work on research projects that would previously seem impossible. Taking this workshop is the first step to move you in that direction. The course focuses on data wrangling: the most fundamental and time-consuming component of the data analysis workflow.

R is free, easy to learn (thanks to [tidyverse](https://www.tidyverse.org/)), fast (thanks to [rcpp](https://cran.r-project.org/web/packages/Rcpp/index.html#:~:text=The%20'Rcpp'%20package%20provides%20R,integration%20of%20third%2Dparty%20libraries.)), runs everywhere, open (16,000+ packages; counting only ones available at the [CRAN](https://cran.r-project.org/)), and has a growing massive and inclusive community called [#rstats](https://twitter.com/search?q=%23rstats&src=hashtag_click).

## Textbook

I use the canonical R textbook written by Grolemund and Wickham. Wickham is the mastermind behind the tidyverse, the most popular data analysis framework in the R ecosystem. Almost all of the course contents used in this course, including the textbook, are **free and accessible online** so that more students can easily access those materials regardless of their backgrounds.

* Garrett Grolemund and Hadley Wickham (2016). [R for Data Science](https://r4ds.had.co.nz/)

## Readings

I use [the GitHub course repository](https://github.com/KDIS-DSPPM/r-fundamentals) in place of readings. All course materials, including lecture notes, code demonstrations, sample data, and assignments, will be posted on this repository. The lecture notes will be provided at least 1-2 days in advance. I expect that you read them before coming to class.  

## References

I am currently working on an open-access textbook titled [“Computational Thinking for Social Scientists.”](https://jaeyk.github.io/comp_thinking_social_science/) The book covers command-line tools, version control, data wrangling, visualization, functional programming, data product development, machine learning, and SQL. If you are interested in learning computational methods further, I recommend reading it. The course is a condensed version of the book's earlier parts.

## Computer requirements

The software needed for the course is as follows:

- Bash 

- Git 

- R and RStudio (latest versions)

- Pandoc and LaTeX (for R markdown)

I provided an [installation guideline](https://github.com/KDIS-DSPPM/r-fundamentals/blob/main/software_setup.md) on the GitHub repository. To avoid installation and configuration issues during class, I will make all the lecture notes using [MyBinder](https://mybinder.org/). The binder helps the code embedded in the lecture notes be reproducible by anyone, anywhere. For the assignments and final exam, you should code in R using your own machine.

## Evaluation

This is a graded class based on the following:

- Completion of assigned homework (50%)

- Participation (25%)

- Final exam (25%)

### 1. Assignment

Four assignments will be assigned throughout the semester. The assignments provide frequent learning opportunities. Each of these assignments should be fairly short and expected to be finished within 8-10 hours of effort. You are encouraged to work in group, but the work you turn in must be your own. Unless otherwise notified, the assignments should be rendered into an HTML output using R markdown (*.rmd) and you should submit both of them via the KDIS course website (not the GitHub repository). In addition, the R markdown files should be reproducible on our end, in the event we want to reproduce your work. I will cover what R markdown is and how to create an HTML output in the second week of the course. The final exam uses the same output format. The assignments will be graded on a check, check-plus, check-minus standards.

### 2. Participation

The class participation portion of the grade can be satisfied in one or more of the following ways:
- attending the lectures (the first class of the week; focusing more on concepts) and sections (the second class of the week focusing more on hands-on practice)
- asking and answering questions in class
- contributing to class discussion through [the Slack workspace](https://slack.com/):  You should ask questions about class material and assignments through the Slack channels so that everyone can benefit from the discussion (not personally emailing to me). We encourage you to respond to each other’s questions as well. A CA will send you an invite to the workspace after the roster is confirmed.

### 3. Final exam

The final exam is a take-home exam that I expect you to work on your work. The exam requires applying the skills you’ve acquired throughout the course to the real world data wrangling challenge. We will provide a link where you can retrieve the final exam and data. You should provide your student ID in the process and complete the exam **within 24 hours.** Like the assignments, you should turn in both the HTML output and R markdown file so that we could reproduce your analysis. This format is very similar to the technical interview required for getting data science jobs, so it should be useful for your career. I will take three things in consideration for the evaluation: **reproducibility**, **efficiency**, and **readability.**

## Accessibility

This class is committed to creating an environment in which everyone can participate, regardless of background, discipline, or disability. If you have a particular concern, please come to me as soon as possible so that we can make special arrangements.

## Course outline

### 1st Week

* Why computational social science?
* Reading: lecture notes
* Extra reading: [Kim ch2](https://jaeyk.github.io/comp_thinking_social_science/motivation.html), [Kim (2020)](https://dlab.berkeley.edu/news/why-teaching-social-scientists-how-code-professional-important)

### 2nd Week

* Flexible, efficient, and reproducible data analysis workflow using R
* Reading: lecture notes
* Extra reading: [Kim ch3](https://jaeyk.github.io/comp_thinking_social_science/git_bash.html), [Wickham (2017)](https://github.com/rstudio/rstudio-conf/blob/master/2017/The_Tidyverse-Hadley_Wickham/tidyverse.pdf)

### 3rd Week

* Getting the big picture of programming: objects and functions
* Reading: lecture notes
* Extra reading: [Kim & Ng (2021)](https://osf.io/preprints/socarxiv/pf7n6/?fbclid=IwAR2ZI0yw_pehS0mxAmeUBOGpzIhiO2LMUPGBzBLTLNo4C2HrJSoH9uZhgTY)
* Assignment: assignment #1 due

### 4th Week

* Playing with data types: vectors, dataframes, and lists  
* Reading: lecture notes
* Extra reading: [GW ch20](https://r4ds.had.co.nz/vectors.html)

### 5th Week

* Understanding the master framework: tidy principles
* Reading: lecture notes
* Extra reading: [GW ch12](https://r4ds.had.co.nz/tidy-data.html)
* Assignment: assignment #2 due

### 6th Week

* Reshaping and cleaning data using tidyverse
* Reading: lecture notes
* Extra reading: [Kim ch4](https://jaeyk.github.io/comp_thinking_social_science/tidy_data.html)

### 7th Week

* Summarizing data using tidyverse
* Reading: lecture notes
* Extra reading: [Kim ch4](https://jaeyk.github.io/comp_thinking_social_science/tidy_data.html)
* Assignment: Assignment #3 due

### 8th Week

* Visualizing data using tidyverse
* Reading: lecture notes
* Extra reading: [GW ch3](https://r4ds.had.co.nz/data-visualisation.html)

### 9th Week

* Simplifying workflow using custom functions
* Reading: lecture notes
* Extra reading: [Kim ch5](https://jaeyk.github.io/comp_thinking_social_science/functional_programming.html)
* Assignment: Assignment #4 due

### 10th Week

* Scaling up workflow using functional programming
* Reading: lecture notes
* Extra reading: [Kim ch5](https://jaeyk.github.io/comp_thinking_social_science/functional_programming.html)

### 11th Week: Reading period

### 12th Week : Final exam (a 24 hour take-home exam)

## Contact

1. Course content related suggestions: [create issues](https://github.com/KDIS-DSPPM/r-fundamentals/issues).

2. Lecture/section related questions: use the Slack workspace.

3. Logistics related personal requests: only in this case contact me via [email](jkim@kdischool.ac.kr)

In the 1 & 2 cases, other students may have similar issues. Therefore, I would like to solve these collective problems collectively.

## Office hour

Every Friday 1-5 PM. You can set up a 30 minutes appointment with me via [this Calendly link](https://calendly.com/jkim-46). The appointments are booked on a rolling basis. Depending on the COVID-19 situation and your current location, we may meet up via Zoom or in my office (**S320**).

There are several uses for office hours. I listed some examples below.

1. You might wonder how computational methods apply to your research or work. In that case, I am happy to talk about computational social science and civic data science applications during office hours.
2. You might find the course too challenging or easy. In that case, I am eager to provide you with additional learning guidelines.
3. You can use this time to chat and help us get to know each other.

## Special thanks

This course is a remix version of [PS239T](https://github.com/rochelleterman/PS239T) originally developed by [Rochelle Terman](http://rochelleterman.com/) (currently Assisant Professor at the University of Chicago) then revised by [Rachel Bernhard](http://rachelbernhard.com/) (currently Assistant Professor at the University of California-Davis). I taught PS239T three times at Berkeley (TA for Rachel, lead instructor, and co-instructor with Nick Kuipers). Other teaching materials draw from the workshops I created for [D-Lab](https://dlab.berkeley.edu/) at UC Berkeley, where I was a senior data science fellow, instructor, and consultant.

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
