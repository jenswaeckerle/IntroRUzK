# IntroRUzK
Welcome to the R Tutorial IntroRUzK. This package was developed by political scientists at the University of Cologne. 
The aim of the package is to teach R to students with a self-learning module, so they can go through the material on their own computer at their own pace.
The examples in this course are from political science, but no prior knowledge is needed to follow along.
There are quizzes and coding exercises included in the tutorial, which will be useful to check progress.

Steps:
1. Download R (https://cran.r-project.org/)
2. Download RStudio (https://posit.co/download/rstudio-desktop/)
3. Install the package "devtools", which is needed for the package. After opening RStudio, copy the following code in the console and hit enter:
```
install.packages("devtools")
```
5. Install this tutorial by running the following code in the same way:
```
devtools::install_github("jenswaeckerle/IntroRUzK")
```
6. Start the first lesson:
```
learnr::run_tutorial("1_Intro_R", "IntroRUzK")
```
