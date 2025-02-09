# Kalahari-Data-Analysis

## Statistical Analysis of Height Data in the Namib Region

## Overview
This repository contains the analysis of two datasets: 
1. **Set 1**: Heights of adult males living in the western edge of the Kalahari Desert in Namib.
2. **Set 2**: Inter-arrival times of customers at an ATM service point of Fidelity Bank Plc, North Central.

The analysis was performed using Microsoft Excel and involves computing descriptive statistics, performing goodness of fit tests, and hypothesis testing on both datasets. The goal is to analyze the distribution of heights in Set 1, inter-arrival times in Set 2, and compare various statistical properties between two samples from Set 1 (heights of adult males) and a second sample from Set 1 (heights of adult females).

## Datasets
### Set 1: Heights of Adult Males in Namib
- Raw data containing height, weight, and gender of people in the western edge of the Kalahari Desert in Namib.
- The collected data focuses on the height of adult males in Namib.

### Set 2: ATM Customer Arrival Times
- This dataset contains the inter-arrival times of customers at an ATM service point at Fidelity Bank Plc, North Central.
- The dataset records the actual arrival time of customers, from which the interval between each occurrence is derived by calculating the time difference.

## Descriptive Statistics
### Set 1 (Heights of Adult Males):
- **Sample Mean**: 154.345
- **Sample Median**: 157
- **Sample Mode**: 159
- **Range**: 81
- **Sample Variance**: 217.2
- **Sample Standard Deviation**: 14.74

From the frequency histogram of Set 1, the distribution of heights follows a **Normal distribution** if outliers are ignored, and a **left-skewed distribution** if outliers are considered.

### Set 2 (ATM Customer Arrival Times):
- **Sample Mean**: 2.19
- **Sample Median**: 2
- **Sample Mode**: 2
- **Range**: 7
- **Sample Variance**: 1.565
- **Sample Standard Deviation**: 1.251

The frequency histogram indicates that Set 2 follows an **Exponential distribution** as the inter-arrival time increases and frequency decreases.

## Goodness of Fit Tests
- **Set 1**: A Chi-square goodness of fit test was performed to determine if the data follows a normal distribution.
- **Set 2**: A Chi-square goodness of fit test was performed to determine if the data follows an exponential distribution.

## Hypothesis Tests
### 1. Single Population Variance (Set 1 vs Set 2 - Female Heights):
- A one-sided lower-tailed chi-square test was conducted to test if the variance in the second sample (heights of adult females) is less than 18.08.
- The null hypothesis was rejected due to insufficient evidence.

### 2. Single Population Mean (Set 1 vs Set 2 - Female Heights):
- A one-sided upper-tailed chi-square test was performed to test if the mean of the second sample (heights of adult females) is greater than 142.
- The null hypothesis was not rejected, suggesting that the mean is equal to 142.

### 3. Comparison of Two Variances (Set 1 vs Set 2 - Male and Female Heights):
- An F-test was used to test if the variances of the two samples (heights of adult males and females) are equal.
- The null hypothesis was not rejected, indicating that the variances are equal.

### 4. Comparison of Two Means (Set 1 vs Set 2 - Male and Female Heights):
- A two-sample two-tailed t-test was performed to test if the means of the two samples (heights of adult males and females) are equal.
- The null hypothesis was not rejected, suggesting that the means of both samples are equal.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The data used in this analysis was collected from publicly available sources.
- Thanks to Microsoft Excel for providing the tools necessary to complete the statistical analysis.

## 📂 Project Report

For a detailed breakdown of the project, including design methodologies, implementation details, and test results, refer to the full project report:

📄 **[Kalahari Data Analysis Project Report](docs/Kalahari_Project_Report.pdf)**  
