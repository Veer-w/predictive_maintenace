# Predictive Maintenance Repository

This repository contains code for predictive maintenance using a RandomForestClassifier. The data used in this project is randomly generated.

## Files:

1. **predictive_maintenance.ipynb:** Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.

2. **sensor_data!.csv:** CSV file containing sensor data.

3. **failure_data!.csv:** CSV file containing failure data.

## Code Overview:

- **Data Pre-processing:** Loading and cleaning sensor and failure data, merging the datasets, and performing one-hot encoding.

- **Feature Engineering:** Converting date columns to numerical features.

- **Model Training:** Using a RandomForestClassifier with specified hyperparameters.

- **Evaluation:** Displaying accuracy, classification report, and confusion matrix on the test set.

- **Cross-Validation:** Applying cross-validation to assess model performance.

## Note:

- The data used in this project is randomly generated for demonstration purposes.

## How to Use:

1. Install the required libraries: `matplotlib`, `pandas`, `scikit-learn`.

2. Run the Jupyter Notebook `predictive_maintenance.ipynb`.

3. Ensure that the CSV files `sensor_data!.csv` and `failure_data!.csv` are in the same directory.

4. Explore the code and adapt it for your specific use case.

## Disclaimer:

The data used in this project is randomly generated and does not represent real-world scenarios.

Feel free to reach out for any questions or improvements!

