# Stat 131A - Spring 2019

- [Policies](syllabus/policies.md)
- [Staff](syllabus/staff.md)
- [Piazza](syllabus/piazza.md)

----- 


## Calendar

+ __Instructor:__ Gaston Sanchez
+ __Lecture:__ MWF 11:00-12:00pm 60 Evans
+ Tentative calendar (weekly topics), subject to change depending on 
the pace of the course.
+ Notes (:file_folder:) involves material discussed in class.
+ Reading (:book:) involves related chapters from __SticiGui__ text.


-----


## 0. Course Introduction, Data and Variables

- :card_index: __Dates__: Jan 22-25
- :paperclip: __Topics__: Understanding the concept of "data" for statistical analysis, the concept of variables, and the difference between qualitative and quantitative variables. Also, we'll discuss how to summarize information with frequency tables, and visual displays with bar-charts.
- :file_folder: __Notes__:
    + Welcome to Stat 131A (chalk and talk)
    + [What is data?](slides/istat-lec01-data-variables.pdf)
    + [Frequency tables and barcharts](slides/istat-lec02-barcharts.pdf)
- :book: __Reading__:
    + [Course policies](syllabus/policies.md) and [Piazza etiquette](syllabus/piazza.md)
    + [Chapter 3: Statistics](https://www.stat.berkeley.edu/~stark/SticiGui/Text/histograms.htm)
- :microscope: __Lab__: No lab
- :speaker: __To Do__: Please spend some time outside class to review the course policies, and piazza etiquette rules.
    + Install [__R__](https://cran.cnr.berkeley.edu/)
    + Install [RStudio](https://www.rstudio.com/products/rstudio/download/#download) Desktop (open source version, free)


-----


## 1. Summarizing Data Graphically and Numerically (part 1)

- :card_index: __Dates__: Jan 28-Feb 01
- :paperclip: __Topics__: Understanding histograms, how to read them, how to graph them, and what makes them different from bar-charts. Likewise, we'll talk about measures of center, their meanings, properties, and how to use them in practice. In addition, we'll discuss other summaries for describing distributions.
- :file_folder: __Notes__:
    + [Histograms, skeweness, and distributions](slides/istat-lec03-histograms.pdf)
    + [Frequencies and Histograms](demos/01-freqs-histograms.md) (demo)
    + [Measures of center](slides/istat-lec04-measures-of-center1.pdf)
    + [Using mean and median](slides/istat-lec05-measures-of-center2.pdf)
    + [Five-number summary and boxplots](slides/istat-lec06-spread-boxplots.pdf)
- :book: __Reading__:
    + [Chapter 3: Statistics](https://www.stat.berkeley.edu/~stark/SticiGui/Text/histograms.htm)
    + [Chapter 4: Measures of Location and Spread](https://www.stat.berkeley.edu/~stark/SticiGui/Text/location.htm)
- :microscope: __Lab__:
    + [Intro to R and RStudio](labs/lab01a-R-basics-questions.pdf) (Tu; due Jan-30)
    + [Histograms](labs/lab01b-histograms-questions.pdf) (Th; due Feb-01)
- :bulb: __Cheatsheet__: [RStudio cheat sheet](cheatsheets/rstudio-cheatsheet.pdf) and [R markdown cheat sheet](cheatsheets/rmarkdown-cheatsheet.pdf)
- :dart: __HW 01__: [Markdown and Histograms](hws/hw01-questions.pdf) (due Feb-03)


-----


## 2. Summarizing Data Graphically and Numerically (part 2)

- :card_index: __Dates__: Feb 04-08
- :paperclip: __Topics__: Having looked at measures of center, we now turn our attention to  measures of spread, their rationales, meanings, and properties. Also, we'll get a first contact with the normal curve, and its approximation for symmetric bell-shaped distributions.
- :file_folder: __Notes__:
    + [Measures of spread: Standard Deviation](slides/istat-lec07-spread-sd.pdf)
    + [Normal Curve](slides/istat-lec08-normal-curve.pdf)
    + Normal curve (demo)
- :book: __Reading__:
    + [Chapter 4: Measures of Location and Spread](https://www.stat.berkeley.edu/~stark/SticiGui/Text/location.htm)
    + [Chapter 23: Normal Curve](https://www.stat.berkeley.edu/~stark/SticiGui/Text/clt.htm)
- :microscope: __Lab__:
    + [Measures of center](labs/lab02a-centers-questions.pdf) (Tu; due Feb-06)
    + Measures of Spread (Th; due Feb-08)
- :bulb: __Cheatsheet__: [Base R](cheatsheets/base-r-cheatsheet.pdf)
- :dart: __HW 02__: [Descriptive Statistics](hws/hw02-questions.pdf) (due Feb-10)


-----


## 3. Scatterplots and Correlation

- :card_index: __Dates__: Feb 11-15
- :paperclip: __Topics__: Describing one variable at a time can be too limiting. However, we can enrich our analysis by studying whether two (quantitative) variables tend to be associated. Like in the univariate case, this can be done with pictures and numeric summaries: e.g. scatter plots and correlation coefficient.
- :file_folder: __Notes__:
    + [Scatter diagrams and correlation](slides/istat-lec09-scatterplots-correlation.pdf)
    + [More about correlation](slides/istat-lec10-more-about-correlation.pdf)
    + corr-coeff-diagrams (demo)
- :book: __Reading__:
    + [Chapter 5: Scatterplots](https://www.stat.berkeley.edu/~stark/SticiGui/Text/scatterplots.htm)
    + [Chapter 6: Association](https://www.stat.berkeley.edu/~stark/SticiGui/Text/association.htm)
    + [Chapter 7: Correlation](https://www.stat.berkeley.edu/~stark/SticiGui/Text/correlation.htm)
    + [Chapter 8: Computing the correlation coefficient](https://www.stat.berkeley.edu/~stark/SticiGui/Text/computeR.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Feb-13)
    + TBA (Th; due Feb-15)
- :bulb: __Cheatsheet__: [Data import cheat sheet](cheatsheets/data-import-cheatsheet.pdf)
- :dart: __HW 03__: TBA (due Feb-17)


-----


## 4. Regression (part 1)

- :card_index: __Dates__: Feb 18-22 _(Holiday Feb-18)_
- :paperclip: __Topics__: When the association between two variables meets certain requirements (e.g. linear association, homoscedasticity, football-shaped scatterplot) such a relationship can be further summarized with the so called _Regression Line_. Consequently, we'll spend time studying the basics of regression, the most (mis)used tool in statistics.
- :file_folder: __Notes__:
    + [Intro to Regression](slides/istat-lec11-regression-intro.pdf)
    + [Regression Line](slides/istat-lec12-regression-line.pdf)
    + heights-data (demo)
- :book: __Reading__:
    + [Chapter 9: Regression](https://www.stat.berkeley.edu/~stark/SticiGui/Text/regression.htm)
    + [Chapter 10: Regression Diagnostics](https://www.stat.berkeley.edu/~stark/SticiGui/Text/regressionDiagnostics.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Feb-20)
    + TBA (Th; due Feb-22)
- :dart: __HW 04__: TBA (due Feb-24)


-----


## 5. Regression (part 2)

- :card_index: __Dates__: Feb 25-Mar 01
- :paperclip: __Topics__: We'll continue the discussion of Regression, looking at diagnostics tools, RMS of residuals, the regression effect, and the famous regression fallacy.
- :file_folder: __Notes__:
    + regression-residuals (demo)
    + regression-strips (demo)
- :book: __Reading__:
    + [Chapter 11: Errors in Regression](https://www.stat.berkeley.edu/~stark/SticiGui/Text/regressionErrors.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Feb-27)
    + 5b: Review session (Th)
- :dart: __HW 05__: TBA (due Mar-03)
- :mortar_board: __MIDTERM 1__: Friday Mar-01


-----


## 6. Probability basics (theories, axioms, and rules)

- :card_index: __Dates__: Mar 04-08
- :paperclip: __Topics__: Statistics can be used for making decisions when we are faced with uncertainties. To do so, you need to learn some of the basic tools provided by Probability, the branch of Math that studies randomness. This part of the course gives you a general introduction to probability.
- :file_folder: __Notes__:
    + Probability: what is it?
    + [Probability concepts (part 1)](slides/istat-lec15-probability1.pdf)
    + [Probability concepts (part 2)](slides/istat-lec16-probability2.pdf)
- :book: __Reading__:
    + [Chapter 13: The Meaning of Probability](https://www.stat.berkeley.edu/~stark/SticiGui/Text/probabilityPhilosophy.htm)
    + [Chapter 17: Probability, Axioms and Fundamentals](https://www.stat.berkeley.edu/~stark/SticiGui/Text/probabilityAxioms.htm)
    + [Chapter 18: The Monty Hall Problem](https://www.stat.berkeley.edu/~stark/SticiGui/Text/montyHall.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Mar-06)
    + TBA (Th; due Mar-08)
- :dart: __HW 06__: TBA (due Mar-10)


-----


## 7. Two-Way tables, Box Models and Random Variables (part 1)

- :card_index: __Dates__: Mar 11-15
- :paperclip: __Topics__: We turn our attention to categorical variables. The objective is to study the relationship between two categorical variables while linking the concept of probability to relative frequencies. This is done via Two-way tables and its associated frequencies (e.g. marginal, conditional, and joint frequencies). We also use introduce the notion of Random Variables, and Box Models.
- :file_folder: __Notes__:
    + [Two-way tables](slides/istat-lec17-two-way-tables.pdf)
    + [Intro to Random Variables and box models](slides/istat-lec18-random-variables.pdf)
- :book: __Reading__:
    + [Chapter 19: Probability Meets Data](https://www.stat.berkeley.edu/~stark/SticiGui/Text/montyHallTest.htm) (Binomial Distribution)
    + [Chapter 20: Random Variables and Discrete Distributions](https://www.stat.berkeley.edu/~stark/SticiGui/Text/randomVariables.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Mar-13)
    + TBA (Th; due Mar-15)
- :dart: __HW 07__: TBA (due Mar-17)


-----


## 8. More Random Variables: Binomial and Normal Distributions

- :card_index: __Dates__: Mar 18-22
- :paperclip: __Topics__: We dive deep into two of the most famous probability distributions: the Binomial distribution, and the Normal distribution. We also introduce the concepts of expected value and standard deviation/error of tickets randomly sampled from box models.
- :file_folder: __Notes__:
    + [Binomial Distribution](slides/istat-lec18-binomial.pdf)
    + [Expected value and Standard error](slides/istat-lec20-expvalue-stderror.pdf)
    + [Normal Approximation](slides/istat-lec21-normal-approximation.pdf)
- :book: __Reading__:
    + [Chapter 21: The Long Run and the Expected Value](https://www.stat.berkeley.edu/~stark/SticiGui/Text/expectation.htm)
    + [Chapter 22: Standard Error](https://www.stat.berkeley.edu/~stark/SticiGui/Text/standardError.htm)
    + [Chapter 23: Normal Distribution](https://www.stat.berkeley.edu/~stark/SticiGui/Text/clt.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Mar-22)
    + TBA (Th; due Mar-24)
- :dart: __HW 08__: TBA (due Mar-24)


-----


## 9. Spring Recess

- :card_index: __Dates__: Mar 25-29
- :paperclip: __Topics__: _Recharge your batteries_


-----


## 10. Sampling and Chance Errors (part 1)

- :card_index: __Dates__: Apr 01-05
- :paperclip: __Topics__: A central topic in statistics has to do with Inference: the problem of obtaining information about a population without examining every unit in the population—--only a random sample from the population. Obviously, random samples vary, so we need to understand how much they vary and how they relate to the population.
- :file_folder: __Notes__:
    + [Intro to sampling](slides/istat-lec22-sample-surverys.pdf)
    + [Sample design](slides/istat-lec23-sample-designs.pdf)
    + [Chance Errors](slides/istat-lec24-chance-errors-sampling.pdf)
- :book: __Reading__:
    + [Chapter 24: Sampling](https://www.stat.berkeley.edu/~stark/SticiGui/Text/sampling.htm)
    + [Chapter 25: Estimating Parameters from SRS](https://www.stat.berkeley.edu/~stark/SticiGui/Text/estimation.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Apr-03)
    + TBA (Th; due Apr-05)
- :dart: __HW 09__: TBA (due Apr-07)


-----


## 11. Sampling and Chance Errors (part 2)

- :card_index: __Dates__: Apr 08-12
- :paperclip: __Topics__: Recall that one of the goals of inference is to draw a conclusion about a population on the basis of a random sample from the population. This involves using a probability model that describes the long-run behavior of sample measurements. In this part of the course we continue to develop the probability machinery that underlies inference (i.e. drawing conclusions from sample data).
- :file_folder: __Notes__:
    + [Sample Distributions](slides/istat-lec25-sampling-distributions.pdf)
    + More Sampling distributions (chalk and talk)
    + Tentative Review
- :book: __Reading__: 
    + [Chapter 25: Estimating Parameters from SRS](https://www.stat.berkeley.edu/~stark/SticiGui/Text/estimation.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Apr-10)
    + 10b: Review Session
- :dart: __HW 10__: TBA (due Apr-14)
- :mortar_board: __MIDTERM 2__: Friday Apr-12


-----


## 12. Confidence Intervals

- :card_index: __Dates__: Apr 15-19
- :paperclip: __Topics__: In inference, we use a sample to draw a conclusion about a population. Two types of inference are the focus of our work in this course: 1) estimate a population parameter with a confidence interval; 2) test a claim about a population parameter with a hypothesis test. The purpose of a confidence interval is to use a sample statistic (e.g. proportion, mean) to construct an interval of values that we can be reasonably confident contains the population parameter.
- :file_folder: __Notes__:
    + [Confidence Intervals for Proportions](slides/istat-lec26-accuracy-percentages.pdf)
    + [Confidence Intervals for Means](slides/istat-lec27-accuracy-averages.pdf)
    + [Introduction to Hypothesis Tests](slides/istat-lec28-hypothesis-tests.pdf)
- :book: __Reading__:
    + [Chapter 26: Confidence Intervals](https://www.stat.berkeley.edu/~stark/SticiGui/Text/confidenceIntervals.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Apr-17)
    + TBA (Th; due Apr-19)
- :dart: __HW 11__: TBA (due Apr-21)


-----


## 13. Hypothesis Tests

- :card_index: __Dates__: Apr 22-26
- :paperclip: __Topics__: Now we look more carefully at the second type of inferential task: testing a claim about a population parameter. We begin our discussion of hypothesis tests with research questions that require us to test a claim. Later we look at how a claim becomes a hypothesis.
- :file_folder: __Notes__:
    + [One sample Z-test](slides/istat-lec29-one-sample-z-test.pdf)
    + Hypothesis test for one Proportion
    + Hypothesis test for one Mean
- :book: __Reading__:
    + [Chapter 27: Hypothesis Testing](https://www.stat.berkeley.edu/~stark/SticiGui/Text/testing.htm)
- :microscope: __Lab__:
    + TBA (Tu; due Apr-24)
    + TBA (Th; due Apr-26)
- :dart: __HW 12__: TBA (due Apr-28)


-----


## 14. Hypothesis Tests

- :card_index: __Dates__: Apr 29-May 03
- :paperclip: __Topics__: More about tests of significance.
- :file_folder: __Notes__:
    + [One sample t-test](slides/istat-lec30-one-sample-t-test.pdf)
    + [Two sample z-test](slides/istat-lec31-two-sample-avgs.pdf)
- :book: __Reading__:
    + [Chapter 27: Hypothesis Testing](https://www.stat.berkeley.edu/~stark/SticiGui/Text/testing.htm)
    + [Chapter 31: Chi-Squared Test](https://www.stat.berkeley.edu/~stark/SticiGui/Text/chiSquare.htm)
- :microscope: __Lab__:
    + TBA (Tu; due May-01) 
    + TBA (Th; due May-03)


-----


## 15. RRR Week and Final Exam

- :card_index: __Dates__: May 06-10
- :paperclip: __Topics__: Prepare for final examination
- :file_folder: __Notes__:
    + No lecture. Instructor will hold OH (in 309 Evans)
- :mortar_board: __FINAL__: May Tu 14, 7-10pm, Rooms TBA
    + See announcement about the final test on bCourses
