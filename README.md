# Prodigy_DS_04

# Overview:
This repository contains the code and analysis performed during my project at Prodigy InfoTech. The notebook Prodigy_DS_04.ipynb demonstrates data preprocessing, exploratory data analysis, sentiment analysis, and predictive modeling tasks using Python.

# Getting Started:
- **Clone the Repository:**  
```bash
git clone https://github.com/vedantcoder44088/Prodigy_DS_04.git
```
- **Navigate to the Project Directory:**  
```bash
cd Prodigy_DS_04
```
- **Install Required Libraries:**  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
- **Download the Dataset:**  
Download the dataset named `twitter_training.csv` and `twitter_validation.csv` and place them in the project directory.

# Project Steps:
1. **Data Loading and Exploration:**  
   - Loaded the training and validation datasets into pandas DataFrames.
   - Explored the structure, columns, and summary statistics of the datasets.
   
2. **Data Preprocessing:**  
   - Addressed missing values in the dataset by removing rows with null values in the "Content" column.
   - Standardized the target variable labels by replacing "Irrelevant" sentiment with "Neutral".
   
3. **Data Visualization:**  
   - Visualized the distribution of sentiment categories using a pie chart.
   - Plotted the top entities and their corresponding post counts using a bar chart.
   - Analyzed sentiment distribution across the top entities using pie charts.
   
4. **Sentiment Analysis:**  
   - Conducted sentiment analysis by categorizing posts into Neutral, Negative, and Positive sentiments.
   
5. **Feature Engineering:**  
   - Utilized CountVectorizer for text feature extraction to prepare the text data for modeling.
   
6. **Model Training:**  
   - Built a Multinomial Naive Bayes model using scikit-learn for sentiment classification.
   
7. **Model Evaluation:**  
   - Evaluated the trained model's performance using accuracy score on the validation dataset.
   
8. **Visualization of Decision Trees:**  
   - Visualized decision trees using the plot_tree function to understand the model's decision-making process.

  
# Requirements:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

# Usage:
- Open the Jupyter Notebook `Prodigy_DS_04.ipynb` to view the project documentation and code.
- Execute each cell of the notebook to reproduce the analysis and results.

# License:
This project is licensed under the MIT License. See the LICENSE file for details.
