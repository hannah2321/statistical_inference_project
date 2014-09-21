Statistical Inference Course Project
=============================

Coursera &amp; John Hopkins Data Science Specialization; Course 6: Statistical Inference

Week 3: Course Project
----------------------------

This is the project for the statistical inference class. In it, you will use simulation to explore inference and do some simple inferential data analysis. The project consists of two parts:

1. Simulation exercises.
2. Basic inferential data analysis.

You will create a report to answer the questions. Please use knitr to create the reports and convert to a pdf. (I will post a very simple introduction to knitr). Each pdf report should be no more than 2 pages with 3 pages of supporting appendix material if needed (code, figures, etcetera). 

Part 1
----------------------------
The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also also 1/lambda. Set lambda = 0.2 for all of the simulations. In this simulation, you will investigate the distribution of averages of 40 exponential(0.2)s. Note that you will need to do a thousand or so simulated averages of 40 exponentials.

Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponential(0.2)s.  You should

1. Show where the distribution is centered at and compare it to the theoretical center of the distribution.
2. Show how variable it is and compare it to the theoretical variance of the distribution.
3. Show that the distribution is approximately normal.
4. Evaluate the coverage of the confidence interval for 1/lambda: X¯±1.96Sn√.

Part 2
----------------------------
Now in the second portion of the class, we're going to analyze the ToothGrowth data in the R datasets package. 

1. Load the ToothGrowth data and perform some basic exploratory data analyses 
2. Provide a basic summary of the data.
3. Use confidence intervals and hypothesis tests to compare tooth growth by supp and dose. (Use the techniques from class even if there's other approaches worth considering)
4. State your conclusions and the assumptions needed for your conclusions. 
