# Student Performance Analysis – EDA

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Students Performance dataset using Python. The main goal is to understand students' academic performance in Mathematics, Reading, and Writing through statistical analysis and visualizations.

The project also calculates total scores, percentages, average scores, and pass/fail status to gain better insights into student performance.

## 🎯 Objectives

- Explore and understand the student performance dataset.
- Calculate statistical measures such as mean, median, mode, and standard deviation.
- Calculate total scores, percentages, and average scores.
- Classify students as Pass or Fail based on their subject scores.
- Identify potential outliers in Mathematics scores.
- Visualize score distributions using histograms and box plots.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization library
- **Jupyter Notebook / Google Colab** – Development environment

## 📂 Dataset

The project uses a Students Performance dataset containing scores for three subjects:

- Mathematics
- Reading
- Writing

The dataset is loaded from `StudentsPerformance.csv`.

**Note:** The CSV file must be available in the correct location before running the notebook.

## 🔍 Project Workflow

### 1. Data Loading and Exploration
- Import the required Python libraries.
- Load the CSV dataset using Pandas.
- Display the first and last few rows.
- Check the dataset dimensions, column names, data types, and descriptive statistics.

### 2. Statistical Analysis
Calculate the following measures for the three subject scores:

- Mean
- Median
- Mode
- Standard deviation
- First quartile (25th percentile)

### 3. Feature Engineering
Create additional columns to analyze academic performance:

- **Total Score:** Sum of Mathematics, Reading, and Writing scores.
- **Percentage:** Total score divided by 300 and multiplied by 100.
- **Average Score:** Average of the three subject scores.
- **Pass/Fail:** Students are classified as Pass if they score at least 40 in all three subjects; otherwise, they are classified as Fail.

### 4. Outlier Detection
Use the Interquartile Range (IQR) method to identify potential outliers in Mathematics scores.

### 5. Data Visualization
- Create a histogram to examine the distribution of Mathematics scores.
- Create box plots to compare the distributions of Mathematics, Reading, and Writing scores.

## 📊 Key Analysis Areas

- Subject-wise score statistics
- Total scores and percentages
- Average student scores
- Pass/fail classification
- Mathematics score outliers
- Distribution of scores across subjects

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Ensure that `EDA_Task_7.ipynb` and `StudentsPerformance.csv` are available.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Install the required libraries if they are not already installed:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

5. Update the CSV file path if necessary.
6. Run the notebook cells in order to perform the analysis.

## 💡 Learning Outcomes

Through this project, I practised:

- Data exploration using Pandas
- Descriptive statistical analysis
- Creating new features from existing data
- Identifying potential outliers using IQR
- Visualizing data distributions
- Understanding student performance through data analysis

## 🔮 Future Enhancements

- Analyze how different factors relate to students' scores.
- Compare performance across student groups.
- Create additional visualizations for subject-wise comparisons.
- Build an interactive dashboard using Power BI or Streamlit.
- Develop a predictive model for student performance, if suitable data and evaluation methods are available.

## 👩‍💻 Author

**Vasundhra V S**

GitHub: [VasundhraVS](https://github.com/VasundhraVS)

---

⭐ If you find this project useful, feel free to explore the notebook and its analysis.
