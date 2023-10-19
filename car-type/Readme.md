---
title: "Car Types"
author: "Erick Borda"
date: "2023-10-10"
output: pdf_document
---

# CarType Dataset Analysis Project

The goal of this analysis is to use statistical techniques on the "CarType" dataset to gain new insights and data understanding. The "CarType" dataset will be analyze with **#R**, Python (Jupyter). Addressing specific business inquiries: identifying the most fuel-efficient car type and determining the most environmentally friendly car. Elaboration on particular tasks is outlined below, encompassing a concise project overview, the identified problem, the approach taken, and the major discoveries

## 1. Identified Problem

The primary problem is to identify the car type that offers the highest fuel efficiency and to determine the most environmentally friendly car based on the given dataset. This involves analyzing relevant features and variables that influence fuel efficiency and environmental impact.

## 2. Research Question

On this project the focus will be on:

-   Fuel Economy (FE).

-   CO2 Emission.

### 2.1. What type of car provides the most fuel economy?

Based on the question the Null Hypothesis is:

**H0:** There is no difference in Combined FE between vehicles with different Cylinders, Engine Displacement and Division.

**H1:** There is difference in Combined FE between vehicles with different Cylinders, Engine Displacement and Division.

### 2.2. What type of car provides the most fuel economy?

Based on the question the Null Hypothesis is:

**H0:** There is no difference in Combined CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.

**H1:** There is difference in Combined CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.

## 3. Data Cleaning.

* To perform the cleaning step is necessary to upload libraries.

* **Upload Excel files**, First step is setting the path:

### 3.1. Missing data

Identify missing values and perform the right approach to the dataset.

### 3.2. Duplicate data.

* Identified the duplicated data
* Remove duplicate data.

## 4. Data Exploration.

* Exploration for Numerical Data.
* Categorical Data.
* Outliers.
* Normal Distribution
* Feature Selection.
* Correlations: Insights & Implications.
* Visual Insights into Fuel Economy and CO2.


## 5. Validating Hypotheses and Addressing Research Questions.

| Fuel Economy                                                                                                               | CO2 Emission                                                                                                                       | Results      |
|---------------------------|---------------------------|------------------|
| **H0:** There is no difference in Combined FE between vehicles with different Cylinders, Engine Displacement and Division. | **H0:** There is no difference in Combined CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division. | **REJECTED** |
| **H1:** There is difference in Combined FE between vehicles with different Cylinders, Engine Displacement and Division.    | **H1:** There is difference in Combined CO2 between vehicles with different Cylinders, Gears, Engine Displacement and Division.    | **ACCEPTED** |

From the above conclusion, we can say there is a relation between Fuel Economy and CO2 emissions, gathering all the information is possible to answer the research questions formulated in the context.

-   What type of car provides the most fuel economy?

-   What type of car is environmentally friendly?

The type of car that provides the most FE and lowest CO2 emission can be defined with the following characteristics:

-   Reducing the number of cylinders tents to decreased fuel consumption.

-   Smaller engines typically have lower fuel consumption.

-   Ford Cars are well know to build cars for the average men.

We can conclusively assert that cars with lower fuel consumption are environmentally friendly

## 6. Recommendations.
To simplify data handling, it's advisable to utilize standardized values and avoid working with different units of measurement.

The code and findings can be found in the project folder associated with the mentioned programming language.

For any inquiries or further details, please [contact me](mailto:erickborda96@.com).
