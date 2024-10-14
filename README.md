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
```

## **Installation**

1. Clone the repository:
```bash
git clone https://github.com/LazarusAA/AgriPredict-Climate-Change-Impact-on-Agriculture.git
```
2. Navigate to the project directory:
```bash
cd AgriPredict-Climate-Change-Impact-on-Agriculture
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## **Dataset** 

The dataset used includes variables related to climate and agricultural outcomes, such as temperature, CO2 emissions, crop yield, and economic impact. You can use your own dataset in ```.csv``` format by placing it in the root directory and updating the file path in the notebook.

## **Usage**

1. Launch the Jupyter Notebook:
```bash
jupyter notebook
```
2. Open the notebook file ```climate_change_impact.ipynb``` and execute the cells step by step to preprocess the data, train the model, and evaluate the results.

3. You can customize the notebook by modifying the dataset or model parameters.

## **Running the Model**

Once the dataset is preprocessed, the notebook will guide you through training the Random Forest model, tuning it with RandomizedSearchCV, and evaluating its performance using Mean Absolute Error.

## **Outputs**

- **Feature Importance:** Visualizations of the top contributing features in the model.
- **Model Performance:** Scatter plots comparing actual vs. predicted values for economic impact.

# **Project Structure** 

```bash
agri-predict/
│
├── climate_change_impact.ipynb                                  # Main Jupyter Notebook
├── climate_change_impact_on_agriculture_2024.csv                # Dataset (replace with your data)
├── README.md                                                    # Project Documentation
└── requirements.txt                                             # Required dependencies
```
# **Results**

The model identifies Crop Yield per Hectare, Irrigation Access, and Total Precipitation as key drivers of economic outcomes in agriculture. The Random Forest model achieves a Mean Absolute Error of 227.51 million USD, with potential for further improvement by incorporating more data or trying advanced models.
