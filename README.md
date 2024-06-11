
# RFMS-Based Credit Scoring System

## Project Overview

This project aims to develop a credit scoring system using the RFMS (Recency, Frequency, Monetary, Seasonality) model. The objective is to classify users into 'Good' (low risk) and 'Bad' (high risk) credit categories based on their transaction history. The classification is performed using machine learning models including Logistic Regression and Random Forest, with hyperparameter tuning to optimize performance.

## Project Structure

- `data/`: Directory containing the raw data files.
- `notebooks/`: Jupyter notebooks for data analysis, preprocessing, model training, and evaluation.
- `src/`: Python scripts for data processing, feature engineering, and model functions.
- `README.md`: Project overview and setup instructions.

## Setup Instructions

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/rfms-credit-scoring.git
    cd rfms-credit-scoring
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Data Preparation

1. Place your transaction data files in the `data/` directory.
2. Run the data preprocessing script to clean and prepare the data:
    ```bash
    python src/preprocess_data.py
    ```

### Model Training and Evaluation

1. Open the Jupyter notebooks in the `notebooks/` directory to follow the analysis and model training steps:
    ```bash
    jupyter notebook
    ```
2. Follow the steps in `model_training.ipynb` to train and evaluate the models.

## Key Components

### Data Preprocessing

- Handling missing values
- Feature scaling
- RFMS feature construction

### Model Training

- Logistic Regression
- Random Forest
- Hyperparameter tuning with Grid Search

### Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Results

The models are evaluated on multiple metrics to ensure robust performance. The best-performing model is selected based on these metrics and is used to classify users into 'Good' and 'Bad' credit risk categories.

## Future Work

- Incorporate additional features to improve model performance
- Explore other machine learning models like Gradient Boosting Machines (GBM)
- Implement a real-time scoring system

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Scikit-learn documentation and tutorials
- Data sources and datasets used for analysis and model training

