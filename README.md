
---

## 🚀 Project Workflow

### 📥 1. Data Loading & Initial Exploration

- Mounted Google Drive and loaded the dataset.
- Conducted Exploratory Data Analysis (EDA):
  - Scatter plots
  - Correlation matrix
  - Histograms
  - Box plots

---

### 🔧 2. Data Preprocessing

- Removed irrelevant/unnecessary columns.
- Parsed timestamps into year, month, day, and hour.
- Scaled numerical features and handled missing values.
- Encoded categorical variables.
- Text preprocessing included:
  - Lowercasing
  - URL removal
  - Tokenization
  - Lemmatization

---

### 🧪 3. Feature Engineering

- Extracted TF-IDF vectors from cleaned text data.
- Combined TF-IDF vectors with preprocessed numerical features.
- Applied **PCA** to reduce dimensionality and noise.

---

### ⚖️ 4. Handling Class Imbalance

- Addressed imbalanced classes using:
  - **SMOTE**
  - **RandomOverSampler**

---

### 🤖 5. Model Training & Evaluation

- Trained two models:
  - **Support Vector Machine (SVM)** with RBF kernel
  - **Random Forest Classifier**
- Evaluated models using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

### 🔍 6. Hyperparameter Tuning

- Used **HalvingRandomSearchCV** for efficient hyperparameter search.
- Tuned final **Random Forest model** with optimal parameters.

---

### 📊 7. Feature Importance Analysis

- Analyzed feature importances for:
  - Top contributing numerical features
  - Influential words from TF-IDF matrix

## 🛠️ Requirements

- Python 3.7+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- imbalanced-learn
- nltk
- tqdm
- PCA (from sklearn)
- TF-IDF Vectorizer
- Google Colab (optional)

---

## 📌 How to Run

1. Clone the repository.
2. Install dependencies using "pip install -r requirements.txt"
3. Launch the Jupyter notebook
4. Follow along with the code in the notebook to train models and visualize results.

