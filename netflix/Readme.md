---
title: "Car Types"
author: "Erick Borda"
date: "2023-10-10"
output: pdf_document
---

# CarType Dataset Analysis Project

The goal of this analysis is to use statistical techniques on the "CarType" dataset to gain new insights and data understanding. The "CarType" dataset will be analyze with **#R**, **Python**. Addressing specific business inquiries: identifying the most fuel-efficient car type and determining the most environmentally friendly car. Elaboration on particular tasks is outlined below, encompassing a concise project overview, the identified problem, the approach taken, and the major discoveries

## 1. Identified Problem

The primary problem is to identify the car type that offers the highest fuel efficiency and to determine the most environmentally friendly car based on the given dataset. This involves analyzing relevant features and variables that influence fuel efficiency and environmental impact.

## 2. Research Question

In this project, we will have a dual focus:

1.  Fuel Economy (FE) - Our research will center on optimizing fuel efficiency in various driving conditions.

2.  CO2 Emission - We will examine vehicle emissions, specifically focusing on reducing carbon dioxide (CO2) emissions.

Additionally, we will place a distinct emphasis on the **Urban sector**, delving into the unique challenges and opportunities it presents for both fuel economy and emissions analysis

### 2.1. What type of car provides the most fuel economy?

Based on the question the Null Hypothesis is:

**H0:** There is no difference in City FE between vehicles with different Cylinders, Engine Displacement and Division.

**H1:** There is difference in City FE between vehicles with different Cylinders, Engine Displacement and Division.

### 2.2. What type of car provides the most fuel economy?

Based on the question the Null Hypothesis is:

**H0:** There is no difference in City CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.

**H1:** There is difference in City CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.

## 3. Data Cleaning.
### 3.1. Missing data

Identify missing values and perform the right approach to the dataset.
**There are no missing values.**

### 3.2. Duplicate data.

* Identified the duplicated data
* Remove duplicate data.
** 7 values were removed**

## 4. Data Exploration.

* Exploration for Numerical Data.
* Categorical Data.
* Outliers.
* Normal Distribution (Not normal distributed).
* Feature Selection.
* Correlations: Insights & Implications.
* Visual Insights into Fuel Economy and CO2.

## 5. Validating Hypotheses and Addressing Research Questions.

To accept or reject the null Hypotesis stated on [2. Research Question], we need to use Kruskal-Wallis test, knowing that the does not follow normal distribution.

The result is p-values less than 2.2e-16 is a very strong indication that there is a significant effect or difference in your data, and you can confidently reject the null hypothesis in favor of the alternative hypothesis.

| Fuel Economy                                                                                                           | CO2 Emission                                                                                                                   | Results      |
|---------------------------|----------------------------|-----------------|
| **H0:** There is no difference in City FE between vehicles with different Cylinders, Engine Displacement and Division. | **H0:** There is no difference in City CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division. | **REJECTED** |
| **H1:** There is difference in City FE between vehicles with different Cylinders, Engine Displacement and Division.    | **H1:** There is difference in City CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.    | **ACCEPTED** |

From the above conclusion, we can say there is a relation between Fuel Economy and CO2 emissions, gathering all the information is possible to answer the research questions formulated in the context.

-   What type of car provides the most fuel economy?

-   What type of car is environmentally friendly?

The type of car that provides the most FE and lowest CO2 emission can be defined with the following characteristics:

-   Reducing the number of cylinders tents to decreased fuel consumption.

-   Smaller engines typically have lower fuel consumption.

-   Ford Cars are well know to build cars for the average men.

We can assert with confidence that vehicles with higher fuel economy are inherently more environmentally friendly, especially within the urban sector. Higher fuel economy signifies efficient use of fuel resources, leading to reduced emissions and a more sustainable transportation system in urban areas.

## 6. Recommendations.

To simplify data handling, it's advisable to utilize standardized values and avoid working with different units of measurement.

# **See the code and findings on its respective lanaguage folder!**

For any inquiries or further details, please [contact me](mailto:erickborda96@.com).
