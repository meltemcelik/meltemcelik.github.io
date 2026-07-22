Meltem Çelik
Computer Engineering | AI & Machine Learning

Computer Engineering senior at İstinye University. I specialize in building robust, production-ready AI and machine learning systems—from managing large-scale memory constraints to deploying hybrid RAG architectures. Stack: Python, SQL, C++, FastAPI, OpenCV, DuckDB.

🛠 Case Studies

1. Microsoft - Hybrid RAG System Architecture

The Problem: Building an end-to-end Question-Answering system over proprietary corporate documents where naive semantic search failed to catch precise keyword contexts, leading to irrelevant retrievals.

What I Did / Decided: I implemented a hybrid retrieval layer combining BM25 keyword search with nomic-embed-text vector search, merging them using Reciprocal Rank Fusion (RRF). I integrated guardrails to block out-of-scope queries and established an automated evaluation script measuring hit@k and MRR on a 52-question golden set.

Outcome: Successfully deployed a production-ready FastAPI/WebSocket service featuring local LLM streaming via Ollama and verified retrieval gains through quantitative metrics.

2. FlyRank AI - Machine Learning Data Pipeline & Leakage Prevention

The Problem: Building a predictive model to identify web pages at risk of losing search traffic. Working with daily Google Search Console data, the primary risk was target leakage—where proxy features would artificially inflate accuracy during training.

What I Did / Decided: I engineered workflows in Python and DuckDB to handle 78-million-row datasets under extreme memory constraints. I made the strict architectural decision to implement automated leakage tests using Scikit-learn, explicitly dropping high-risk features (like raw impressions and clicks) before training.

Outcome: Delivered a clean, leakage-free classification pipeline with self-testing assertions that automatically flag data integrity errors during runtime.

🤖 Ask My AI Agent
Want to know more about my architectural decisions, how I handle extreme computational constraints, or my problem-solving approach? 👉 Chat with my AI Copilot here

📬 Contact

GitHub: github.com/meltemcelik

LinkedIn: linkedin.com/in/meltem-çelik-655905332

Email: meltemcelik034@gmail.com
