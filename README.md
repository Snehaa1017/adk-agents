🚀 # **ADK Agents: app_01 & app_03**
A set of Google Agent Development Kit (ADK) agents for AI-powered voice and text tasks.

📝 **Project Overview**
This repository contains two ADK agents:

app_01: General question-answering Gemini agent

app_03: AI news assistant using Google Search for recent AI news

✨ Features
> Gemini LLM integration
> Voice and text support
> Google Search tool capability
> API key authentication via .env file

🛠️ **Getting Started**
Prerequisites
Python 3.11+

## **Google ADK installed**

Gemini API key from Google AI Studio

**Installation**
bash
git clone https://github.com/<yourusername>/adk-agents.git
cd adk-agents
Configuration
Add your Gemini API key to a .env file inside each agent folder:

**text**
GOOGLE_API_KEY=your_actual_key_here
GOOGLE_GENAI_USE_VERTEXAI=0
Running..
From the parent directory, run:

**bash**
adk web --host 0.0.0.0 --port 8002
Visit: http://localhost:8002

📦 Directory Structure
text
adk-agents/
  app_01/
    agent.py
    __init__.py
    .env
  app_03/
    agent.py
    __init__.py
    .env
  .gitignore
  README.md
  
🔒 License
MIT or another license of your choice.

🤝 Credits
Developed by sneha using Google ADK and Gemini APIs.

