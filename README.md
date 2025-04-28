# DATA-ANALYST-INTERNSHIP-Task-5
Exploratory Data Analysis (EDA)
1. Dataset Overview
Dataset: Titanic Dataset

Rows: 891 (depending on clean version)

Columns: 12

Main Features:

Passenger information: Name, Sex, Age, Ticket, Fare, Cabin

Travel class: Pclass

Boarding port: Embarked

Survival outcome: Survived

2. Initial Observations
Missing Values:

Age had missing values (~20%), filled with median.

Cabin had many missing values, marked as "Unknown".

Embarked had minor missing values, filled with mode ('S' - Southampton).

Data Types:

Age and Fare are continuous (numerical).

Pclass, Survived, Sex, and Embarked are categorical.

3. Univariate Analysis (Single Variables)
Survival Rate:

38% survived, 62% did not survive.

Sex:

More males (65%) than females (35%) onboard.

Age:

Most passengers were between 20 to 40 years old.

Pclass:

3rd class had the most passengers.

4. Bivariate and Multivariate Analysis
Sex vs Survival:

Females had a significantly higher survival rate compared to males.

Pclass vs Survival:

Passengers from 1st class had the highest survival rate.

3rd class had the highest mortality rate.

Age vs Survival:

Children and young adults had better survival chances.

Fare vs Survival:

Higher fare-paying passengers were more likely to survive.

5. Correlation Analysis
Positive correlation between Fare and Survived (~0.26).

Negative correlation between Pclass and Survived (~-0.34).

No strong correlation among other features.

6. Key Findings and Insights
Gender played a crucial role in survival: females were prioritized.

Socio-economic status influenced survival: wealthier passengers had better chances.

Younger passengers (especially under 10 years) had relatively better survival rates.

Embarkation point slightly influenced survival rates, with passengers from Cherbourg (C) having a higher survival rate.

Conclusion
The Titanic dataset clearly shows the impact of social structures on survival — highlighting gender, class, and financial ability as major survival predictors.

This EDA reveals critical factors that would have impacted real-world survival chances on the Titanic.

