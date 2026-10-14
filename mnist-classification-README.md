# MNIST Handwritten Digit Classification

## Objective
Explore 28×28 handwritten digit images and compare classification approaches, including binary digit-5 detection, SGD, Random Forest, multiclass SVM/SGD, confusion matrices, and KNN experiments with noisy/shifted images.

## Tools
Python, pandas, NumPy, Matplotlib, SciPy, scikit-learn, Jupyter Notebook.

## Dataset
Download the [Digit Recognizer dataset on Kaggle](https://www.kaggle.com/competitions/digit-recognizer/data). Place `train.csv` in a local `data/` folder or update `DATA_PATH` in the notebook. The dataset is not included in this repository.

## Run
1. Install dependencies: `pip install -r requirements.txt`
2. Download `train.csv` from Kaggle.
3. Set `DATA_PATH` to the CSV file.
4. Open `mnist-classification.ipynb` and run cells in order. Some cross-validation and augmentation steps may take several minutes.

## Topics covered
- Data loading and visualization
- Binary classification: digit 5 vs. all other digits
- Precision, recall, F1, precision-recall curves, ROC-AUC
- Random Forest comparison
- Multiclass classification with SVM and SGD
- Confusion matrices and error analysis
- Noisy-image cleanup and image-shift augmentation

## Results
Record accuracy and evaluation metrics from your completed notebook run here. Results are intentionally not hard-coded because they depend on the exact run and environment.
