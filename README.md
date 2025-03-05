# AI_GEN_AGENTS
We dive into the world of Generative AI in Retail Supply Chains and walk you through building an intelligent AI agent that can optimize inventory, predict demand, and streamline logistics. Whether you're a supply chain professional or an AI enthusiast, this guide will help you leverage AI for smarter decision-making and operational efficiency

Organize Your Project Locally
Create this folder structure:

supplychain-ai-agent/
├── data/
│   └── starbucks_sales.csv       # Sample dataset
├── app.py                        # Gradio UI code
├── train_model.py                # Fine-tuning script
├── requirements.txt              # Dependencies
└── README.md                     # Documentation

# AI Supply Chain Agent 🤖

A generative AI agent for retail supply chain operations using **LLaMA 2**, **LangChain**, and **Gradio**. Predicts demand, answers inventory questions, and automates restocking.

## Features
- 📊 Inventory Q&A using Retrieval-Augmented Generation (RAG)
- 📈 Fine-tuning on retail sales data
- 💬 Gradio chatbot interface

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/mkishorekumar/AI_GEN_AGENTS.git
   cd AI_GEN_AGENTS
   
## Install dependencies:
   pip install -r requirements.txt
   
## Request access to LLaMA 2 or use Falcon.

### Usage

# Run the Gradio app: 
python app.py

Ask questions like:

"What's the inventory of oat milk in Store 101?"

"Should I order more espresso beans for Store 102?"
