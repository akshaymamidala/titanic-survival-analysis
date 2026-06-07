# Titanic Passenger Survival Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

**An in-depth Exploratory Data Analysis (EDA) of the Titanic disaster to uncover the key factors that influenced passenger survival.**

---

## 📋 Table of Contents

- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Key Insights](#key-insights)
- [Visualizations](#visualizations)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Detailed Analysis & Conclusions](#detailed-analysis--conclusions)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🎯 Problem Statement

Perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Matplotlib and derive meaningful insights about the factors that affected survival rates during the Titanic tragedy (April 15, 1912).

---

## 📊 Dataset

- **Name**: `Titanic-Dataset.csv`
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Rows**: 891 (Passengers)
- **Columns**: 12

**Features include:**
- `Survived`, `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, `Embarked`, `Cabin`, etc.

**Note**: Missing values in `Age` and `Cabin` were handled during preprocessing.

---

## 🛠 Technologies Used

- **Python 3.12**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **SciPy** – Statistical analysis

---

## 📈 Key Insights

### Survival Rate Overview
- Overall survival rate: **38.4%** (342 survived, 549 died)

### Major Factors Affecting Survival:

| Factor              | Insight                                     | Survival Rate                    |
|---------------------|---------------------------------------------|----------------------------------|
| **Gender**          | Women had much higher survival chance       | Female: 74.2%<br>Male: 18.9%     |
| **Passenger Class** | Higher class = higher survival              | 1st: 63%<br>2nd: 47%<br>3rd: 24% |
| **Age Group**       | Children had priority                       | Child: ~58%<br>Adult: ~33%       |
| **Fare**            | Higher fare correlated with better survival | Strong positive correlation      |

### Other Observations:
- Most deaths occurred among **adult males** in **3rd class**.
- Clear evidence of "**Women and children first**" policy.
- Passengers who embarked from **Cherbourg** had higher survival rates.

---

## 📊 Visualizations

The project includes the following insightful visualizations:

1. **Overall Survival Rate**
2. **Survival by Gender**
3. **Survival by Passenger Class**
4. **Survival by Age Group** (with bar & pie charts)
5. **Age Distribution**
6. **Fare vs Age** (Scatter Plot)
7. **Survival & Death Count** by multiple categories

*(All visualizations are saved as high-resolution PNG files in the repository)*

---

## 📁 Project Structure

```bash
titanic-survival-analysis/
├── Titanic1.ipynb                 # Main Jupyter Notebook
├── Titanic-Dataset.csv            # Original dataset
├── AgeGroup_based.png             # Key visualization
├── requirements.txt               # Python dependencies
├── README.md                      # This file
└── images/                        # (Optional) All plots

🚀 How to Run the Project
1. Clone the Repository
Bashgit clone https://github.com/YOUR_USERNAME/titanic-survival-analysis.git
cd titanic-survival-analysis
2. Install Dependencies
Bashpip install -r requirements.txt
3. Launch Jupyter Notebook
Bashjupyter notebook
Open Titanic1.ipynb to explore the full analysis.

📝 Detailed Analysis & Conclusions
Main Conclusions:

Gender was the strongest factor — women were given priority.
Socio-economic status (Passenger Class) played a critical role.
Age mattered — children had significantly higher survival chances.
3rd class passengers had the lowest survival rate due to limited access to lifeboats.
The data strongly supports the historical account of the Titanic evacuation.


🔮 Future Improvements

Build a Machine Learning model to predict survival (Logistic Regression, Random Forest, etc.)
Feature engineering (Title extraction from Name, Family Size, etc.)
Interactive visualizations using Plotly or Seaborn
Deploy as a Streamlit web app


📄 License
This project is open-source and available under the MIT License.

Made with ❤️ for Data Science & Storytelling
Feel free to ⭐ star the repo if you found it helpful!
