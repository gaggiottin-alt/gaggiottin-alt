
# Data Science Portfolio — Noemi Gaggiotti

Welcome to my Data Science Portfolio!

I am a Data Science student at Merrimack College, graduating in December 2026. My academic work focuses on data analytics, machine learning, statistical modeling, data visualization, and Geographic Information Systems (GIS).

This portfolio showcases projects completed throughout my undergraduate studies, including predictive modeling, business analytics, unsupervised machine learning, quantum machine learning research, and public health data analysis.

I am particularly interested in using data to solve real-world problems, identify meaningful patterns, and support data-driven decision-making in business, government, and research.

**Email:** gaggiottin@merrimack.edu, noemigaggiotti@gmail.com

**Location:** Andover, Massachusetts

---

## Achievements

- Bachelor of Science in Data Science, Merrimack College — Expected December 2026
- Cumulative GPA: 3.456
- Dean's List and President's List
- Completed an independent Directed Study in Quantum Machine Learning under Dr. Don Roosan, earning an A
- Completed Data Analysis for Business with an A-
- Experience analyzing large-scale public health data from the National Survey on Drug Use and Health (NSDUH)
- Fluent in English, Italian, and Spanish

---

## Technical Skills

**Programming Languages**
- Python
- R
- SQL

**Software and Tools**
- RStudio
- Tableau
- Microsoft Excel
- ArcGIS
- Google Colab
- Jupyter Notebook
- Google Workspace

**Data Analysis**
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Predictive Modeling
- Classification and Clustering
- Association Rule Mining
- Geographic Information Systems (GIS)

**Machine Learning**
- Logistic Regression
- Decision Trees
- Random Forest
- Bagging
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Graph Neural Networks (GNNs)

---

## Projects

### 1. Cannabis Use Disorder Prediction — Data Science Capstone

**Technologies:** R, RStudio, Statistical Analysis, Machine Learning

**Status:** In Progress

This capstone project investigates demographic, socioeconomic, mental health, and substance-use predictors of Cannabis Use Disorder (CUD) using 232,441 survey responses from the combined 2021–2024 National Survey on Drug Use and Health (NSDUH).

The analysis includes cleaning and preprocessing survey data, examining CUD prevalence across demographic groups, and applying chi-square tests and Cramér's V to identify statistical associations.

The project also investigates Major Depressive Episode (MDE) as a related outcome, with plans to compare predictive factors across both conditions.

**Key Methods:**
- Data cleaning and preprocessing
- Exploratory data analysis
- Chi-square tests and Cramér's V
- Logistic regression
- Decision trees
- Random Forest classification
- Classification model evaluation

**Project Goal:** Identify important predictors of CUD and MDE and evaluate the usefulness of machine learning methods for analyzing large-scale public health survey data.

---

### 2. Customer Shopping Behavior and Segmentation

**Technologies:** R, RStudio, ggplot2, K-Means, Hierarchical Clustering, DBSCAN

This project analyzes customer shopping behavior using a dataset containing 3,900 customer records and 16 variables.

The objective was to explore customer purchasing patterns and identify meaningful groups based on age, purchase amount, review ratings, and previous purchases.

I performed exploratory data analysis, normalized numerical variables, and applied multiple unsupervised machine learning methods to compare customer segmentation approaches.

**Key Methods:**
- Data cleaning and preprocessing
- Min-max normalization
- Descriptive statistics and data visualization
- K-Means clustering
- Silhouette analysis
- Hierarchical clustering
- DBSCAN

**Key Finding:** K-Means clustering revealed groups with different purchasing characteristics, including clusters with average purchase amounts of approximately $81.80 and $37.80.

**Business Application:** Customer segmentation can support marketing strategies, customer behavior analysis, and business decision-making.

---

### 3. Netflix Genre Association Analysis

**Technologies:** R, RStudio, Apriori Algorithm, Association Rule Mining, Data Visualization

This project analyzes 8,807 Netflix titles to investigate whether certain genres frequently appear together.

Using the Apriori algorithm, I identified association rules between genres and evaluated the strength of these relationships using support, confidence, and lift.

The analysis focused on identifying meaningful patterns in Netflix's catalog and considering how these patterns could inform content organization and recommendations.

**Key Methods:**
- Data cleaning and transformation
- Transaction data preparation
- Apriori association rule mining
- Support, confidence, and lift analysis
- Data visualization

**Key Findings:**
- International Korean TV Shows showed a strong association with Romantic TV Shows, with a lift of approximately 12.1.
- Horror Movies were strongly associated with Thrillers, with a lift of approximately 5.39.
- TV Mysteries showed a strong association with TV Dramas.

**Business Application:** These findings could help inform content categorization and the development of more targeted browsing categories.

---

### 4. Seattle Rainfall Prediction

**Technologies:** Python, Pandas, scikit-learn, Matplotlib, Machine Learning

This project uses historical Seattle weather data to investigate whether rainfall can be predicted using meteorological and seasonal features.

I developed and compared Bagging and Random Forest classification models, using a chronological training and testing split to evaluate performance on previously unseen weather observations.

Hyperparameter combinations were evaluated using a manual grid search with Out-of-Bag (OOB) accuracy.

**Key Methods:**
- Exploratory data analysis
- Feature engineering
- Bagging classification
- Random Forest classification
- Hyperparameter tuning
- Out-of-Bag evaluation
- Confusion matrices and classification metrics

**Key Finding:** The weather-informed Random Forest achieved 78.6% test accuracy, outperforming a calendar-only model.

**Project Goal:** Evaluate how weather conditions and seasonal patterns contribute to predicting rainy days.

---

### 5. Quantum Machine Learning for Molecular Property Prediction

**Directed Study — Dr. Don Roosan**

**Technologies:** Python, Google Colab, Graph Neural Networks, Quantum Machine Learning, QM9

This directed study investigated classical, hybrid quantum-classical, and geometry-aware neural network approaches for predicting HOMO-LUMO molecular energy gaps.

The project used the QM9 molecular dataset to explore how machine learning architectures can learn relationships between molecular structures and quantum chemical properties.

I implemented a classical Graph Neural Network (GNN), evaluated a hybrid quantum-classical tutorial model, and researched the DimeNet architecture for incorporating three-dimensional molecular geometry.

**Key Methods:**
- Molecular dataset preparation
- Graph Neural Networks
- Mean Squared Error evaluation
- Hybrid quantum-classical learning
- DimeNet architecture research

**Key Findings:**
- The classical GNN achieved a validation MSE of 0.2981 after 20 training epochs.
- The hybrid tutorial model reached a training MSE of 0.2924 after 10 epochs.
- DimeNet was identified as a promising architecture for capturing molecular geometry through distances and angular relationships.

**Project Status:** Classical and hybrid model experiments completed; DimeNet implementation and debugging remained in progress at the conclusion of the directed study.

---

### 6. Movie Performance Analysis

**Technologies:** Python, Data Cleaning, Exploratory Data Analysis, Data Visualization

This project examined more than 85,000 movie records to investigate relationships between production budgets, revenue, genres, runtimes, and audience engagement.

I used Python to clean and explore the dataset, generating visualizations to identify patterns in movie performance over approximately 25 years.

**Key Methods:**
- Data cleaning
- Exploratory data analysis
- Scatter plots
- Bar charts
- Boxplots
- Trend analysis

**Project Goal:** Identify relationships between movie characteristics and financial performance through data exploration and visualization.

---

### 7. Amazon Rainforest Conservation GIS Module

**Technologies:** ArcGIS Online, GIS, Spatial Analysis, Mapping

**Status:** In Progress

This GIS project explores the spatial relationships between Indigenous territories, protected conservation areas, and the Amazon rainforest.

The project uses geographic datasets to examine conservation boundaries and investigate areas of overlap and proximity.

**Planned Methods:**
- Geographic layer integration
- Satellite imagery basemaps
- Buffer analysis
- Spatial overlay and intersection
- Geographic interpretation

**Project Goal:** Explore how GIS techniques can support conservation research and help identify areas for further investigation into the protection of Indigenous territories and rainforest ecosystems.

---

## Education

**Merrimack College**

Bachelor of Science in Data Science  
Expected Graduation: December 2026

**Relevant Coursework:**
- Foundations of Data Science I and II
- Data Mining and Predictive Analytics I and II
- Data Analysis for Business
- Creating Information Graphics
- Geographic Information Systems
- Optimization
- Modeling and Simulation
- Basic Statistics
- Calculus I
- Discrete Mathematics
- Problem Solving with Python

**Suffolk University**

Previous coursework in Communications, Journalism, Media Studies, Conflict Resolution, and Visual Communication.

---

## Career Interests

I am interested in opportunities involving:

- Data Analysis and Business Analytics
- Data Visualization and Reporting
- Predictive Analytics and Machine Learning
- Public Sector and Government Data Analysis
- Research and Statistical Analysis
- Geographic Information Systems

Thank you for visiting my portfolio!
