# Iris Classification using PyTorch

## Objective

This project demonstrates the implementation of a deep learning model using PyTorch to classify the famous Iris dataset. The main goals are:

- Build a neural network for multi-class classification
- Train the model on the Iris dataset
- Evaluate the model's performance using various metrics

## Dataset Description

The Iris dataset is a classic in machine learning, consisting of 150 samples with 4 features each:

1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

The target variable has 3 classes representing Iris flower species:

- Setosa
- Versicolor
- Virginica

## Steps to Run the Code in Jupyter

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Run the notebook:
   - Navigate to the `Assignment2_Iris.ipynb` file
   - Run all cells to preprocess data, train the model, and evaluate performance

## Model Evaluation

The model's performance is assessed using:

- Accuracy
- Confusion Matrix
- Classification Report
- ROC curves for multi-class classification

## Dependencies and Installation Instructions

### Required Libraries

```
pandas==2.0.3
numpy==1.24.3
scikit-learn==1.2.2
torch==2.0.1
matplotlib==3.7.2
```

### Installation

Install all required libraries via pip:

```bash
pip install -r requirements.txt
```

Or install each library individually:

```bash
pip install pandas numpy scikit-learn torch matplotlib
```

**Note:** For PyTorch installation, please refer to the [official PyTorch installation guide](https://pytorch.org/get-started/locally/) to ensure you install the correct version for your system and CUDA requirements.

## Conclusion

This project showcases the implementation of a simple neural network for classification tasks using PyTorch. The Iris dataset serves as an excellent starting point for those new to classification problems and provides hands-on experience with deep learning frameworks like PyTorch.
