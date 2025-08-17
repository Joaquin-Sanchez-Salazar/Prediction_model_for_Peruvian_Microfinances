# Prediction Model for Peruvian Microfinances

This repository contains the datasets and Python scripts developed to build, train, and validate machine learning models for predicting outcomes in the Peruvian microfinance sector.  

The project includes:  
1. Data preprocessing.  
2. Training and validation of an Artificial Neural Network (ANN) model.  
3. Training and validation of a Convolutional Neural Network (CNN) model.  

---

## Repository Structure

- **`Dataset IA`**  
  A folder containing all datasets used in this project, organized by year.  
  - Available in release tag **v1.0.0** as a compressed `.zip` file.  

- **`Main.ipynb`**  
  Jupyter Notebook for training and validating the **ANN model**.  

- **`CNN_test.ipynb`**  
  Jupyter Notebook for training and validating the **CNN model**.  

- **`Pre-procesamiento.ipynb`**  
  Jupyter Notebook for **data preprocessing**, transforming the raw datasets into a cleaned and structured dataframe for modeling.  

- **`df_modelo_final`**  
  The final processed dataframe generated in *Pre-procesamiento.ipynb*, used as input for both models.  

- **`requirements.txt`**  
  List of required Python packages and dependencies for running the ANN model.  

- **Model files**  
  Saved models generated during training.  
  - **`ANN_uni_mejor_modelo.keras`**: the best-performing ANN model to date.  

---

## Requirements & Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Prediction_model_for_Peruvian_Microfinances.git
   cd Prediction_model_for_Peruvian_Microfinances```
2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt```

## Requirements & Installation
1. Run Pre-procesamiento.ipynb to preprocess the raw datasets and generate the final dataframe.
2. Use Main.ipynb to train and validate the ANN model.
3. Use CNN_test.ipynb to train and validate the CNN model.

## Notes
- The datasets are not included directly in the repository for storage efficiency. Please download them from the release section (v1.0.0).
- The ANN and CNN models were developed and evaluated for research purposes in the context of Peruvian microfinance prediction.
