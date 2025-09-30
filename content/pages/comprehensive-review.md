---
content_type: page
description: 'This document provides a review for the final exam. '
draft: false
title: Comprehensive Review
uid: fbb3296f-7c11-431e-a51a-9dc9744c53e1
---
## Short Questions

### Question 1

You realize your wallet is missing. You have either left it in the office or at a friend's place. It seems very likely that your friend would have texted you by now if you had left it at her place. You know it is unlikely that someone in the office would have tracked you down by now if you had lost it there. You have not been contacted.

What other information do you need in order to compute the probability that you left it in the office? Select all that apply and select "none of the above" if none of the choices can be used to compute the probability that you left it in the office.

1. the conditional probability that you left it at your friends
2. the conditional probability that you left it in the office
3. the prior probability that you left your wallet in the office
4. none of the above.

### Question 2

True or false? The Poisson distribution is a special case of the exponential distribution.

### Question 3

Consider a \\(\mathcal{B}(n, p)\\) and a \\(\mathcal{H}(A, B, n)\\) where \\(p=A/(A+B)\\). Which of the following statements is true? Select all that apply.

1. The variance of the binomial is always smaller than the variance of the hypergeometric.
2. The variance of the hypergeometric is always smaller than or equal to the variance of the binomial.
3. The relative sizes of the variances depend on the choice of both \\(n\\) and \\(p\\).
4. The variance of the binomial is always smaller than or equal to the variance of the hypergeometric.

### Question 4

True or false? Knowing the distribution of the test statistic under the null allows you to calculate (the probability of a type I error) and (the probability of a type II error).

### Question 5

Suppose that judges can decide to whom they give a GPS bracelet when individuals who have been arrested for a crime are released on bail (pending judgement).

Separately, a researcher runs an RCT for the impact of bracelets: people who are released on bail are randomly assigned to receive a bracelet or not. She finds that the bracelet reduces the probability of committing a crime while on bail by 5 percentage points (and this difference is significant).

Another researcher obtains a separate data set on the regular program (where the judge can decide whether or not to give the bracelet), that has many variables about the people who were arrested (including whether or not they were given a bracelet when released), and runs a machine learning algorithm to find out what predicts whether someone will commit a crime while on bail. They find that the bracelet tends to predict **greater** recidivism ("recidivism" means relapse into criminal behavior)

True or false? This implies that one of the two studies must be incorrect. 

## Long Question 1

You are interested in doing a project on jail sentences and recidivism. You find publicly available data listing plea deals and court decisions resulting in jail sentences for Middlesex County, Massachusetts. The list contains de-identified information on offense, sex, age, and prison of incarceration. You scrape the data and perform some preliminary analysis. You wish to contact the prisoners and ask each to participate in a survey. You then survey those who are willing and analyze the resulting data.

### Question 6

You must obtain approval from your IRB before \_\_\_\_\_\_\_\_\_\_\_\_\_\_.

1. You administer your survey.
2. You do any preliminary analysis.
3. You contact the prisoners.
4. You scrape the data.

### Question 7

Suppose you conclude, later in continuing research, that recidivism (whether released prisoners commit additional crimes) is a function of length of original sentence, \\(S\\), distance of prison from hometown, \\(D\\), and sex of offender, (\\(M\\) =1 if male). In particular, the probability of recidivism, P(R), is \\(S/32+D/40+0.1M\\)*.* [![](file:///C:/Users/CHERYL~1/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif)](https://www.codecogs.com/eqnedit.php?latex=S%2F32%20%2B%20D%2F40%20%2B%200.1M.#0)Suppose also that \\(S\\) follows a uniform distribution \\(U(1,15)\\); \\(D\\) follows an exponential distribution \\(\exp(0.05)\\); and 80% of offenders are male.

What is the expected recidivism rate?

## Long Question 2—Prof. Ellison's Commute

Sara Elison needs to commute to MIT every day. She currently lives near campus, but is considering moving to a place near Fenway Park (Boston's baseball stadium). Her colleagues who live near there tell her that the commute from the office to the Fenway is independent across days and follows a \\(\mathcal{N}(20,9)\\)[![](file:///C:/Users/CHERYL~1/AppData/Local/Temp/msohtmlclip1/01/clip_image014.gif)](https://www.codecogs.com/eqnedit.php?latex=%7B%5Ccal%20N%7D(20%2C9)#0) (where 20 is the average commute and 9 is the variance) on days where there is a home game at Fenway and \\(\mathcal{N}(12,4)\\)[![](file:///C:/Users/CHERYL~1/AppData/Local/Temp/msohtmlclip1/01/clip_image016.gif)](https://www.codecogs.com/eqnedit.php?latex=%7B%5Ccal%20N%7D(12%2C4)#0) (where 12 is the average commute and 4 is the variance) on other days.

### Question 8

What is the probability that the commute on a particular game day exceeds 22 minutes?

### Question 9

What is the probability that all commutes on a particular 3-game homestand (3 games played at Fenway) exceed 22 minutes?

### Question 10

What is the probability that the commute on a particular game day exceeds the commute on a particular non-game day?

## Long Question 3—Scrabble Pizza Party

You and your friend decide to throw a Scrabble pizza party. You don't know how many pizzas to order, so you want to obtain an estimate of slices each person would eat. You perform a poll of ten randomly selected patrons to see how many slices they each ate. Their responses are denoted \\(X_i, i= 1, …, 10\\), and

\\(\bar{X}=\frac{1}{10}\sum_{i=1}^{10}X_i=4.3\\)

\\(s^2=\frac{1}{9}\sum_{i=1}^{10}(X_i-\bar{X})^2=2.7\\)

Assuming that the \\(X_i\\)s are *i.i.d.* normal, construct a 95% confidence interval for the mean of the \\(X_i\\)s. Enter the lower and upper bounds on the interval \[a,b\].

*Please round your answer to 2 decimal points.*

Lower bound **a**:

Upper bound **b**:

### Question 12

How many patrons would you have had to poll to limit the width of the confidence interval to one slice?

*Please round your answer **up** to the nearest whole number.*

### Question 13

Suppose your friend gives you the additional information that the s have a uniform distribution on instead. Unfortunately, he has already thrown away the original data and kept the sample mean and the sample variance he computed.

True or false? You can still construct a confidence interval for the mean of the s.

## Long Question 4—Neyman Analysis and Fisher Exact Test

Suppose that the 8 large regions of Vietnam were randomized into one of the following groups: 

- In some regions, the local health care centers continued to be run by the government (control group: 4 regions).
- In others, the health centers were subcontracted out to an NGO (treatment group: 4 regions).

You have access to information from a child health survey, which covers  1,000 children per region and gives you information on whether or not the children have been fully immunized.

A collaborator proposes to run a standard Neyman analysis on the sample of 4,000 treatment and 4,000 control children, ignoring the region altogether.

Denote \\(\overline{Y_T}=0.80\\) the sample average immunization rate in the treatment group, \\(\overline{Y_C}=0.58\\) the sample average immunization rate in the control group, \\(\sigma^2_T=1.2^2\\) the estimated variance in the treatment group, and \\(\sigma^2_C=2.3^2\\)[![](file:///C:/Users/CHERYL~1/AppData/Local/Temp/msohtmlclip1/01/clip_image032.gif)](https://www.codecogs.com/eqnedit.php?latex=%5Csigma_C%5E2%3D2.3%5E2#0) the estimated variance in the control group.

What is the collaborator's estimate of the average treatment effect?

What is the collaborator's estimate of the associated variance?

### Question 15

You object to the collaborator's approach and instead propose to use the fact that the randomization was done at the region level very seriously and aggregate the data at the region level. Since the sample is small, you propose to run a Fisher exact test.

True or false? The test will test the hypothesis H<sub>0</sub> that the average treatment effect is significantly different from 0.

### Question 16

At the regional level, the rates of fully immunized children in treatment regions are as follows:

Treatment regions: 85%, 99%, 100%, 76%

Control regions: 26%, 45%, 97%, 72%

Using a permutation table or R code, construct your Fisher exact test. Please enter the p-value you obtained from the test you constructed.

True or false? You can reject H0 at the 5% level.

## Long Question 5 - Flowers in China

China suffers from an enormous gender imbalance: there are many more boys than girls. Part of this is due to selective abortion, and part is due to worse treatment of girls.

Nancy Qian was interested in finding out whether parents consider the future possible wages of a girl when deciding how much to feed them and take care of them. To this end, she exploits the reform that brought household responsibility system reform in China. After Deng Xiaoping replaced Mao Zedong in 1979, households were given the choice about what crop to grow (before, they essentially had to grow cereals), and suitable regions started producing tea and orchards.

Women are particularly useful for tea growing, which requires nimble hands. Therefore she proposed that parents would start taking better care of girls in regions that produce tea. Girls would be more likely to survive, and this would translate into a relatively lower share of males in those regions after the reform, thus justifying a difference in difference approach.

Let \\(POST\\) be a dummy for post reform, and \\(TEA\\) be a dummy for whether the region produces tea. Let \\(Y_{it}\\) be the fraction of boys in region \\(i\\) at time \\(t\\).

She runs the following regression:

\\(Y_{it}=\beta_0+\beta_{1}TEA_i+\beta_{2}POST_i+\beta_{3}POST_i\ast{TEA_i}+\epsilon_{it}\\)

## [![](file:///C:/Users/CHERYL~1/AppData/Local/Temp/msohtmlclip1/01/clip_image034.gif)](https://www.codecogs.com/eqnedit.php?latex=Y_%7Bit%7D%3D%5Cbeta%20_0%2B%5Cbeta%20_1%20TEA_%20i%20%2B%5Cbeta%20_2%20POST_%20t%20%2B%5Cbeta%20_3%20POST_%20t*TEA_%20i%2B%5Cepsilon%20_%7Bit%7D#0)Question 17

This question has 3 parts:

- Given the regression she runs, which variables denote the average fraction of males in tea-regions, pre-reform?
- Given the regression she runs, which variables denote the average fraction of males in non-tea regions, pre-reform?
- In this strategy, which coefficient gives her the causal effect of growing tea on the average fraction of males?

### Question 18

True or false? Instead of including the TEA dummy, she could include one dummy for each of the regions (excluding one) to account for inherent differences between regions.

## Long Question 6 - More on Flowers in China

[Download the data set](https://studio.mitxonline.mit.edu/assets/courseware/v1/bbf68069ed2763d0bf83506acd468a88/asset-v1:MITxT+14.310x+3T2021+type@asset+block/qian.csv) used in Qian's paper (qian.csv). The data contains the following variables:

●     **admin**: an ID for each region in China.

●     **birthyear**: a variable that corresponds to year.

●     **sex**: the sex ratio (male/female) that were born in that region in that year.

●     **teasown**: whether tea is produced in region *j*.

Load the data in R and now answer the following questions:

### Question 23

Explore the data and input the following variables:

Number of observations:

Mean of birthyear:

75th percentile of sex:

Maximum value of teasown:

### Question 24

Create a variable post=1 if birthyear >= 1979 Similarly, create the interaction between teasown and this variable.

In how many observations is the dummy post switched on?

*In part 2, please round your answer to the third decimal place, i.e. if your answer is 0.1245, round to 0.125 and if it is 0.1243, round to 0.124.*

Observations:

What is the mean of the interaction?