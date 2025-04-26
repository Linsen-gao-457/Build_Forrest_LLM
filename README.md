# Build LLM from scratch

A lightweight implementation of a Large Language Model built from scratch!

# 📖Overview

Forrest LLM is a project aimed at building and fine-tuning a transformer-based language model from the ground up. It provides a clear, modular implementation that makes it easy to understand the inner workings of modern LLMs while maintaining good performance.

# 🔍Feature

- ☑️Modular Architecture
- ☑️End-to-End Training Pipeline
- ☑️Task-Specific Fine-Tuning
- ☑️Open-source
- ☑️Lightweight

# 📁Install

This project can be run in two environments:

- **Google Colab**: For most notebooks(recommended for exploration)
- **Local Machine**: Required for the fine-tuned instruction model

### Opention 1: Google Colab Setup

1. Clone the repository

```
git clone https://github.com/Linsen-gao-457/Build_Forrest_LLM.git
cd Build_Forrest_LLM
```

2. Upload to Cloab

- Open Google Colab
- Upload the notebook files from your cloned repository
- Each notebook contains the necessary setup code to install dependencies

### Opention 2: Local Machine Setup (Required for Fine-tuned Instruction Model)

1. Clone the repository

```
git clone https://github.com/Linsen-gao-457/Build_Forrest_LLM.git
cd Build_Forrest_LLM
```

2. Set up environment
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Install [Ollama](https://ollama.com/)

- Download Ollama from ollama.com
- Install following the instructions for your operating system
- Run the Llama3 model
  ```
  ollama run llama3
  ```
