---
layout: default
---

<div class = "uk-container uk-container-small">
  
<br><br>

## Topics
{:.no_toc}
* TOC
{:toc}



# Course Overview

Welcome to Intro to Data Science for the Social Sector. This is a broad overview course designed to expose you to common and useful open source tools in the field. 

A few notes about the semester:


#### In-Person Review Sessions

The course can be completed entirely online, but I will also offer a weekly face-to-face review sessions if you prefer to ask questions or discuss content in a classroom. 



#### Rules for Success

Learning a new skill like R programming is never painless, but you can follow a few simple rules to succeed at this course:

* Find a study group.
* Work until you get stuck, then post a question to the [discussion forum](https://ds4ps.github.io/course_website/discussions/).
* [Schedule office hours](https://calendly.com/lecy/15min) when needed.
* Attend weekly review sessions
 

#### Assignments

Your grade is comprised of the following:
 
* 60% - Weekly labs  
* 20% - Final project 
* 20% - Discussion boards 

Labs will give you practice with the key concepts and functions of the week. They are graded pass-fail and you get to drop one lab (chances are you will have one rough week this semester). To pass you need to get at least half of the questions correct and demonstrate that you understand the material. 

This grading system is designed as a way for you to focus on the big picture each week and not worry if a specific function or model is not working properly. Computer languages can be unforgiving in the sense that one minor error can prevent the program from running. 

Learning a programming language is a lot like learning a natural language in that it is easy to become conversant enough to find your way around a city and order some food at a restaurant, but much harder to become fluent. The goal is for you to become conversant in R by the end of the semester so that you can begin using tutorials and discussion forums to further your journey.

Discussion boards will be used to reflect upon case studies of data science tools in practice. The final project will require you to practice skills from the semester by building a basic dashboard.


#### Textbook

You are not required to purchase a textbook. I have referenced several useful reference texts in the syllabus, many of which are available free online.

The text available on this website is a set of lecture notes created using Markdown documents so that you can easily copy and paste code from the examples, or borrow document formats that you like. All of the raw files are available on GitHub, and can be easily accessed by clicking on the "edit" link on each page.

 
<br>
----------
<br><br>
 
 

# Unit 01 - Introduction to Data Science 

## Data Science Applications in the Social Sector

It is always helpful to motivate a topic with an example. I like this case study of change that occurred when the Philadelphia police began transitioning from managing a department using instinct of senior officers to using data to identify areas of high need and most effective practices.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZJNESMhIxQ0?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


## What is Data Science? 

"A data scientist is a person who should be able to leverage existing data sources, and create new ones as needed in order to extract meaningful information and actionable insights. These insights can be used to drive business decisions and changes intended to achieve business goals... ‘The Perfect Data Scientist’ is the individual who is equally strong in business, programming, statistics, and communication."

FROM: [ What Is Data Science, and What Does a Data Scientist Do? ](https://www.innoarchitech.com/what-is-data-science-does-data-scientist-do/)

"Universities can hardly turn out data scientists fast enough. To meet demand from employers, the United States will need to increase the number of graduates with skills handling large amounts of data by as much as 60 percent."

FROM: [Data Science: The Numbers of Our Lives, The New York Times](https://www.nytimes.com/2013/04/14/education/edlife/universities-offer-courses-in-a-hot-new-field-data-science.html)

“Data Scientists identify complex business problems whilst leveraging data value. They work as part of a multidisciplinary team with data architects, data engineers, analysts and others.”

FROM: [Data Scientist Career Pathways in Government](https://github.com/ukgovdatascience/data_scientist_career_path/blob/master/index.md).


## Why R?

This course is organized around learning the foundations of programming in R. Although there are several good choices for languages that specialize in data analysis, R has advantages:

* It is completely free and open source.
* It has a large and active user community.
* R Studio has integrated many tools from the 'data science ecosystem' so that lots of tasks can be done with a single language, making the return on time spent learning R much higher.

For some background information on R, read the New York Times story: [Data Analysts Captivated by R’s Power](https://www.nytimes.com/2009/01/07/technology/business-computing/07program.html). Or Check out this 1-minute explainer video:

<br>

<iframe src="https://player.vimeo.com/video/180644880" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<br>

You will find this background information helpful as you start using R:

* [ Helpful Vocabulary ](https://github.com/DS4PS/Data-Science-Class/raw/master/HANDOUTS/Helpful%20Programming%20Vocabulary.pdf)
* [ Base R Cheat Sheet ](https://www.rstudio.com/wp-content/uploads/2016/05/base-r.pdf)

See the [Resources](https://ds4ps.github.io/course_website/resources/) tab for some additional information about R and R Studio.




## Week 1 Assignments:



**PART I**

Install R and [R Studio](https://www.rstudio.com/products/rstudio/download/) on your machine. See the [Resources](https://ds4ps.github.io/course_website/resources/) tab for tips.

Install [Pandoc](http://pandoc.org/installing.html) if you would like to create PDF reports.



**PART II - Create a Markdown Bio**

Create a short bio for the class. Each question requires a different type of text or graphic. Use [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to format each answer correctly.

1. Add your name to a **Header 1** element called, "Bio of YOUR NAME".
2. Add a **picture** of yourself to the bio.
3. Write a short **paragraph** about why you joined this class.
4. Create a **list** of three fun facts about yourself. 
5. Add a **link** to the website of your degree program of study at ASU.
6. OPTIONAL: Embed a YouTube **video** of a weird song that is currently in your music playlist. 

The full lab instructions are available [HERE](https://ds4ps.github.io/Data-Science-Class/LABS/lab-01-instructions.html).

[ Download the Rmd Template ](https://cdn.rawgit.com/DS4PS/Data-Science-Class/master/LABS/lab-01-template.Rmd)


<br>
----------
<br><br>




# Unit 2 - Functions and Vectors

**Aug 26-Sept 2** 

By the end of this unit, you will be able to:
* Use functions in R.
* Select appropriate data types.
* Change data types through casting.


#### Key Concepts

* functions()
* arguments
* assignment
* vectors
* objects
* data types
  * numeric
  * charactor
  * factor
  * logical
* casting


## Readings

Course text, [CH2: Functions](https://ds4ps.github.io/Data-Science-Class/TEXTBOOK/docs/functions.html)  [ Lecture ]()  
Course text, [CH3: Data Structures](https://ds4ps.github.io/Data-Science-Class/TEXTBOOK/docs/data-structures.html)  

For additional material, check out:

Teetor, P. (2011). [R cookbook: Proven recipes for data analysis, statistics, and graphics.](http://www.bagualu.net/wordpress/wp-content/uploads/2015/10/R_Cookbook.pdf) " O'Reilly Media, Inc.". **CH 5.2-5.5**


## Week 2 Assignments

You have one lab and one discussion topic this week:

[ Lab 02 - Functions and Vectors ](https://ds4ps.github.io/Data-Science-Class/LABS/lab-02-instructions.html)

[ Discussion Topics ](https://ds4ps.github.io/course_website/assignments/)

Note the due date on the lab has been changed to Sunday, September 2nd.


<br>
----------
<br><br>



# Unit 3 - Business Logic
**Aug 31 - Sept 7**

By the end of this unit, you will be able to:
* Express business cases as statements in R using logical operators.
* Use operators to break your data into relevant groups. 


<br><br><br><br>

</div>
