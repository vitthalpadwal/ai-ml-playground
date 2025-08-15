<b>Repo configuration<b>
git add
git commit -m "add doc"
git branch -M main
git remote add origin https://github.com/vitthalpadwal/ai-ml-playground.git
git push -u origin main


1. LocalAIAgentWithRAG
```Configure local llm llama2.2 and embedding model using ollama and langchain and chrome db
  to generate answer for question using RAG for restaurant review dataset using local file
  
  ollama pull llama3.2
  ollama pull mxbai-embed-large
```
2. Ollama With Fast API
```Configure ollama with fastapi to for api query and response
  ollama pull mistral
  cd ollama_with_fast_api
  python main.py
  Open browser or advance request client and hit below url
  http://127.0.0.1:8000/generate?prompt="Hello World"
  
  or run the below python test code with request module
  python test-api.py
```
