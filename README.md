
# Age Fossil Prediction

## Project Description
### Background
Fossils provide a window into the Earth's geological and biological history, offering insights into past life forms, climates, and environments. Accurately determining the age of fossils is crucial for reconstructing Earth's history, understanding evolutionary processes, and guiding conservation efforts. Traditional methods of dating fossils, such as radiometric dating, rely heavily on specific isotope ratios, which can vary in reliability depending on the age and composition of the sample.

Given the importance of accurate fossil dating in scientific research, there is a need for a more comprehensive approach that integrates multiple data sources and uses advanced analytical techniques. This project leverages machine learning to predict fossil ages based on a dataset containing various geological features and isotope ratios. By employing different regression models, this project aims to improve the precision and reliability of fossil age estimations, contributing to more informed scientific conclusions and research efforts.

### Problem Statement
The task of dating fossils accurately is challenged by the diversity of geological and isotopic factors that can affect the age estimations. Traditional methods may not fully account for the complex relationships between these factors, leading to uncertainties and potential errors in fossil age determination.

To address this issue, this project aims to:

Develop a predictive model using machine learning techniques that integrates multiple geological features and isotopic ratios to enhance the accuracy of fossil age predictions.
Compare and evaluate the performance of different regression models—Linear Regression, Ridge Regression, and Lasso Regression—based on their ability to predict fossil ages using the dataset obtained from Kaggle.
Provide actionable insights on the best modeling approach for different contexts, whether high precision, quick implementation, or handling multicollinearity among features is prioritized.

## Features

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


## Techniques Used
- **Data Preprocessing**: Cleaning and feature transformation.
- **Exploratory Data Analysis (EDA)**: Visualizing and analyzing data to understand feature distributions and correlations.
- **Modeling**: Implementing machine learning models, including Linear Regression, Ridge Regression, and Lasso Regression.
- **Model Evaluation**: Using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R² to evaluate model performance.

## How to Use
1. **Install Dependencies**: Ensure all dependencies like `pandas`, `numpy`, `scikit-learn`, and `matplotlib` are installed.

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Notebook**: Open the notebook using Jupyter Notebook or Jupyter Lab and execute each cell to see the analysis and prediction results.

## Conclusion

The analysis reveals that while all three regression models—Linear, Ridge, and Lasso—can be used to predict the age of fossils, each model has its strengths depending on the specific needs of the project. Lasso Regression is suitable for high-precision scenarios due to its capability to minimize prediction errors, making it ideal for scientific research requiring high accuracy. On the other hand, Linear Regression offers a simpler and more interpretable approach that performs adequately when quick implementation and easy explanation are required.

Ridge and Lasso models are particularly useful when dealing with multicollinearity among predictor variables, such as various isotopic data. The regularization in these models helps reduce overfitting, resulting in more stable and reliable predictions. However, continuous evaluation of the model performance is recommended to ensure alignment with changing data landscapes and research objectives. This approach helps maintain the relevance and accuracy of fossil age predictions over time, enabling more accurate and efficient analysis tailored to specific business or research needs.

By integrating machine learning techniques with geological data, this project demonstrates the potential of data-driven methods to enhance the accuracy and reliability of fossil dating, providing valuable contributions to scientific research and historical reconstruction efforts.

## Reference Links
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib Documentation](https://matplotlib.org/)

## License
This project is licensed under the Apache License 2.0. For more information, visit [Apache Software License](https://www.apache.org/licenses/LICENSE-2.0).

