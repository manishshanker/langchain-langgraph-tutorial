# Tutorial 1: Introduction to LangChain

Welcome to the first tutorial in our LangChain and LangGraph series! In this tutorial, we'll introduce you to LangChain, a powerful framework for building applications with large language models (LLMs).

## What you'll learn

1. What is LangChain and why it's useful
2. How to install and set up LangChain
3. Basic concepts: Chains, Agents, and Memory
4. Building your first LangChain application

## Prerequisites

- Basic understanding of Python
- Familiarity with Jupyter Notebooks
- A Groq API key (sign up at https://console.groq.com)

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/doomL/langchain-langgraph-tutorial
   cd langchain-langgraph-tutorial/Tutorial01
   ```

2. Create a new virtual environment and activate it:
   ```
   python3 -m venv env
   source env/bin/activate
   ```
3. Install the required packages:
   ```
   pip install -r ../requirements.txt 
   ```
4. Set up your Groq API key:
   ```
   export GROQ_API_KEY='your-api-key-here'
   cp ../.env.example ../.env
   ```
   Edit the `.env` file and replace `your-api-key-here` with your actual Groq API key.
   And Langsmith API key if you want to track you llm calls.
   ```

5. Open the Jupyter Notebook:
   ```
   jupyter notebook Tutorial_1_Introduction_to_LangChain.ipynb
6. Follow along with the notebook to learn about LangChain and create your first application!

## Next Steps

After completing this tutorial, you'll have a solid foundation in LangChain. In the next tutorial, we'll dive deeper into working with language models in LangChain.

Happy learning!