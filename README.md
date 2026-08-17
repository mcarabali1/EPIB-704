<img src="title.png" width="500"/>

# EPIB 704: Doctoral Level Epidemiologic Methods I

_Please note that this page is updated every teaching/academic year with new resources_

**Instructor:** Mabel Carabali.

**Schedule:** Tuesdays and Thursdays (08:35 -10:25 AM).

-   First day of class: Sept 1st, 2026.
-   Last day of class: December 1st, 2026.

**Teaching Assistants:**

-   Sammy Lowe
-   TBC

**TA HOURS**
- TBC

# Course Description

This is a first semester doctoral level course in epidemiologic theory and the estimation of epidemiologic effect measures and their confidence intervals in a variety of different study designs. This course places an emphasis on causal inference concepts and its distinction from, and yet simultaneously dependency, on statistical models. The course will also emphasize the limitations of mainstream null hypothesis statistical significance (NHST) paradigm and encourage the recognition of the value of an estimation (Bayesian) paradigm for optimal inferences.

## Goals

The overarching goal is to establish and strengthen the foundation of epidemiological knowledge, by providing the basis of epidemiology, addressing fundamental and advanced aspects of descriptive epidemiology, causal inference, and data analysis tied to the identification of best practices given the numerous study designs.

## Objective

The objective of EPIB 704 is to provide students with a **deeper theoretical understanding** of the foundations of epidemiology some and empirical tools for data handling, data analysis, critical thinking and interpretation of the epidemiological inference. This course is also an entry point for advanced epidemiology (e.g., advanced knowledge of traditional biases), specially an introduction to modern methods. Hence, the emphasis on keep it up with the literature. EPIB 704 will equip student with strategies to:

1) identify common threats of the validity or biases, 

2) identify and interpret their effects in the measurement of associations, and 

3) identify opportunities to investigate, correct, and address these biases. 

## Instructional Methods

The course will have a “hands-on” approach whereby the various key statistical concepts covered will be illustrated by computer coding, to allow standard and new calculus for modern epidemiologic methods. Counting has historically been the essential background to epidemiologic research and remains so in the $21^{st}$ century but is now often best accomplished by simulation and sampling of posterior probability distributions. Examples of the required computing code will be extensively provided. 

Attention will also be given to exploratory data analysis (tabular and graphical), data interpretation, critical examination of assumptions and reproducible research. Students will focus mainly on cumulative incidence measures for categorical outcomes, with attention to model checking and screening for confounders and effect measure modifiers. Regression models covered will include linear, logistic, Poisson, survival, and if time allows, meta-analytical models. Experimental and quasi-experimental designs will be discussed. Other topics that the course will touch on include attributable fractions, selection bias, measurement error, model building and sensitivity analyses, bootstrapping, matched data, and missing data.

## Reference Textbooks

1.  **What if?** by Miguel Hernán and James Robins, available here: <https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/> (Chapters 1-11)
2.  **Modern Epidemiology** by Timothy L. Lash, Tyler J. VanderWeele, Sebastien Haneuse, Kenneth J. Rothman, available at the McGill Library here (General reference appropriate for most program courses) <https://mcgill.on.worldcat.org/oclc/1236198056>
3.  **Regression and Other Stories** by Andrew Gelman, Jennifer Hill, and Aki Vehtari, available here: <https://users.aalto.fi/~ave/ROS.pdf>

-   If you want a deeper dive into Bayesian statistics, we suggest as an optional resource the excellent:

4.  **Statistical rethinking: a Bayesian course with examples in R and Stan** by Richard McElreath available at the McGill Library here: <https://mcgill.worldcat.org/title/statistical-rethinking-a-bayesian-course-with-examples-in-r-and-stan/oclc/1145123627&referer=brief_results> (Chapters 1-10).

-   Associated website: <https://xcelab.net/rm/statistical-rethinking/> and YouTube lectures [here](https://youtube.com/playlist?list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus).
-   Free electronic versions of all these books are available online but, depending on your financial situation, it may be worthwhile for you to invest in your own copies.
-   Other readings will be assigned each week from published journal articles.

# Lecture Schedule and Slides 

We have pre-selected a list of topics to go through the 13 weeks-long course. Each lecture is aimed at addressing specific epidemiological concepts, addressing both theoretical and analytic/practical aspects. At the beginning of each lecture/topic I will present the learning objectives and expectation. Here you will find a list of the (tentative) Lectures. The recommended readings and links to other resources will be posted on MyCourses by the start of the academic semester.

**To be updated**

# Data for Assignments 

Data for assignments can be found in the folder: [EPIB-704
/EPIB704_HW_data_2025/](https://github.com/mcarabali1/EPIB-704/tree/main/EPIB704_HW_data_2025) or in the overall data folder [/EPIB-704/tree/main/data](https://github.com/mcarabali1/EPIB-704/tree/main/data) folder. 
We have three options for you to import the assignments datasets into R:

- Option 1: Install our epib.704 package:
  - a) First, install the remotes package: `install.packages("remotes")`
  - b) Then, install the epib.704.data package: `remotes::install_github("mcarabali1/epib.704.data")`
  - c) Select and load the respective dataset by using `epib.704.data::datasetname` 

- Option 2: Install them directly in R using their URL:
  - a) Assign the df URL to an R object: `urlfile <- "https://raw.githubusercontent.com/mcarabali1/EPIB-704/main/data/covidkenya.csv"`
  - b) Import the df into R: `mydata <- read.csv(url(urlfile))`

- Option 3: Download the files directly from the repository onto your computer and import them into R.
