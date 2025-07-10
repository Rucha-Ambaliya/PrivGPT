# PrivGPT 
### 🤖 Local AI Chatbot with Streamlit + Ollama

A clean, dynamic chatbot UI built with Streamlit that lets you chat with locally running LLMs (via [Ollama](https://ollama.com)). Fully offline, fully yours.

---

## 🎥 Demo
- https://ollama.com/download

## 🚀 How to Run

1. **Install Ollama** (if not already):  
   👉 https://ollama.com/download

2. **Pull a model** (e.g., `phi3`, `qwen3`):  
   ```bash
   ollama pull phi3
   ```

3. **Start Ollama server**:  
   ```bash
   ollama serve
   ```

4. **Install Dependencies**:  
   ```bash
   pip install streamlit requests
   ```

5. **Run the Streamlit app**:  
   ```bash
   streamlit run app.py
   ```

---

## ⚙️ Key Features

- ✅ Multi-model support
- ✅ Dynamic model switching
- ✅ Real-time model info
- ✅ Auto-refresh models
- ✅ Connection monitoring
- ✅ Export full chat history

---

## 📦 Example Models

You can use any model pulled into Ollama. Some popular ones:
```bash
ollama pull phi3
ollama pull qwen3
ollama pull llama2
ollama pull mistral
```

---

## 🙏 Credits

Built with guidance from **Faiz Khatri** 🙌  
Created by [Rucha Ambaliya](https://github.com/Rucha-Ambaliya)