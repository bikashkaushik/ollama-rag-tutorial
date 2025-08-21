# Ollama RAG Tutorial Requirements

1. Set Up a Virtual Environment
	- python3 -m venv pythonvenv
	- source pythonvenv/bin/activate
2. Install Required Packages
	- pip install langchain
	- pip install -U langchain-community
	- pip install -U langchain-ollama
	- pip install -U langchain-chroma
	- pip install chromadb
	- pip install pypdf

3. Install and Configure Ollama
	Download and install Ollama to run models locally. (https://ollama.com/download)
	Pull and Run Required Models
		Embedding model (for text embeddings) (https://ollama.com/library/nomic-embed-text)
			- ollama pull nomic-embed-text
   		LLM model (for language generation) (https://ollama.com/library/mistral)
			- ollama run mistral
