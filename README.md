# 🏠 Loan Status Prediction

This project implements a **Support Vector Machine (SVM)** classifier to predict loan approval status based on various applicant features. The model is built using Python, leveraging popular data science libraries like `pandas`, `numpy`, `seaborn`, and `scikit-learn`.

## 📊 Dataset

The dataset used for this project is `train_u6lujuX_CVtuZ9i (1).csv`, which contains information about loan applicants, including their demographics, income, loan amount, credit history, and the final loan status (approved or not approved).

## ✨ Features

* **Data Loading and Inspection**: Loads the dataset into a pandas DataFrame and provides initial insights into its structure and content.
* **Missing Value Handling**: Identifies and handles missing values by dropping rows with `NaN` entries.
* **Categorical to Numerical Conversion**: Transforms categorical features (Gender, Married, Dependents, Education, Self_Employed, Property_Area, Loan_Status) into numerical representations using label encoding and direct replacement for better model compatibility.
* **Data Splitting**: Divides the dataset into training and testing sets to evaluate model performance.
* **Model Training**: Trains an SVM classifier with a linear kernel on the preprocessed training data.
* **Accuracy Evaluation**: Assesses the model's performance by calculating accuracy scores on both the training and test datasets.

## 🛠️ Technologies Used

* **Python**
* **pandas**: For data manipulation and analysis.
* **numpy**: For numerical operations.
* **seaborn**: For data visualization (specifically, count plots for exploratory analysis).
* **scikit-learn**: For machine learning, including SVM and accuracy metrics.

## 🚀 Getting Started

To run this project, ensure you have Python installed and the necessary libraries.

### Installation

1. **Clone the repository (if applicable):**

```
git clone <repository_url>
cd <repository_name>
```

2. **Install the required Python packages:**

```
pip install pandas numpy seaborn scikit-learn
```

### Usage

1. **Place the dataset**: Make sure the `train_u6lujuX_CVtuZ9i (1).csv` file is in the same directory as the Jupyter notebook (`Loan_Status.ipynb`).
2. **Run the Jupyter Notebook**: Open and run the `Loan_Status.ipynb` notebook in a Jupyter environment (e.g., Jupyter Lab, Jupyter Notebook, Google Colab).

The notebook will:
   * Load and preprocess the data.
   * Train the SVM model.
   * Print the accuracy scores on the training and test datasets.

## 📈 Results

The notebook outputs the accuracy of the SVM model on both the training and test datasets. For instance, the provided notebook snippet shows:

* **Accuracy on training data**: 0.7986 (approximately 79.86%)
* **Accuracy on test data**: 0.8333 (approximately 83.33%)

This indicates that the model generalizes reasonably well to unseen data.

## 🧑‍💻 Contributing

Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open-source and available under the MIT License.
