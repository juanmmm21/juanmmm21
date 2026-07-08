# Juan Martos Cuevas


---

## iOS Apps

| App | Description | Repository |
| :--- | :--- | :---: |
| **Convall** | Cloud-based file converter built with Flutter. | [Repo](https://github.com/juanmmm21/Convall) |
| **Tickertape** | Currency converter for iOS with a retro-inspired UI. | [Repo](https://github.com/juanmmm21/Tickertape) |
| **Latent** | Privacy-focused, local-first note-taking app using on-device AI (CoreML) for embeddings and automatic note linking. | [Repo](https://github.com/juanmmm21/Latent) |
| **Wond** | White noise iOS App. | [Repo](https://github.com/juanmmm21/Wond) |

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

## AI Projects

| Project | Description | Repository |
| :--- | :--- | :---: |
| **local-llm-studio** | A native macOS studio for local LLMs with private file context and web search integration. | [Repo](https://github.com/juanmmm21/local-llm-studio) |
| **the-autonomous-enclave** | A local multi-agent simulation where LLM-driven digital citizens perceive, reason, and trade in a synthetic economy under computational scarcity, observed and steered in real time via a pixel-art web dashboard. | [Repo](https://github.com/juanmmm21/the-autonomous-enclave)

---

## Beacon Search Engine

### Ingestion

| Project | Description | Repository |
| :--- | :--- | :---: |
| **web-crawler-scheduler** | An async, polite web crawler with priority frontier, robots.txt compliance, and outbound link graph extraction. | [Repo](https://github.com/juanmmm21/web-crawler-scheduler) |
| **html-content-extractor** | A boilerplate-removal pipeline that extracts clean main content, titles, and metadata from raw crawled HTML. | [Repo](https://github.com/juanmmm21/html-content-extractor) |

### Indexing

| Project | Description | Repository |
| :--- | :--- | :---: |
| **inverted-index-builder** | An inverted index builder implementing tokenization, positional postings, and document frequency from scratch. | [Repo](https://github.com/juanmmm21/inverted-index-builder) |
| **index-compression-codec** | A postings-list compression codec implementing delta encoding, varint, and bitpacking for scalable inverted indexes. | [Repo](https://github.com/juanmmm21/index-compression-codec) |

### Ranking and Relevance

| Project | Description | Repository |
| :--- | :--- | :---: |
| **bm25-ranking-engine** | A from-scratch implementation of the BM25 ranking algorithm for lexical relevance scoring over an inverted index. | [Repo](https://github.com/juanmmm21/bm25-ranking-engine) |
| **pagerank-link-analysis** | An iterative PageRank implementation computing page authority from a crawled link graph using sparse matrix operations. | [Repo](https://github.com/juanmmm21/pagerank-link-analysis) |
| **learning-to-rank-reranker** | A learning-to-rank reranker combining BM25, PageRank, and auxiliary features via gradient-boosted trees. | [Repo](https://github.com/juanmmm21/learning-to-rank-reranker) |

### Query Serving

| Project | Description | Repository |
| :--- | :--- | :---: |
| **query-parser-autocomplete** | A query parser with operator support, spellcheck, and prefix/n-gram based autocomplete suggestions. | [Repo](https://github.com/juanmmm21/query-parser-autocomplete) |
| **distributed-index-sharding** | A sharded inverted index with distributed query fan-out and ranked result merging across nodes. | [Repo](https://github.com/juanmmm21/distributed-index-sharding) |

### Flagship Application

| Project | Description | Repository |
| :--- | :--- | :---: |
| **beacon-search-console** | A full search engine console (FastAPI + React) assembling crawling, indexing, ranking, and reranking into a working product over a real corpus. | [Repo](https://github.com/juanmmm21/beacon-search-console) |

---

## Strata Database Engine

### Storage and Persistence

| Project | Description | Repository |
| :--- | :--- | :---: |
| **bplus-tree-storage-engine** | Disk-backed B+Tree storage engine with buffer pool management and page-level indexing, built from scratch. | [Repo](https://github.com/juanmmm21/bplus-tree-storage-engine) |
| **lsm-tree-engine** | Log-Structured Merge Tree storage engine with memtable flushing, immutable SSTables, and background compaction. | [Repo](https://github.com/juanmmm21/lsm-tree-engine) |
| **write-ahead-log-recovery** | Binary write-ahead log with checkpointing and redo/undo crash recovery for pluggable storage engines. | [Repo](https://github.com/juanmmm21/write-ahead-log-recovery) |

### Transactions and Concurrency

| Project | Description | Repository |
| :--- | :--- | :---: |
| **mvcc-transaction-manager** | From-scratch MVCC transaction manager implementing snapshot isolation and the standard SQL isolation levels. | [Repo](https://github.com/juanmmm21/mvcc-transaction-manager) |
| **lock-manager-deadlock-detector** | Fine-grained two-phase locking manager with wait-for graph cycle detection for deadlock resolution. | [Repo](https://github.com/juanmmm21/lock-manager-deadlock-detector) |

### Query Engine

| Project | Description | Repository |
| :--- | :--- | :---: |
| **sql-query-parser** | Hand-written SQL lexer and parser producing a typed AST for a documented SQL subset. | [Repo](https://github.com/juanmmm21/sql-query-parser) |
| **cost-based-query-optimizer** | Cost-based query optimizer turning a SQL AST into an efficient physical execution plan with join reordering. | [Repo](https://github.com/juanmmm21/cost-based-query-optimizer) |
| **vectorized-execution-engine** | Vectorized, batch-oriented query execution engine with NumPy-accelerated relational operators. | [Repo](https://github.com/juanmmm21/vectorized-execution-engine) |

### Distribution and High Availability

| Project | Description | Repository |
| :--- | :--- | :---: |
| **raft-replication-log** | From-scratch Raft consensus implementation for leader election and replicated log commitment. | [Repo](https://github.com/juanmmm21/raft-replication-log) |
| **distributed-query-router** | Sharding and query routing layer that fans out queries across replicated nodes and merges partial results. | [Repo](https://github.com/juanmmm21/distributed-query-router) |

### Flagship Application

| Project | Description | Repository |
| :--- | :--- | :---: |
| **nanosql** | Embeddable SQL engine with CLI/REPL and a Python driver, assembling from-scratch storage, transaction, query, and consensus engines. | [Repo](https://github.com/juanmmm21/nanosql) |

[Email](mailto:martoscuevasjuan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/juan-martos-cuevas-071019354/)
