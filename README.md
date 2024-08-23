# Python AI Chatbot

This project enables the deployment of a local Python AI chatbot using Ollama and LLaMA models. You can interact with the chatbot locally without relying on cloud services.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
  - [1. Install Ollama](#1-install-ollama)
  - [2. Verify Installation](#2-verify-installation)
  - [3. Download LLaMA Model](#3-download-llama-model)
  - [4. Deploy the Chatbot](#4-deploy-the-chatbot)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

This project includes:
- **`main.py`**: The Python script that runs your local AI chatbot.
- **Installation and Deployment Instructions**: Step-by-step guidance on setting up and running the chatbot using Ollama and LLaMA models.

## Prerequisites

- Python 3.7 or higher
- At least 8 GB of RAM for running LLaMA models
- Basic knowledge of Python and command-line usage
- Ollama installed on your computer

## Setup

### 1. Install Ollama

Ollama allows you to manage and run LLaMA models locally. Follow these steps to install it:

1. Visit the [Ollama official website](https://ollama.com).
2. Download and install the application suitable for your operating system.

### 2. Verify Installation

Open your terminal or command prompt and run the following command:

```bash
ollama --version
```

Ensure that Ollama is installed correctly.

### 3. Download LLaMA Model

To use the LLaMA 3 model (8 billion parameters), run:

```bash
ollama pull llama3
```

### 4. Deploy the Chatbot

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/python-ai-chatbot.git
   cd python-ai-chatbot
   ```

2. **Create a Python Virtual Environment**

   Create and activate a virtual environment:

   ```bash
   python3 -m venv chatbot
   source chatbot/bin/activate  # On Windows: chatbot\Scripts\activate
   ```

3. **Install Dependencies**

   Install the required Python packages:

   ```bash
   pip install langchain ollama
   ```

4. **Run the Chatbot**

   Execute the chatbot script:

   ```bash
   python main.py
   ```

   Follow the on-screen instructions to interact with the chatbot.

## Features

- **Local Execution**: Run the chatbot entirely locally without external API calls.
- **Contextual Awareness**: The chatbot maintains conversation context for more meaningful responses.
- **Easy Customization**: Customize the `main.py` script and client templates to suit your needs.

## Acknowledgements

- [Ollama](https://ollama.com) for local model management software.
- [LangChain](https://www.langchain.com) for the integration library.
