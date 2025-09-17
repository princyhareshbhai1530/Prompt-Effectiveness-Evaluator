# 🧪 Prompt Effectiveness Evaluator

## 📌 Overview
This project implements a **Prompt Effectiveness Evaluator** — an interactive framework to **compare multiple prompt engineering strategies** (Zero-shot, Role-based, Chain-of-Thought, etc.) across tasks such as:
- Summarization
- Q&A
- Sentiment Rephrasing
- Sales Projection (with CSV demo support)
- General Text Generation

It provides **objective evaluation metrics** (ROUGE-L, BLEU, BERTScore, Sentiment Confidence) and **visualizations** (bar charts, radar plots) to analyze how different prompts impact output quality.

---

## 🚀 Features
- 📂 Support for multiple **task types**
- 📝 Manage and test **custom prompt variants**
- 🤖 **LLM integration** (GPT-4 family: `gpt-4o`, `gpt-4o-mini`, `gpt-4.1`, `gpt-4.1-mini`)
- ⚡ **Mock mode** (runs without API key, for demo/reproducibility)
- 📊 Metrics: ROUGE-L, BLEU, optional BERTScore, Sentiment
- 📈 Visualizations: Bar charts + Radar chart
- 📥 Upload and evaluate with your own **CSV data**
- ⬇️ Download raw outputs & metrics (CSV/JSON)

---

## 🏗️ Project Structure
-PromptEffectivenessEvaluator/

── Prompt-Effectiveness-Evaluator.py # Streamlit main app

── modules/
 
 ├── llm_query.py # Handles model calls (GPT or mock)[Code included in main python file]

 ├── evaluation.py # Computes metrics (ROUGE, BLEU, etc.)[Code included in main python file]

 ├── visualization.py # Generates plots (Plotly)[Code included in main python file]

── data/

 ├── sample_prompts.json

 ├── sales_data.csv # Example sales dataset

---

## 📑 Research Paper
A detailed **research paper** related to this project is also attached in the repository:  
**Prompt Effectiveness Evaluator: Analyzing the Impact of Prompt Engineering on LLM Outputs**  

This paper covers:
- Theoretical background of prompt engineering
- Experimental setup and evaluation metrics
- Sales Projection case study
- Insights and results discussion

---

## 📚 References
[1] A. Shukla, *Prompt Effectiveness Evaluator: Analyzing the Impact of Prompt Engineering on LLM Outputs*, 2025. (Attached in this repository)
