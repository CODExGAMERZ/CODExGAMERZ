# ✦ Aryan (CODExGAMERZ)

<p align="left">
  <a href="https://codexgamerz.github.io"><img src="https://img.shields.io/badge/Live%20Portfolio-codexgamerz.github.io-6366f1?style=flat-square&logo=firefox" alt="Portfolio" /></a>
  <a href="https://github.com/CODExGAMERZ"><img src="https://img.shields.io/badge/GitHub-CODExGAMERZ-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="https://www.instagram.com/aryannotsinha"><img src="https://img.shields.io/badge/Instagram-aryannotsinha-E4405F?style=flat-square&logo=instagram" alt="Instagram" /></a>
</p>

### AI Engineer & Systems Developer
I specialize in building **performance-first developer tooling, local-first machine learning pipelines, and hybrid AI systems** optimized for low-latency execution, hardware efficiency, and absolute data privacy.

---

## ⚡ Technical Core

* **🧠 Deep Learning & Transformers** — Autoregressive decoder-only Transformer design (causal self-attention, rotary positional embeddings, KV-caching, FlashAttention) trained from scratch.
* **🤖 Retrieval-Augmented Generation (RAG)** — Intent-driven multi-agent workflows (LangGraph), vector similarity databases (Qdrant), and Reciprocal Rank Fusion (RRF) algorithms.
* **🛠️ Systems & Developer Tooling** — Abstract Syntax Tree (AST) parsing with WebAssembly Tree-sitter, VS Code extension development, and custom Electron/Code-OSS IDE compilation.

---

## 🚀 Selected Flagship Projects

### **[Code Autocomplete LLM](https://github.com/CODExGAMERZ/Code-AutoComplete-LLM)**  
*Multilingual GPT-style autocomplete model trained from scratch supporting Python, C, and Java.*  
* **Architecture**: Integrated Rotary Embeddings (RoPE), GeGLU gating, and soft logit capping into a causal decoder framework.
* **Optimization**: Enabled FlashAttention (SDPA) and dynamic KV-caching to accelerate inference speeds on consumer GPUs.
* **Stack**: `PyTorch` • `Transformers` • `FlashAttention` • `BPE Tokenizer` • `DDP`

### **[B.Tech-AI-Tutor-7B](https://github.com/CODExGAMERZ/B.Tech-AI-Tutor-7B)**  
*Fine-tuned academic study tutor built on top of Qwen-2.5-7B-Instruct, optimized for Colab training & local GGUF running.*  
* **Architecture**: Trained a custom 5-layer dataset pipeline spanning ~480K instruction-tuning samples and 15K preference pairs.
* **Optimization**: Configured multi-phase pipeline executing SFT and DPO via Unsloth, quantized to GGUF format for low-latency local running (Ollama/llama.cpp).
* **Stack**: `PyTorch` • `Qwen-2.5` • `Unsloth` • `DPO / SFT` • `HuggingFace` • `GGUF` • `Ollama`

### **[SentinelRAG](https://github.com/CODExGAMERZ/SentinelRAG)**  
*Privacy-first local search engine transforming directories and Obsidian vaults into context-aware systems.*  
* **Ingestion**: Engineered a debounced filesystem watcher parsing markdown links and headers in real-time.
* **Retrieval**: Fused vector search scores with SQLite structural centrality metrics using Reciprocal Rank Fusion (RRF).
* **Stack**: `Python` • `LangGraph` • `Qdrant` • `Ollama` • `SQLite`

### **[JarvisRAG](https://github.com/CODExGAMERZ/JarvisRAG)**  
*Local-first knowledge base assistant ingesting documents into a vector database with a central command UI.*  
* **Ingestion**: Ingests `.pdf`, `.txt`, and `.md` files dynamically using local embedding models into a FAISS vector store.
* **Interface**: Features a futuristic browser console with MathJax LaTeX rendering, marked-down contexts, and a live search telemetry stream.
* **Stack**: `Python` • `FastAPI` • `FAISS` • `Gemini API` • `Tailwind CSS`


### **[KeyCode](https://github.com/CODExGAMERZ/KeyCode)**  
*A custom Windows distribution of VS Code (Code - OSS) with a built-in AI autocomplete companion.*  
* **Built-in Extension**: Developed a custom completion provider utilizing Fill-in-the-Middle (FIM) prompt formatting.
* **Latency**: Optimized client-side response paths through request debouncing and predictive local caching.
* **Stack**: `TypeScript` • `Electron` • `Node.js` • `Ollama`

### **[LogicScope](https://github.com/CODExGAMERZ/LogicScope)** ([Live Demo](https://logicscope.vercel.app/))  
*Real-time code visualizer rendering DSA recursion trees and UML diagrams as you type.*  
* **Analysis**: Developed an offline-first parsing engine running WebAssembly-compiled Tree-sitter AST queries in-browser.
* **Visualization**: Transformed code structures dynamically into interactive Mermaid.js diagrams.
* **Stack**: `TypeScript` • `WebAssembly` • `Tree-sitter` • `Mermaid.js` • `Extension API`

---

## 🛠️ Technology Stack

```
┌──────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Languages        │ Python • TypeScript • JavaScript (ES6+) • Kotlin • C • HTML5 • CSS3    │
├──────────────────┼────────────────────────────────────────────────────────────────────────┤
│ AI & ML          │ PyTorch • TensorFlow • FAISS • SentenceTransformers • LangGraph • LLMs │
├──────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Developer Tools  │ VS Code Extension API • WebAssembly • Electron • Monaco Editor • ASTs   │
├──────────────────┼────────────────────────────────────────────────────────────────────────┤
│ Backend & Infra  │ Node.js • FastAPI • Flask • SQLite • Qdrant • Supabase • WebSockets    │
└──────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub Metrics

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" valign="top">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=CODExGAMERZ&show_icons=true&theme=calm&hide_border=true&bg_color=0D0D11&title_color=6366f1&icon_color=6366f1&text_color=A1A1AA" alt="Aryan's GitHub Stats" />
      </a>
    </td>
    <td align="center" valign="top">
      <a href="https://github.com/ashutoshgwarpal/github-readme-streak-stats">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=CODExGAMERZ&theme=dark&hide_border=true&background=0D0D11&ring=6366f1&fire=10b981&currStreakNum=F4F4F5&sideNums=A1A1AA&sideLabels=A1A1AA&dates=A1A1AA" alt="Aryan's Streak Stats" />
      </a>
    </td>
  </tr>
</table>

<p align="center">
  <i>Explore all 22+ projects and live web simulators on my <b><a href="https://codexgamerz.github.io">Live Portfolio</a></b>.</i>
</p>
