Agent go BRrrrrrrrrrrr ........

### Pinned Projects

**[northstar](https://github.com/sidmanale643/northstar)** `TypeScript` 
Observability, debugging, and evaluation platform for AI agents. Python SDK auto-instruments OpenAI and Anthropic calls, capturing request messages, tool calls, token usage, USD cost, latency, and exceptions without changing application control flow. Data flows through a background worker to a Supabase Edge Function and into private Postgres tables with Row Level Security. Includes a versioned prompt template system, a LiteLLM-backed LLM service wrapper, and a full eval framework with deterministic graders and LLM judges. Dashboard is a separate Next.js app for visualizing traces, runs, and scores.

**[terminus-cli](https://github.com/sidmanale643/terminus-cli)** `Python`
AI-powered development companion that lives in your terminal. Multi-agent coordinator spawns specialized background workers (explorer, implementer, verifier, summarizer) to handle parallel tasks. Scans your entire codebase for context-aware suggestions and executes natural language tasks — reading, editing, creating, and refactoring files with precision. Built with a React/Ink terminal UI (with a classic Rich fallback), session memory via SQLite, automatic context compaction, and a skills system loaded from `.skills/` directories. Supports Groq, OpenRouter, and Gemini models with optional Langfuse observability and Daytona sandboxing.

**[rewind-view](https://github.com/sidmanale643/rewind-view)** `TypeScript`
Standalone Node.js CLI and web UI for indexing and browsing AI assistant sessions from Claude, Codex, OpenCode, and Antigravity. Auto-discovers sessions from their default locations, indexes them into a local SQLite database with FTS5 full-text search, and serves a browser-based UI for reviewing transcripts. CLI supports regex grep with context lines, provider-filtered search, session stats, and idempotent re-indexing via content hashes. Zero-config — just `npx rewind-view` and it indexes everything, opens the browser, and stays running. Data lives in `~/.rewind/data/` and persists across sessions.

**[bloom](https://github.com/sidmanale643/bloom-vault)** `Python`
Agent-run Obsidian knowledge vault following Andrej Karpathy's LLM wiki pattern. Drop raw material — YouTube videos, arXiv papers, web articles, PDFs, screenshots, pasted notes — into `inbox/` and an AI agent (Codex or Claude Code) turns it into durable source notes, concept pages, people profiles, and cited query reports. A deliberate 2-source rule prevents thin summaries from becoming concept pages; ideas only graduate to the wiki when they appear across multiple independent sources. Maintains a keyword glossary, research threads, connection graph, and health dashboard. Keeps raw sources separate from synthesized concepts so the derived layer becomes a searchable thinking surface.

**[shell-mind](https://github.com/sidmanale643/shell-mind)** `Python`
AI-powered CLI that translates plain English into precise shell commands. Covers Docker, Kubernetes, Git, AWS CLI, Terraform, and more — with explanations and safety checks baked in. Interactive mode asks follow-up questions when commands need more context, while one-shot mode generates and optionally auto-executes commands directly. An agent mode enables autonomous multi-step DevOps workflows with web search integration for documentation lookups. Built on Groq for fast inference with an optional Tavily-powered web search for unfamiliar tools.

**[file-sense](https://github.com/sidmanale643/file-sense)** `TypeScript`
Hybrid search engine combining BM25 keyword matching with semantic vector search for local document retrieval. Searches through PDFs, Word documents, and text files using reciprocal rank fusion to blend exact keyword matches with meaning-aware results. Features real-time incremental indexing as documents change, hardware-adaptive modes (eco/balanced/performance) that automatically adjust to your system's capabilities, and a modern React frontend with smooth animations. All processing happens locally — no cloud required. Built with FastAPI, sentence-transformers, FAISS, and Elasticsearch under the hood.

**[stash](https://github.com/sidmanale643/stash)** `TypeScript`
Spotlight-inspired bookmark manager with a keyboard-first search interface. `Cmd+K` opens a fuzzy search powered by Fuse.js across titles, URLs, descriptions, and tags with weighted scoring. Links are automatically categorized by domain rules (40+ patterns) into a hierarchical category tree, and organized into custom collections with nested support. Features Supabase cloud sync with offline-first localStorage fallback, automatic metadata extraction with preview images via Peekalink, batch operations, dark mode, and Three.js-powered background animations. Built with React 19, TypeScript, Vite 7, and Tailwind CSS v4.

