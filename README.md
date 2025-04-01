# Multi-Agent-System-with-Ollama-and-LangChain
This project implements a multi-agent system using ollama and langchain to interact with various tools, including web search, financial news lookup, code execution, and stock data retrieval. The system utilizes qwen2.5 as the primary language model and integrates multiple APIs and functionalities.

## Features

- **Natural Language Processing**: Utilizes `ollama` with Qwen 2.5 LLM for intelligent responses.  
- **Web Search**: Fetches general and financial news using DuckDuckGo Search.  
- **Stock Market Data**: Retrieves real-time stock data via `yfinance`.  
- **Code Execution**: Runs Python code dynamically within the system.  
- **Multi-Agent Framework**: Enables different agents to handle specialized tasks efficiently.  

## Installation

### Prerequisites

Ensure you have the following installed:  

- Python 3.8+  
- `pip`  

### Setup

Clone the repository:  
```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

## Install dependencies:

```sh
pip install -r requirements.txt
```

## Example Queries
"Fetch the latest stock price of Tesla."

"Run this Python script: print(2+2)."

"Get the latest news on artificial intelligence."



