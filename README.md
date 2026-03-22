# 🚀 Sonar Signal Classification (Rock vs Mine)

## 📌 Project Overview
This project builds a **Machine Learning model** to classify underwater objects as either **Rock (R)** or **Mine (M)** using sonar signal data.

The model learns patterns from sonar signal reflections at different frequencies and predicts the type of object.

---

## 📊 Dataset Information
- Total Columns: **61**
  - **60 Features** → Sonar signal reflections at different frequencies  
  - **1 Label** → Object type (`R` = Rock, `M` = Mine)  
- Total Samples: **208**

---

## 🧠 Machine Learning Approach
- Type: **Supervised Learning (Classification)**
- Algorithm Used: **Logistic Regression**

---

## ⚙️ Steps Performed
1. Data Loading using Pandas  
2. Data Preprocessing  
3. Splitting data into:
   - Features (`X`)
   - Labels (`y`)
4. Train-Test Split:
   - `test_size = 0.1`
   - `stratify = y` (to maintain class balance)
5. Model Training using Logistic Regression  
6. Model Evaluation using Accuracy Score  

---

## 📈 Results
- **Training Accuracy:** 83.4%  
- **Testing Accuracy:** 76.2%  

---

## 📊 Visualization
- Bar graph comparing **Train vs Test Accuracy**
- (Optional) Confusion Matrix for performance analysis  

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
