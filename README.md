# 🧠 Enhanced Q&A Chatbot with Ollama + LangChain + Streamlit  

This project is a **Q&A chatbot** powered by **open-source LLMs** (via [Ollama](https://ollama.com/)) and **LangChain**, with an interactive **Streamlit UI**.  

We can select different models (like `mistral`, `llama2`, `codellama`, `gemma`, etc.), adjust parameters like **temperature** and **max tokens**, and chat with your own locally running AI assistant.  

---

## 🚀 Features
- 🔹 Choose from multiple **open-source models**  
- 🔹 Simple and interactive **Streamlit UI**  
- 🔹 Adjustable **temperature** & **max tokens**  
- 🔹 Uses **LangChain pipelines** for structured responses  
- 🔹 Runs fully **locally** with Ollama  

---

## ⚡ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```
---

## Install dependencies
```bash
  pip install -r requirements.txt

```

##  Pull models
 ```bash
ollama pull mistral
ollama pull llama2
ollama pull codellama
ollama pull gemma
ollama pull phi

 ```

## Run App
```bash
streamlit run app.py

```
