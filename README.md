# 📊 Customer Churn Prediction using PySpark

This project focuses on predicting customer churn in a telecom dataset using Apache Spark (PySpark). The goal is to identify customers likely to stop using the service, which helps businesses proactively improve retention.

## 🚀 Features

✅ Load and explore a telecom customer dataset  
✅ Perform data preprocessing using PySpark (null handling, encoding, scaling)  
✅ Handle class imbalance using oversampling  
✅ Visualize data using Matplotlib, Seaborn, and Plotly  
✅ Train and evaluate multiple classification models (Logistic Regression, Decision Tree, Random Forest)  
✅ Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrix

## 🧪 Technologies Used

- Python  
- Apache Spark (PySpark)  
- Pandas & NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  

## 📁 Dataset

The dataset used is a telecom churn dataset containing customer demographics, services, and account information.  
Target variable: `Churn` (Yes/No)

## 🧹 Data Preprocessing

- Handled missing values  
- Categorical encoding using StringIndexer  
- Feature vectorization using VectorAssembler  
- Feature scaling using MinMaxScaler  
- Oversampling to address class imbalance

## 🤖 Models Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Model performance is compared using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix

## 📈 Results

After training and evaluating all models, the best performing model can be selected based on F1-score and other metrics.

## 🧰 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/customer-churn-pyspark.git
   cd customer-churn-pyspark
   ```

2. Make sure you have PySpark installed:

   ```bash
   pip install pyspark pandas numpy matplotlib seaborn scikit-learn plotly
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook churn_prediction.ipynb
   ```

4. Follow through the notebook to understand the pipeline and results.

## 📌 Folder Structure

```
customer-churn-pyspark/
│
├── churn_prediction.ipynb       # Main analysis notebook
├── data/
│   └── telecom_customer_churn.csv
├── README.md                    # Project overview
```

## 📜 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

🔍 Built with ❤️ by Zeyad Ahmed
