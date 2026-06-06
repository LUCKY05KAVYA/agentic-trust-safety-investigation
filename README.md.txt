# 🛡️ Agentic Trust & Safety Investigation System

An intelligent **LangGraph-based agent** that automates manual Trust & Safety reviews for e-commerce product listings. Detects counterfeits, misleading claims, brand impersonation, and policy violations.

## ✨ Key Features

- Multi-step agentic workflow using **LangGraph**
- Cross-modal verification (Text vs Image consistency)
- Self-reflection loop for improved decisions
- Structured output with risk level, action, violations & confidence
- Interactive Gradio web demo

## 🛠️ Tech Stack

- **Framework**: LangGraph
- **LLM**: Llama-3.1-8B (Groq)
- **Frontend**: Gradio
- **Structured Output**: Pydantic + JSON mode

## 📊 Evaluation Results

- **Violation Recall**: 100%
- **Violation F1 Score**: 66.7%
- **False Negative Rate**: 0%
- **Average Latency**: ~22.7 seconds

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook Agentic_Trust_Safety_Investigation.ipynb