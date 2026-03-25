📌 About the Project

This project explores different machine learning techniques to identify fraudulent transactions in a credit card dataset. It compares how well each model performs at catching fraud.

🤖 Models Used

| Model | Type | Description |
| Neural Network | Supervised | Learns from labeled fraud examples |
| Isolation Forest | Unsupervised | Flags unusual transactions as anomalies |
| K-Means | Unsupervised | Clusters transactions into normal vs suspicious |
| One-Class SVM | Semi-supervised | Learns boundary around normal transactions |

🛠️ Technologies Used
1. Python
2. TensorFlow / Keras - Neural Network
3. Scikit-learn - Isolation Forest, K-Means, One-Class SVM
4. Pandas & NumPy - Data Handling
5. Matplotlib & Seaborn - Data Visualization

📊 Evaluation Metrics 
1. Precision — Of all fraud predictions, how many were actually fraud?
2. Recall — Of all actual fraud cases, how many did the model catch?
3. Confusion Matrix — Visual breakdown of correct vs incorrect predictions
4. Classification Report — Full summary of model performance

📁 Dataset

[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.
