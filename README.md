# ✦ ARYAN (CODExGAMERZ)

<p align="left">
  <a href="https://codexgamerz.github.io"><img src="https://img.shields.io/badge/Portfolio-codexgamerz.github.io-6366f1?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/CODExGAMERZ"><img src="https://img.shields.io/badge/GitHub-CODExGAMERZ-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:aryansinha1920@gmail.com"><img src="https://img.shields.io/badge/Email-aryansinha1920%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.instagram.com/aryannotsinha"><img src="https://img.shields.io/badge/Instagram-aryannotsinha-E4405F?style=for-the-badge&logo=instagram" alt="Instagram" /></a>
</p>

### AI Engineer & Systems Developer
I specialize in building **performance-first developer tooling, local-first machine learning pipelines, and hybrid AI systems** optimized for low-latency execution, hardware efficiency, and absolute data privacy. My goal is to shift complex computational workloads back to client hardware through optimized architectures, lightweight compilers, and custom client runtimes.

---

## ⚡ Technical Core Areas

- 🧠 **Deep Learning & Transformers**: Autoregressive decoder-only Transformer design (causal self-attention, rotary positional embeddings (RoPE), KV-caching, FlashAttention) trained from scratch.
- 🤖 **Retrieval-Augmented Generation (RAG)**: Intent-driven multi-agent workflows (LangGraph), high-performance vector databases (Qdrant, FAISS), and Reciprocal Rank Fusion (RRF) for hybrid retrieval.
- 🛠️ **Systems & Developer Tooling**: Abstract Syntax Tree (AST) parsing with WebAssembly Tree-sitter, VS Code extension development, and custom Electron/Code-OSS IDE compilation.
- 💻 **Desktop & Native Wrappers**: Lightweight native GUI applications using PyWebView, FastAPI, Monaco Editor integration, and sub-process compiler integration.

---

## 🚀 Flagship Projects

### 🔌 [Homogenous](https://github.com/CODExGAMERZ/homogenous)
*Local-first, zero-overhead agentic CLI coding assistant built in TypeScript and Ink.*
- **Architecture & TUI**: Dynamic terminal UI using React 19 and Ink, featuring syntax-highlighted code blocks, state-reactive borders, and live spinners.
- **Provider Routing**: Connects both local offline runtimes (Ollama, LM Studio) and cloud APIs (Anthropic, OpenAI, Groq, NVIDIA NIM, DeepSeek) with failover.
- **Advanced Control**: Standing plan mode (`/plan` & `/apply`), safe auto-approve safeguards, and unified colorized diff rollback system.
- **Stack**: `TypeScript` • `Node.js` • `React (Ink)` • `Ollama` • `Anthropic` • `MCP SDK` • `Zod`

### 🧠 [Code Autocomplete LLM](https://github.com/CODExGAMERZ/Code-AutoComplete-LLM)
*Multilingual GPT-style autocomplete model trained from scratch supporting Python, C, and Java.*
- **Architecture & Design**: Integrated **Rotary Positional Embeddings (RoPE)**, **GeGLU gating**, and soft logit capping into a custom causal decoder framework.
- **Optimization**: Enabled **FlashAttention (SDPA)** and dynamic **KV-caching** to accelerate local inference speeds on consumer GPUs.
- **Stack**: `PyTorch` • `Transformers` • `FlashAttention` • `BPE Tokenizer` • `DDP`

### 📚 [B.Tech-AI-Tutor-7B](https://github.com/CODExGAMERZ/B.Tech-AI-Tutor-7B)
*Fine-tuned academic study tutor built on top of Qwen-2.5-7B-Instruct, optimized for Colab training & local GGUF running.*
- **Dataset Pipeline**: Engineered a custom 5-layer dataset pipeline spanning ~480K instruction-tuning samples and 15K preference pairs.
- **Training & Quantization**: Configured a multi-phase pipeline executing SFT and DPO via Unsloth, quantized to GGUF format for low-latency running locally with Ollama/llama.cpp.
- **Stack**: `PyTorch` • `Qwen-2.5` • `Unsloth` • `DPO / SFT` • `HuggingFace` • `GGUF` • `Ollama`

### 🛡️ [SentinelRAG](https://github.com/CODExGAMERZ/SentinelRAG)
*Privacy-first local search engine transforming directories and Obsidian vaults into context-aware systems.*
- **Ingestion & Sync**: Engineered a debounced filesystem watcher parsing markdown links and headers in real-time.
- **Retrieval Engine**: Fused vector search scores with SQLite structural centrality metrics using Reciprocal Rank Fusion (RRF) for highly contextual answers.
- **Agent Workflows**: Designed self-correcting agent state graphs verifying prompt retrieval context to prevent LLM hallucinations.
- **Stack**: `Python` • `LangGraph` • `Qdrant` • `Ollama` • `SQLite`

### 🖥️ [KeyCode (Custom IDE Fork)](https://github.com/CODExGAMERZ/KeyCode)
*A custom Windows distribution of VS Code (Code - OSS) with a built-in AI autocomplete companion.*
- **Built-in Extension**: Developed a custom completion provider utilizing Fill-in-the-Middle (FIM) prompt formatting.
- **Latency & Caching**: Optimized client-side response paths through request debouncing and predictive local caching.
- **Stack**: `TypeScript` • `Electron` • `Node.js` • `Ollama`

### ⚡ [VoltC IDE](https://github.com/CODExGAMERZ/VoltC)
*A native desktop IDE for Ubuntu executing client-side compilation and sub-process GCC checks.*
- **Features**: Developed client-side compiling, sub-process GCC diagnostics, and real-time gutter diagnostics.
- **Visuals**: Features interactive AST analysis and local visual memory allocation charts.
- **Stack**: `Python` • `FastAPI` • `Monaco Editor` • `PyWebView`

### 👁️ [LogicScope](https://github.com/CODExGAMERZ/LogicScope) | [Live Demo](https://logicscope.vercel.app/)
*Real-time code visualizer rendering DSA recursion trees and UML diagrams as you type.*
- **AST Parsing**: Developed an offline-first parsing engine running WebAssembly-compiled Tree-sitter AST queries in-browser.
- **Visualization**: Transformed code structures dynamically into interactive Mermaid.js diagrams.
- **Stack**: `TypeScript` • `WebAssembly` • `Tree-sitter` • `Mermaid.js` • `VS Code Extension API`

### 🤖 [JarvisRAG](https://github.com/CODExGAMERZ/JarvisRAG)
*Local-first knowledge base assistant ingesting documents into a vector database with a central command UI.*
- **Ingestion**: Ingests `.pdf`, `.txt`, and `.md` files dynamically using local embedding models into a FAISS vector store.
- **Interface**: Features a futuristic browser console with MathJax LaTeX rendering, marked-down contexts, and a live search telemetry stream.
- **Stack**: `Python` • `FastAPI` • `FAISS` • `Gemini API` • `Tailwind CSS`

---

## 🛠️ Technology Stack & Tools

<table>
  <tr>
    <td width="50%">
      <b>Languages</b><br/>
      <code>Python</code> • <code>TypeScript</code> • <code>JavaScript (ES6+)</code> • <code>Kotlin</code> • <code>C</code> • <code>HTML5</code> • <code>CSS3</code>
    </td>
    <td width="50%">
      <b>AI & Deep Learning</b><br/>
      <code>PyTorch</code> • <code>TensorFlow</code> • <code>FAISS</code> • <code>SentenceTransformers</code> • <code>LangGraph</code> • <code>HuggingFace</code>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b>Developer Tooling</b><br/>
      <code>VS Code Extension API</code> • <code>WebAssembly</code> • <code>Electron</code> • <code>Monaco Editor</code> • <code>Tree-sitter (ASTs)</code>
    </td>
    <td width="50%">
      <b>Backend & Infrastructure</b><br/>
      <code>Node.js</code> • <code>FastAPI</code> • <code>Flask</code> • <code>Qdrant</code> • <code>SQLite</code> • <code>Supabase</code> • <code>WebSockets</code>
    </td>
  </tr>
</table>

---

## 📊 GitHub Metrics

<p align="center">
  <a href="https://github.com/CODExGAMERZ">
    <img src="https://github-stats-extended.vercel.app/api?username=CODExGAMERZ&show_icons=true&theme=calm&hide_border=true&bg_color=0D0D11&title_color=6366f1&icon_color=6366f1&text_color=A1A1AA" alt="Aryan's GitHub Stats" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/CODExGAMERZ">
    <img src="https://streak-stats.demolab.com/?user=CODExGAMERZ&theme=dark&hide_border=true&background=0D0D11&ring=6366f1&fire=10b981&currStreakNum=F4F4F5&sideNums=A1A1AA&sideLabels=A1A1AA&dates=A1A1AA" alt="Aryan's Streak Stats" />
  </a>
</p>

<p align="center">
  <i>Explore 23+ projects, research tools, and simulators on my <b><a href="https://codexgamerz.github.io">Live Portfolio</a></b>.</i>
</p>
