# ✦ Aryan (CODExGAMERZ)

<p align="left">
  <a href="https://codexgamerz.github.io"><img src="https://img.shields.io/badge/Live%20Portfolio-codexgamerz.github.io-6366f1?style=flat-square&logo=firefox" alt="Portfolio" /></a>
  <a href="https://github.com/CODExGAMERZ"><img src="https://img.shields.io/badge/GitHub-CODExGAMERZ-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="https://www.instagram.com/aryannotsinha"><img src="https://img.shields.io/badge/Instagram-aryannotsinha-E4405F?style=flat-square&logo=instagram" alt="Instagram" /></a>
</p>

I design and build **performance-first developer tools, local machine learning pipelines, and hybrid AI systems** optimized for security, execution speed, and absolute data privacy. My work focuses on moving heavy computational workloads—from Transformer models and AST parsing to data profiling—directly to the user's local hardware.

---

## ⚡ Core Specializations

* **🧠 Deep Learning & NLP** — Training custom Transformer architectures from scratch, causal self-attention mechanisms, KV-caching optimizations, and BPE tokenizer vocab training.
* **🤖 Local AI & RAG Orchestration** — Designing privacy-first offline workflows using LangGraph agent pipelines, local Ollama endpoints, and RRF-fused database retrievals (Qdrant & SQLite).
* **🛠️ Developer Tooling** — VS Code extensions, custom compiler runners, and custom forks of standard editor shells (Electron/Code-OSS).
* **⚙️ Systems Integration** — Building low-latency backend APIs (FastAPI/Flask) packaged inside responsive desktop shells (PyWebView/Monaco Editor).

---

## 🚀 Featured Engineering Projects

### 🤖 Local AI & Machine Learning
* **[Code Autocomplete LLM](https://github.com/CODExGAMERZ/Code-AutoComplete-LLM)**  
  *A GPT-style multilingual code autocompletion Transformer (Python/C/Java) trained entirely from scratch.*  
  `PyTorch` `Transformers` `FlashAttention` `BPE Tokenizer` `GPU Acceleration`  
  * Manually implemented causal self-attention, rotary embeddings (RoPE), KV-caching, and logit soft-capping.
  * Packaged self-contained checkpoints embedding the token vocabulary directly into PyTorch weights.
* **[SentinelRAG](https://github.com/CODExGAMERZ/SentinelRAG)**  
  *A local-first, privacy-focused hybrid RAG engine and CLI for document databases & Obsidian Vaults.*  
  `Python` `LangGraph` `Qdrant` `Ollama` `SQLite`  
  * Combines vector similarity with graph-like centrality scoring using Reciprocal Rank Fusion (RRF).
  * Implemented an agentic self-correction loop checking prompt context against retrieval groundings.
* **[Hybrid AI Chatbot](https://github.com/CODExGAMERZ/chatbot-ai)**  
  *A self-improving offline conversation pipeline matching semantic memory with intent classifiers.*  
  `Python` `TensorFlow` `FAISS` `SentenceTransformers`
* **[DataMind AI](https://github.com/CODExGAMERZ/DataMind-ai)**  
  *An Android assistant app for compiling research summaries and gamified statistical insights.*  
  `Kotlin` `Jetpack Compose` `Gemini API` `Supabase`

### 🛠️ Developer Tools & IDEs
* **[KeyCode](https://github.com/CODExGAMERZ/KeyCode)**  
  *A customized open-source distribution of VS Code (Code - OSS) built for Windows.*  
  `TypeScript` `Electron` `Node.js` `Ollama`  
  * Features a built-in inline autocomplete companion engine with debounced local telemetry and FIM prompt construction.
* **[LogicScope](https://github.com/CODExGAMERZ/LogicScope)** ([Live Demo](https://logicscope.vercel.app/))  
  *A real-time DSA visualizer extension rendering Mermaid diagrams and call stacks directly in the gutter.*  
  `VS Code Extension` `TypeScript` `WebAssembly` `Tree-sitter` `Mermaid.js`
* **[DataPrism](https://github.com/CODExGAMERZ/DataPrism)** ([Live Demo](https://dataprismext.vercel.app/))  
  *An offline tabbed dataset profiler and visual descriptive statistics engine for CSV and JSON.*  
  `VS Code Extension` `TypeScript` `React` `Vite`
* **[ModelSight](https://github.com/CODExGAMERZ/Model-Sight)** ([Live Demo](https://modelsight.vercel.app/))  
  *A live telemetry dashboard and runtime error explainer extension for PyTorch and Keras.*  
  `VS Code Extension` `Python` `WebSockets` `HTML5`
* **[VoltC](https://github.com/CODExGAMERZ/VoltC)**  
  *A native desktop C/C++ IDE wrapper for Linux desktops featuring sub-process compiler pipelines.*  
  `Python` `FastAPI` `Monaco Editor` `PyWebView`
* **[C-Code-Assistant](https://github.com/CODExGAMERZ/C-Code-Assistant) & [Python-Code-Assistant](https://github.com/CODExGAMERZ/Python-Code-Assistant)**  
  *Local IDE shells with compilation checkpoints, flake8/cppcheck linting, and LLM self-correcting logic.*  
  `Flask` `Ollama` `GCC` `Python`

### 🌐 Web Apps & Utilities
* **[llm-advisor.dev](https://github.com/CODExGAMERZ/llm-advisor)** ([Live Demo](https://llm-advisor-ai.vercel.app/))  
  *A static hardware memory calculator estimating VRAM requirements for local LLM weights & KV-cache.*  
  `JavaScript (ESM)` `CSS Grid` `Hardware Modeling`
* **[VoltC Showcase](https://github.com/CODExGAMERZ/VoltC-Website)** ([Live Demo](https://volt-c.vercel.app/))  
  *An interactive landing page hosting an online, sandboxed C simulator compiled client-side.*  
  `HTML5` `Vanilla CSS` `Monaco Editor` `Vercel`
* **[Kryptonix](https://github.com/CODExGAMERZ/crypto-website)** ([Live Demo](https://kryptonix-tv.vercel.app/))  
  *An obsidian-themed crypto portal caching API calls locally with resilient fallback streams.*  
  `JavaScript` `TradingView Widgets` `localStorage Caching`

---

## 🛠️ Technical Stack

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
