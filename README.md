# LLMs for Automating Scrum Practices

## Overview
A proof-of-concept LLM-driven Scrum assistant that automates sprint planning, 
dependency detection, and retrospective summarisation using LLaMA-3.1-8B-Instruct 
on real open-source project data.

## Key Results
- F1 = 0.89 for proactive dependency detection
- 85% sprint assignment classification accuracy
- 82% structured output schema coverage rate

## Tech Stack
Python · LLaMA-3.1-8B-Instruct · Hugging Face API · Prompt Engineering · 
Pandas · Scikit-learn · Google Colab

## How to Run
1. Clone the repo: `git clone https://github.com/kusumik/llm-scrum-automation`
2. Install dependencies: `pip install -r requirements.txt`
3. Add your Hugging Face API token to the notebook config
4. Open `llm_scrum_automation.ipynb` in Jupyter or Google Colab

## Dataset
Real open-source Agile project data (GitHub Issues / Jira-style records)

## Context
Master's Thesis — MSc Data Science, AI & Digital Business  
GISMA University of Applied Sciences, Berlin · Sept 2025
