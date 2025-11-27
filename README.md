\# 🌍 NLP Automation Mercury WebApp



An advanced \*\*multilingual NLP text classification dashboard\*\* built with \[Mercury](https://mljar.com/mercury/) and Python.  

This app allows users to upload CSV or Excel files containing transcripts, then automatically performs:



\- 🧹 Text cleaning and normalization  

\- 🌍 Language detection with confidence scoring  

\- 🔄 Intelligent translation (Google Translator API)  

\- 💭 Sentiment analysis (TextBlob + Afinn hybrid scoring)  

\- 🏷️ Category and subcategory prediction using rule-based keywords  

\- 📊 Export of results to CSV with statistics  



---



\## 🚀 Features



\- Upload `.csv` or `.xlsx` datasets with `Conversation Id` and `transcripts` columns

\- Automatic detection of meaningless text and filtering

\- Multilingual support (English, Spanish, French, Portuguese, Italian, etc.)

\- Confidence-based translation pipeline

\- Hybrid sentiment scoring (TextBlob + Afinn)

\- Rule-based category/subcategory overrides

\- Parallel processing for large datasets

\- Generates output CSV with predictions and summary statistics



---



\## 📦 Requirements



Install dependencies with:



```bash

pip install -r requirements.txt



