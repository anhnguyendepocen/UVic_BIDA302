---
title: 'BIDA302: Course Outline'
author: "Martin Monkman"
date: "`r Sys.Date()`"
output: 
  github_document
#  word_document: default
#  html_document: default
---


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# Data Analytics & Coding Fundamentals: BIDA302

February 29–April 4, 2020

9:00 am–4:00 pm (lunch break 12:00–1:00pm)

[Continuing Studies Building Lab C](https://www.uvic.ca/search/browse/maps.php)



## Prerequisites

None.


## Course description

In this course you will develop the ability to script and code for basic tasks in Data Analytics in common data analytic tools such as R, Python, and Excel. This will allow you to import and export data appropriately and perform fundamental data manipulations and to automate basic analysis elements.

### Learning objectives

By the end of this course, you should be able to:

* Perform basic data manipulations

* Create variables

* Apply key concepts of variables, constants and functions

* Calculate descriptive statistics

* Perform basic logical formula functions

* Group and ungroup data

* Data Importing

* Data Exporting

* Extract and combine data

* Create what-if scenarios



## Instructor

Martin Monkman

* email: <mmonkman@uvic.ca>

* skype: <a href="skype:monkmanmh?call">monkmanmh</a>


virtual (skype) office hours:

* Tuesday, 8:00 pm - 9:00 pm

* or by appointment (send me an email)


## Course content

RStudio cloud:

* This course uses rstudio.cloud

* To access the course site, please click this link: [rstudio.cloud: BIDA302_2020a]()

* You will need to create an account (if you don't have one already) when you initially log in


Moodle:

* This course uses Moodle—an online learning management system—as a supplementary resource for the class. 

* To access, login to [https://distance.moodle.uvcs.uvic.ca/](https://distance.moodle.uvcs.uvic.ca/) with your Netlink ID.


Text: 

* Garrett Grolemund and Hadley Wickham, [R for Data Science](https://r4ds.had.co.nz/). (Free online text.)

* Additional readings will be introduced with each lesson.

***

## Continuing Studies Statement on Use of Educational Technology

This course will require the use of RStudio Cloud and may use other education technology such as internet-based applications, cloud services, or social media. In order to complete this course you will be required to either consent to the disclosure of your personal information outside of Canada to enable use of these technologies, or work with the instructor to use other privacy protective options (such as using an alias or nickname).

***

## Course Philosophy

Analysis of data helps us make better decisions. And computers have accelerated how much data we can analyze.

We can do data analysis using GUI (Graphical User Interface) tools, such as Excel or Tableau. But using a programing language to write code that generates your analysis will make you more efficient and effective, open up a universe of additional functionality, and make your analysis workflow: 

* reproducible and auditable, 

* accurate, and 

* collaborative.  

The emphasis in this course will be on analytic methods, coding concepts, and programming practice that are universal; you will be able to apply them in whatever analytic setting you find yourself, and are independent of the tool you'll be using. 

In this course we will be primarily using the open source programming language R, with tangents into data analysis coding in Excel and Python.

Here's another course description, one that I really like, so (with the author's permission) I am including it here:

> Over the last decade there has been a revolution in statistical and scientific computing. Open source languages like R and Python have overtaken older (and expensive!) corporate software packages like SAS and SPSS, and there are now thousands of books and blog posts and other online resources with excellent tutorials about how to analyze pretty much any kind of data.

>This class will expose you to R—one of the most popular, sought-after, and in-demand statistical programming languages. Armed with the foundation of R skills you’ll learn in this class, you’ll know enough to be able to find how to analyze any sort of data-based question in the future.

<small>(from the Syllabus to [PMAP 8521: Program Evaluation for Public Service](https://evalf19.classes.andrewheiss.com/syllabus/#pep-talk), Andrew Heiss, Georgia State University)</small>



***

## Course Outline

**_subject to change_**

| Week      | Date | Topics   | Lesson |
|---        |:---  |:---      |:---:  |
|1          | 2020-02-29 | Why code? Why R? <br> Introduction to R, RStudio, and R Markdown <br> Programming foundations <br> The data science process and data wrangling  | &#8212; |
|2          | 2020-03-07 | Good coding habits <br> Tidy data <br> Importing and exporting data: part 1 <br> R Markdown: the next level | &#8212; |
|3          | 2020-03-14 | Exploratory data analysis: data visualization <br> Data wrangling: categorical variables & relational data <br> Excel: macros and VBA | &#8212; |
|4          | 2020-03-21 | Writing your own functions <br> An introduction to modeling <br> Importing and exporting data: part 2 | &#8212; |
|5          | 2020-03-28 | Modeling, forecasting and what-if scenarios (R and Excel) <br> Working with strings <br> Working with dates <br> R Markdown: moving beyond documents and notebooks | &#8212; |
|6          | 2019-04-04 | Plots, charts and other data visualization <br> Python: the other data science language <br> Where to from here? Other data analytics coding challenges | &#8212; |


#### Concordance: course objective to lesson topics

| Course objective      | Lesson topic   | Lessons |
|---        |:---  |:---:  |
|Perform basic data manipulations | Basic data manipulations <br> Working with dates <br> Working with strings | &#8212;  |
|Create variables <br> Calculate descriptive statistics <br> Perform basic logical formula functions <br> Group and ungroup data <br> Extract and combine data | Data wrangling | &#8212; | 
|Apply key concepts of variables, constants and functions | Programming foundations <br> Writing your own functions <br> | &#8212; | 
|Data Importing <br> Data Exporting | Importing and exporting data | &#8212; | 
| Create what-if scenarios | Modeling, forecasting, and what-if scenarios | &#8212; |

***

## Evaluation



### Class participation (marks: 20)

* attendance

* doing the readings

* asking questions and responding to the questions of others

* collaborating with other participants


### Weekly assignments (marks: 12 each, 48 total)

* Tour assignments, due Weeks 2 through 5.

* These four assignments will review the concepts introduced in that week's lesson and build on previous concepts.

* The assignments will be introduced and discussed at the end of the week's lesson; there may be time to work on the assignment in-class.

* There will be no "weekly assignment" introduced in week 5 and to hand in at Week 6, because you'll be working on your Capstone Project that week.

* **Due date:** Each assignment is due at 23:59 (11:59 pm) on the Thursday following the class; late assignments will be accepted until 8:00 am Saturday following class. Anything later than that will not be accepted, as we will review the assignment during Saturday's class.


### Additional optional stretch assignments (marks: 0)

* These _optional_ assignments will give you the opportunity for additional practice and to flex your developing coding muscles.

* They are optional.


### Capstone Project (marks: 30)

* A small project that will require the application of all of the concepts introduced

  - importing data
  
  - data wrangling
  
  - data modeling and summarization
  
  - communication (including visualization)

* The project will be introduced in Week 4.

* Some projects will be available for you to choose from, but you may also bring your own data.


***

## Pep Talk!

"Smart people ask stupid questions." (Source unknown)

Any language, computer or human, can be a challenge to learn. We bring our established ways of thinking, and another language won't always conform to those ideas. For example, French has gendered nouns—for example, _le pot_ (pot or drink) and _la peau_ (skin)—and English does not. For an English-speaker, this can be frustrating!

One of the most important developers of R packages (and co-author of our textbook), Hadley Wickham, was recently [quoted in an interview](https://r-posts.com/advice-to-young-and-old-programmers-a-conversation-with-hadley-wickham/):

>**It’s easy when you start out programming to get really frustrated and think, “Oh it’s me, I’m really stupid,” or, “I’m not made out to program.” But, that is absolutely not the case. Everyone gets frustrated.** I still get frustrated occasionally when writing R code. It’s just a natural part of programming. So, it happens to everyone and gets less and less over time. Don’t blame yourself. Just take a break, do something fun, and then come back and try again later.

><small>Source: [Advice to Young (and Old) Programmers: A Conversation with Hadley Wickham](https://r-posts.com/advice-to-young-and-old-programmers-a-conversation-with-hadley-wickham/), at [R-posts.com](https://r-posts.com/)</small>


## Some advice from people who took BIDA302 before...

People who have previously taken this course were asked "Imagine that time travel is possible...You have just been transported back four weeks to the day before this course started. What is one thing you would tell your past self about this course?" Here's some of their answers:

* It won’t be as scary as you think it will be.

* You’ll get better soon.

* Need to spend more time studying since the class is 6 hours a week, 1-2 hours a week outside class won’t be enough for a dinosaur like me.

* To do the homework on Saturday after class so you haven’t forgotten everything!

* **Reading the textbook will help you, use it.**

  - Review the data before starting to work with it. It helps to understand what the data is, how it might be used.

  - Review the material in the Saturday lesson as you will need it for the assignment.

  - If you start having to use functions you aren’t familiar with, you’re on the wrong track.

  - Keep it simple, and then add on as you go.

* Prepare to learn lots about R and RStudio. …And bring coffee!



***


**_Bonus mark_**

Congratulations! You read to the end of the Syllabus. 

For a single bonus mark, before 2020-03-05 11:59 PM PDT please email me the following:

* a picture of a geographic location (a building, city skyline, natural landscape, etc., real or imaginary) with a bit of information as to what the picture shows, and why you chose it.



-30-
