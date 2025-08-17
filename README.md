# Customer Churn Prediction using Neural Networks 🧠

This project predicts **customer churn** using a Neural Network, while addressing **class imbalance**.

## 🚀 Steps in Notebook
1. **Data Preprocessing**  
   - Handle missing values, categorical encoding, normalization  
   - Train/Test split  

2. **Model Building**  
   - Neural Network (Keras Sequential API)  

3. **Model Training**  
   - Early stopping  
   - Class imbalance strategies (baseline, oversampling, SMOTE, etc.)  

4. **Evaluation**  
   - Threshold tuning (best F1-score)  
   - Classification report (precision, recall, F1)  
   - Confusion matrix heatmap  
   - ROC & PR curves  

5. **Results**  
   - Best threshold & metrics printed  
   - Plots stored in `results/`  

## 📊 Example Output
- Best Threshold = `0.373`  
- Best F1-score = `0.72`  

Confusion matrix heatmap:

![Confusion Matrix](results/confusion_matrix.png)

## ⚡ How to Run
1. Clone repo:
   ```bash
   git clone https://github.com/<your-username>/Customer_Churn_NN.git
   cd Customer_Churn_NN
