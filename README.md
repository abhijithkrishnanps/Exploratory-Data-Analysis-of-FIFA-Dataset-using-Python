# Exploratory-Data-Analysis-of-FIFA-Dataset-using-Python
Exploratory Data Analysis of FIFA Player Dataset using Python. Includes data cleaning, preprocessing, and visualization of player attributes like age, nationality, club, and performance metrics. Covers correlation analysis, feature engineering, and predictive modeling to estimate player wages and uncover key insights.

FIFA Player Data Analysis

Overview
This project performs **Exploratory Data Analysis (EDA)** on a FIFA player dataset using Python. It focuses on understanding player attributes, distributions, and relationships between variables, along with building a predictive model to estimate player wages.

Objectives
* Clean and preprocess raw player data
* Analyze distributions of key attributes (age, rating, wages, etc.)
* Identify correlations between player performance metrics
* Perform feature engineering for better insights
* Build a regression model to predict player wages

Dataset
The dataset contains detailed information about FIFA players, including:
* Personal details (age, nationality, club)
* Physical attributes (height, weight)
* Performance metrics (overall rating, potential)
* Financial data (wages, value)

Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

Project Workflow

1. Data Cleaning
   * Handling missing values
   * Formatting columns
   * Removing inconsistencies

2. Exploratory Data Analysis
   * Statistical summaries
   * Distribution plots (histograms, boxplots)
   * Player attribute comparisons

3. Correlation Analysis
   * Heatmaps to identify relationships
   * Key factors affecting wages and performance

4. Feature Engineering
   * Selecting relevant features
   * Transforming variables for modeling

5. Model Building
   * Gradient Boosting Regressor
   * Predicting player wages based on attributes

Key Insights
* Player wages strongly correlate with overall rating and potential
* Younger players with high potential show significant value trends
* Certain physical and performance attributes influence valuation

How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/fifa-eda.git
   ```
   
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook

   ```bash
   jupyter notebook Exploratory_data_analysis.ipynb
   ```

Project Structure

├── Exploratory_data_analysis.ipynb
├── fifa_dataset.csv
├── README.md
└── requirements.txt

Future Improvements
* Add more advanced machine learning models
* Deploy as a web app/dashboard
* Include interactive visualizations

Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.
