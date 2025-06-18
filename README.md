# Titanic-Survival-EDA
# 📌 Project Description
This project performs in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to uncover hidden patterns and insights related to passenger demographics and survival rates.
No machine learning or classification is done — this is purely data analysis and visualization.

Target Column: Survived

0: Did not survive

1: Survived
# 🧹 Step 1: Data Cleaning
Handled Missing Values:

Age: Filled with median

Embarked: Filled with mode

Cabin: Dropped due to too many missing entries

Dropped Columns for EDA Simplicity:

Cabin, PassengerId, Name, Ticket

# 📊 Step 2: Univariate Analysis
Target Distribution:

Survival count using countplot

Age Distribution:

Histogram with KDE

Gender Distribution:

Countplot of Sex

# 🔍 Step 3: Bivariate Analysis
Survival vs Gender:

Compared survival counts across genders

Survival vs Passenger Class (Pclass):

Identified class-based survival patterns

Age vs Survival:

Box plot to observe age patterns for survivors and non-survivors

# 📈 Step 4: Correlation Analysis
Encoding:

Sex: male → 0, female → 1

Embarked: S → 0, C → 1, Q → 2

Heatmap:

Shows correlation among features including Survived, Age, Fare, etc.

Useful for identifying linear relationships and potential influencers of survival

# 📎 Notable Observations
Females had higher survival rates

Higher-class passengers (Pclass = 1) were more likely to survive

Young children and people in certain embarkation ports showed different survival trends

# 🛠️ Libraries Used
python

pandas

numpy

seaborn

matplotlib

# 👩‍💻 Owner
[Harshitha Kakumanu](https://github.com/Kakumanu-Harshitha)

