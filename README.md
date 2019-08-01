# How to Truly "Excel" at Data Analysis and Visualization: An Introduction to the R Programming Language

This introductory R course aims to teach participants without programming experience the basics of the R statistical programming language for reproducible data analysis. R is a freely available programming environment that is well-suited for common activities in data analysis including complex data manipulation, statistical analysis, automation, and publication-quality data visualization. We will introduce basic concepts of R programming as well as more generalizable best practices in working with laboratory data.

The goals for this course are for participants to be comfortable performing the following basic tasks on a data set:
- Import a csv, text, or Excel file
- Create a relevant subset of data for analysis
- Add columns to the data set based on calculations or manipulation of existing columns
- Calculate summary statistics for the entire data set and/or important subgroups of data
- Perform basic statistical tests on a data set
- Develop simple visualizations that summarize data such as barplots and scatterplots
- Produce a reproducible report so others can clearly understand and repeat an analysis

Instructors:
- Daniel Herman
- [Patrick Mathias](https://www.linkedin.com/in/pcmathias/)
- Joseph Rudolf

## Pre-course work/requirements

- A laptop (macOS, Windows, or Linux) with WiFi
  - Please confirm you can connect to the WiFi prior to class
- Please complete the following survey so we can better understand your R experience and what you want out of the course: [Pre Course Survey](https://forms.gle/rQhMoGregT7LzczC6)
- The program that we will be using to interact with R during the course is called RStudio. We will be using a cloud based RStudio server, hosted at [RStudio.Cloud](https://rstudio.cloud/), in our workshop. Our intent in using a cloud-based platform to minimize possible in-class setup issues.
- Please follow the instructions in [this presentation](https://github.com/pcmathias/AACC-2019-Introduction-to-R/blob/master/presentations/00%20-%20Setup_Cloud_Account.pptx) to setup an [RStudio.Cloud](https://rstudio.cloud/) account. 
<!---
- [Link](https://rstudio.cloud/spaces/19998/join?access_code=MVMM2UkHscHnpf%2FBa04Cb7e%2BBXnUi6g4QpFXVq6c) to RStudio.Cloud workspace
--->
   - *Note: Some older internet browsers may not be compatible with RStudio.cloud. See [this web page](https://support.rstudio.com/hc/en-us/articles/227449447-Supported-browsers-for-RStudio-Connect) for additional information.*
- While not required, we **highly** recommend installing RStudio Desktop on your laptop as well. See instructions below.

### Installing RStudio onto your own computer

Working with our cloud based RStudio instance will be the most straightforward way to proceed through the sessions. However, in the long term, you will need R and RStudio installed on your own computer in order to work on private or PHI containing data. You can find a video with step by step instructions for installing on Mac or PC by following the links below:

- [macOS Video](https://www.youtube.com/watch?v=GM88tYlEy_g) 
- [Windows Video](https://www.youtube.com/watch?v=JRKmZK5-6aE)

Please complete each step in the video in turn including the final step, installing the tidyverse packages.

## Accessing/interacting with the course content

There are multiple ways to access and interact with the content, depending on whether you choose to proceed through the workshop using the cloud based RStudio or one on your own laptop. 

1. If you choose to use the the cloud based RStudio instance, all the course content will be pre-loaded. 
2. If you would prefer to run RStudio on your own computer:
   * Download the course material from the course github [repository](https://github.com/pcmathias/AACC-2019-Introduction-to-R) as a \*.zip file from [here](https://github.com/pcmathias/AACC-2019-Introduction-to-R/archive/master.zip) 
   * Unzip the file to a convenient location (your desktop or documents folder)
   * When you open RStudio, set this location as your working directory 

## Original Contributions

The content for this course was originally developed for the 2019 [Pathology Informatics Summit](https://github.com/amromeo/api_r2019) workshop and some modifications were made for the University of Washington [Laboratory Medicine Core](https://github.com/pcmathias/LM-Core-Data-Analysis) curriculum. The original contributors and content they were responsible for were as follows:
- Joe Rudolf: Introduction to R & RStudio
- Patrick Mathias: Reproducible Reporting & Importing
- Amrom Obstfeld: Data Transformation & Exploratory Data Analysis
- Stephan Kadauke: Data Visualization
- Dan Herman: Summarization & Statistics

## Acknowledgments

All of the course instructors have previous experience implementing and executing R workshops at a variety of venues. The workshop we are presenting for the API community is in many ways a product of these past experiences. The workshop also integrates content, best practices, and lessons from a variety of educators in the R community. We would like to specifically acknowledge: 

- [MSACL Data Science 201](https://github.com/pcmathias/MSACL-intermediate-R-course), a course produced by Patrick Mathias and several collaborators, presented at the Mass Spectrometry: Applications to the Clinical Lab meeting.
- Stephan Kadauke's R workshop for Pathology trainees and faculty, developed at the Massachusetts General Hospital and the Hospital of the University of Pennsylvania
- Steve Master and Dan Holmes's AACC Introduction to R Workshop 
- [Data Science in the Tidyverse](https://github.com/AmeliaMN/data-science-in-tidyverse), a RStudio course with materials posted online
- [R for Data Science](http://r4ds.had.co.nz/index.html), the online textbook by Garrett Grolemund and Hadley Wickham, is invaluable in navigating the tidyverse and learning R in general
- Blog posts and documentation by [Jenny Bryan](https://github.com/jennybc) helped steer the project content and as well as some discussion about packages
- Amy Willis' [Advanced R Course repository](https://github.com/adw96/biostat561) as a resource for understanding content in a longer, advanced R course
- Keith Baggerly and Karl Broman's [Reproducible Research](https://github.com/kabagg/sisbid_2018_rr) module at the [Summer Institute in Statistics for Big Data](https://www.biostat.washington.edu/suminst/sisbid) - a big thank you to Keith Baggerly for all of his input and guidance!
- Greg Wilson's [Teaching Tech Together](http://teachtogether.tech/en/), which offers practical advice about teaching programming. 
- Claus Wilke's [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/), a compendium of Do's and Don'ts of data visualization. 
- Method validation and some other content has been borrowed from the [basic R course at AACC](https://github.com/pcmathias/AACC-Introduction-to-R)
