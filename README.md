# AI Multi-Agent Customer Retention System 

## Overview
An automated backend system leveraging a multi-agent LLM orchestration framework to analyze user behavior metadata, predict churn risk, and generate personalized customer retention strategies. 

## Architecture & Goals
This project utilizes autonomous AI agents, each assigned a specific role in the data evaluation pipeline:
1. **Data Extraction Agent:** Parses raw user metadata and interaction logs.
2. **Analysis Agent:** Evaluates churn probability based on historical patterns.
3. **Strategy Agent:** Generates tailored retention proposals and structured JSON outputs for API integration.

## Tech Stack
* **Language:** Python 3.10+
* **Frameworks:** CrewAI (Agent Orchestration)
* **LLM Integration:** Claude / Llama 3.1 APIs
* **Data Processing:** Pandas, JSON validation, REST APIs

## Current Status
**Work in Progress (Active Development)**
Currently focused on building the core agent-routing logic, setting up the API endpoints, and refining the system prompts for optimal LLM reasoning.
