# IntroRUzK
Welcome to the R Tutorial IntroRUzK. This package was developed by political scientists at the University of Cologne. 
The aim of the package is to teach R to students with a self-learning module, so they can go through the material on their own computer at their own pace.
The examples in this course are from political science, but no prior knowledge is needed to follow along.
There are quizzes and coding exercises included in the tutorial, which will be useful to check progress.

To start the course, please follow these steps:
1. Download R (https://cran.r-project.org/) and install it. Get the newest version that fits your operating system. You don't have to ever open R, just download it.
2. Download RStudio (https://posit.co/download/rstudio-desktop/) and install it. Again, get the newest version that fits your operating system.
3. Open RStudio.
4. Install the package "devtools", which is needed for the course. After opening RStudio, copy the following code in the console and hit enter. The installation will take a while, during which there is a bunch of red text flashing through the console. Don't panic. It's fine.
```
install.packages("devtools")
```
5. Install this tutorial by running the following code in the same way. Again, there will be red texts, which looks like errors, but are not (hopefully).
```
devtools::install_github("jenswaeckerle/IntroRUzK")
```
6. Start the first lesson:
```
learnr::run_tutorial("1_Intro_R", "IntroRUzK")
```
