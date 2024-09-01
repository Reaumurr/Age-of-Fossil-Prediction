
# Age Fossil Prediction

### Project Description
This notebook aims to predict the age of fossils based on various geological features and related data using machine learning models. The project leverages data analysis techniques and machine learning algorithms to develop an accurate prediction model.

### Features

Source taken from Kaggle.com with Dataset Title `Predict the Age of a Fossil`

* Dataset : [Click Here](https://www.kaggle.com/datasets/stealthtechnologies/predict-the-age-of-a-fossil)

This dataset offers a variety of attributes valuable for comprehensive analysis. It contains 4,398 instances and 13 attributes, a mix of categorical and numerical data types. Importantly, the dataset is complete with no null values. Here's a breakdown of the attributes:

| Feature | Description |
| :--- | :--- |
| uranium_lead_ratio | Ratio of uranium to lead isotopes in the fossil sample.|
| carbon_14_ratio | Ratio of carbon-14 isotopes present in the fossil sample.|
| radioactive_decay_series | Measurement of the decay series from parent to daughter isotopes.|
| stratigraphic_layer_depth | Depth of the fossil within the stratigraphic layer, in meters.|
| isotopic_composition | Proportion of different isotopes within the fossil sample.|
| fossil_size | Size of the fossil, in centimeters.|
| fossil_weight | Weight of the fossil, in grams.|
| geological_period | Geological period during which the fossil was formed.|
| surrounding_rock_type | Type of rock surrounding the fossil.|
| paleomagnetic_data | Paleomagnetic orientation data of the fossil site.|
| stratigraphic_position | Position of the fossil within the stratigraphic column.|
| age | Calculated age of the fossil based on various features, in years.|


### Techniques Used
- **Data Preprocessing**: Cleaning and feature transformation.
- **Exploratory Data Analysis (EDA)**: Visualizing and analyzing data to understand feature distributions and correlations.
- **Modeling**: Implementing machine learning models, including Linear Regression, Ridge Regression, and Lasso Regression.
- **Model Evaluation**: Using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R² to evaluate model performance.

### Cara Menggunakan
1. **Install Dependencies**: Ensure all dependencies like `pandas`, `numpy`, `scikit-learn`, and `matplotlib` are installed.

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Notebook**: Open the notebook using Jupyter Notebook or Jupyter Lab and execute each cell to see the analysis and prediction results.

### Reference Links
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib Documentation](https://matplotlib.org/)

### License
This project is licensed under the Apache License 2.0. For more information, visit [Apache Software License](https://www.apache.org/licenses/LICENSE-2.0).

