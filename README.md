# Chat With Your Data - Powered by LLM

## Overview

**Chat With Your Data** is an innovative project that enables users to interact with their datasets through natural language conversations. Built on Large Language Models (LLMs) and Streamlit, this tool simplifies data exploration, querying, and retrieval, providing actionable insights effortlessly.

---

## Key Features

- **Natural Language Queries**: Perform complex data operations with simple, conversational commands.
- **Document Support**: Upload and process documents in formats like CSV, PDF, and TXT.
- **Retrieval-Augmented Generation (RAG)**: Combines LLMs with vectorized data stores for precise and context-aware responses.
- **API Flexibility**: Supports OpenAI, Hugging Face, and Cohere APIs.
- **Streamlit Interface**: A user-friendly GUI for seamless interaction.

---

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (LangChain Framework)
- **LLM Integration**: OpenAI, Hugging Face, Cohere
- **Vector Store**: ChromaDB
- **Deployment**: Streamlit Cloud

---

## Installation and Setup

### Prerequisites

- Python 3.8 or later
- Streamlit
- API keys for LLM services (e.g., OpenAI, Hugging Face, or Cohere)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-with-your-data.git

2. Navigate to the project directory:
   ```bash
   cd chat-with-your-data
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the application
 ```bash
streamlit run main.py
```

## 
Here is the markdown code for your README content that you can directly add to your readme.md file:

markdown
Copy code
# Chat With Your Data - Powered by LLM

## Overview

**Chat With Your Data** is an innovative project that enables users to interact with their datasets through natural language conversations. Built on Large Language Models (LLMs) and Streamlit, this tool simplifies data exploration, querying, and retrieval, providing actionable insights effortlessly.

---

## Key Features

- **Natural Language Queries**: Perform complex data operations with simple, conversational commands.
- **Document Support**: Upload and process documents in formats like CSV, PDF, and TXT.
- **Retrieval-Augmented Generation (RAG)**: Combines LLMs with vectorized data stores for precise and context-aware responses.
- **API Flexibility**: Supports OpenAI, Hugging Face, and Cohere APIs.
- **Streamlit Interface**: A user-friendly GUI for seamless interaction.

---

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python (LangChain Framework)
- **LLM Integration**: OpenAI, Hugging Face, Cohere
- **Vector Store**: ChromaDB
- **Deployment**: Streamlit Cloud

---

## Installation and Setup

### Prerequisites

- Python 3.8 or later
- Streamlit
- API keys for LLM services (e.g., OpenAI, Hugging Face, or Cohere)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-with-your-data.git
2. Navigate to the project directory:
```bash
cd chat-with-your-data

3. Install dependencies:
```bash
pip install -r requirements.txt

4. Run the application:
```bash
streamlit run main.py
```
## Usage
After Running the app.
### Create a Vector Store
1. **Select LLM Provider:** Choose between OpenAI, Hugging Face.(You will need API key)
2. **Select the Retrievers:**
      -  Cohere reranker(You will need API key)
      -  Contextual Compression
      -  Vectorstore Backed Retriever
4. **Upload Data:** Upload documents in supported formats.(TXT or CSV)
5. **Provide a vector store name**: e.g. (`vector`, `vectorstore`, `vectordb` etc.)
6. Click on **Click VectorStore**

**OR**

### Open a saved VectorStore.
You can Directly Upload a saved vector store.

**Now you can chat with your data.**


## Test My Application

[Test my application](https://chatwithyourdata-tzsckgsmsp5jz6ch6ervfm.streamlit.app/)  
You can use `NLP.txt` and/or `langchain.txt` present in repo as data file.


## Acknowledgments
- [Streamlit](https://streamlit.io/) for the interactive interface.
- [OpenAI](https://openai.com/), [Hugging Face](https://huggingface.co/), and [Cohere](https://cohere.com/
) for LLM support.
- [LangChain](https://www.langchain.com/) for modular framework integration.
- [Ala Eddine GRINE](https://medium.com/thedeephub/rag-chatbot-powered-by-langchain-openai-google-generative-ai-and-hugging-face-apis-6a9b9d7d59db): Special thanks for the inspiration and guidance provided through his GitHub repository and Medium blog.
   
