# Real-time Healthcare Insights and Predictive Analysis of Cardiovascular Disease
## Project Overview
This project is a Data Science and Big Data Analytics solution that uses Apache Spark to analyze and predict trends in Cardiovascular Disease (CVD) death rates.
The goal is to move healthcare from a reactive to a proactive model by providing dynamic, real-time insights and long-term trend forecasting.
## Key Features
- Historical Data Analysis (2010–2020): Deep dive into 10 years of historical CVD death rate data to understand past trends and risk factors.
- Scalable Architecture: Leverages Apache Spark for high-speed, large-scale data processing and model training.
- Real-time Simulation: Simulates a real-time data monitoring system to provide immediate health insights.
- Predictive Analytics: Uses Spark-based machine learning (likely MLlib) to forecast CVD death rates and future trends up to the year 2030.
- Proactive Decision Making: Provides actionable predictions to assist healthcare systems and policy makers with resource planning and intervention strategies.
## Technologies Used
- Big Data / Analytics: Apache Spark
- Language	: Python (using PySpark).
- Data Tools :	PySpark	Python API for Spark, used for data processing and machine learning.
- Visualization	: Pandas, Plotly Express
- Environment	: Jupyter/Colab Notebook
## Getting Started
Follow these steps to get the project running on your local machine.
### Prerequisites
You need a working installation of Apache Spark and Python 3.x.
- Java: Ensure Java 8 or later is installed (required for Spark).
- Apache Spark: Download and set up Spark.
- Python: Python 3.7+ is recommended.

## Installation
1. Clone the Repository : 
Bash
  - git clone [Your-Repo-Link-Here]
  - cd [cardiovascular_prediction]
2. Install Python Dependencies:
Bash
  - pip install pyspark pandas plotly
3. Usage
- Data Setup: Ensure your cleaned dataset (cleaned_structured_data_final.csv) is accessible to your Spark environment (e.g., in a local directory or a configured cloud storage like Google Drive, as used in cvd_predict.py).
- Run the Analysis: Execute the main script using spark-submit:
  - Bash :
     spark-submit cvd_predict.py


Alternatively, open the project in a Jupyter or Colab environment and run the notebook cells.


## Project Structure 
- cvd_predict.py : The main Spark/PySpark script containing the data loading, EDA, real-time simulation logic, and the predictive model training/forecasting for 2030.
- data/ : (Recommended) Directory for storing the raw and cleaned data files.
- notebooks/ : (Recommended) Directory for exploratory notebooks
