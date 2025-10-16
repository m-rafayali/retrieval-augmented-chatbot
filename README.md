<<<<<<< HEAD
# 🚀 Insurance RAG Chatbot  
**AI-powered insurance assistant with Retrieval-Augmented Generation (RAG), ChromaDB, and Gradio UI.**  
##  Overview  
A chatbot that answers insurance policy questions by retrieving relevant documents from a knowledge base using **RAG** (ChromaDB for vector storage) and generating responses via LLMs (e.g., GPT-3.5, Llama 2). Built with Gradio for easy testing.  

---

## 🛠️ Setup  

### 1. Install Dependencies  
```bash
pip install langchain chromadb gradio sentence-transformers
```

### 2. Download Knowledge Base  
The insurance document dataset is stored in a separate Git repo. Run:  
```bash
# Clone with sparse checkout (saves bandwidth)
git clone --depth=1 --filter=blob:none --sparse https://github.com/ed-donner/llm_engineering.git
cd llm_engineering
git sparse-checkout set week5/knowledge-base
git pull
```
*Note:* Move the `knowledge-base/` folder to this project’s root after download.  



##  Tech Stack  
- **RAG Pipeline**: LangChain + ChromaDB (vector storage)  
- **Embeddings**: `sentence-transformers/all-MiniLM-L6-v2`  
- **UI**: Gradio  
- **Knowledge Base**: Pre-processed insurance documents ( FAQs).  

## License  
MIT  


1. **Clear setup instructions** with code blocks.  
2. **Highlights ChromaDB** and the sparse checkout trick.  
3. **Ready for Colab** (badge + pip installs).  
4. **Minimalist structure** for easy navigation.  

Need a **quickstart script** for `app.py`? Let me know! 🎯
=======
# retrieval-augmented-chatbot
An intelligent Retrieval-Augmented Chatbot that combines Large Language Models (LLMs) with document retrieval for accurate, context-aware answers. Uses vector embeddings, semantic search, and context injection to enhance responses with domain-specific knowledge. Built with Python and LangChain.
>>>>>>> 236740274a7791c0eb2753dd0ffdf6e755f4e3da
