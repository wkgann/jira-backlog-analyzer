# 🗂️ Jira Backlog Analyzer

An AI-powered Jira backlog analysis tool built with Google Gemini and LangChain, developed in Google Colab.  


---

## What It Does

This notebook analyzes a Jira backlog using a Large Language Model (LLM) to help teams:

- **Cluster** related Jira issues by theme or topic
- **Identify duplicates** using cosine similarity
- **Generate summaries** of issue clusters using Gemini 2.5 Flash
- **Surface insights** from large, unstructured backlogs

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Google Gemini 2.5 Flash | LLM for cluster report generation |
| LangChain (`langchain_google_genai`) | LLM orchestration |
| Google Colab | Development environment |
| Python | Core language |

---
---

## 🔑 API Key Setup (If You Run It)

This notebook uses the **Google Gemini API**. If you choose to run it:

1. Get a free API key from [Google AI Studio](https://aistudio.google.com)
2. In Colab, click the 🔑 **Secrets** icon in the left sidebar
3. Add a secret named `GEMINI_API_KEY` and paste your key
4. Toggle **Notebook access ON**

The notebook reads the key securely via:
```python
from google.colab import userdata
api_key = userdata.get('GEMINI_API_KEY')
```

---

## 📄 Related Article

> 📝 Link to the full article on Towards Data Science: TBD

---

## Author

Made by **[K Gann]** · [LinkedIn]([https://linkedin.com/in/w-j-ketty-g-8b933a11]
---

## License

This project is open for learning and reference purposes.  
Feel free to adapt the code with attribution.
