# Zabbix-RAG

Zabbix-RAG is a **Retrieval-Augmented Generation (RAG)** application that leverages Zabbix documentation as a Vector Database to provide intelligent query responses. This system enables users to query Zabbix-related information in natural language and receive detailed and relevant answers sourced directly from the documentation.

## Features

- **Documentation Parsing**: Converts Zabbix documentation into manageable chunks for embedding.
- **Vector Database**: Uses FAISS for efficient vector-based storage and retrieval of embeddings.
- **Local LLM Integration**: Powered by a locally hosted Llama 2 model through ChatOllama, making it cost-effective and API-free.
- **Natural Language Querying**: Allows users to ask Zabbix-related questions in plain language and get contextual answers.

---

## Prerequisites

Before starting, ensure you have the following:

1. **Python 3.8+** installed.
2. [FAISS](https://github.com/facebookresearch/faiss) for vector storage.
3. [Ollama](https://ollama.ai/) installed and running locally.
4. Zabbix documentation in PDF format (`documentation.pdf`).

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/zabbix-RAG.git
   cd zabbix-RAG
    ```

2. **Install Dependencies: Use pip to install the required Python libraries**:

    ```bash
        pip install -r requirements.txt
    ```

3. **Prepare the Documentation: Place your Zabbix documentation PDF in the data folder**:
    ```bash
    /data/index/documentation/zabbix_documentation.pdf
    ```