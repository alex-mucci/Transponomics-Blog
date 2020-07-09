---
layout: post
title: What is going on with Covid-19?
published: true
subtitle: Exploring the covid-19 testing data
tags:
  - Covid-19
  - Coronavirus
  - Economy
  
share-img: 'https://github.com/alex-mucci/blog/blob/gh-pages/img/Covid-19 Image.jpg'
date: '2020-07-09'
---

### **Research Question**: 
Is the covid-19 virus getting worse?

### Covid-19 Background
If you have not heard of the covid-19, or corona viurus, by now then you must be Amish or living in your mom's basement. The most recent stories surrounding the virus has been 
on the rise in positive test throughout the US. The [**articles**](https://edition.cnn.com/world/live-news/coronavirus-pandemic-07-08-20-intl/h_bb382d40fcd19925a2914b9f535280e5) 
give a sense that the virus has spread the most recently than ever before. My first thought after reading the storieswas that testing has increased, so is this rise in positive 
tests simply because we are testing more people now. That thought is what inspired me to write this blog. Numerous measures of how infectious the virus is are tested. The goal of 
this blog is to answer the question of whether or not the virus is more infectious and what direction the virus is trending. All of the data used for this analysis is obtained
from the [**Our World**](https://ourworldindata.org/coronavirus) is Data website. 

### Positive Tests vs Positive Rate
Most of the news articles reporting on the virus use the daily number of positive tests as a measure of how infectious the virus is. The issue with using the daily number of
positive tests is that it could increase due to an increase in testing, not an increase in the spread of the virus. Figure 1 below using the positive rate and cummulative positive
rate of tests to measure how much the virus is spreading. The positive rate of tests is simply the total number of new positive covid-19 cases divided by the total number
of tests performed that day. The cummulative postive rate is the total number of positive tests divided by the total number of tests performed. The cummulative positive rate 
smooths out a lot of noise in the data.

**Figure 1**

![]({{site.baseurl}}/img/covid_figure1.jpg)

As you can clearly see the positive rate tests for the virus has declined since the first outbreak and has leveled off in the past month or so. There has been a large increase in 
the number of tests given. Figure 2 illustrates the growth and Trump's twitter account will keep you updated on it as well. 

**Figure 2**
![]({{site.baseurl}}/img/covid_figure2.jpg)

Figure 2 leads me to think that the increase in positive cases is due to the increase in testing. Figure 3 visualizes the change in daily positive tests. There is clearly a large
jump in positive cases since mide June. Looking back to figure 2 does not show a sharp jump in the number of tests given. This lead me to question whether or not the postive rate
of tests is a good measure of the spread of the virus. 

**Figure 3**
![]({{site.baseurl}}/img/covid_figure3.jpg)


### Number of Tests per Positive Test
The large numbers of tests and positive tests leads to small percent changes in the positive test rate when there is an increase in the number of postive tests. Figure 4 shows 
a new measure I thought to try, which is the number of tests per positive tests. This measure represents the total number of tests that is given before a positive test is found. 
The measure moves in the opposite direction of the previous measures. The difference means that the higher the measure is the less the virus is spreading, so the line moving up is
good. This measure does a much better job at captureing the recent jump in positive cases since mid-June. 

**Figure 4**
![]({{site.baseurl}}/img/covid_figure4.jpg)


### Conclusion
The conclusion of this is that both the total number of positive tests or the positive rate can be misleading when determing how much a virus is spreading. The number of tests
 per positive test does a much better job at visualizing the change in the spread of a virus. The measure is a little counter-intuitive with higher being less spread and lower
 meaning the virus is spreading more, but overall I would recommend using it versus the other two options. 
 
 The spread of the virus is clearing growing since mid-June, so there is some merit behind the articles claiming the virus is getting worse, but I would not go as far as saying 
 the virus is the worse it has ever been. Storylines saying that the highest daily total number of positive tests has been recorded makes a person believe that the virus is worse
 than it has ever been before. Instead I would say that virus has clearly taken a turn for the worse and that we are trending towards the virus being worse than it ever has before. 

