# Data-Analyst-Mohammed

# Project Description: Exploratory Data Analysis (EDA) on Titanic Dataset

# Project Title: Unveiling the Dynamics of Disaster: A Multifaceted Exploratory Data Analysis of the Titanic Passenger Dataset

**Objective:*

The main goal of this project is to conduct an exploratory data analysis (EDA) on the Titanic dataset. I want to dig into the data to find interesting patterns, trends, and insights about the passengers and what factors might have influenced their chances of survival during the Titanic disaster. By looking at things like age, gender, passenger class, and fare, I hope to get a better understanding of who survived and why.

Dataset:

The dataset contains information about the passengers on the Titanic, including:

PassengerID: A unique identifier for each passenger.

Survived: Whether the passenger survived (0 = No, 1 = Yes).

Pclass: Passenger class (1st, 2nd, 3rd class).

Name: The name of the passenger.

Sex: The gender of the passenger.

Age: The age of the passenger.

SibSp: Number of siblings/spouses aboard.

Parch: Number of parents/children aboard.

Ticket: Ticket number.

Fare: Fare paid by the passenger.

Cabin: Cabin number.

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

# Methodology:

**Here's how I plan to approach this project:*

Data Collection and Preparation:

Load the Titanic dataset using Python and the Pandas library.

Clean the data, which includes handling missing values (e.g., filling in missing ages), correcting data types, and renaming columns to make them easier to work with.

Descriptive Statistics:

Calculate summary statistics (like mean, median, mode) for numerical features like age and fare.

Create frequency distributions for categorical features like passenger class and sex.

Data Visualization:

Create different types of visualizations to help understand the data:

Histograms and box plots to see the distribution of continuous variables like age and fare.

Bar charts to show survival rates for different groups (e.g., males vs. females, different passenger classes).

Heatmaps to visualize correlations between numerical variables.

Survival Analysis:

Compare survival rates across different categories:

By gender: See if there's a significant difference in survival rates between men and women.

By passenger class: Analyze how passenger class affected survival chances.

By age group: Divide passengers into age groups and see how survival varies.

Insights and Findings:

Summarize the findings based on the visualizations and statistical analysis. I'll highlight any notable trends and patterns (e.g., whether women and children had higher survival rates, or if first-class passengers had a survival advantage).


**Insights and Findings*

Based on the exploratory analysis conducted on the Titanic dataset, several key insights emerged:

Gender and Survival: Female passengers had a significantly higher survival rate than males. This aligns with the maritime protocol of "women and children first." The bar chart clearly showed survival rates among females were more than double that of males.


![image](https://github.com/user-attachments/assets/159ee56c-347b-48c2-916c-a9f659f4f8ab)

Passenger Class and Survival: First-class passengers had the highest probability of survival. Passengers in second and third class had considerably lower survival rates, indicating a class-based disparity in access to lifeboats or early evacuation.

![image](https://github.com/user-attachments/assets/1cae25c1-29c8-4474-9925-5b0708c43f2e)
Age and Survival: Children (especially under age 12) showed a higher survival rate compared to adults and seniors. This reinforces the idea that younger passengers were prioritized during evacuation efforts.

![image](https://github.com/user-attachments/assets/fc609473-693c-4644-a55a-036edef3f45a)
Fare Paid: There was a positive correlation between fare amount and survival rate. Passengers who paid higher fares (often in first class) had better survival outcomes.

![image](https://github.com/user-attachments/assets/eb02fc9d-f97e-4de1-ab91-b82bc50e1160)

Embarkation Port: While not a major predictor, passengers embarking from Cherbourg (C) showed slightly higher survival rates compared to those from Queenstown (Q) or Southampton (S), likely due to the class distribution of passengers embarking from each port.

Correlation Matrix: The heatmap indicated moderate positive correlations between survival and variables like fare and class (inverse relationship between class number and survival).

![image](https://github.com/user-attachments/assets/b12b42fc-e771-4aa9-a860-00b6131548f1)

# Deliverables:

A comprehensive Jupyter Notebook containing all the analysis steps, including the code, visualizations, and explanations of what I found.

A presentation summarizing the key insights and visualizations, suitable for sharing with others.

This EDA project will show my ability to analyze data, find meaningful insights, and communicate those insights effectively. It'll be a valuable addition to my data analysis portfolio.

# Conclusion

Implications:
Data-driven decision-making in safety planning can benefit from understanding such trends ensuring equitable evacuation plans regardless of class or gender.

This type of analysis also reinforces the importance of fair access to emergency resources, especially in transportation and disaster response sectors.

Future Directions:
A predictive machine learning model (e.g., logistic regression, decision tree, or random forest) could be developed using the features explored (e.g., age, sex, class) to classify survival likelihood.

Further feature engineering (e.g., extracting titles from names, combining family members) can be explored to improve model performance.

Comparison with similar maritime disasters may reveal broader patterns or validate findings.



