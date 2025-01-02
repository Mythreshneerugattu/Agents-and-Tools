# Agents-and-Tools
A multi-purpose AI assistant integrating OpenAI models, job search, cryptocurrency pricing, weather forecasting, and language translation capabilities using LangChain and external APIs.

# Multi-Purpose AI Assistant

This project showcases an AI assistant with multiple functionalities built using LangChain and OpenAI GPT models. It supports weather forecasting, job searching, cryptocurrency price retrieval, and language detection/translation.

## Features
- **Weather Forecasting:** Provides weather information in JSON format for any given city.
- **Job Search Assistant:** Retrieves job openings in a specified industry with structured details.
- **Cryptocurrency Pricing:** Fetches live cryptocurrency prices and their 24-hour change percentage.
- **Language Detection and Translation:** Detects input language and translates it to English using Deepl API.

## Requirements
- Python 3.8+
- API keys for OpenAI, CoinMarketCap, and Deepl (add to a `.env` file).

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repositoryname.git
   cd repositoryname

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Create a .env file with API keys:
```bash
OPENAI_API_KEY=your_openai_key
CMC_API_KEY=your_coinmarketcap_key
DEEPL_API_KEY=your_deepl_key
