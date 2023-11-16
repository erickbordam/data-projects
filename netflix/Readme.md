---
title: "Car Types"
author: "Erick Borda"
date: "2023-11-14"
output: pdf_document
---

# **Netflix Dataset Analysis**

## 1. Identified Problem

The central challenge is to comprehend the dynamic content creation landscape within the streaming industry. Through a detailed analysis of trends encompassing content duration, ratings, and international distribution, this study seeks to offer crucial insights into the ever-changing preferences of audiences, the intricate dynamics of regional content, and the strategic choices made by both content creators and streaming platforms. This knowledge becomes pivotal in adapting content strategies, customizing offerings to diverse audience segments, and refining content creation processes to align with the evolving demands of the global streaming market.

## 2. Research Question

In this project, it'll be focus on:
1. How does the duration of content (movies and TV shows) vary across different content ratings, and are there significant differences in duration between content rated for different audiences?
2.	How does the movie duration trend change before and after the year 2000?
3.	How does the content production change over time? Is there any variation in popular genre over the years?
4.	What kind of TV shows/movies are streamed most on Netflix?

## **3. Null Hypothesis.**

* How does the duration of content (movies and TV shows) vary across different content ratings, and are there significant differences in duration between content rated for different audiences?
  -  **H0:**  There is no significant difference in the mean duration of content (movies and TV shows) among different content ratings.
  - **H1:** There is significant difference in the mean duration of content (movies and TV shows) among different content ratings.
* How does the movie duration trend change before and after the year 2000?
  - **H0:** There is no significant difference in the mean duration of movies before and after the year 2000.
  - **H1:** There is significant difference in the mean duration of movies before and after the year 2000.
* How does the content production change over time? Is there any variation in popular genres over the years?
  - **H0:** There is no significant difference in the proportion of content production across different years, nor is there any variation in the popularity of genres over the years.
  - **H1:** There is significant difference in the proportion of content production across different years, nor is there any variation in the popularity of genres over the years.
* What kind of TV shows/movies are streamed most on Netflix?
  - **H0:** There is no significant difference in the popularity of different genres or types of TV shows/movies streamed on Netflix.
  - **H1:** There is significant difference in the popularity of different genres or types of TV shows/movies streamed on Netflix.

## 3. Data Cleaning.
### 3.1. Missing data

Identify missing values and perform the right approach to the dataset.
**There are no missing values.**

### 3.2. Duplicate data.

* Identified the duplicated data
**There are no duplicated values.**

## 4. Data Exploration.

* Exploration for Numerical Data.
* Categorical Data.
* Outliers.
* Enhanced dataset.
* Normal Distribution (Not normal distributed).
* Visualization.

## 5. Validating Hypotheses and Addressing Research Questions.

To accept or reject the null Hypotesis stated on [2. Research Question], we need to use Kruskal-Wallis test, knowing that the does not follow normal distribution, to do that we need execute the following code:

### **5.1. Research question #1.**

Kruskal-Wallis test p-value for movie duration across content ratings: 3.7682246902139096e-198
**Reject the null hypothesis: There are no significant differences in movie durations across content ratings.**
Kruskal-Wallis test p-value for TV show duration across content ratings: 3.6392564604246986e-09
**Reject the null hypothesis: There are no significant differences in TV show durations across content ratings.**

### **5.2. Research Quesetion #2.**
T-test p-value for movie duration before and after 2000: 1.6555793633300572e-35
Reject the null hypothesis: There is no significant difference in movie durations before and after 2000.
### **5.3. Research Question #3.**
For analyzing variations in popular genres over time, no hypothesis test is required as it involves observing trends in data and identifying changing patterns without specific hypothesis testing.
### **5.4. Research Question #4.**
For determining the most streamed content, statistical hypothesis testing may not be applicable. Instead, it involves finding the most occurring categories based on the data.


# **See the code and findings on its respective lanaguage folder!**

For any inquiries or further details, please [contact me](mailto:erickborda96@.com).
