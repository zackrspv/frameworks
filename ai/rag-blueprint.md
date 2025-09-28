# RAG (Retrieval-Augmented Generation) Blueprint

## ⚙️ Pattern
- **Embed** → Store domain knowledge in a vector DB  
- **Retrieve** → Match user queries with relevant chunks  
- **Generate** → LLM uses context + prompt structure  

## 🧭 My Notes
- Use lightweight embeddings (e.g., bge-base-en) for scale.  
- Always separate **short-term vs. long-term KBs**.  
- Weekly fine-tuning > giant one-off training runs.  
