# CRL-search-chatbot
search CRL

# CRL Search App (Streamlit)

This is a Streamlit web app that allows you to upload and search across up to **300 PDF files** using keyword-based search powered by **TF-IDF**.

## 🔍 Features

- Upload multiple PDFs (up to 300)
- Search using keywords or phrases
- Returns top matching results with:
  - Filename
  - Page number
  - Text snippet
  - Relevance score

## 🚀 How to Deploy on Streamlit Cloud

1. Create a GitHub repository and upload:
   - `app.py`
   - `requirements.txt`
   - (Optional) `README.md`

2. Go to https://streamlit.io/cloud

3. Click **“New app”**, select your GitHub repo, and deploy!

## 🖥️ Local Usage (Optional)

If you have Python installed:

```bash
pip install -r requirements.txt
streamlit run app.py
