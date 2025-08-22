# 🛫 Airline Passenger Satisfaction using Machine Learning

This project analyzes airline passenger data and builds **Machine Learning models** to predict whether a passenger is **satisfied or dissatisfied** with their flight experience.  

---

## 📌 Overview

Airline companies strive to understand what factors impact customer satisfaction.  
This project uses ML techniques to:  
- Explore passenger demographics and travel patterns  
- Identify key features influencing satisfaction  
- Build predictive models to classify passenger satisfaction  

---

## 📂 Dataset

- Source: [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)  
- Features include:  
  - **Demographics**: Gender, Age, Customer type  
  - **Flight Details**: Class, Flight distance, Delay info  
  - **Service Ratings**: In-flight entertainment, Seat comfort, Food, etc.  
- Target variable: `satisfaction` (*Satisfied / Neutral or Dissatisfied*)  

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Jupyter Notebook**
- Libraries:
  - pandas, numpy → Data handling  
  - matplotlib, seaborn → Data visualization  
  - scikit-learn → ML models & evaluation  

---

## ⚙️ Methodology

1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical features  
   - Normalize/standardize features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize class imbalance  
   - Correlation heatmaps  
   - Feature importance analysis  

3. **Model Training**  
   - Logistic Regression  
   - Decision Trees  
   - Random Forest  
   - Gradient Boosting  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix  

---

## 📊 Results

- Compared different ML models  
- Identified top factors influencing satisfaction (e.g., service quality, flight delays, class)  
- Best performing model achieved **[insert accuracy here, e.g., 92%]**  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MinnaFathima/AirLine-Passenger-Satisfaction-using-Machine-Learning.git
   cd AirLine-Passenger-Satisfaction-using-Machine-Learning

2. Install dependencies:
   pip install -r requirements.txt


3. Open the Jupyter Notebook:
   jupyter notebook "Airline Passenger Satisfaction using ML.ipynb"

   ---
   

📌 Future Improvements

Hyperparameter tuning for better accuracy

Deploy as a web app (Flask/Streamlit) for real-time predictions

Incorporate deep learning for enhanced feature learning


