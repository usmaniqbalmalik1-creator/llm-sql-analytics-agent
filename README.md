# LLM SQL Analytics Agent

A natural-language analytics assistant that generates validated, read-only SQL for a demo SQLite sales database and displays the results.

## Features
- LLM-powered question answering or analysis
- Context-aware processing
- Streamlit interface
- Environment-based API configuration
- Clear project structure for extension

## Workflow
User Input -> Context / Schema -> LLM -> Validation or Retrieval -> Result

## Project Structure
```text
llm-sql-analytics-agent/
├── app.py
├── requirements.txt
└── .env.example
```

## Quick Start
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
```

Configure the required variables in `.env` using `.env.example`, then run:

```bash
streamlit run app.py
```

## Portfolio Focus
**LLM Applications • Text-to-SQL • SQL • Python • Data Analytics**

> Never commit API keys, passwords, or private user/company data.