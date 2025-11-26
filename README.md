**Azure-AI-Code-Interpreter-Agent**
A Python-based Azure AI Agent that analyzes local data files using the Code Interpreter tool and returns statistical insights through a conversational terminal interface.

This project demonstrates how to build an AI Agent powered by Azure OpenAI that can analyze uploaded data files using the Code Interpreter Tool.
The agent runs inside a terminal-based chat loop, allowing users to interactively ask questions about the uploaded data and receive computed results in real time.

### **🚀 Features**
🧠 AI Agent with Code Interpreter

Uses Azure AI Agents API

Supports Python execution within the agent

Allows statistical and analytical operations

📄 Automatic File Upload & Processing

Uploads data.txt to Azure Agents

Enables Python-based analysis on the uploaded file

💬 Interactive Chat Loop

Users can ask any question about the dataset

Agent computes results and returns answers

Conversation history is preserved

📊 Statistical Insights

The agent can:

Calculate metrics (mean, sum, min, max, variance)

Analyze textual or numerical patterns

Run Python code dynamically

### **🏗 Tech Stack**

Python 3

Azure OpenAI / Azure AI Agents

Azure Identity

Code Interpreter Tool

dotenv for environment variables

**📁 Project Structure**

📦 azure-ai-code-interpreter-agent
 ┣ 📜 main.py
 ┣ 📜 data.txt
 ┣ 📜 .env (user creates)
 ┣ 📜 .env.example
 ┣ 📜 requirements.txt
 ┗ 📜 README.md

** 🔧 Environment Variables Required**

PROJECT_ENDPOINT=YOUR_AZURE_PROJECT_ENDPOINT
MODEL_DEPLOYMENT_NAME=YOUR_MODEL_DEPLOYMENT_NAME

**📌 Ideal Use Cases**

Data analysis automation

Educational demonstrations of Azure AI Agents

Projects showcasing Code Interpreter capabilities

Terminal-based conversational data exploration
