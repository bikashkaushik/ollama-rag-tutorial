# Ollama RAG Tutorial Requirements

1. Set Up a Virtual Environment
	- python3 -m venv pythonvenv
	- source pythonvenv/bin/activate
2. Install Required Packages
	- pip install langchain
	- pip install -U langchain-community
	- pip install -U langchain-ollama
	- pip install -U langchain-chroma
	- pip install -U chromadb
	- pip install -U pypdf

3. Install and Configure Ollama
   	1. Download and install Ollama to run models locally. (https://ollama.com/download)
	2. Pull and Run Required Models
		1. Embedding model (for text embeddings) (https://ollama.com/library/nomic-embed-text)
			- ollama pull nomic-embed-text
   		2. LLM model (for language generation) (https://ollama.com/library/mistral)
			- ollama run mistral
