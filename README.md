# LANGCHAIN_TUTORIAL
This is a tutorial for the LangChain project.

## Introduction
This tutorial will guide you through the process of setting up a LangChain component and using it to create a simple LLM APP.

## Components
This tutorial will cover the following Langchain components:
1. LLM & Chat
2. Prompt
3. Indexes
4. Chains
5. Memory
6. Agents

## Prerequisites
- Python 3.9 or higher
- Ollama - local language model server
- Poetry - Python dependency management tool

## Installation
1. Clone the repository
2. Install Ollama - [see link](https://ollama.com/)
3. Install Poetry - [see link](https://python-poetry.org/docs/)
4. Setup virtual environment
    ```bash
    python -m venv .venv
    ```
5. Activate virtual environment
    ```bash
    source .venv/bin/activate
    ```
6. Install dependencies
    ```bash
    poetry install
    ```
7. pull llama-3 model - This will download the model from the Ollama server (can take a while depending on the model size)
    ```bash
    ollama pull llama3
    ```
8. Run Jupyter Notebook
    ```bash
    jupyter notebook
    ```