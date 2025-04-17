# PRODIGY_DS_02

**### Task 2: Titanic Dataset Analysis**

 Objective
Explore and analyze the Titanic dataset to identify patterns and relationships in passenger data — such as survival rates by gender, class, and age — and visualize these patterns using statistical plots.

 Exploratory Data Analysis (EDA)
Data Overview:
Used .info() and .describe() to understand column types, null values, and summary statistics.
Identified missing values using df.isnull().sum().
📷 [image](https://github.com/user-attachments/assets/1b89c7f4-02e6-45f4-8f78-f6c4eaeed640)

Correlation Heatmap:
Created a heatmap to visualize relationships between numerical variables.
Strongest positive correlation observed between Pclass and Fare.
📷![image](https://github.com/user-attachments/assets/13d4032b-62cd-4afc-b27e-42dfcc16e68e)

Age Distribution:
Visualized age distribution using histogram with KDE curve.
Shows a peak around 25-30 years.
📷 ![image](https://github.com/user-attachments/assets/d9fce67b-fea4-4b00-92c3-6a6e1f8bd317)

Survival by Passenger Class:
Used seaborn countplot to show survival distribution across classes.
Passengers in 1st class had higher survival rates.
📷 ![image](https://github.com/user-attachments/assets/5fdf4ed1-980e-4b2b-99bb-529c7bdb4028)

Survival by Gender:
Survival rates for females were significantly higher than for males.
📷 [image](https://github.com/user-attachments/assets/9216b652-4494-40a0-b7a4-988a3426bc44)

Survival Count by Class (Grouped by Survival):
Another view of how survival varied among classes (1, 2, 3).
📷![image](https://github.com/user-attachments/assets/3bc19437-d586-4bab-918a-c0d1d6bde2b5)
