Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores and analyzes the Titanic dataset using Python, pandas, seaborn, and matplotlib. The goal is to clean the data, perform exploratory data analysis (EDA), visualize key relationships, and extract insights.


📁 Files

titanic_EDA.ipynb — Jupyter Notebook with full analysis



🔷 Dataset

We use the Titanic dataset from the Seaborn library which contains passenger data such as:

age — Age of passenger

sex — Gender

Pclass — Passenger class (1, 2, 3)

embarked — Port of embarkation

fare — Ticket fare

survived — Survival (0 = No, 1 = Yes)



🧹 Data Cleaning

✅ Fill missing values:

age → filled with median

embarked → filled with mode ✅ Drop column deck due to excessive missing values




📊 EDA Visualizations

Survival counts

Survival by gender

Survival by passenger class

Age distribution

Age vs. survival (boxplot)

Correlation heatmap



📈 Key Insights

Females had a higher survival rate than males

Higher class passengers had better chances of survival

Younger passengers were more likely to survive



🚀 Tools Used

Python

pandas

seaborn

matplotlib

Jupyter Notebook



📌 How to Run

1. Clone this repository


2. Open titanic_EDA.ipynb in Jupyter Notebook


3. Run all cells step by step
