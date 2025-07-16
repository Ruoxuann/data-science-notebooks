# 📊 Data Science Projects

Welcome to my Data Science project repository! This repo serves as a collection of hands-on projects I've built across various areas of data science, including web scraping, data visualization, and machine learning.

### ✅ Currently included projects:

* 🎬 [film-scraping-analysis](#-film-scraping-analysis): Python web scraping and visualization project
* 📚 [predict-students-academic](#-predict-students-academic): Machine learning project to predict student academic performance

More projects will be added continuously, covering areas such as data preprocessing, feature engineering, NLP, and deep learning.

---

## 🎬 film-scraping-analysis

**Overview:**
This project uses Python to scrape movie information (ratings, number of reviews, release years, etc.) from a film website and visualize the data using popular data science libraries.

**Highlights:**

* Automated scraping of structured movie data from multiple pages
* Visualization of rating distributions, trends by year, and more
* Clean and readable charts with support for multilingual labels

**Tech stack:**

* Web scraping: `requests`, `BeautifulSoup`
* Data manipulation & visualization: `pandas`, `matplotlib`, `seaborn`

---

## 📚 predict-students-academic

**Overview:**
This project predicts students' academic performance based on their demographic and behavioral data, using various machine learning models.

**Highlights:**

* Data exploration and preprocessing (handling missing values, encoding categorical features, etc.)
* Comparison of multiple models (e.g., Logistic Regression, Random Forest, XGBoost)
* Model evaluation using cross-validation, confusion matrix, ROC curves

**Tech stack:**

* Data handling: `pandas`, `numpy`
* Machine learning: `scikit-learn`, `xgboost`
* Visualization: `matplotlib`, `seaborn`

---

## 📁 Project Structure

```
├── film-scraping-analysis/
│   ├── scraper.py
│   ├── analysis.ipynb
│   └── README.md
│
├── predict-students-academic/
│   ├── data/
│   ├── model_training.ipynb
│   └── README.md
│
└── README.md  ← (This file)
```

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Navigate to each project folder and run the notebooks or scripts as needed.

---

## 🧠 Tools & Technologies

* Python 3.x
* Jupyter Notebook
* pandas, numpy
* matplotlib, seaborn
* scikit-learn, xgboost
* requests, BeautifulSoup

---

## 🔭 Future Plans

* Add NLP projects (e.g., sentiment analysis, text classification)
* Incorporate deep learning models (TensorFlow or PyTorch)
* Work with real-world datasets for end-to-end pipelines
