# EduFund User Behavior Analysis & Prediction

## Overview
This project focuses on analyzing user behavior data from EduFund to predict the likelihood of users creating financial goals. The goal was to provide actionable insights that could help the platform enhance user engagement.

## Objective
The objective of this project was to:
- Analyze user data to understand behavioral patterns.
- Handle missing values effectively to ensure data integrity.
- Build a predictive model to forecast goal creation behavior.

## Approach
### Data Preprocessing
- Performed **Exploratory Data Analysis (EDA)** to understand the dataset's structure.
- Handled **missing values** through imputation techniques to fill in gaps in the data.

### Model Building
- Engineered relevant features from user data (e.g., demographics, platform interactions).
- Implemented a **Random Forest Classifier** to predict goal creation behavior.

### Results
- The model achieved an accuracy of over 50%, offering useful insights into user engagement trends.

## Technologies Used
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Jupyter Notebooks**

## Installation
To run this project on your local machine, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/edufund-user-prediction.git

Navigate into the project directory:

bash
Copy code
cd edufund-user-prediction
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy code
jupyter notebook
Files
data/edufund_user_data.csv: The raw dataset containing user behavior data.
notebooks/edufund_analysis.ipynb: Jupyter notebook where the data analysis and model building is performed.
models/random_forest_model.pkl: The trained Random Forest model ready for use.
requirements.txt: List of dependencies needed to run the project.
Contributing
Feel free to open issues or submit pull requests if you have any improvements or suggestions. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the EduFund team for providing the dataset and business insights.
Inspiration from machine learning tutorials and community contributions.
Key Insights
The feature importance analysis highlighted that user activity and demographic data are significant predictors of goal creation.
Handling missing values effectively ensured the robustness of the model, leading to more reliable predictions.
The final model, while achieving over 50% accuracy, can be improved further with additional data and advanced techniques.
How to Use
To run the project locally:

Navigate into the project directory:

bash
Copy code
cd edufund-user-prediction
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:

bash
Copy code
jupyter notebook
Files
data/edufund_user_data.csv: The raw dataset containing user behavior data.
notebooks/edufund_analysis.ipynb: Jupyter notebook where the data analysis and model building is performed.
models/random_forest_model.pkl: The trained Random Forest model ready for use.
requirements.txt: List of dependencies needed to run the project.
markdown
Copy code

### Key Additions:
- **Instructions for how to install dependencies and run Jupyter notebook**: Added steps for navigating to the project directory and installing required dependencies (`pip install -r requirements.txt`) and running the notebook (`jupyter notebook`).
- **Files Section**: Added detailed descriptions of the files included in the project like the dataset, notebook, model file, and requirements.
- **How to Use**: Added clear steps for setting up the project locally.

Let me know if this works for you!
