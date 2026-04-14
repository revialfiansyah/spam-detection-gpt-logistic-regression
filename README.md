Final project: Spam email detection using GPT feature extraction and Logistic Regression

# 🛡️ Spam Email Detection using GPT Feature Extraction + Logistic Regression

## 📌 Overview
This project evaluates the effectiveness of **Generative Pre-trained Transformer (GPT)**
as a feature extractor for a **Logistic Regression** model in detecting spam emails.

## 🎯 Objectives
- Evaluate GPT embeddings vs. Without GPT
- Build a Logistic Regression classifier on extracted features
- Measure accuracy, precision, recall, and F1-score

## 🛠️ Tech Stack
- **Python** · scikit-learn · Hugging Face Transformers · PyTorch
- **Models:** GPT (feature extraction) + Logistic Regression
- **Dataset:** spam_ham_dataset

## 📊 Results
| Method | Accuracy | Precision | Recall |  F1-Score | ROC-AUC |

| Without GPT + LR | 0.7227 | 0.7142 | 0.3412 | 0.6514 | 0.5365 |

| GPT + LR | 0.9758 | 0.9557 | 0.9590 | 0.9574 | 0.9935 |

Confuse matrix without GPT:
<img width="488" height="349" alt="image" src="https://github.com/user-attachments/assets/1c4c5f5c-c677-4a58-af99-ea38a6e48a44" />


Confuse matrix with GPT:
<img width="484" height="377" alt="image" src="https://github.com/user-attachments/assets/5daa7252-5df7-4083-aad2-6ed276a8ce39" />


Model evaluation metrics without GPT:
<img width="539" height="370" alt="image" src="https://github.com/user-attachments/assets/e1897400-61ed-41bf-8c0f-36e2870ec290" />


Model evaluation metrics with GPT:
<img width="521" height="365" alt="image" src="https://github.com/user-attachments/assets/29f6504f-e13f-484a-950a-61d3453c3aea" />


ROC Curve without GPT:
<img width="539" height="342" alt="image" src="https://github.com/user-attachments/assets/f910ac18-3663-4912-8171-4431dcc4af57" />


ROC Curve with GPT:
<img width="526" height="349" alt="image" src="https://github.com/user-attachments/assets/2a570b79-8a68-485e-8777-b52268160797" />



## 🚀 How to Run
# Clone repository
git clone https://github.com/username/spam-detection-gpt-logistic-regression

# Install dependencies
pip install -r requirements.txt

# Open notebook
Google Collabnotebook notebook/spam_detection_gpt_logistic.ipynb


## 👤 Author
**Mochamad Revi Alfiansyah** — 152020001
Institut Teknologi Nasional Bandung
