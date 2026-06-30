# Juan Martos Cuevas


---

## iOS Apps

| App | Description | Repository |
| :--- | :--- | :---: |
| **Convall** | Cloud-based file converter built with Flutter. | [Repo](https://github.com/juanmmm21/Convall) |
| **Tickertape** | Currency converter for iOS with a retro-inspired UI. | [Repo](https://github.com/juanmmm21/Tickertape) |
| **Latent** | Privacy-focused, local-first note-taking app using on-device AI (CoreML) for embeddings and automatic note linking. | [Repo](https://github.com/juanmmm21/Latent) |

---

## AI Core Infrastructure

### Data Processing and Input

| Project | Description | Repository |
| :--- | :--- | :---: |
| **bpe-tokenizer-from-scratch** | Byte Pair Encoding (BPE) tokenizer built from scratch for LLM data pipelines. | [Repo](https://github.com/juanmmm21/bpe-tokenizer-from-scratch) |
| **semantic-chunking-engine** | Embedding-based document chunker that segments text at semantic boundaries for RAG. | [Repo](https://github.com/juanmmm21/semantic-chunking-engine) |
| **multimodal-doc-parser** | Document parsing pipeline for structured Markdown, tables, and visuals from PDFs and images (PyMuPDF, VLMs). | [Repo](https://github.com/juanmmm21/multimodal-doc-parser) |
| **llm-annotation-studio** | Web-based annotation studio for text classification, RLHF/DPO alignment, and NER tagging. | [Repo](https://github.com/juanmmm21/llm-annotation-studio) |

### Representation, Storage, and Retrieval

| Project | Description | Repository |
| :--- | :--- | :---: |
| **contrastive-embedding-trainer** | Contrastive training of text embeddings with PyTorch and Siamese networks (Triplet Cosine Loss). | [Repo](https://github.com/juanmmm21/contrastive-embedding-trainer) |
| **nano-vector-db** | Lightweight vector database with HNSW indexing and cosine similarity search. | [Repo](https://github.com/juanmmm21/nano-vector-db) |
| **knowledge-graph-extractor** | Pipeline to build structured knowledge graphs from unstructured text using LLMs. | [Repo](https://github.com/juanmmm21/knowledge-graph-extractor) |
| **hybrid-search-retrieval-pipeline** | Hybrid retrieval combining dense vector search and sparse BM25 keyword matching. | [Repo](https://github.com/juanmmm21/hybrid-search-retrieval-pipeline) |
| **cross-encoder-reranker** | Cross-encoder pipeline to re-rank retrieved documents for RAG. | [Repo](https://github.com/juanmmm21/cross-encoder-reranker) |

### Inference, Lifecycle, and Control

| Project | Description | Repository |
| :--- | :--- | :---: |
| **llm-inference-server** | LLM inference server with token streaming and dynamic request batching. | [Repo](https://github.com/juanmmm21/llm-inference-server) |
| **semantic-model-router** | Semantic router that assigns prompts to the optimal LLM to reduce latency and cost. | [Repo](https://github.com/juanmmm21/semantic-model-router) |
| **llm-guardrails-shield** | Bidirectional security layer against prompt injection and data leaks. | [Repo](https://github.com/juanmmm21/llm-guardrails-shield) |

### Agents and Autonomy

| Project | Description | Repository |
| :--- | :--- | :---: |
| **orchestra-agents** | Multi-agent framework with autonomous ReAct reasoning loops. | [Repo](https://github.com/juanmmm21/orchestra-agents) |
| **agentic-memory-layer** | Structured memory layer with short- and long-term vector storage for AI agents. | [Repo](https://github.com/juanmmm21/agentic-memory-layer) |
| **secure-tool-runtime** | Sandboxed execution runtime for safe LLM code and API execution. | [Repo](https://github.com/juanmmm21/secure-tool-runtime) |

### MLOps, Synthetic Data, and Quality

| Project | Description | Repository |
| :--- | :--- | :---: |
| **synthetic-data-generator** | Engine to generate and filter synthetic instruction datasets using LLMs. | [Repo](https://github.com/juanmmm21/synthetic-data-generator) |
| **dataset-version-control** | Version control for ML datasets to ensure reproducible training runs. | [Repo](https://github.com/juanmmm21/dataset-version-control) |
| **llm-qlora-finetuner** | QLoRA/PEFT fine-tuning pipeline for custom datasets with PyTorch. | [Repo](https://github.com/juanmmm21/llm-qlora-finetuner) |
| **llm-eval-harness** | Automated evaluation suite to benchmark LLM output quality and detect regressions. | [Repo](https://github.com/juanmmm21/llm-eval-harness) |
| **llm-observability-tracer** | End-to-end tracing for LLM API calls, token usage, and latency. | [Repo](https://github.com/juanmmm21/llm-observability-tracer) |

### Applications

| Project | Description | Repository |
| :--- | :--- | :---: |
| **nexus-second-brain** | Privacy-first personal knowledge management app with semantic search, document parsing, and chat. | [Repo](https://github.com/juanmmm21/nexus-second-brain) |
| **ai-core-infra-hub** | Web control panel that integrates and orchestrates the AI Core Infrastructure projects. | [Repo](https://github.com/juanmmm21/ai-core-infra-hub) |

---

## Quantitative Trading Core Infrastructure

### Data Pipelines

| Project | Description | Repository |
| :--- | :--- | :---: |
| **websocket-feed-handler** | Async WebSocket client with auto-reconnect for live crypto exchange feeds. | [Repo](https://github.com/juanmmm21/websocket-feed-handler) |
| **order-book-reconstructor** | In-memory L2/L3 order book reconstructor for low-latency bid/ask maintenance. | [Repo](https://github.com/juanmmm21/order-book-reconstructor) |
| **market-data-lakehouse** | Streaming pipeline that aggregates ticks into OHLCV candles and stores them in Parquet and DuckDB. | [Repo](https://github.com/juanmmm21/market-data-lakehouse) |

### Analytics

| Project | Description | Repository |
| :--- | :--- | :---: |
| **ta-indicators-from-scratch** | NumPy-vectorized technical indicators implemented without third-party TA libraries. | [Repo](https://github.com/juanmmm21/ta-indicators-from-scratch) |
| **alpha-signal-generator** | Pluggable strategy engine that emits entry and exit signals from market data. | [Repo](https://github.com/juanmmm21/alpha-signal-generator) |

### Backtesting and Execution

| Project | Description | Repository |
| :--- | :--- | :---: |
| **event-driven-backtester** | Event-driven simulator that replays historical ticks and fills second by second. | [Repo](https://github.com/juanmmm21/event-driven-backtester) |
| **market-condition-simulator** | Backtest middleware that injects network latency and order book slippage. | [Repo](https://github.com/juanmmm21/market-condition-simulator) |
| **order-routing-gateway** | Exchange-agnostic gateway that routes orders to live APIs or paper trading. | [Repo](https://github.com/juanmmm21/order-routing-gateway) |

### Risk and MLOps

| Project | Description | Repository |
| :--- | :--- | :---: |
| **risk-management-engine** | Pre-trade risk gate enforcing position sizing, stop-loss, and max drawdown limits. | [Repo](https://github.com/juanmmm21/risk-management-engine) |
| **quant-metrics-calculator** | Performance analytics toolkit computing Sharpe, Sortino, profit factor, and equity curves. | [Repo](https://github.com/juanmmm21/quant-metrics-calculator) |
| **trade-audit-logger** | Millisecond-precision audit trail for trades, orders, decisions, and system errors. | [Repo](https://github.com/juanmmm21/trade-audit-logger) |

### Control Interface

| Project | Description | Repository |
| :--- | :--- | :---: |
| **quant-terminal-web** | Web dashboard for monitoring bots, viewing live performance, and triggering emergency stops. | [Repo](https://github.com/juanmmm21/quant-terminal-web) |

---

[Email](mailto:martoscuevasjuan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/juan-martos-cuevas-071019354/)
