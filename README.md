# 📌 **Amharic Telegram NER - Entity Extraction from E-commerce Channels**  

## 🚀 **Project Overview**  
This project aims to extract important entities (products, prices, locations) from Ethiopian Telegram e-commerce channels. Using **Natural Language Processing (NLP)** and **Named Entity Recognition (NER)**, we will fine-tune a model to process Amharic text efficiently.  

---

## 🛠 **Project Structure**  
```
├── .vscode/                    # VS Code settings
├── .github/workflows/          # CI/CD workflows
│   ├── unittests.yml
├── src/                        # Source code
│   ├── data_ingestion.py       # Fetches messages from Telegram channels
│   ├── data_preprocessing.py   # Cleans and prepares raw data
│   ├── train_ner_model.py      # Fine-tunes the NER model
├── notebooks/                  # Jupyter notebooks for analysis
│   ├── labeling_data.ipynb     # Manually labeling dataset in CoNLL format
│   ├── model_comparison.ipynb  # Comparing multiple NER models
│   ├── model_interpretability.ipynb  # Explainability analysis (SHAP & LIME)
├── data/                       
│   ├── labeled_dataset.conll   # Manually labeled dataset for training
├── tests/                      # Unit tests
├── scripts/                    # Additional scripts
├── requirements.txt            # Dependencies
├── README.md                   # Project documentation (this file)
└── .gitignore                  # Ignore unnecessary files
```

---

## 📌 **Project Tasks & Branches**  

| Task # | Task Name | Branch | Description |
|--------|----------------------|-----------|-------------|
| **1** | Data Ingestion & Preprocessing | `task-1` | Scrapes messages from Telegram, preprocesses text, and stores structured data. |
| **2** | Dataset Labeling (CoNLL Format) | `task-2` | Manually labels a dataset with product, price, and location entities. |
| **3** | Fine-Tuning the NER Model | `task-3` | Trains a Named Entity Recognition (NER) model on Amharic text. |
| **4** | Model Comparison & Selection | `task-4` | Evaluates different models (XLM-Roberta, DistilBERT, mBERT) for best performance. |
| **5** | Model Interpretability | `task-5` | Uses SHAP & LIME to explain how the model makes decisions. |

---

## 🔥 **Getting Started**  
### **1️⃣ Install Dependencies**  
Make sure you have Python installed, then install the required libraries:  
```bash
pip install -r requirements.txt
```

### **2️⃣ Run Data Ingestion (Task 1)**  
```bash
python src/data_ingestion.py
```

### **3️⃣ Label the Dataset (Task 2)**
Open the Jupyter notebook to manually label messages in **CoNLL format**:  
```bash
jupyter notebook notebooks/labeling_data.ipynb
```

### **4️⃣ Fine-Tune the NER Model (Task 3)**
```bash
python src/train_ner_model.py
```

### **5️⃣ Compare Models (Task 4)**
Run the notebook to evaluate different NER models:  
```bash
jupyter notebook notebooks/model_comparison.ipynb
```

### **6️⃣ Interpret Model Predictions (Task 5)**
```bash
jupyter notebook notebooks/model_interpretability.ipynb
```

---

## 📊 **Technologies Used**  
✅ **Python**  
✅ **Telegram Scraping (Telethon, Python-Telegram-Bot)**  
✅ **Natural Language Processing (NLP)**  
✅ **Hugging Face Transformers (XLM-Roberta, BERT, mBERT, AfroXMLR)**  
✅ **Jupyter Notebook**  
✅ **SHAP & LIME for Model Interpretability**  

---

## 💡 **Future Improvements**  
🔹 Add support for more Ethiopian languages.  
🔹 Expand entity recognition to include **brand names and contact information**.  
🔹 Improve accuracy by collecting more labeled data.  

---

## 🤝 **Contributing**  
Want to contribute? Follow these steps:  
1. **Fork** this repository  
2. Create a **new branch** (`feature-new-idea`)  
3. **Commit** your changes  
4. Open a **Pull Request**  

