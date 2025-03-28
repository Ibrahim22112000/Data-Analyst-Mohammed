# Data-Analyst-Mohammed

# Exploratory Data Analysis 

Unveiling the Dynamics of Disaster: A Multifaceted Exploratory Data Analysis of the Titanic Passenger Dataset

Objective:

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


# Insights and Findings

Based on the exploratory analysis conducted on the Titanic dataset, several key insights emerged:

Gender and Survival: Female passengers had a significantly higher survival rate than males. This aligns with the maritime protocol of "women and children first." The bar chart clearly showed survival rates among females were more than double that of males.

![image](https://github.com/user-attachments/assets/2063ad74-cc5b-4fb3-afd6-8aac7e85ec50)


Passenger Class and Survival: First-class passengers had the highest probability of survival. Passengers in second and third class had considerably lower survival rates, indicating a class-based disparity in access to lifeboats or early evacuation.



![image](https://github.com/user-attachments/assets/159ee56c-347b-48c2-916c-a9f659f4f8ab)


Age and Survival: Children (especially under age 12) showed a higher survival rate compared to adults and seniors. This reinforces the idea that younger passengers were prioritized during evacuation efforts.


![image](https://github.com/user-attachments/assets/1cae25c1-29c8-4474-9925-5b0708c43f2e)


Fare Paid: There was a positive correlation between fare amount and survival rate. Passengers who paid higher fares (often in first class) had better survival outcomes.



![image](https://github.com/user-attachments/assets/eb02fc9d-f97e-4de1-ab91-b82bc50e1160)

Embarkation Port: While not a major predictor, passengers embarking from Cherbourg (C) showed slightly higher survival rates compared to those from Queenstown (Q) or Southampton (S), likely due to the class distribution of passengers embarking from each port.

Correlation Matrix: The heatmap indicated moderate positive correlations between survival and variables like fare and class (inverse relationship between class number and survival).


# Deliverables:

A comprehensive Jupyter Notebook containing all the analysis steps, including the code, visualizations, and explanations of what I found.

A presentation summarizing the key insights and visualizations, suitable for sharing with others.

This EDA project will show my ability to analyze data, find meaningful insights, and communicate those insights effectively. It'll be a valuable addition to my data analysis portfolio.

# Conclusion

In summary, this exploratory data analysis has underscored key factors influencing survival on the Titanic, highlighting the advantages conferred by being female, of a higher passenger class, or a child. These patterns likely reflect the "women and children first" protocol and disparities in resource access. The implications extend to modern safety planning, emphasizing equitable evacuation strategies regardless of class or gender. Future work includes building predictive models using features like age, sex, and class, and further feature engineering (e.g., titles, family size) to improve accuracy. A comparative analysis with other maritime disasters may reveal broader patterns, validating these findings and informing a more comprehensive understanding of crisis survival dynamics.





