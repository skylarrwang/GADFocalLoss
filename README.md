# **Project README**

## **Overview**
This project is designed to analyze graph anomaly detection using a GraphSAGE-based model with tailored loss functions and hyperparameter tuning. The provided Jupyter Notebook contains all necessary code for package installation, dataset preprocessing, model training, evaluation, and visualization.

---

## **Usage Instructions**

### **1. Download the Notebook**
Download the provided Jupyter Notebook file (`GAD_Focal.ipynb`) to your local system.

### **2. Download the JSON File**
Download the associated hyperparameter configuration files in JSON format (`gen_1000_hyperparameters.json` and gen_time_hyperparameters.json`). Ensure it is stored in the same directory as the notebook or update the file path in the notebook if necessary.

### **3. Run Setup Cells**
Open the notebook in Jupyter, Google Colab, or your preferred environment. Start by running the setup cells to:
- Install any required dependencies
- Import necessary libraries
- Load the dataset and initialize configurations

### **4. Run the Notebook**
The notebook is designed to be run sequentially. You can either:
- **Run cells step-by-step**: Follow the logical flow of the notebook, executing each cell in order.
- **Run All**: Select "Run All" in your notebook environment to execute all cells automatically. The notebook should run without interruptions if dependencies are properly installed.

---

## **Dependencies**
Ensure the following libraries are installed:
- `torch`
- `torch_geometric`
- `pytorch_lightning `
- `pygod`
- `numpy`
- `sklearn`
- `pandas`
- `matplotlib`
- `optuna`

If missing, install them using the first cell in the notebook. Please contact us with questions for setup / reproducibility!
