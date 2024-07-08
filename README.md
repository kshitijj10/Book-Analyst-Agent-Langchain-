# Book Analyst Agent

This project leverages LangChain, OpenAI's GPT-3.5-turbo, and other tools to create an AI agent that can analyze books and answer questions about them. The agent uses a combination of text retrieval and language models to provide concise and accurate insights from the book.

## Data Source
Pick any book of your choice and ask questions to get insights.

## Installation

To set up the environment and install the necessary packages, run the following commands:

```bash
pip install langchain langchain_chroma langchain_community langchain_core langchain_openai langchain_text_splitters langgraph amazon-textract-textractor pypdf
pip install --upgrade --quiet boto3 langchain-openai tiktoken python-dotenv
pip install --upgrade --quiet "amazon-textract-caller>=0.2.0"
