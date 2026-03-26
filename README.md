# Multi-Agent Research System

An automated research pipeline built using Microsoft AutoGen that coordinates multiple AI agents to perform academic literature searches, extract insights, and generate structured research reports.

## 🚀 Overview

This system follows a structured workflow to ensure comprehensive results:

1. **Topic Refinement** – Converts broad topics into precise search queries.
2. **Paper Discovery** – Fetches relevant academic papers from the arXiv database.
3. **Insight Synthesis** – Extracts key ideas, methodologies, and findings.
4. **Report Generation** – Compiles the data into a structured Markdown report.
5. **Gap Analysis** – Evaluates the report to identify limitations and future research directions.

## 🛠️ Tech Stack

- **Framework**: Microsoft AutoGen (v0.2.35)
- **Model**: Llama 3.3 70B (via Groq API)
- **Data Source**: arXiv API
- **Language**: Python 3.10+

## 📦 Installation

To set up the project locally, run the following commands in your terminal:

```bash
git clone https://github.com/princexj/multi_agent_research_team.git
cd multi_agent_research_team
pip install -r requirements.txt
```

## 🔧 Environment Setup

Create a file named `.env` in the root directory and add your Groq API key:

```
GROQ_API_KEY=your_api_key_here
```

## ▶️ Usage

1. Run the main script:

```bash
python main.py
```

2. **Input Topic**: Enter a research topic when prompted (e.g., `"Transformer vs BDH Architecture"`).
3. **Confirm Execution**: Press `Enter` when the system requests permission to execute the arXiv search tool.
4. **Output**: The final research report will be automatically saved as a `.md` file in the project folder.

## 📜 License

This project is licensed under the MIT License.
