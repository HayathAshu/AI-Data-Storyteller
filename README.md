# 📊 Imarticus AI-Powered Data Storyteller

This project is built as part of the **Imarticus Data Science Internship Assessment**.  
It is an **AI-powered Data Storytelling App** that automatically analyzes datasets, generates insights in plain English, creates visualizations, and exports an executive summary report.

---

## 🚀 Features

- 📂 **Upload your dataset** (CSV/Excel)
- ✅ **Dataset validation** (checks rows, columns, missing values, duplicates)
- 📊 **Automated EDA**
  - Numeric summary (`describe()`)
  - Categorical top values
  - Missing value analysis
  - Correlation analysis
- 📈 **Visualizations**
  - Bar chart (categorical)
  - Line chart (timeseries/numeric)
  - Correlation heatmap
- 🧠 **Plain-English insights**
  - Rule-based summarizer (always available)
  - (Optional) HuggingFace LLM for natural language executive summaries
- 📝 **Export report**
  - Downloadable **PDF report** with insights and charts
  - Export insights as **text file**
- 🖥️ **Interactive dashboard** built with [Streamlit](https://streamlit.io/)

---

## 🛠️ Installation & Setup

### 1. Clone or download the project
Save the file **`Imarticus_AI_Data_Storyteller_app.py`** in a folder.

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
# Activate it:
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
