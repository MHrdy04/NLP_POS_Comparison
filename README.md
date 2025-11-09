# 🧠 Comparison of Part-of-Speech Tagging Methods  
### *(Rule-Based vs. Statistical Approaches)*  

**Author:** M. Himesh and G.praneeth 
**Based on Paper:** *“Comparison of Part-of-Speech Tagging Methods: Rule-Based vs. Statistical Approaches” (2025)*  

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green)
![License](https://img.shields.io/badge/License-Academic-yellow)

---


> *“Exploring how linguistic rules and statistical models shape modern NLP tagging.”*

---

## 📘 Overview  
This project demonstrates and compares two foundational **Part-of-Speech (POS) Tagging** approaches in **Natural Language Processing (NLP)**:  

1️⃣ **Rule-Based Tagging** — built with linguistic rules and handcrafted patterns  
2️⃣ **Statistical Tagging** — trained using probabilistic language models (Unigram / Bigram Taggers)  

The project analyzes their **performance, interpretability, and scalability** using the **Brown Corpus** from NLTK and evaluates each using standard metrics like **Accuracy, Precision, Recall, and F1-score**.  

This project complements the academic paper:  
> *“Comparison of Part-of-Speech Tagging Methods: Rule-Based vs. Statistical Approaches”*  
> by G. Praneeth & M. Himesh (2025)

---

## ⚙️ Features  
- Implementation of **Rule-Based** and **Statistical (Bigram)** POS Taggers  
- Evaluation using **Accuracy, Precision, Recall, F1-score**  
- **Visual comparisons** of performance metrics  
- Reproducible **Jupyter Notebook** with comments  
- Ready for academic and GitHub presentation  

---

## 🧩 Technologies Used  
- Python 3.10+  
- NLTK  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Pandas  
- NumPy  
- Jupyter Notebook  

---
## 📁 Repository Structure
```text
📦 NLP_POS_Comparison
 ┣ 📓 POS_Tagging_Comparison.ipynb     # Main Jupyter Notebook
 ┣ 📄 README.md                         # Project description (this file)
 ┣ 📊 accuracy_plot.png                  # Generated charts
 ┣ 📊 metrics_plot.png
 ┗ 📜 requirements.txt                  # Dependencies

```

---

# POS Tagging Comparison Project
## Rule-Based vs Statistical Taggers
Tested on Python 3.10+

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)<your-username>/NLP_POS_Comparison.git
cd NLP_POS_Comparison
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Launch the Jupyter Notebook
```bash
jupyter notebook POS_Tagging_Comparison.ipynb
```

### 3️⃣ Launch the Jupyter Notebook
```bash
jupyter notebook POS_Tagging_Comparison.ipynb
```

## 4️⃣ Run All Cells
The notebook will:
* Add Hidden Markov Model (HMM) implementation
* Incorporate Neural POS Taggers (BiLSTM / BERT)
* Extend to multilingual and domain-specific corpora
* Build a Streamlit Web App for interactive tagging

---

## 📦 Requirements
```bash
pip install -r requirements.txt
```
---

## requirements.txt
```bash
nltk==3.9.1
scikit-learn==1.5.2
matplotlib==3.9.2
seaborn==0.13.2
pandas==2.2.3
numpy==1.26.4
jupyter==1.1.1
```

---

## 📈 Example Output  

| Method | Precision | Recall | F1-Score | Accuracy |
|:--------|:-----------:|:--------:|:-----------:|:-----------:|
| Rule-Based | 0.88 | 0.87 | 0.87 | 0.89 |
| Statistical (Bigram) | 0.93 | 0.92 | 0.92 | 0.94 |

---

## 📊 Visualization

* Accuracy Comparison Bar Chart
* Precision / Recall / F1 Comparison Chart

---

## 🧮 Evaluation Metrics  

- **Accuracy:** Percentage of correctly predicted tags  
- **Precision:** Correct predicted tags / Total predicted tags  
- **Recall:** Correct predicted tags / Total actual tags  
- **F1-Score:** Harmonic mean of precision and recall  

---

## 📘 Reference Paper  
> G. Praneeth & M. Himesh  
> _“Comparison of Part-of-Speech Tagging Methods: Rule-Based vs. Statistical Approaches.”_  
> (2025)

---

## 📚 Key References  

- Brill, E. (1992). _A Simple Rule-Based Part-of-Speech Tagger._  
- Ratnaparkhi, A. (1996). _A Maximum Entropy Model for POS Tagging._  
- Toutanova, K. et al. (2003). _Feature-Rich POS Tagging with a Cyclic Dependency Network._  
- NLTK Documentation: [https://www.nltk.org/](https://www.nltk.org/)

---

## 💡 Future Improvements  

- Add **Hidden Markov Model (HMM)** implementation  
- Incorporate **Neural POS Taggers** (BiLSTM / BERT)  
- Extend to **multilingual and domain-specific** corpora  
- Build a **Streamlit Web App** for interactive tagging  






