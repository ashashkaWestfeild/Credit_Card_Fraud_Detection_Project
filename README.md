# Credit Card Fraud Detection using Deep Neural Networks

## Project Overview
This project demonstrates the implementation of a **Deep Neural Network (Multi-Layer Perceptron)** from scratch using NumPy to detect fraudulent credit card transactions. It compares the performance of the neural network against a baseline **Logistic Regression** model on the full Credit Card Fraud Detection dataset.

The project highlights the core mechanics of deep learning by manually implementing:
*   Forward Propagation
*   Backpropagation
*   Gradient Descent Optimization

## Dataset
 The dataset contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
 
 *   **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) (The notebook downloads the data automatically).

## Files
*   `Credit_Card_Fraud_Detection_Project.ipynb`: The main Jupyter Notebook containing the code, analysis, and visualizations.
*   `requirements.txt`: List of Python dependencies required to run the project.

## How to Run
1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook Credit_Card_Fraud_Detection_Project.ipynb
    ```

## Results
The project analyzes the trade-off between model complexity and performance, specifically focusing on **Recall** as the primary metric for fraud detection. The MLP model typically outperforms the linear baseline in detecting non-linear fraud patterns.

## Technologies Used
*   Python
*   NumPy (Core linear algebra)
*   Pandas (Data manipulation)
*   Matplotlib (Visualization)
*   Scikit-Learn (Data preprocessing & splitting)

---
*This project is for educational purposes.*
