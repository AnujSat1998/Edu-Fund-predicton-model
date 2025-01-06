# EduFund User Behavior Analysis & Prediction

## Overview
This project focuses on analyzing user behavior and predicting the likelihood of a user creating a financial goal using EduFund's platform. The dataset provided contains information about user activities, demographics, and interactions. The project involves data analysis, handling missing values, feature engineering, and model building using a Random Forest Classifier.

## Installation and Setup
To set up this project locally:

1. **Navigate into the project directory**:
    ```bash
    cd edufund-user-prediction
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:
    ```bash
    jupyter notebook
    ```

## Files
- **data/edufund_user_data.csv**: The raw dataset containing user behavior data.
- **notebooks/edufund_analysis.ipynb**: Jupyter notebook where the data analysis and model building is performed.
- **models/random_forest_model.pkl**: The trained Random Forest model ready for use.
- **requirements.txt**: List of dependencies needed to run the project.

## Project Description
This project involves the following steps:

1. **Data Preprocessing**: 
   - Loading the dataset, handling missing values, and performing data type conversions.
   - Encoding categorical variables and normalizing numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing the dataset to uncover patterns and relationships.
   - Identifying important features for model building.

3. **Model Building**:
   - Using the Random Forest Classifier to predict the likelihood of goal creation based on the features.
   - Evaluating the model's performance using accuracy, precision, and recall metrics.

4. **Feature Importance Analysis**:
   - Analyzing which features are most important in predicting user goal creation.

5. **Handling Missing Values**:
   - Imputing missing values to ensure the robustness of the model.

6. **Final Model**:
   - The final model is saved and ready for predictions, achieving an accuracy of over 50%.

## Contributing
Feel free to open issues or submit pull requests if you have any improvements or suggestions. Contributions are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the EduFund team for providing the dataset and business insights. Inspiration from machine learning tutorials and community contributions.

## Key Insights
- The feature importance analysis highlighted that user activity and demographic data are significant predictors of goal creation.
- Handling missing values effectively ensured the robustness of the model, leading to more reliable predictions.
- The final model, while achieving over 50% accuracy, can be improved further with additional data and advanced techniques.
