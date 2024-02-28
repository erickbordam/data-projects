---
title: "Energy Consumption and CO2 Emission prediction"
author: "Erick Borda"
date: "2024-02-28"
output: pdf_document
---

# **Energy consumption and CO2 emissions predictions and forecasts analysis project**

## **1. Exploratory Data Analysis (EDA).**

The central challenge is to comprehend the dynamic content creation landscape within the streaming industry. Through a Exploratory Data Analysis (EDA) marks the primary phase of analysing data. It involves uncovering insights into the dataset's contents, characteristics, and size

## **2. Data Preprocessing**

Data preprocessing techniques enhance data quality, crucial for accuracy and efficiency. This step is vital in knowledge discovery as quality decisions rely on quality data. Detecting and rectifying data anomalies early on, along with reducing the data for analysis, significantly benefits decision-making processes.

## **3. Model Selection**

I've experimented with a range of models to address my time series forecasting problem, starting with the simplicity of Linear Regression, advancing through the complexity of Random Forest and Gradient Boosting regressors, considering the non-linear capabilities of SVR, tapping into the deep learning arena with an MLP regressor, and not overlooking the time series specificity of ARIMA. Each model offered unique insights into the data, with ensemble methods like Random Forest and Gradient Boosting standing out for their robust performance. However, when grouping data and incorporating temporal features, these models required careful tuning to maintain their trend prediction capabilities. The journey through these various models has laid a foundation for a comprehensive understanding of the strengths and limitations inherent in each approach when applied to time series data grouped by country and year

## 4. Random Forest Prediction Results.
After settling on Random Forest for my model prediction due to its initial performance superiority, I encountered an unexpected twist when retraining with data grouped by country and year; the traditional performance metrics plummeted. However, the model's ability to forecast the overall trend remained relatively unaffected. This peculiar outcome has been a critical learning point, indicating that while Random Forest can grasp the broad strokes of the data's direction, fine-tuning is required to improve its precision on grouped datasets. Despite the metric downturn, the trend consistency reassures me of the model's underlying value, suggesting that with further refinement, particularly in feature engineering, Random Forest could achieve a more balanced predictive prowess

## **5. Conclusion**

Random Forest and comparative had better performance than the rest over all, but after the selection metrics significantly declined upon retraining the model with data grouped by country and year, the capacity to capture and predict overarching trends persisted. This divergence between metric performance and trend prediction accuracy underscores a crucial insight—that the true value of a model in time series analysis often transcends numerical scores, residing instead in its ability to discern the direction of future movements. This phenomenon highlights the importance of evaluating models not just on their immediate accuracy but on their relevance and utility in forecasting trends, especially in complex, real-world scenarios where decisions hinge on understanding future directions rather than exact figures.

## **6. Future works**
Moving forward, the experience points toward a dual path of refinement and exploration. The initial success in trend prediction, despite lower metrics, indicates the potential for further enhancing model performance through targeted feature engineering and the incorporation of domain-specific knowledge. Concurrently, there lies a compelling case for exploring alternative modeling approaches that are inherently suited to capturing temporal dependencies and handling grouped data. Models for seasonal trends, or LSTM networks for deep learning-based time series forecasting, present promising results. Additionally, simpler models with strong regularization techniques, like Linear, Lasso or Ridge Regression, could offer a balance between complexity and interpretability. These future endeavors aim not only to elevate metric scores but also to bolster the model's innate ability to forecast trends, ensuring that predictive analytics remains both accurate and actionable in the face of evolving data landscapes

# **See the code and more insights on the notebook file!**

For any inquiries or further details, please [contact me](mailto:erickborda96@.com).
