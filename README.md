# 🌱 Crop Recommendation with Machine Learning

> Predicting the ideal crop to plant based on soil nutrients and climate conditions using Random Forest Classifier.

---

## 📋 About the Project

This project applies Machine Learning to recommend the most suitable crop for a given set of soil and climate conditions. Using a real-world agricultural dataset, I performed exploratory data analysis and trained a classification model capable of identifying the ideal crop among 22 different options.

The goal is to demonstrate how AI can support decision-making in precision agriculture — helping farmers choose the right crop based on data, not guesswork.

---

## 📊 Dataset

- **Source:** [Crop Recommendation Dataset – Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- **Records:** 2,200 samples
- **Features:**
  | Feature | Description |
  |---------|-------------|
  | `N` | Nitrogen content in soil (kg/ha) |
  | `P` | Phosphorus content in soil (kg/ha) |
  | `K` | Potassium content in soil (kg/ha) |
  | `temperature` | Average temperature (°C) |
  | `humidity` | Relative humidity (%) |
  | `ph` | Soil pH level |
  | `rainfall` | Annual rainfall (mm) |
  | `label` | Target crop (22 classes) |

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights extracted during EDA:

- Distribution of soil nutrients across different crops
- Correlation heatmap between features
- Boxplots showing climate conditions per crop category
- Identification of crops with similar growing requirements

---

## 🤖 Model

| Detail | Value |
|--------|-------|
| Algorithm | Random Forest Classifier |
| Library | scikit-learn |
| Train/Test Split | 80% / 20% |
| Evaluation Metric | Accuracy, Classification Report |

The Random Forest was chosen for its robustness with tabular data, resistance to overfitting, and interpretability — important qualities when applying AI in agricultural contexts.

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/joao-cabral-aa334b122/crop-recommendation-ml.git
cd crop-recommendation-ml
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Get the dataset**
```bash
python get_dataset.py
```
**4. Run the notebook**
```bash
jupyter notebook notebook.ipynb
```

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

Install all at once:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

## 📁 Project Structure

```
crop-recommendation-ml/
│
├── data/
│   └── Crop_recommendation.csv   # Dataset
│
├── notebook.ipynb                # Main notebook (EDA + Model)
├── requirements.txt              # Dependencies
└── README.md                     # This file
```

---

## 📈 Results

The trained model achieved strong performance on the test set, correctly classifying crops across all 22 categories. Detailed metrics (precision, recall, F1-score) are available inside the notebook.

---

## 💡 Motivation

This project was built as part of my studies in Computer Engineering, with a focus on applying Artificial Intelligence to real-world problems. Agriculture is one of the most impactful domains for AI adoption, and this project is a practical demonstration of that potential.

---

## 👨‍💻 Author

**João Rodolpho Vitor Cabral**  
Computer Engineering student at UNINTER  
[LinkedIn](https://www.linkedin.com/in/joao-cabral-aa334b122/) • [joaorodolhocabral@gmail.com](mailto:joaorodolhocabral@gmail.com)
