# Spam Message Classification

A Natural Language Processing (NLP) project for analyzing and classifying messages as **spam** or **non-spam (ham)** using Python and machine learning techniques.

## 📌 Project Overview

This project explores spam message classification using text preprocessing, Natural Language Processing, data analysis, visualization, and machine learning techniques.

The project is implemented in a Jupyter Notebook:

```text
Spam.ipynb
```

The dataset used by the project is:

```text
spam.csv
```

## 🛠️ Technologies & Libraries

The project uses the following Python libraries:

* **Pandas** — data loading and manipulation
* **Matplotlib** — data visualization
* **Seaborn** — statistical visualization
* **spaCy** — Natural Language Processing
* **NLTK** — text preprocessing and NLP
* **Gensim** — NLP and text processing
* **Scikit-learn** — machine learning
* **VADER Sentiment** — sentiment analysis

## 📂 Project Structure

```text
Spam-Classification/
│
├── Spam.ipynb
├── spam.csv
├── requirements.txt
├── pyproject.toml
└── README.md
```

## ⚙️ Setup

This project uses **uv** for Python package and environment management.

### 1. Clone the repository

```bash
git clone <https://github.com/Tharunluckys/ML-Notebooks.git>
cd <NLP/Spam.ipynb>
```

### 2. Create the environment

```bash
uv venv
```

### 3. Install the dependencies

```bash
uv sync
```

If you are setting up the project without the existing `pyproject.toml`, you can install the required packages with:

```bash
uv pip install pandas matplotlib seaborn spacy nltk gensim scikit-learn vaderSentiment
```

### 4. Install the spaCy model

The project uses the `en_core_web_sm` spaCy model.

```bash
uv run python -m spacy download en_core_web_sm
```

### 5. Install the Jupyter kernel

```bash
uv add --dev ipykernel
```

Then select the project's `.venv` environment as the kernel in VS Code.

## ▶️ Running the Project

Open:

```text
Spam.ipynb
```

in **VS Code** or **Jupyter Notebook**.

Select the Python kernel associated with the project's `.venv` environment and run the notebook cells sequentially.

Make sure `spam.csv` is available in the expected project directory.

## 📊 Dataset

The project reads the dataset using:

```python
pd.read_csv("spam.csv", encoding="latin-1")
```

The dataset contains text messages that are used for spam classification and NLP analysis.

## 🔍 Project Workflow

The notebook covers the process of working with textual data, including:

1. Loading the dataset
2. Exploring the data
3. Text preprocessing
4. Natural Language Processing
5. Feature preparation
6. Machine learning
7. Visualization and analysis
8. Spam classification

## 🎯 Objective

The main objective of this project is to understand how Natural Language Processing and machine learning can be applied to identify spam messages from textual data.

## 🚀 Future Improvements

Possible improvements include:

* Comparing multiple machine learning algorithms
* Improving text preprocessing
* Experimenting with different feature-extraction techniques
* Evaluating models using additional performance metrics
* Building a simple web interface for spam prediction
* Deploying the trained model as an application

## 👨‍💻 Author

**Tharun Lucky**

---
