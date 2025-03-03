# Resume Categorization System

## 📌 Project Overview  
The **Resume Categorization System** is a machine learning-based application designed to automate the classification of resumes into predefined job categories. This solution reduces manual effort in HR processes, enhances accuracy, and minimizes human intervention.

## 🚀 Features  
✅ Preprocessing of raw resumes (text cleaning, tokenization, stopword removal, etc.)  
✅ Exploratory Data Analysis (EDA) including visualization and word cloud generation  
✅ Feature extraction using CountVectorizer with n-grams (Bi-grams, Tri-grams)  
✅ Model training using classification algorithms (e.g., Logistic Regression, Random Forest, SVM, XGBoost)  
✅ Performance evaluation using accuracy, precision, recall, and F1-score  
✅ End-to-end pipeline for training and predicting resume categories  

## 📂 Dataset  
- The dataset consists of resumes labeled with job categories.
- Contains **79 rows and 3 columns** (`File_Path`, `Resume_Text`, `Category`).
- The `Resume_Text` column stores extracted resume content.
- No missing or duplicate values.

## 🔧 Technologies Used  
- Python 🐍  
- Scikit-learn 🤖  
- XGBoost ⚡  
- Pandas & NumPy 🔢  
- Natural Language Processing (NLP) 📝  
- TensorFlow/Keras (optional for deep learning)  
- Jupyter Notebook 📓  


## 🛠️ Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/rangane90/Resume-Categorization
   cd Resume-Categorization-System
   ```
2. Create a virtual environment (optional but recommended):  
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Usage  
1. Load the dataset and preprocess resumes.
2. Perform **Exploratory Data Analysis (EDA)** and visualize category-wise distributions.
3. Train the model using different ML classifiers.
4. Evaluate the model performance.
5. Use the trained model to predict the category of new resumes.

## 📈 Model Performance (XGBoost)  
| Metric       | Score  |
|-------------|--------|
| Accuracy    | 95%    |
| Precision   | 96%    |
| Recall      | 95%    |
| F1-Score    | 95%    |

### Classification Report (XGBoost)  
```
   precision    recall  f1-score   support

           0       1.00      1.00      1.00         5
           1       0.86      1.00      0.92         6
           2       1.00      1.00      1.00         4
           3       1.00      0.80      0.89         5

    accuracy                           0.95        20
   macro avg       0.96      0.95      0.95        20
weighted avg       0.96      0.95      0.95        20
```

## 📌 Future Enhancements  
🔹 Implement deep learning-based classification models  
🔹 Deploy the model as a web app using Flask/Django  
🔹 Enhance the dataset with more labeled samples  

## 🤝 Contribution  
Contributions are welcome! Feel free to fork this repo, create a branch, and submit a pull request.  

## 📝 License  
This project is licensed under the MIT License.  

