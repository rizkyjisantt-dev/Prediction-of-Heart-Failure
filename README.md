# Prediction of Heart Failure

## 📌 About the Project
This project is a machine learning-based web application for predicting heart failure. It provides insights into cardiovascular diseases, which are the leading cause of global mortality. The application is built using **Streamlit** and implements three machine learning models:

- **Gaussian Naive Bayes**
- **K-Nearest Neighbors (K-NN)**
- **Decision Tree Classifier**

## 🎯 Objective
The goal of this project is to help predict heart failure based on clinical features. By leveraging machine learning models, we aim to support early detection and prevention efforts for cardiovascular diseases.

## 📊 Dataset
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data). It contains 12 key features that contribute to predicting heart failure outcomes.

### Dataset Features:
- **Age**: Age of the patient
- **Anaemia**: Reduction of red blood cells or hemoglobin (boolean)
- **Creatinine Phosphokinase**: Enzyme level in the blood (mcg/L)
- **Diabetes**: If the patient has diabetes (boolean)
- **Ejection Fraction**: Percentage of blood leaving the heart with each contraction (percentage)
- **High Blood Pressure**: If the patient has hypertension (boolean)
- **Platelets**: Blood platelet count (kiloplatelets/mL)
- **Serum Creatinine**: Level of serum creatinine in the blood (mg/dL)
- **Serum Sodium**: Level of serum sodium in the blood (mEq/L)
- **Sex**: Gender of the patient (binary)

## 🔧 Implementation
This application consists of six main components:
1. **Home** – Introduction to heart failure
2. **Dataset** – Displays the heart failure dataset
3. **Preprocessing** – Normalization using MinMaxScaler
4. **Modeling** – Training models and evaluating accuracy
5. **Implementation** – User input-based heart failure prediction
6. **Visualization** – Model accuracy comparison using bar charts

## 🛠️ How to Run the Application
1. Clone this repository:
   ```bash
   git clone https://github.com/rizkyjisantt-dev/Prediction-of-Heart-Failure.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Prediction-of-Heart-Failure
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## 📌 Machine Learning Models Used
- **Gaussian Naive Bayes**
- **K-Nearest Neighbors (K-NN)**
- **Decision Tree Classifier**

Each model is evaluated based on accuracy scores, and users can interactively select a model for prediction.

## 📈 Visualization
The application includes an interactive bar chart to compare the accuracy of different models using **Altair**.

## 💡 Future Improvements
- Implement additional models (e.g., SVM, Random Forest, etc.)
- Enhance UI/UX for better user experience
- Deploy the application online for public access

## 🤝 Contributors
- **Mochammad Rizki Aji Santoso** (200411100086)

## 📜 License
This project is licensed under the MIT License.

---

🚀 *Feel free to contribute or raise any issues related to the project!*

