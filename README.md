# ✈️ Airlines Delay Flight Prediction using Machine Learning

##  Project Overview  
This project predicts whether a flight will be **delayed** or **on time** using various **Machine Learning algorithms**.  
We explore flight delay data, perform **data preprocessing**, train multiple classification models, and evaluate them using accuracy, ROC curves, and feature importance.

---
## Using Requirements
pandas,
numpy,
matplotlib,
seaborn,
scikit-learn,
xgboost

---

##  Dataset
- **Source**: Airline on-time performance dataset (Kaggle-https://www.kaggle.com/datasets/ulrikthygepedersen/airlines-delay)
- **Features**:
  - `Airline` – Airline carrier code  
  - `Flight` – Flight number  
  - `Origin` – Departure airport  
  - `Destination` – Arrival airport  
  - `Distance` – Distance between airports  
  - `Scheduled_Departure` – Scheduled departure time  
    
- **Target**:
  - `Delayed` – 1 if delayed, 0 if on-time

---

##  Workflow
1. **Import Libraries**  
2. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Class distribution check  
   - Outlier detection  
   - Correlation heatmaps  
3. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features  
   - Normalization/Scaling  
4. **Model Training**  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Logistic Regression  
   - XGBoost Classifier  
   - AdaBoost Classifier  
5. **Model Evaluation**  
   - Accuracy Score  
   - ROC Curve Visualization  
   - Feature Importance Plot  

---

##  Results
| Model                   | Accuracy |
|------------------------|----------|
| Decision Tree           | **68%**  |
| Random Forest           | **73%**  |
| Logistic Regression     | **58%**  |
| XGBoost                 | **66%**  |
| AdaBoost                | **62%**  |

---

##  Key Visualizations
- **Class Distribution**                                                                                           <img width="614" height="443" alt="Screenshot 2025-08-10 081305" src="https://github.com/user-attachments/assets/db26da5b-5ffd-4ce8-832f-662d4d09da97" />
  
   
<img width="608" height="444" alt="Screenshot 2025-08-10 081325" src="https://github.com/user-attachments/assets/cb42981e-e605-4b59-a01c-9b8ae87049c7" />

- **Correlation Heatmap**  
  
<img width="805" height="489" alt="Screenshot 2025-08-10 081341" src="https://github.com/user-attachments/assets/47846380-fdc6-41b6-a10f-00eea4a1e3ca" />

- **ROC Curves**  
  
<img width="578" height="472" alt="Screenshot 2025-08-10 081410" src="https://github.com/user-attachments/assets/4c11263d-5278-4ca9-80e9-709a03ac9c81" />

- **Feature Importance (Random Forest)**  
   
<img width="814" height="631" alt="Screenshot 2025-08-10 081427" src="https://github.com/user-attachments/assets/e1c3e615-cac3-4cd7-871a-c49644f4db4d" />

-

# Run Jupyter Notebook
jupyter notebook Airlines_Delay_Flight_Prediction_using_ML.ipynb
