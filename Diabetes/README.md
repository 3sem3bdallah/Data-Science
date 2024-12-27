# Diabetes Data Science Project 🩺📊

## Project Overview 📋

This project aims to analyze a synthetic diabetes dataset to understand the factors contributing to diabetes and its impact on individuals. The dataset includes various health metrics such as age, gender, blood pressure, glucose levels, BMI, insulin levels, and more. The analysis involves data cleaning, exploratory data analysis (EDA), and machine learning to derive meaningful insights and build predictive models.

## Dataset 📁

The dataset consists of health metrics for individuals, including attributes such as age, gender, BMI, blood pressure, glucose level, insulin level, family history, physical activity, smoking status, alcohol consumption, diet score, sleep duration, occupation stress score, diabetic status, and an ID. It contains 48,215 rows and 17 columns.

## Project Structure 🏗️

- **Data Cleaning**: Handling missing values, duplicates, and outliers to ensure clean data.
- **Exploratory Data Analysis (EDA)**: Analyzing key properties of the dataset to form meaningful insights.
- **Data Visualization**: Visualizing relationships between different features using plots.
- **Machine Learning**: Building and evaluating predictive models to classify diabetic status.

## Notebooks 📓

- `project_DS.ipynb`: The main Jupyter notebook containing the entire workflow, including data cleaning, EDA, visualization, and machine learning.

## Key Insights 🔍

1. **Family History Impact**: Higher count of diabetic individuals with a family history suggests a potential genetic predisposition to diabetes.
2. **BMI Distribution**: Understanding the distribution of BMI provides insights into the overall health of the population.
3. **Age vs BMI**: Scatter plot analysis shows the relationship between age, BMI, and insulin levels.
4. **Correlation Matrix**: Highlights strong positive and negative correlations between various features.
5. **Gender Distribution**: Pie chart shows the distribution of genders in the dataset.

## Machine Learning 🤖

- **Model**: Decision Tree Classifier
- **Performance Metrics**: Accuracy, Precision, Recall, F1 Score

## How to Run 🚀

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:
    ```bash
    jupyter notebook project_DS.ipynb
    ```

## Conclusion 🏁

The dataset provides valuable insights into the factors contributing to diabetes. The analysis highlights the importance of family history, BMI, and other health metrics in understanding diabetes risk. The machine learning model helps in predicting diabetic status based on these features.

## License 📜

This project is an open source .

## Acknowledgments 🙏

Special thanks to the contributors and the data science community for their support and resources.
