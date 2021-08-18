# r-bootcamp-fall-2021

Materials for the August 2021 R bootcamp at UC Berkeley. See here for information about the bootcamp, including logistics, how to get the course content, and how to install the software you need for the bootcamp on your laptop.

All content is available here, though we'll be making edits through the start of the event.

Co-trainers: UC Berkeley Statistics and the D-Lab.

## Description

### Overview

This is the website for the ninth annual R bootcamp at Berkeley. The bootcamp will be an intensive two-day introduction to R using RStudio. Topics will include:

 * R basics - reading and manipulating data, working with R data objects, doing calculations, making plots
 * programming in R
 * doing data analysis / data science / statistical work in R
  * more advanced topics: efficiency, object-oriented programming, advanced graphics, batch jobs, parallel processing

No prior experience with R is expected, but some familiarity with programming concepts such as variables, loops, if-then-else statements, functions, etc. will be helpful.

## Logistics - when, where, and how

Physical location: [Valley Life Sciences Building (VLSB)](https://www.berkeley.edu/map) Room 2050 (Chan Shun Auditorium), Berkeley campus. Please enter VLSB from the east entrance. This is the door facing California Hall (which is up the hill) and the opposite side of the building from downtown Berkeley/BART. 

Virtual location: See email or Piazza for the links. Note that track 2 will be entirely virtual.

Time: 
  - Saturday, August 21, 8:15 am - 5 pm
  - Sunday, August 22, 9 am - 4:30 pm

We'll start formally on Saturday morning at 8:30 am, but please plan to get here by 8:15 so you can sign in and get settled. And if you need help with any software installation please come at 8 am.

Note that street parking in Berkeley near campus on Saturdays is generally subject to two hour limits.

In the past, we've generally provided snacks during breaks. Because of various coronavirus-related limitations, we won't be able to do that this year. Please bring your own drinks and snacks for breaks and please eat only outside during the breaks.

You will probably want to [make sure you can use the campus WiFi (EduRoam)](https://berkeley.service-now.com/kb_view.do?sysparm_article=KB0013807) in advance of the event. But if you need wireless access as a guest (i.e., you don't have a CalNet ID), connect to 'CalVisitor'.

## Track 2 information

Some of you on Saturday afternoon and Sunday afternoon will opt to join the second track to revisit and reinforce material from the morning sessions at a more relaxed pace. **The second track will only be offered virtually.**

You can certainly participate in-person either morning and then join virtually in the afternoon. If so, you may want to head home or somewhere else quiet during the lunch break. You can also bring headphones and simply use the hallway in VLSB, though I'm not sure how easy it will be to find a comfortable spot.

## Health information

Vaccination requirements will follow [campus requirements](https://uhs.berkeley.edu/requirements/covid19), so essentially everyone should be vaccinated. In particular, those of you arriving from another country should carefully examine these requirements, which will determine if you can attend the bootcamp in person.

Facial coverings are required while inside buildings on campus, per [recent campus masking policy](https://coronavirus.berkeley.edu/return-to-campus/face-coverings/). 

The bootcamp will be a large room where there is some ability for participants who wish to spread out to spread out. 

## Preparing for the course - course content

Course content is available through Github. Please download a copy of the course materials before arriving at the bootcamp using one of the two options below (if you're familiar with Git you'll also know how to do this by cloning the repository):

  1) open RStudio. Go to “File→New Project” and select “Version Control” and “Git”. Enter 'https://github.com/berkeley-scf/r-bootcamp-fall-2021' as the “Repository URL” and click “Create Project” (you can choose the directory in which to place the project with the “Create project as subdirectory of” option). It should create a “r-bootcamp-fall-2021” directory with all of the materials within whichever directory you chose. To open one of the R Markdown files, go to the lower right panel, click on 'Files', then 'r-bootcamp-fall-2021', then 'modules' and finally click on the .Rmd file of interest. It will open in the upper left panel.

  2) Alternatively, simply download a zip file containing all the content at https://github.com/berkeley-scf/r-bootcamp-fall-2021/archive/main.zip.

Here is the [schedule for the main track of the bootcamp](https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/schedule/schedule.pdf). We will also offer a second track that allows those first encountering R or programming to have time for more intensive practice with the initial material. Here is the [schedule for the second track](https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/schedule/schedule-track2.pdf). After lunch on the first day you'll have the opportunity to decide whether you want to stay with the main track or attend the second track. You do NOT need to decide in advance.

We recommend that you take a look at the syllabus and the background module (https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/modules/module0_induction.html) in advance to get a sense for what we'll cover. And for those of you with absolutely no experience with R, it will help with your learning curve if you try to play around with R using the material in (https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/modules/module1_basics.html) beforehand. Alternatively, if you have absolutely no experience with R or similar languages (e.g., Python, MATLAB), you might check out [Swirl](https://swirlstats.com).

For the presentation materials (including embedded demo code), see the html files in *modules*. The *_slides_* files have individual pages, while the other html files are one continuous page per module. To run the demo code, open the .Rmd file for the module in RStudio. You can then run individual chunks of code.

## Preparing for the course - software installation

Please come with a fully-charged laptop (Mac, Windows, or Linux are all ok) with R, RStudio, and Git installed. RStudio and Git are optional but highly recommended. 

To install the software, it's best if you can install software directly on your laptop.

  - Install the following directly on your laptop:
  
      - R [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/install/RandRStudioInstall.html)
      - RStudio (optional but highly recommended) [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/install/RandRStudioInstall.html)
      - Git (optional but recommended for obtaining course content) [(details here)](https://htmlpreview.github.io/?https://github.com/berkeley-scf/r-bootcamp-fall-2021/blob/main/install/gitInstall.html)

Alternatively, IF INSTALLING ON YOUR LAPTOP FAILS, the following is an alternative way to access R and RStudio through a browser:

  - Please use your CalNet ID and password to login [here](https://r.datahub.berkeley.edu). Once logged in, you should be in an RStudio session in the browser. At this point you can get a copy of the bootcamp files that your RStudio session can access by following instruction #1 above under the section "Preparing for the course - course content".

Note that our ability to troubleshoot R or RStudio installed directly on your machine is limited (particularly in Windows). We'll try to help, but if we run into roadblocks, we'll direct you to the browser option.

## Course Discussion and Questions

Please ask questions both during the presentations and during the breakout sessions. 

- Questions from those attending in person can be asked to the presenter or to the circulating bootcamp assistants.
- The [online discussion forum on Piazza](https://piazza.com/berkeley/fall2021/rbootcampfall2021) for discussion and answering questions during (and before) the bootcamp.
- The [Zoom virtual front desk](https://dlab.berkeley.edu/frontdesk) for virtual 'in-person' help during the hours of the event. This is intended primarily for virtual participants.

If you need to contact us directly with an administrative question you can email r-bootcamp@lists.berkeley.edu.
