# 🎬 Netflix Data Analysis and Linear Regression Model

## 📌 Overview
This project explores the Netflix dataset and builds a **Linear Regression model** to predict the release year of content based on features like type, rating, and country.  
It demonstrates data cleaning, exploratory data analysis (EDA), feature encoding, and model evaluation using Python.

---

## 🧩 Steps Performed
1. **Data Loading & Inspection**  
   - Loaded the dataset using Pandas  
   - Checked shape, column names, and data types  

2. **Data Cleaning**  
   - Handled missing values in `director`, `cast`, `country`, and `rating`  
   - Filled missing values with mode or placeholder values like `'Unknown'`

3. **Exploratory Data Analysis (EDA)**  
   - Visualized content type distribution (Movies vs TV Shows)  
   - Found top countries by content  
   - Analyzed content added over the years  

4. **Feature Encoding & Splitting**  
   - Encoded categorical features (`type`, `rating`, `country`) using LabelEncoder  
   - Split data into training (80%) and testing (20%) sets  

5. **Model Building**  
   - Built a **Linear Regression** model using `scikit-learn`  
   - Trained the model and made predictions  

6. **Model Evaluation**  
   - Evaluated model using:
     - R² Score  
     - Mean Absolute Error (MAE)  
     - Mean Squared Error (MSE)  
   - Visualized Actual vs Predicted Release Years  

---

## 🧰 Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📊 Results
- The Linear Regression model provides insights into patterns in Netflix data.  
- R² Score might be low due to categorical nature of data — this is expected for educational demonstration.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Netflix-LinearRegression-EDA.git
   ```
2. Navigate into the project folder:
   ```bash
   cd Netflix-LinearRegression-EDA
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook or script:
   ```bash
   jupyter notebook notebooks/netflix_eda_model.ipynb
   ```

---

## 📁 Dataset
The dataset used is **`netflix_titles.csv`** from [Kaggle: Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows).

---

## ✨ Future Improvements
- Try **classification** to predict whether content is a *Movie* or *TV Show*  
- Use **Random Forest** or **XGBoost** for better performance  
- Build a simple **Streamlit dashboard** for interactive visualization  

---

## 👨‍💻 Author
**Your Name**  
Data Science Enthusiast | Python | Machine Learning
