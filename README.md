
# 🎓 Online Course Recommendation System
## 📌 Project Overview

The Online Course Recommendation System is a Machine Learning project that recommends similar online courses based on their characteristics. The recommendation engine uses the K-Nearest Neighbors (KNN) algorithm to find courses that are most similar to the course selected by the user.

The project also includes a Streamlit web application, allowing users to interactively select a course and receive personalized recommendations.

# 🚀 Features
Interactive Streamlit web application
Course recommendation using KNN,Collabrative Filtering,Content based Filtering
Displays:
Course Name
Difficulty Level
Certification Offered
Rating
Similarity Score
User-friendly interface
Fast recommendations using pre-trained model
# 🛠️ Technologies Used
Category	Tools
Programming Language	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-learn
Recommendation Algorithm	K-Nearest Neighbors (KNN)
Model Serialization	Joblib
Sparse Matrix	SciPy
Web Framework	Streamlit

# 🔍 Exploratory Data Analysis (EDA)
### The notebook performs several data analysis and preprocessing steps:
Data Inspection
Loaded dataset using Pandas
Checked dataset shape
Displayed column information
Examined data types
Data Cleaning
Missing value analysis
Duplicate record detection
Converted categorical variables
Prepared data for machine learning
Outlier Detection
### Boxplots were used to identify outliers in numerical features such as:
Course Duration
Rating
Enrollment Numbers
Course Price
Feedback Score
Data Visualization
### Several visualizations were created, including:
Course difficulty distribution
Course ratings
Enrollment trends
Course pricing
Feature distributions
# 🤖 Machine Learning Workflow
### 1. Data Preprocessing
Cleaned missing values
Converted categorical columns
Selected important features
Generated feature vectors
### 2. Feature Engineering
Course information was transformed into numerical feature vectors suitable for similarity comparison.
### 3. Model Building
The recommendation engine uses the K-Nearest Neighbors (KNN) algorithm.
Why KNN?
KNN recommends courses by measuring the similarity between the selected course and all other courses in the dataset.
Courses with the smallest distance are considered the most similar.
# 💻 Streamlit Application

### The app.py file provides the user interface.Workflow
Load processed dataset.
Load trained KNN model.
Display course selection dropdown.
User selects a course.
Recommendation button is clicked.
Recommended courses are displayed.
### Interface Components
Sidebar for selecting recommendation model
Course dropdown menu
Recommend button
Recommendation table
