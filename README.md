# Personal AI Research Agent

## Overview

An autonomous Python-based AI agent that performs iterative, structured research on a given topic.

The system transforms a single user input into a complete research workflow:

- Generates an executive summary (10 lines)
- Produces clarification questions to refine scope
- Iteratively improves results through feedback loops (up to 3 cycles)
- Outputs a final structured report

---

## Features

- Autonomous agent-driven research pipeline  
- AI-generated concise summarization  
- Context-aware question generation  
- Iterative refinement loop (3 cycles)  
- Multi-format output: PDF / PPT / Web  

---

## Architecture

- Agent Orchestration Layer (workflow control)  
- Data Layer (information retrieval & preprocessing)  
- NLP Layer (summarization & question generation)  
- Memory Layer (context tracking via vector search)  
- Output Layer (report generation)  

---

## Tech Stack

- Python  
- OpenAI API  
- BeautifulSoup / requests  
- FAISS  
- Streamlit / FastAPI  
- python-pptx / reportlab  

---

## Usage

```bash
python main.py

## Goal
To simulate a real-world autonomous AI research assistant using iterative reasoning, context refinement, and structured output generation.
