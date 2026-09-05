# Sidhant

**AI Engineer**

[Twitter](https://twitter.com/sidmanale643) ·
[LinkedIn](https://linkedin.com/in/sidhantmanale) ·
[GitHub](https://github.com/sidmanale643) ·
[Email](mailto:sidmanale643@gmail.com)

---

## Stack

|                     | Technologies                                                                                            |
| ------------------- | ------------------------------------------------------------------------------------------------------- |
| **Languages**       | `Python` · `TypeScript` · `SQL` · `Bash`                                                                |
| **AI / ML**         | `PyTorch` · `CUDA` · `Transformers` · `Hugging Face` · `LangChain` · `LangGraph` · `LlamaIndex` · `MCP` |
| **Backend & Data**  | `FastAPI` · `Pydantic` · `SQLite` · `PostgreSQL` · `Redis` · `LanceDB`                                  |
| **Developer Tools** | `Docker` · `Kubernetes` · `GCP` · `Git` · `GitHub` · `Supabase` · `Langfuse`                            |

---

## Working On

* **Inference engineering** — LLM serving, KV caching, batching, GPU memory management, and runtime performance.
* **AI agents** — Stateful coding agents, subagents, tool execution, orchestration, and self-improving harnesses.
* **Memory** — Local-first semantic memory, knowledge graphs, hybrid retrieval, and memory decay.
* **Observability & evals** — Tracing, datasets, evaluators, regression testing, and CI/CD gates for AI systems.

---

## Projects

### [Helios](https://github.com/sidmanale643/helios)

Lightweight LLM inference engine built from scratch in PyTorch.

Implements Qwen3 with grouped-query attention, RoPE, RMSNorm, SwiGLU, Hugging Face weight loading, and autoregressive decoding. Includes KV and prefix caching, shared GPU-memory budgeting, Paged Attention, Flash Attention, `torch.compile`, continuous batching, and benchmarks for TTFT, inter-token latency, throughput, and cache hit rates.

### [Ares](https://github.com/sidmanale643/Ares)

Coding harness built around a persistent IPython workspace.

Uses a stateful `repl_py` tool for repository inspection, file manipulation, shell execution, and iterative development. Includes process-isolated subagents, progressive skill loading, persistent session history, and a trajectory-driven self-improvement system that updates prompts, skills, and subagent specifications across runs.

### [Terminus CLI](https://github.com/sidmanale643/terminus-cli)

AI coding agent with an autonomous tool-calling loop.

Supports repo-aware file operations, shell execution, web search, sandboxing, model routing, automatic context compaction, persistent SQLite sessions, reusable skills, and project-level instructions. Mission Control coordinates Scout, Worker, and Verifier agents with dependency-aware execution, structured evidence, and lifecycle persistence.

### [Atlas](https://github.com/sidmanale643/Atlas)

Local-first semantic memory framework for AI agents.

Converts conversations into atomic memories and persists validated entities, relationships, and temporal context as a SQLite knowledge graph. Uses hybrid BM25 + cosine retrieval over local embeddings, with reranking based on recency, access reinforcement, and an exponential-decay fade mechanism.

Includes an interactive Three.js 3D brain mapping memories across 11 regions and exposes the core through FastAPI, CLI workers, and MCP tools.

### [Evalon](https://github.com/sidmanale643/evalon)

Local, terminal-first observability and evaluation platform for Python agents.

Records traces, nested spans, events, metrics, token usage, latency, errors, and cost estimates in SQLite. Supports versioned datasets, deterministic and custom-Python evaluators, LLM-as-judge evaluation, baselines, regression comparisons, concurrent evaluation runs, and CI/CD gates.

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sidmanale643&label=Profile%20Views&color=blue&style=flat-square" alt="Profile views" />
</p>
