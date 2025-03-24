Mycotoxin Prediction using Hyperspectral Imaging

Project Overview:
This project aims to predict the concentration of vomitoxin (DON) in corn samples using hyperspectral imaging data. The objective is to build a machine learning model to predict DON levels based on spectral reflectance values.

Dataset:
The dataset contains 448 spectral reflectance values representing different wavelengths.
The target variable is vomitoxin_ppb (DON concentration).
Missing values were handled using median imputation.

How to Run the Project:
Open the Colab Notebook: Google Colab Notebook Link
Upload the Dataset: The dataset (MLE-Assignment.csv) needs to be uploaded when prompted.
Run All Cells: Select Runtime → Run all to execute the entire notebook.
View Results: Evaluation metrics and visualizations will be displayed in the notebook.

Results
After training the model with the best hyperparameters, the following results were achieved:
Mean Absolute Error (MAE): 3847.11 ppb
Root Mean Squared Error (RMSE): 11,410.97 ppb
R² Score: 0.534
These metrics suggest moderate prediction accuracy, with room for further improvements.

Contents
Mycotoxin_Prediction.ipynb: The complete notebook containing all steps from data preprocessing to model evaluation.
Report.pdf: A brief report summarizing the project, including methodology, results, and conclusions.

Future Improvements:
Experiment with ensemble models like XGBoost or LightGBM.
Perform additional feature engineering using domain knowledge.
Implement more advanced hyperparameter tuning.
Deploy the model using Flask or FastAPI.

References:
Scikit-Learn: For model training and evaluation.
Optuna: For hyperparameter tuning.
SHAP: For interpretability.
Matplotlib & Seaborn: For data visualization.

Contact:
If you have any questions, feel free to reach out at:
GitHub: kattabhavana9
Email: 22211a6757@bvrit.ac.in

