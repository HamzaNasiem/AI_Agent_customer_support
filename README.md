# AI Agent for Customer Support

An AI agent that categorizes, analyzes sentiment, and responds to customer queries using LangGraph and LangChain.

## Features

- Categorizes queries (Technical, Billing, General)
- Analyzes sentiment (Positive, Neutral, Negative)
- Provides responses and escalates negative queries

### OPENAI_API_KEY=your_openai_api_key

## Usage

from your_module import run_customer_support

result = run_customer_support("Your customer query here.")
print(result)
