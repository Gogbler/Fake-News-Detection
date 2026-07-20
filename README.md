# 📰 Fake News Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

# 📌 Project Overview

Fake News Detection is a Natural Language Processing (NLP) and Machine Learning project that automatically classifies news articles as **Real** or **Fake**.

The project uses text preprocessing, TF-IDF Vectorization, and multiple Machine Learning algorithms to analyze news content and determine its authenticity.

This project demonstrates the complete Machine Learning pipeline from data preprocessing to model evaluation and prediction.

---

# 🎯 Objectives

- Detect fake news articles automatically.
- Apply NLP preprocessing techniques.
- Compare different Machine Learning algorithms.
- Evaluate model performance using standard metrics.
- Build a reusable prediction system.

---

# 🚀 Features

- Data Cleaning
- Text Preprocessing
- Stopword Removal
- TF-IDF Vectorization
- Multiple Machine Learning Models
- Model Comparison
- Accuracy Evaluation
- Classification Report
- Confusion Matrix
- Manual Prediction Function
- Easy-to-understand Notebook

---

# 📂 Repository Structure

```
Fake-News-Detection/
│
├── Fake.csv                         # Fake news dataset
├── True.csv                         # Real news dataset
├── Fake_News_Detection.ipynb        # Main Jupyter Notebook
├── IBM_PPT_FAKE_NEWS_DETECTION.pptx # Project Presentation
├── requirements.txt                 # Required libraries
├── README.md                        # Project Documentation
├── LICENSE                          # MIT License
└── .gitignore
```

---

# 🛠 Technologies Used

| Category | Technologies |
|----------|--------------|
| Language | Python |
| IDE | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| NLP | Regex, NLTK |
| Feature Extraction | TF-IDF Vectorizer |
| Machine Learning | Scikit-Learn |
| Version Control | Git & GitHub |

---

# 📊 Dataset Information

The dataset consists of two CSV files:

### Fake.csv

Contains fake news articles collected from unreliable news sources.

### True.csv

Contains authentic news articles collected from verified news organizations.

### Dataset Columns

- title
- text
- subject
- date

---

# 🔄 Project Workflow

```
Dataset
     │
     ▼
Load Data
     │
     ▼
Merge Dataset
     │
     ▼
Label Encoding
     │
     ▼
Text Cleaning
     │
     ▼
Data Splitting
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Train ML Models
     │
     ▼
Model Evaluation
     │
     ▼
Prediction
```

---

# 🧹 Data Preprocessing

The following preprocessing techniques are applied:

- Convert text to lowercase
- Remove punctuation
- Remove numbers
- Remove URLs
- Remove HTML tags
- Remove special characters
- Remove extra spaces
- Tokenization
- Stopword removal
- Text normalization

---

# 🤖 Machine Learning Models

The project compares multiple algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

# 📈 Model Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Fake-News-Detection.git
```

Move into the project directory

```bash
cd Fake-News-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Fake_News_Detection.ipynb
```

---

# ▶️ How to Run

1. Clone the repository.
2. Install all required libraries.
3. Open the notebook.
4. Run all cells.
5. Train the models.
6. Test with custom news articles.

---

# 📝 Manual Prediction

Example:

```python
manual_testing("Breaking news...your article here...")
```

Output

```
Prediction:
Genuine News
```

or

```
Prediction:
Fake News
```

---

# 📊 Sample Results

| Model | Purpose |
|--------|----------|
| Logistic Regression | Baseline classifier |
| Decision Tree | Rule-based classification |
| Random Forest | Ensemble learning |
| Gradient Boosting | Boosted ensemble model |

The notebook compares these models using accuracy and classification metrics to identify the best-performing approach.

---


# 📚 Python Libraries

```
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
re
string
```

---

# 🔮 Future Improvements

- Deep Learning (LSTM)
- Bi-LSTM
- GRU
- BERT
- RoBERTa
- DistilBERT
- Flask Web Application
- Streamlit Deployment
- REST API
- Docker Container
- Cloud Deployment
- Real-time News Verification

---

# 📈 Applications

- News Verification
- Social Media Monitoring
- Journalism
- Digital Media Platforms
- Fact Checking Systems
- Educational Research
- Content Moderation

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Aditya Singh**

B.Tech (Artificial Intelligence & Machine Learning)

United Institute of Technology, Prayagraj

📧 Email: adityasinghuit013@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/aditya-singh-47b065253

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates future improvements and helps others discover the project.

---

## 📬 Contact

For suggestions, collaborations, or feedback:

**Email:** adityasinghuit013@gmail.com

**LinkedIn:** https://www.linkedin.com/in/aditya-singh-47b065253

---

### ⭐ If you like this project, don't forget to Star the repository!
