# 📰 News Topic Classifier Using BERT

A News Topic Classification system built using the BERT transformer model for automatically classifying news headlines into different categories.

This project uses the **AG News Dataset** and fine-tunes **BERT (bert-base-uncased)** to classify news into four categories:

- 🌍 World
- ⚽ Sports
- 💼 Business
- 🔬 Sci/Tech

---

## 📌 Project Overview

This project implements a deep learning-based news classification system using **BERT (Bidirectional Encoder Representations from Transformers)**.

The model is trained on the AG News dataset and predicts the category of a news headline. A simple interactive interface is also created using **Gradio** for real-time predictions.

---

## 🚀 Features

✅ News headline classification using BERT  
✅ Fine-tuned transformer model  
✅ AG News dataset integration  
✅ Evaluation metrics (Accuracy & F1 Score)  
✅ Classification report generation  
✅ Confusion matrix visualization  
✅ Interactive Gradio web interface  

---

## 📂 Dataset

The project uses the **AG News Dataset** available through the Hugging Face datasets library.

Dataset Categories:

| Label | Category |
|--------|----------|
| 0 | World |
| 1 | Sports |
| 2 | Business |
| 3 | Sci/Tech |

---

## 🛠️ Technologies Used

- Python
- BERT (Transformers)
- Hugging Face Transformers
- Hugging Face Datasets
- Scikit-learn
- NumPy
- Matplotlib
- Gradio

---

## 📦 Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
cd YOUR_REPOSITORY_NAME
```

Install required libraries:

```bash
pip install transformers datasets accelerate evaluate scikit-learn matplotlib gradio
```

---

## ▶️ How to Run

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
task1.ipynb
```

Run all cells sequentially.

---

## 🧠 Model Used

This project uses:

**BERT Base Uncased**

```text
bert-base-uncased
```

The model is fine-tuned for multi-class sequence classification.

---

## ⚙️ Training Configuration

| Parameter | Value |
|-----------|------|
| Learning Rate | 2e-5 |
| Batch Size | 16 |
| Epochs | 2 |
| Max Length | 128 |
| Weight Decay | 0.01 |

---

## 📊 Evaluation

The model performance is evaluated using:

- Accuracy Score
- F1 Score
- Classification Report
- Confusion Matrix

Example output:

```text
World
Sports
Business
Sci/Tech
```

---

## 📈 Confusion Matrix

The project visualizes classification performance using a confusion matrix generated with Matplotlib.

---

## 🖥️ Gradio App

An interactive Gradio application is included where users can enter a news headline and receive a predicted category instantly.

Example:

**Input:**

```text
Apple launches new AI-powered iPhone
```

**Output:**

```text
Sci/Tech
```

---

## 📁 Project Structure

```text
├── task1.ipynb
├── saved_model/
├── saved_model.zip
├── README.md
```

---

## 🔮 Future Improvements

- Train on larger datasets
- Improve model accuracy with hyperparameter tuning
- Deploy the model online
- Add more news categories
- Build a complete web application

---

## 👩‍💻 Author

Developed as a Machine Learning / NLP project using BERT for news topic classification.

---

## ⭐ Support

If you found this project helpful, please give it a star ⭐ on GitHub.
