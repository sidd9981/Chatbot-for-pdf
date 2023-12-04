@@ -1,2 +1,19 @@

# Search-Your-PDF-App

Search Your PDF App using Langchain, ChromaDB, Sentence Transformers, and LaMiNi LM Model. This app is completely powered by Open Source Models. No OpenAI key is required.

### Getting Started

Install required dependencies

```bash
pip install -r requirements.txt
```

Persist db from documents

```bash
python -m ingest
```

Run experiment on web

```bash
streamlit run chatbot.py
```
