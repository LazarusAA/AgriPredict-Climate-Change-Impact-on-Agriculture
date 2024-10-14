# **AgriPredict: Climate Change Impact on Agriculture**

## **Project Overview**
AgriPredict is a machine learning project that explores the economic impact of climate change on agriculture. By analyzing factors such as temperature, CO2 emissions, precipitation, and crop yield, the model predicts the economic outcomes in agriculture. The project leverages a **Random Forest Regressor** to model the relationships between climate and agricultural productivity.

## **Key Features**
- **Data Preprocessing**: Encoding of categorical variables and scaling of numerical data.
- **Exploratory Data Analysis**: Visualizations of the relationships between environmental factors and agricultural outcomes.
- **Model Training and Tuning**: Training a Random Forest model and tuning it using `RandomizedSearchCV`.
- **Feature Importance Analysis**: Understanding which variables most influence the economic impact.
- **Prediction and Evaluation**: Evaluating the model's performance with **Mean Absolute Error (MAE)** and visualizing actual vs. predicted values.

## **Technologies Used**
- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`

## **Getting Started**
### Prerequisites
To run the project, ensure you have Python 3.x installed along with the required libraries. Install the dependencies using the following command:

```bash
pip install -r requirements.txt
