# Open_Avenues_Build_Fellowship_Projects

# 🏥 1. Develop NLP Models for Medical Data Extraction

**Build Project – Open Avenues Build Fellowship (June 2025 – August 2025)**  
**Build Fellow:** Deeptanshu (Jay) Jha

---

## 📌 Overview
This project automates the extraction of structured medical information from **unstructured radiology reports**.  
Using **NLP pipelines**, **fine-tuned transformer models**, and an **interactive Streamlit app**, the solution converts free-text clinical documents into clean, structured **JSON outputs**—helping clinicians, researchers, and analysts save time and unlock insights.

---

## 🎯 Problem Statement
Over **80%** of hospital data is locked in **free-text reports**, making it difficult to analyze or integrate into downstream analytics pipelines.  
This project addresses that by:
- Parsing unstructured reports
- Extracting key sections (Title, Clinical Indication, Findings, Impression, Recommendations)
- Outputting machine-readable **JSON** formats in seconds

---

## 🛠 Key Features

- **📄 Prompt-Based Extraction**  
  - Uses LLMs with strict JSON schemas to bootstrap extraction  
  - Ensures field consistency and structure

- **🤖 Fine-Tuned Transformer Model (BIOES Tagging)**  
  - Improved **F1 score** from **0.78 → 0.92**  
  - Significant accuracy gains for **rare fields**

- **🔁 Reproducible Workflows with Metaflow**  
  - Parallelizes data ingestion, EDA, prompt experiments, fine-tuning, and evaluation

- **💻 Interactive Streamlit App**  
  - Paste or upload reports  
  - Toggle between **extraction modes** (Prompt-based or Regex fallback)  
  - Batch-process CSVs and download structured outputs

- **📊 Comprehensive Evaluation**  
  - Per-field **precision, recall, and F1**  
  - **ROUGE-L** for semantic similarity  
  - Handles missing/variant CSV column names (e.g., `ReportText` → `text`)

---

## 📂 Screenshots to Streamlit Application of Medical Data Extraction

![1. Single Report Output (Structured Input)]( https://github.com/suhasi-gadge/Open_Avenues_Build_Fellowship_Projects/blob/main/Medical%20Data%20Extraction%20Using%20NLP/img/Single%20Report%2001.png) 

![2. Single Report Output (Un-Structured Input)](https://github.com/suhasi-gadge/Open_Avenues_Build_Fellowship_Projects/blob/main/Medical%20Data%20Extraction%20Using%20NLP/img/Single%20Report.png)

![3. Batch Evaluation Output (CSV Input)](https://github.com/suhasi-gadge/Open_Avenues_Build_Fellowship_Projects/blob/main/Medical%20Data%20Extraction%20Using%20NLP/img/Batch%20Evaluation.png)

