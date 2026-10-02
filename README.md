# KSTU Workspace

**KSTU Workspace** — это корпоративная On-Premise система мониторинга, управления проектной деятельностью, файловым хранилищем и графовой базой знаний со встроенным ИИ-агентом.

## Концепция
Система устраняет «фрагментацию контекста». Вместо переключения между Jira, Notion, Google Drive и ChatGPT, команды получают единое цифровое пространство. 
Ключевая особенность: интеллектуальный RAG-агент, который не только ищет ответы по документам компании, но и умеет самостоятельно управлять задачами через механизм Function Calling.

## 🛠 Технологический стек
* **Backend:** Python 3.11+, FastAPI, SQLAlchemy (asyncpg), PostgreSQL 16 + `pgvector`.
* **Frontend:** React 18, TypeScript, Tailwind CSS, Vite.
* **AI & NLP:** LangChain / LlamaIndex, локальные LLM (Ollama) / OpenAI API.
* **Инфраструктура:** Docker, Docker Compose, MailHog (SMTP).

## 📚 Документация
* 📄 [Техническое задание (Версия 2.1)](docs/technical_specification.md)

---
*Разработано студентами КГТУ им. И. Раззакова (группа ПИ(б)-1-24).*