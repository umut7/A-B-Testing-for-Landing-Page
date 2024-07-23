# A/B Testing Data Science Project

## Overview

This project involves A/B testing to evaluate the effectiveness of different variations of a Call-To-Action (CTA) button for LunarTech. A/B testing is a statistical method used to compare two or more variations to determine which one performs better in terms of a specific metric, such as conversion rate. 
This is a small project that can be found on the FreeCodeCamp YouTube channel.

## Project Structure

- `ab_test_click_data`: Contains the dataset used for the A/B testing.
- `A-B Testing for Landing Page`: Jupyter notebooks with data analysis and visualizations.
- `README.md`: Project overview and instructions.

## Data

The dataset used in this project includes user interaction data with different versions of the CTA button. Each entry records whether a user clicked on the button and which version of the button was shown.

## Analysis

1. **Data Overview**: Preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing the data to understand its structure and distribution.
3. **Hypothesis Testing**: Performing statistical tests to determine if there is a significant difference between the variations.
4. **Results Visualization**: Plotting the results to show the findings clearly.

I used a Z-test for proportions to test these hypotheses, calculating the test statistic and p-value to conclude.
The technologies I used for this project are:
1- numpy
2- pandas
3- scipy
4- seaborn
5- matplotlib

## Results

The analysis shows that Experimental Group Test (B) performed significantly better than Control Group Test (A) with a higher click-through rate.

## Conclusion

Based on the A/B testing results, it is safe to say that the "Enroll Now" button is preferred over the "Secure Free Trial" button.
