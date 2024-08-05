### My Goal
For this episode of the series, my task is to use binary classification to predict a patient's smoking status given information about various other health indicators.

## Project Description

The project aims to develop a machine learning model for predicting smoking status based on various health-related features. The dataset includes information such as age, weight, blood pressure, and cholesterol levels. The goal is to build a model that can accurately classify individuals as smokers or non-smokers.

## Project Structure

- `data/`
  - `train.csv` : Training dataset.
  - `test.csv` : Test dataset.
- `notebooks/`
  - `smoker_status_prediction.ipynb` : Jupyter Notebook containing the full project code and analysis.
- `src/`
  - `data_preprocessing.py` : Script for data preprocessing steps.
  - `model_training.py` : Script for model training and evaluation.
  - `visualization.py` : Script for data visualization.
- `README.md` : Project overview and instructions.
- `requirements.txt` : List of required Python packages.
- `submission.csv` : Sample submission file.

## Data Description

### Training Data

- **Total Entries**: 159,256
- **Columns**: 24

The training dataset includes the following columns:

- `id`: Unique identifier for each entry.
- `age`: Age of the individual.
- `height(cm)`: Height in centimeters.
- `weight(kg)`: Weight in kilograms.
- `waist(cm)`: Waist circumference in centimeters.
- `eyesight(left)`: Left eye vision score.
- `eyesight(right)`: Right eye vision score.
- `hearing(left)`: Left ear hearing score.
- `hearing(right)`: Right ear hearing score.
- `systolic`: Systolic blood pressure.
- `relaxation`: Relaxation blood pressure.
- `fasting blood sugar`: Fasting blood sugar level.
- `Cholesterol`: Cholesterol level.
- `triglyceride`: Triglyceride level.
- `HDL`: High-density lipoprotein cholesterol level.
- `LDL`: Low-density lipoprotein cholesterol level.
- `hemoglobin`: Hemoglobin level.
- `Urine protein`: Urine protein level.
- `serum creatinine`: Serum creatinine level.
- `AST`: Aspartate aminotransferase level.
- `ALT`: Alanine aminotransferase level.
- `Gtp`: Gamma-glutamyl transferase level.
- `dental caries`: Presence of dental caries (yes/no).
- `smoking`: Target variable indicating smoking status (0 = Non-Smoker, 1 = Smoker).

### Testing Data

- **Total Entries**: 106,171
- **Columns**: 23 (The `smoking` column is excluded from the test data)

The testing dataset includes the same columns as the training data, except the `smoking` column, which is the target variable.

## Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Binary-Prediction-of-Smoker-Status-using-Bio-Signals.git
   cd Binary-Prediction-of-Smoker-Status-using-Bio-Signals
