# Ollama RAG Tutorial Requirements

- python3 -m venv pythonvenv    #Setup virtual environment
- source pythonvenv/bin/activate
- pip install langchain
- pip install -U langchain-community
- pip install -U langchain-ollama
- pip install -U langchain-chroma
- pip install chromadb
- pip install pypdf

- ollama pull nomic-embed-text  #this will pull 'nomic-embed-text' embedding model locally (https://ollama.com/library/nomic-embed-text)
- ollama run mistral #this will pull and run 'mistral' LLM model locally (https://ollama.com/library/mistral)
	
