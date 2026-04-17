## GenAI Retail Analytics Chatbot

An intelligent, interactive conversational assistant designed to provide real-time insights into retail sales performance. This project leverages Generative AI (LLMs) to transform natural language user queries into actionable data visualizations and descriptive analytics.

## Key Features
- **Natural Language Understanding:** Uses GPT-4/Gemini Pro to interpret complex sales-related questions.
- **Dynamic SQL Generation:** Automatically converts user prompts into SQL queries against a SQLite database.
- **Interactive Chat UI:** Built with a responsive interface including chat history, query metadata (timestamps/latency), and suggested questions.
- **Automated Reporting:** "Download Report" functionality to export conversation logs and analytical findings.
- **Data Insights:** Tracks top-performing products, sales trends, and promotional impacts.

## Tech Stack
- **Language:** Python 3.x
- **Backend:** Flask / SQLite
- **Frontend:** ipywidgets / React (interface mockup)
- **AI/LLM:** OpenAI GPT-4 or Google Gemini Pro API
- **Data Science:** Pandas, Matplotlib, Seaborn
- **Documentation:** ReportLab (for PDF generation)

## Workflow Architecture
1. **Data ETL:** Raw transactional data is cleaned and mapped to retail categories (Groceries, Electronics, etc.).
2. **Intent Classification:** The GenAI engine determines if a user wants a descriptive summary or a visual chart.
3. **Query Execution:** The system generates and runs SQL queries to fetch real-time data.
4. **Response Generation:** Results are summarized by the LLM and displayed in the chat interface with processing metadata.
