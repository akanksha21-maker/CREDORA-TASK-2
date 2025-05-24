# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)  
**Akanksha Bhosle | Data Science Intern @ Credora**

---

## 📌 Task Overview

As part of my Week 2 task at Credora, I worked on the famous Titanic dataset from Kaggle. The goal was to clean the dataset, handle missing values, convert categorical data, and perform exploratory data analysis (EDA) to uncover patterns related to passenger survival.

---

## 📂 Dataset Used

Dataset Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

**Files Used:**
- `train.csv`: Main file used for cleaning and analysis.
- `test.csv`: Used for structure reference (not required for EDA).
- `gender_submission.csv`: Sample submission format (for Kaggle competition).

---

## 🧹 Data Cleaning & Preprocessing

- Handled missing values in `Age` (median) and `Embarked` (mode).
- Dropped columns with too many nulls or low relevance: `Cabin`, `Ticket`, `Name`.
- Converted `Sex` to numeric (male = 0, female = 1).
- One-hot encoded `Embarked`.
- Verified final structure using `.info()` and `.head()`.

---

## 📊 Visualizations Created

1. **Survival Countplot**  
2. **Survival by Gender**  
3. **Age Distribution (Histogram)**  
4. **Fare vs Survival (Boxplot)**  
5. **Correlation Heatmap**

---

## 💡 Key Insights

- Most passengers did not survive.
- Females had a much higher survival rate than males.
- First-class passengers and children had higher survival chances.
- Passengers who paid higher fares were more likely to survive.
- Strong correlation between `Survived`, `Sex`, `Pclass`, and `Fare`.

---

## ⚠️ Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Missing values in Age & Embarked | Filled using median and mode respectively |
| Many nulls in Cabin column | Dropped the column |
| Categorical values | Converted to numeric or used one-hot encoding |
| Unnecessary columns | Removed `Name` and `Ticket` for clarity |

---

## 🛠️ Tools & Libraries Used

- **Platform:** Google Colab  
- **Version Control:** GitHub  
- **Python Libraries:**  
  - `Pandas`, `NumPy`  
  - `Matplotlib`, `Seaborn`  

---

## 🔗 Project Links

- 📓 [Google Colab Notebook](https://colab.research.google.com/drive/18wRhKed6_bZNq_1pKu20-3sLSikLKwdB)  
- 💻 [GitHub Repository](https://github.com/akanksha21-maker/CREDORA-TASK-2)

---

## 📬 Contact

- **Name:** Akanksha Bhosle  
- **Email:** *akanshabhosle31@gmail.com*  
- **LinkedIn:** [linkedin.com/in/akanksha-bhosle](www.linkedin.com/in/akanksha-bhosle-0bb8422b4)

---

> “Data is only valuable when it tells a story — and this task helped me learn how to find that story through analysis and visuals.”
