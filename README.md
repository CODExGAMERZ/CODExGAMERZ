# 👋 Hey, I'm Aryan (CODExGAMERZ)

### AI Engineer • ML Developer • Software Builder

I build **AI systems, developer tools, and performance-focused software** designed for real-world usage — not just prototypes.

My work focuses on combining:

* **Machine Learning & Deep Learning**
* **Large Language Models & Local Inference**
* **System Design & Compiler Integration**
* **Client-Side Optimization & Caching Architectures**

I enjoy exploring how modern systems work internally — from **Transformers and semantic retrieval** to **compilers, hybrid AI, and developer automation tools**.

---

# 🚀 Featured Projects

## 🤖 Hybrid AI Chatbot with Semantic Memory & Self-Learning Pipeline
A production-oriented AI assistant architecture demonstrating how modern assistants are built beyond simple API wrappers. It uses classical NLP/Keras for intent classification, FAISS vector search for local concept memory, and a custom LLM teacher fallback model.

* **🧠 Smart Decision Flow:** FAISS Semantic Memory ➔ Local Knowledge Base ➔ Intent Classifier ➔ LLM Fallback (Teacher).
* **🔄 Self-Improving Loop:** Automatically clusters unrecognized inputs, generates responses using LLM, and retrains locally.
* **⚡ Hybrid Architecture:** Minimizes external API inference costs while maintaining high quality.

`Python` `TensorFlow (Keras)` `FAISS` `Sentence Transformers` `NLP` `Machine Learning`

🔗 **Repository:** [https://github.com/CODExGAMERZ/chatbot-ai](https://github.com/CODExGAMERZ/chatbot-ai)

---

## 🧠 Python Code Autocomplete LLM (Decoder-Only GPT from Scratch)
A GPT-style autoregressive Transformer trained entirely from scratch for Python code autocompletion.

* **⚙️ True GPT Decoder:** Implements causal self-attention mechanism, layer normalization, and causal masking.
* **⚡ KV-Cache Support:** Uses stored key/value tensors during generation to achieve O(1) step incremental decoding speed.
* **💾 Checkpoint System:** Includes a resume-safe local training framework capable of recovering from interrupts (Ctrl+C).

`PyTorch` `Tokenizers` `Deep Learning` `Language Modeling` `Transformers`

🔗 **Repository:** [https://github.com/CODExGAMERZ/Code-AutoComplete-LLM](https://github.com/CODExGAMERZ/Code-AutoComplete-LLM)

---

## ⚡ llm-advisor.dev – Hardware Rig Compatibility Calculator
A precision advisor for running Large Language Models on local consumer rigs, workstations, servers, and Apple Silicon.

* **🔬 Mode A (Model ➔ Specs):** Dynamic VRAM breakdown (Weights vs. KV Cache vs. Overhead) and tokens/sec estimates.
* **🖥️ Mode B (Specs ➔ Model):** Ranks and filters which models fit your exact GPU, RAM, CPU class, and multi-GPU layout.
* **🧮 Mode C (Custom Model):** Calculates custom parameter size, bits, and attention style overheads (GQA, MQA, MHA).
* **🍏 macOS Unified Memory:** Tailored memory limits and command guides for Apple Silicon architectures.

`Vanilla JavaScript` `ES Modules (ESM)` `Math Estimation` `Web Design`

🔗 **Repository:** [https://github.com/CODExGAMERZ/llm-advisor](https://github.com/CODExGAMERZ/llm-advisor)

---

## 💻 C-Code-Assistant & 🐍 Python-Code-Assistant
Fully local, AI-powered programming companion IDEs that serve code completions, linting, error fixing, and execution.

* **▶️ In-Browser Runners:** Runs code with sub-process execution timeouts (GCC/Python) directly from the browser.
* **🔍 Live Code Linting:** Gutter marker visual integrations utilizing `cppcheck`/`gcc` for C and `flake8`/`py_compile` for Python.
* **🔄 Quality-Retry Gate:** Real-time stream auditor that uses LLMs to self-correct code output if validations fail.
* **🔒 Same-Origin Proxy:** Flask proxy routes all Ollama traffic, removing the need to expose Ollama origins.

`Python` `Flask` `JavaScript` `Compiler Integration` `Developer Tools` `Ollama`

🔗 **C Assistant Repo:** [https://github.com/CODExGAMERZ/C-Code-Assistant](https://github.com/CODExGAMERZ/C-Code-Assistant)  
🔗 **Python Assistant Repo:** [https://github.com/CODExGAMERZ/Python-Code-Assistant](https://github.com/CODExGAMERZ/Python-Code-Assistant)

---

## 🌐 Kryptonix – Advanced Cryptocurrency Tracker
A premium, dark-first obsidian glassmorphism crypto dashboard with dual-level caching and resilient fallback mechanisms.

* **📊 Live Markets Portal:** Interactive spot lists, exchange tracking, growth categories, and institutional Bitcoin holdings.
* **🧮 Double Caching:** Custom 5-minute local storage cache that protects user interactions from CoinGecko API rate limits.
* **🔌 Resilient Fallbacks:** Dynamically launches a clean warning banner and loads cached mock data when API limit hits (429).
* **📈 TradingView widgets:** Integrates high-fidelity interactive charting dashboards and quote widgets.

`JavaScript` `Chart.js` `TradingView API` `HTML5` `CSS3` `REST APIs`

🔗 **Repository:** [https://github.com/CODExGAMERZ/crypto-website](https://github.com/CODExGAMERZ/crypto-website)  
🔗 **Live Demo:** [https://codexgamerz.github.io/crypto-website/](https://codexgamerz.github.io/crypto-website/)

---

## ⏱️ FocusFlow – Productivity & Task Tracking App
A lightweight task stopwatch and analytics app optimized for fluid micro-animations and zero state loss.

* **⏲️ Per-Task Stopwatches:** Run independent timers concurrently without code blocks or timing delays.
* **📊 Focus Analytics:** Automatically updates today's time, all-time records, and trending top-focus tasks.
* **💾 Safe Tick Persistence:** Timer states are written instantly to `localStorage` on completion and updates, avoiding page reload resets.

`Vanilla JavaScript` `Performance Optimization` `UI Engineering` `Local Storage`

🔗 **Repository:** [https://github.com/CODExGAMERZ/focusflow](https://github.com/CODExGAMERZ/focusflow)  
🔗 **Live Demo:** [https://codexgamerz.github.io/focusflow/](https://codexgamerz.github.io/focusflow/)

---

## 🎬 CineFinder – Movie Discovery Engine
A modern glassmorphic web catalog to discover film statistics, director crews, cast lineups, ratings, and box office charts.

* **🧩 Key Checker Wizard:** Evaluates and guides developers to set up OMDb credentials via UI helpers.
* **🌟 Skeleton Loaders:** Synchronous loading card outlines that pulse to preserve layout dimensions.
* **📱 Responsive Layout:** Grid layout built on vanilla flex and CSS layouts.

`JavaScript` `OMDb API` `CSS Glassmorphism` `HTML5`

🔗 **Repository:** [https://github.com/CODExGAMERZ/Movie](https://github.com/CODExGAMERZ/Movie)

---

## 🔲 Custom QR Code Generator CLI
An interactive and CLI utility to customize, generate, and preview QR codes.

* **🎨 Wizard Setup:** Step-by-step console questionnaire for colors, sizes, borders, and image paths.
* **🖥️ Console Previews:** Renders high-fidelity ASCII QR codes in the terminal before exporting PNG assets.
* **🛠️ Script Integration:** Supports automation flags for silent generation.

`Python` `qrcode` `Pillow` `CLI Design`

🔗 **Repository:** [https://github.com/CODExGAMERZ/QrCODE-GENRATOR](https://github.com/CODExGAMERZ/QrCODE-GENRATOR)

---

# 🧠 Interests & Research Areas

* Artificial Intelligence & Machine Learning
* Deep Learning & Transformer Architectures
* Hybrid AI Systems (Traditional ML + Vector DBs + LLMs)
* Local AI & Inference Bandwidth Optimization
* Developer Tooling & Static Analysis Integration

---

# 🛠 Tech Stack

### Languages
`Python` `JavaScript (ES6+)` `C` `HTML5` `CSS3`

### AI / Deep Learning
`PyTorch` `TensorFlow / Keras` `FAISS` `Sentence Transformers` `NLP` `Ollama` `Tokenizers`

### Tools & Infrastructures
`Git` `GitHub Pages` `Flask` `MinGW / GCC` `cppcheck` `flake8` `REST APIs`

---

# 📫 Connect With Me

🐙 GitHub: [https://github.com/CODExGAMERZ](https://github.com/CODExGAMERZ)  
📸 Instagram: [https://www.instagram.com/aryannotsinha](https://www.instagram.com/aryannotsinha)

---

> “I enjoy building systems that are efficient, understandable, and genuinely useful — whether it's a custom-trained LLM, a developer tool, or a responsive caching client.”
