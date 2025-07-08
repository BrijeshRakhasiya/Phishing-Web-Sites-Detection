# 🛡️ Phishing URL Detection using Machine Learning

This project focuses on building and comparing several machine learning models to detect **phishing URLs**, which are malicious web links used to deceive users into revealing sensitive information.

## 📌 Objective

To develop a machine learning-based solution that classifies URLs as **phishing** or **legitimate** with high accuracy, helping users and organizations defend against phishing attacks.

---

## 📂 Dataset

- **Features**: The dataset includes various features extracted from URLs such as:
  - Use of `https`
  - Presence of IP address
  - Length of the URL
  - Special characters (`@`, `//`, `-`)
  - Domain-related features
- **Target**: `1` for phishing, `0` for legitimate

---

## 🔧 Models Used

| ML Model                | Accuracy  | F1 Score | Recall   | Precision |
|-------------------------|-----------|----------|----------|-----------|
| Gradient Boosting       | **0.9742**| **0.9772**| 0.9660   | **0.9887**|
| Random Forest           | 0.9697    | 0.9730   | 0.9672   | 0.9789    |
| MLP Classifier          | 0.9697    | 0.9730   | 0.9672   | 0.9789    |
| Support Vector Machine  | 0.9643    | 0.9684   | 0.9573   | 0.9798    |
| Decision Tree           | 0.9575    | 0.9619   | 0.9627   | 0.9611    |
| K-Nearest Neighbors     | 0.9561    | 0.9608   | 0.9596   | 0.9619    |
| Logistic Regression     | 0.9335    | 0.9412   | 0.9297   | 0.9530    |
| Naive Bayes             | 0.6047    | 0.4538   | **0.9945**| 0.2939    |

> ✅ **Gradient Boosting** performed the best in terms of F1-score and precision.

---

## 📊 Evaluation Metrics

- **Accuracy**: Overall correctness of the model
- **F1 Score**: Harmonic mean of precision and recall
- **Recall**: Ability to detect phishing URLs (true positives)
- **Precision**: Correctness of phishing predictions

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/BrijeshRakhasiya/Phishing-Web-Sites-Detection.git

2. Navigate to the project folder:
   ```bash
     cd phishing-url-detection

3. Install dependencies::
   ```bash
     pip install -r requirements.txt

4. Run the notebook:
   ```bash
     jupyter notebook "Phishing URL Detection.ipynb"


# 🚀 Results
Gradient Boosting achieved:

Accuracy: 97.42%

F1-Score: 97.72%

Precision: 98.86%

This model is ideal for real-world deployment to protect against phishing attacks.

## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**
   
