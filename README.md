# GenAi-StockAnalyzer-Phidata-Openai
## Overview  
This repository contains implementations of AI agents designed for **financial data analysis** and **web intelligence gathering**. These agents leverage **Groq's LLaMA 3.3-70B model** and **OpenAI GPT-4o** (optional) for processing queries, analyzing financial data, and retrieving real-time web information.  

## Features  
- **Web Intelligence Agent:** Gathers and summarizes web-based information using DuckDuckGo.  
- **Finance Agent:** Retrieves stock prices, analyst recommendations, and company information via YFinance tools.  
- **Company Symbol Lookup:** Matches company names to their stock symbols.  
- **Multi-Agent Team:** Combines web and finance agents for comprehensive responses.  
- **Structured Output:** Uses **tables** to display financial data.  
- **Live Streaming of Responses.**  

## How It Works  
1. **Web Agent:** Fetches real-time web-based information and always includes sources.  
2. **Finance Agent:** Retrieves and displays financial data in table format.  
3. **Agent Team:** Combines both agents for enhanced insights.  
4. **Custom Tool Integration:** Includes a company symbol lookup function for stock analysis.  

## Technologies Used  
- **Python**  
- **Phidata AI (Phi Agents & Models)**  
- **Groq AI (LLaMA 3.3-70B)**  
- **OpenAI GPT-4o** (optional)  
- **YFinance API** (financial data retrieval)  
- **DuckDuckGo Search API** (web-based queries)  
- **dotenv** (environment variable management)  

## Usage  
- **Summarize Analyst Recommendations:** Query stock insights using the **Finance Agent.**  
- **Fetch Latest News:** Use the **Web Agent** to retrieve up-to-date web content.  
- **Compare Stocks:** The Finance Agent can compare stocks using fundamentals and analyst insights.  
- **Symbol Lookup:** The system provides ticker symbols when needed.  