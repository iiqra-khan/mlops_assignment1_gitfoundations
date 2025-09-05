# Tyre Classification with Early Stopping

This project implements a tyre classification model using machine learning techniques, featuring early stopping to prevent overfitting.

## Features

- Tyre image classification
- Early stopping during training
- Model evaluation and metrics

## Folder Structure

- `earlystopping.ipynb` - Source code for model training and evaluation
- `EDA.ipynb` - exploratory data analysis 
- `README.md` - Project documentation

## Requirements

- Python 3.x
- TensorFlow or PyTorch
- NumPy, pandas, scikit-learn

## Usage

1. Clone the repository.
2. Install dependencies:  
    ```bash
    pip install -r requirements.txt
    ```
3. Run training script:  
    ```bash
    python src/train.py
    ```

## Early Stopping

Early stopping monitors validation loss and halts training when performance stops improving, helping to avoid overfitting.

## License

This project is licensed under the MIT License.