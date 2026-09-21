# Multi-Agent AI Research Assistant

An AI-powered research assistant that uses a **multi-agent architecture** to automate information gathering, analysis, fact-checking, and report generation.

## Features

- Multi-agent research workflow
- Automated web/source information gathering
- Content analysis and summarization
- Fact-checking and source comparison
- Structured research report generation

## Architecture

```text
User Query
    ↓
Orchestrator Agent
    ↓
Research → Analysis → Fact-Checking
    ↓
Report Writer
    ↓
Final Research Report



##Tech Stack
Python
LLMs / Generative AI
LangChain / LangGraph
Web Search APIs
Streamlit
How It Works
User submits a research query.
The orchestrator breaks it into subtasks.
Specialized agents research, analyze, and verify information.
The report agent combines the results into a structured response.
Installation
git clone https://github.com/your-username/multi-agent-research-assistant.git
cd multi-agent-research-assistant
pip install -r requirements.txt

Create a .env file with the required API keys.

Run the application:

streamlit run app.py


Developed By
Sarthak Sharma
