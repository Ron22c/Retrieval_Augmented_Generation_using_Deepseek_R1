# Local RAG with DeepSeek R1

1. Download Ollama: https://ollama.com/
2. ollama pull deepseek-r1:1.5b
3. ollama pull mxbai-embed-large
4. run ollama
5. create a virtual environment: python3 -m venv deepseek
6. activate virtual environment: source deepseek/bin/activate
7. pip install -r requirements.txt
8. streamlit run app.py