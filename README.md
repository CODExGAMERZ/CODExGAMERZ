# 👋 Hey, I'm Aryan (CODExGAMERZ)

### AI Engineer • ML Developer • Software Builder

I build **AI systems, developer tools, and performance-focused software** designed for real-world usage — not just prototypes. 

🚀 **Explore my live portfolio: [codexgamerz.github.io](https://codexgamerz.github.io)**

---

## 🛠️ Focus Areas

* **🧠 Machine Learning & Deep Learning** — Custom models, training pipelines, and inference optimization.
* **🤖 Large Language Models & Local Inference** — Building and deploying language models on consumer hardware.
* **⚙️ System Design** — Compiler integration, proxy architectures, and hybrid systems.
* **⚡ Client-Side Optimization** — Caching architectures, performance tuning, and resilient UIs.

I enjoy exploring how modern systems work internally — from **Transformers and semantic retrieval** to **compilers, hybrid AI, and developer automation tools**.

---

# 🚀 Featured Projects

## 🤖 Hybrid AI Chatbot
A production-oriented AI assistant architecture demonstrating how modern assistants are built beyond simple API wrappers. It uses classical NLP/Keras for intent classification, FAISS vector search for local concept memory, and a custom LLM teacher fallback model.

* **🧠 Smart Decision Flow:** FAISS Semantic Memory ➔ Local Knowledge Base ➔ Intent Classifier ➔ LLM Fallback (Teacher).
* **🔄 Self-Improving Loop:** Automatically clusters unrecognized inputs, generates responses using LLM, and retrains locally.
* **⚡ Hybrid Architecture:** Minimizes external API inference costs while maintaining high quality.

`Python` `TensorFlow (Keras)` `FAISS` `Sentence Transformers` `NLP` `Machine Learning`

🔗 **Repository:** [github.com/CODExGAMERZ/chatbot-ai](https://github.com/CODExGAMERZ/chatbot-ai)

---

## 🧬 Code Autocomplete LLM
A GPT-style autoregressive Transformer trained entirely from scratch for Python code autocompletion.

* **⚙️ True GPT Decoder:** Implements causal self-attention mechanism, layer normalization, and causal masking.
* **⚡ KV-Cache Support:** Uses stored key/value tensors during generation to achieve O(1) step incremental decoding speed.
* **💾 Checkpoint System:** Includes a resume-safe local training framework capable of recovering from interrupts (Ctrl+C).

`PyTorch` `Tokenizers` `Deep Learning` `Language Modeling` `Transformers`

🔗 **Repository:** [github.com/CODExGAMERZ/Code-AutoComplete-LLM](https://github.com/CODExGAMERZ/Code-AutoComplete-LLM)

---

## ⚡ llm-advisor.dev
A precision advisor for running Large Language Models on local consumer rigs, workstations, servers, and Apple Silicon.

* **🔬 Mode A (Model ➔ Specs):** Dynamic VRAM breakdown (Weights vs. KV Cache vs. Overhead) and tokens/sec estimates.
* **🖥️ Mode B (Specs ➔ Model):** Ranks and filters which models fit your exact GPU, RAM, CPU class, and multi-GPU layout.
* **🧮 Mode C (Custom Model):** Calculates custom parameter size, bits, and attention style overheads (GQA, MQA, MHA).
* **🍏 macOS Unified Memory:** Tailored memory limits and command guides for Apple Silicon architectures.

`Vanilla JavaScript` `ES Modules (ESM)` `Math Estimation` `Web Design`

🔗 **Repository:** [github.com/CODExGAMERZ/llm-advisor](https://github.com/CODExGAMERZ/llm-advisor)  
🔗 **Live Demo:** [llm-advisor-ai.vercel.app](https://llm-advisor-ai.vercel.app/)

---

## 🛠️ C-Code-Assistant
A fully local, AI-powered programming companion IDE that serves C code completions, linting, error fixing, and execution.

* **▶️ In-Browser Runner:** Runs C code with sub-process execution timeouts (GCC) directly from the browser.
* **🔍 Live Code Linting:** Gutter marker visual integrations utilizing `cppcheck`/`gcc`.
* **🔄 Quality-Retry Gate:** Real-time stream auditor that uses LLMs to self-correct code output if validations fail.
* **🔒 Same-Origin Proxy:** Flask proxy routes all Ollama traffic, removing the need to expose Ollama origins.

`Python` `Flask` `JavaScript` `Compiler Integration` `Developer Tools` `Ollama` `GCC`

🔗 **Repository:** [github.com/CODExGAMERZ/C-Code-Assistant](https://github.com/CODExGAMERZ/C-Code-Assistant)

---

## 🐍 Python-Code-Assistant
A fully local, AI-powered programming companion IDE that serves Python code completions, linting, error fixing, and execution.

* **▶️ In-Browser Runner:** Runs Python code with sub-process execution timeouts directly from the browser.
* **🔍 Live Code Linting:** Gutter marker visual integrations utilizing `flake8`/`py_compile`.
* **🔒 Same-Origin Proxy:** Flask proxy routes all Ollama traffic, removing the need to expose Ollama origins.

`Python` `Flask` `JavaScript` `Developer Tools` `Ollama` `flake8`

🔗 **Repository:** [github.com/CODExGAMERZ/Python-Code-Assistant](https://github.com/CODExGAMERZ/Python-Code-Assistant)

---

## ⚡ VoltC
A native, lightweight C/C++ desktop IDE for Ubuntu Linux, showcased via an interactive simulator landing page.

* **💻 Main Product (VoltC IDE):** A native Ubuntu desktop application combining a FastAPI backend, Monaco Editor, and a PyWebView shell to provide a lightning-fast native environment.
* **🌐 Showcase Website:** A dedicated landing website featuring a fully interactive online IDE simulator for users to try the IDE features directly in-browser.
* **🤖 VoltC v2 AI Debug Assistant:** Right-click compilation errors for plain-English translations and inline diff suggestions powered by any OpenAI-compatible API.
* **🔌 Git Integration & clangd LSP:** Built-in Git panel supporting stage, commit, and diff views alongside a persistent PTY terminal and full auto-completion/diagnostics.
* **📊 Stack & Heap Memory Visualizer:** Automatically scans and renders live memory structure diagrams with pointer arrows during execution.

`Python` `FastAPI` `Monaco Editor` `C/C++` `Git` `LSP` `PyWebView` `WebSocket`

🔗 **Repository:** [github.com/CODExGAMERZ/VoltC](https://github.com/CODExGAMERZ/VoltC)  
🔗 **Live Demo (Showcase):** [volt-c.vercel.app](https://volt-c.vercel.app/)

---

## 💎 Kryptonix
A premium, dark-first obsidian glassmorphism crypto dashboard with dual-level caching and resilient fallback mechanisms.

* **📊 Live Markets Portal:** Interactive spot lists, exchange tracking, growth categories, and institutional Bitcoin holdings.
* **🧮 Double Caching:** Custom 5-minute local storage cache that protects user interactions from CoinGecko API rate limits.
* **🔌 Resilient Fallbacks:** Dynamically launches a clean warning banner and loads cached mock data when API limit hits (429).
* **📈 TradingView Widgets:** Integrates high-fidelity interactive charting dashboards and quote widgets.

`JavaScript` `Chart.js` `TradingView API` `HTML5` `CSS3` `REST APIs`

🔗 **Repository:** [github.com/CODExGAMERZ/crypto-website](https://github.com/CODExGAMERZ/crypto-website)  
🔗 **Live Demo:** [kryptonix-tv.vercel.app](https://kryptonix-tv.vercel.app/)

---

## 🎯 FocusFlow
A lightweight task stopwatch and analytics app optimized for fluid micro-animations and zero state loss.

* **⏲️ Per-Task Stopwatches:** Run independent timers concurrently without code blocks or timing delays.
* **📊 Focus Analytics:** Automatically updates today's time, all-time records, and trending top-focus tasks.
* **💾 Safe Tick Persistence:** Timer states are written instantly to `localStorage` on completion and updates, avoiding page reload resets.

`Vanilla JavaScript` `Performance Optimization` `UI Engineering` `Local Storage`

🔗 **Repository:** [github.com/CODExGAMERZ/focusflow](https://github.com/CODExGAMERZ/focusflow)  
🔗 **Live Demo:** [focusflow-tv.vercel.app](https://focusflow-tv.vercel.app/)

---

## 📚 WebNotes
A premium, interactive web client designed for organizing, reading, and studying programming study guides and reference notes.

* **📖 Interactive Carousel:** Includes a 3-card rotating notes selector with scale/opacity adjustments.
* **🐍 Language Bundles & Metaphors:** Packaged with detailed Python, Java, and C guides using real-world metaphors and GDB/Vim cheat sheets.
* **⬆️ Markdown Import & Auto-Theme:** Drop markdown files into the browser; the app auto-parses headings and applies custom language themes from 24 language configurations using syntax scoring.
* **📄 Print Overrides (PDF):** Download notes as high-contrast print-ready PDFs with clean custom CSS print stylesheets.

`Vanilla JavaScript` `Marked.js` `Highlight.js` `Html2pdf.js` `HTML5 / CSS3`

🔗 **Repository:** [github.com/CODExGAMERZ/WebNotes](https://github.com/CODExGAMERZ/WebNotes)  
🔗 **Live Demo:** [webynotes.netlify.app](https://webynotes.netlify.app/)

---

## 🎬 CineFinder
A modern glassmorphic web catalog to discover film statistics, director crews, cast lineups, ratings, and box office charts.

* **🧩 Key Checker Wizard:** Evaluates and guides developers to set up OMDb credentials via UI helpers.
* **🌟 Skeleton Loaders:** Synchronous loading card outlines that pulse to preserve layout dimensions.
* **📱 Responsive Layout:** Grid layout built on vanilla flex and CSS layouts.

`JavaScript` `OMDb API` `CSS Glassmorphism` `HTML5`

🔗 **Repository:** [github.com/CODExGAMERZ/Movie](https://github.com/CODExGAMERZ/Movie)

---

## 📱 QR Code Generator CLI
An interactive and CLI utility to customize, generate, and preview QR codes.

* **🎨 Wizard Setup:** Step-by-step console questionnaire for colors, sizes, borders, and image paths.
* **🖥️ Console Previews:** Renders high-fidelity ASCII QR codes in the terminal before exporting PNG assets.
* **🛠️ Script Integration:** Supports automation flags for silent generation.

`Python` `qrcode` `Pillow` `CLI Design`

🔗 **Repository:** [github.com/CODExGAMERZ/QrCODE-GENRATOR](https://github.com/CODExGAMERZ/QrCODE-GENRATOR)

---

# 🧠 Interests & Research Areas

* 🤖 **AI & Machine Learning** — Neural networks, classification, and intelligent automation.
* 🧬 **Deep Learning & Transformers** — Attention mechanisms, GPT architectures, and training from scratch.
* 🔗 **Hybrid AI Systems** — Combining traditional ML, vector DBs, and LLMs for robust pipelines.
* ⚡ **Local AI & Inference Optimization** — Running models on consumer hardware with minimal latency.
* 🛠️ **Developer Tooling & Static Analysis** — Linting integrations, code assistants, and compiler toolchains.
* 🌐 **Performance-First Web Engineering** — Caching, resilient UIs, and zero-dependency architectures.

---

# 🛠️ Tech Stack

### 💻 Languages
`Python` `JavaScript (ES6+)` `C` `HTML5` `CSS3`

### 🧠 AI / Deep Learning
`PyTorch` `TensorFlow / Keras` `FAISS` `Sentence Transformers` `NLP` `Ollama` `Tokenizers`

### 🔧 Tools & Infrastructures
`Git` `GitHub Pages` `Flask` `FastAPI` `PyWebView` `WebSockets` `MinGW / GCC` `cppcheck` `flake8` `REST APIs`

---

# 📫 Connect With Me

- **🐙 GitHub:** [github.com/CODExGAMERZ](https://github.com/CODExGAMERZ)
- **📸 Instagram:** [@aryannotsinha](https://www.instagram.com/aryannotsinha)
- **⚡ Portfolio:** [codexgamerz.github.io](https://codexgamerz.github.io)

---

> *"I enjoy building systems that are efficient, understandable, and genuinely useful — whether it's a custom-trained LLM, a developer tool, or a responsive caching client."*
