# Nissan Pow

🍁 **ML & Systems Engineer** · **Waterloo & McGill alum**

Toronto → Waterloo → Montreal → New York → Seattle → San Francisco

Building at the intersection of **spatial computing & hardware acceleration**, **robotics & embodied AI**, and **high-performance systems**.

Core contributor to [Metaflow](https://github.com/Netflix/metaflow).

![Tokens Burned](https://img.shields.io/badge/tokens%20burned-∞-cc785c?style=flat-square&logo=anthropic&logoColor=white)

## ⚙️ Agent Infrastructure

- 📊 **[agent-insights](https://github.com/npow/agent-insights)** — Persistent dashboard that scores agent coding sessions and auto-applies instruction-file fixes.
- 🔄 **[claude-relay](https://github.com/npow/claude-relay)** — Drop-in OpenAI and Anthropic API proxy server routing through Claude Code.
- 🧩 **[claude-skills](https://github.com/npow/claude-skills)** — Reusable slash-command workflows that make Claude Code reliable on complex multi-step tasks.
- 🔀 **[interchange](https://github.com/npow/interchange)** — Policy-based routing of multi-agent tasks to optimal AI models automatically.
- 🗜️ **[kompact](https://github.com/npow/kompact)** — LLM context compression proxy — 40–70% token savings with zero code changes.
- 🎨 **[oh-my-claude](https://github.com/npow/oh-my-claude)** — Statusline framework for Claude Code with live context, spend, CI, and runtime signals.
- ⚙️ **[rampart](https://github.com/npow/rampart)** — Durable LLM agent runtime with built-in crash recovery, budget enforcement, and permission gates.
- 🧵 **[sagaflow](https://github.com/npow/sagaflow)** — Run long-lived, durable agent workflows that outlive individual sessions.
- 🔁 **[session-sync](https://github.com/npow/session-sync)** — Switch from Claude Code to Codex or any AI coding agent without losing your active session.
- 🔭 **[sessionlog](https://github.com/npow/sessionlog)** — Real-time ingestion and storage to see every tool call, error, and decision your agent made.
- 🐝 **[swarmd](https://github.com/npow/swarmd)** — Mission-enforced Claude agent runner — refuses to stop until success criteria pass, durable across crashes.

## 🛡️ AI Security

- 🔓 **[clawbreaker](https://github.com/npow/clawbreaker)** — Dynamic adversarial sandbox scanner that executes untrusted agent skills before install.
- 🚩 **[ctfbench](https://github.com/npow/ctfbench)** — Automated benchmark evaluating autonomous AI coding agents against capture-the-flag security challenges.
- 🛡️ **[memshield](https://github.com/npow/memshield)** — Stop memory poisoning and state corruption attacks on persistent AI agent memory.
- 🤠 **[outclaw](https://github.com/npow/outclaw)** — Inline content firewall for OpenClaw: secrets, prompt injection, unsafe domains, and tool risks.

## 🛰️ Telemetry & Forensics

- 🎭 **[botc-ai](https://github.com/npow/botc-ai)** — Blood on the Clocktower AI spectator: browser simulation with LLM players, lock-based discussion, and real-time voting.
- 🦞 **[moltbook-analysis](https://github.com/npow/moltbook-analysis)** — Forensic network teardown of Moltbook, an AI-only social network of 41k+ agents. ([Read the report](https://npow.github.io/posts/lobster-tank/))
- ✈️ **[skypulse](https://github.com/npow/skypulse)** — Zero-setup 3D browser globe tracking 6,000+ commercial aircraft in real time.
- 🚢 **[spyglass](https://github.com/npow/spyglass)** — Real-time global maritime traffic map with live AIS tracking and vessel emissions estimation.

## 🌊 Metaflow Ecosystem

### Developer Tools
- 🔬 **[metaflow-dataprofiler](https://github.com/npow/metaflow-dataprofiler)** — Instant EDA reports on every DataFrame in your Metaflow steps — zero code changes.
- 📓 **[metaflow-jupyter](https://github.com/npow/metaflow-jupyter)** — Jupyter-native Metaflow: multi-cell flows, DAG widgets, inline artifacts, and notebook-to-flow export.
- 📜 **[metaflow-logs](https://github.com/npow/metaflow-logs)** — Ship Metaflow task logs to any OpenTelemetry-compatible backend.
- 🔧 **[metaflow-mcp-server](https://github.com/npow/metaflow-mcp-server)** — Inspect runs, logs, and artifacts directly from your AI coding agent.
- 🔔 **[metaflow-notifications](https://github.com/npow/metaflow-notifications)** — Step failure alerts and run lifecycle webhooks for Metaflow pipelines.
- 📊 **[metaflow-observability](https://github.com/npow/metaflow-observability)** — Zero-config OpenTelemetry step metrics (duration, CPU, memory, disk, GPU).
- 🔥 **[metaflow-profiler](https://github.com/npow/metaflow-profiler)** — Interactive flamegraph profiling card for Metaflow steps.
- 📈 **[metaflow-traincard](https://github.com/npow/metaflow-traincard)** — Live loss curves, GPU telemetry, and checkpoints in your Metaflow run card.

### Backends
- 🌐 **[metaflow-akash](https://github.com/npow/metaflow-akash)** — Run Metaflow steps on Akash's decentralized cloud without vendor lock-in.
- 🐟 **[metaflow-bacalhau](https://github.com/npow/metaflow-bacalhau)** — Run Metaflow steps on distributed Bacalhau compute without rewriting your workflow.
- 🏗️ **[metaflow-gha](https://github.com/npow/metaflow-gha)** — Run Metaflow steps on free GitHub Actions VMs with no cloud account needed.
- ⚡ **[metaflow-modal](https://github.com/npow/metaflow-modal)** — Run Metaflow steps on serverless GPUs with zero infrastructure overhead.
- 🔐 **[metaflow-phala](https://github.com/npow/metaflow-phala)** — Run Metaflow steps inside Phala Cloud TEE Confidential VMs with one decorator.
- 🏖️ **[metaflow-sandbox](https://github.com/npow/metaflow-sandbox)** — Millisecond-start Daytona/E2B cloud sandboxes with consistent dependencies.

### Coordination & Services
- 📜 **[metaflow-contracts](https://github.com/npow/metaflow-contracts)** — Catch bad data between Metaflow steps before it corrupts your pipeline.
- 🚦 **[metaflow-coordinator](https://github.com/npow/metaflow-coordinator)** — Coordinate shared services across parallel workers (queues, rate limiters, barriers, Redis, Postgres).
- ✋ **[metaflow-hitl](https://github.com/npow/metaflow-hitl)** — Pause Metaflow pipelines for human review with zero compute cost while waiting.
- 🗄️ **[metaflow-local-service](https://github.com/npow/metaflow-local-service)** — Track Metaflow runs anywhere without a database — starts on demand, stops when idle.
- 🎛️ **[metaflow-optuna](https://github.com/npow/metaflow-optuna)** — Parallel hyperparameter tuning with true adaptive TPE — no sequential bottleneck.
- 🚀 **[metaflow-serve](https://github.com/npow/metaflow-serve)** — Deploy ML models from Metaflow flows with full lineage tracking.
- 🪶 **[metaflow-serverless](https://github.com/npow/metaflow-serverless)** — Serverless Metaflow metadata service on free-tier Postgres with zero setup.

### Orchestrators & Kits
- 🔩 **[metaflow-backend-kit](https://github.com/npow/metaflow-backend-kit)** — Scaffold, validate, and compliance-test Metaflow compute backends.
- 🔷 **[metaflow-dagster](https://github.com/npow/metaflow-dagster)** — Dagster scheduling, observability, and UI for your Metaflow pipelines.
- 🦅 **[metaflow-flyte](https://github.com/npow/metaflow-flyte)** — Schedule and monitor your Metaflow pipelines through Flyte without rewriting them.
- 🌊 **[metaflow-kestra](https://github.com/npow/metaflow-kestra)** — Kestra scheduling, triggers, and UI for your Metaflow pipelines.
- 🧙 **[metaflow-mage](https://github.com/npow/metaflow-mage)** — Mage pipeline orchestration and UI for your Metaflow flows.
- 🧰 **[metaflow-orchestrator-kit](https://github.com/npow/metaflow-orchestrator-kit)** — Build correct Metaflow orchestrators with a compliance test suite and scaffold.
- 🛰️ **[metaflow-prefect](https://github.com/npow/metaflow-prefect)** — Prefect scheduling, deployments, and UI for your Metaflow pipelines.
- ⏱️ **[metaflow-temporal](https://github.com/npow/metaflow-temporal)** — Temporal scheduling, durable workflows, and UI for your Metaflow pipelines.
- 🌪️ **[metaflow-windmill](https://github.com/npow/metaflow-windmill)** — Windmill workflow automation and UI for your Metaflow pipelines.

## ⭐ Awesome Lists

- ⭐ **[awesome-metaflow](https://github.com/npow/awesome-metaflow)** — Every Metaflow extension, compute backend, orchestrator, and resource worth knowing, curated and organized.
- 🚀 **[awesome-tenstorrent](https://github.com/npow/awesome-tenstorrent)** — Curated academic research bibliography, peer-reviewed publications, and systems guide for Tenstorrent hardware, Tensix spatial cores, and TT-Metalium.

## 💡 Product Intelligence

- 📐 **[context-bench](https://github.com/npow/context-bench)** — Benchmark any system that transforms LLM context: compressors, RAG rerankers, and memory managers.
- 🗺️ **[deeprecon](https://github.com/npow/deeprecon)** — Map markets, score white-space opportunities, and generate diligence reports before you build.
- 🧭 **[elicit](https://github.com/npow/elicit)** — Synthesize user interviews to discover exact customer pain points and feature priorities.
- 🔎 **[evidencekit](https://github.com/npow/evidencekit)** — Multi-provider web search fanout across 12+ providers with policy routing, deduplication, and reranking.
- 👻 **[ghostwriter](https://github.com/npow/ghostwriter)** — Autonomous AI content engine with anti-slop quality validation gates.
- 🕵️ **[github-roast](https://github.com/npow/github-roast)** — Detect PR farming and rank OSS contributors for program admissions in minutes.
- 💬 **[morphly](https://github.com/npow/morphly)** — Adapt messages to each recipient's communication style — write once, land differently for everyone.
- 📏 **[skill-bench](https://github.com/npow/skill-bench)** — A/B test Claude Code skills and prompts with statistical rigor.
- 💳 **[stripe-analytics-mcp](https://github.com/npow/stripe-analytics-mcp)** — 30-second morning SaaS health check via MCP (MRR, churn, failed payments, trial risk).
- 🪄 **[summon](https://github.com/npow/summon)** — Scaffold and generate a working full-stack project from a single sentence.
- 📰 **[upshot](https://github.com/npow/upshot)** — Deduplicate, cluster, and prioritize daily newsletters and RSS feeds into one brief.

## 🎲 Board Games

- 🏭 **[brass-birmingham](https://github.com/npow/brass-birmingham)** — Full-fidelity digital adaptation of the top-ranked economic board game.
- 🍔 **[food-chain-magnate](https://github.com/npow/food-chain-magnate)** — Browser adaptation of Splotter's strategy classic with procedural maps.
- 🌌 **[galactic-uprising](https://github.com/npow/galactic-uprising)** — Asymmetric strategy board game (Dominion vs. Liberation) in vanilla JavaScript.
- ⚔️ **[mage-knight](https://github.com/npow/mage-knight)** — Solo deckbuilding conquest game with tactical combat and procedural map generation.
- 🎲 **[too-many-bones](https://github.com/npow/too-many-bones)** — Solo dice-builder RPG adaptation with tactical grid encounters.
- 💍 **[war-of-the-ring](https://github.com/npow/war-of-the-ring)** — Asymmetric epic with hidden Fellowship movement and Shadow AI.
- 🌱 **[worldseed](https://github.com/npow/worldseed)** — AI-generated infinite side-scrolling platformer powered by BytePlus Ark.

## 🛠️ Tools & Systems

- 🏷️ **[airline-codes](https://github.com/npow/airline-codes)** — Lightweight npm dataset for airline IATA/ICAO code lookups.
- 🧱 **[cssbox](https://github.com/npow/cssbox)** — Fast embeddable Rust CSS layout engine for document rendering without a browser.
- 🖼️ **[giphy-mcp-server](https://github.com/npow/giphy-mcp-server)** — Search, trending, and random GIFs as MCP tools for AI coding agents.
- 🔗 **[ibc-explorer](https://github.com/npow/ibc-explorer)** — Trace multi-hop Cosmos IBC transfers, decode denom hashes, and catch stuck packets.
- 💻 **[localbatch](https://github.com/npow/localbatch)** — Test AWS Batch workloads locally without an AWS account.
- 📦 **[nebraska-analysis](https://github.com/npow/nebraska-analysis)** — Find the hidden packages your entire software supply chain depends on.
- 🟠 **[ordisat](https://github.com/npow/ordisat)** — Query Bitcoin addresses, Runes tokens, and Ordinals inscriptions in one unified API.
- 🚔 **[oxicop](https://github.com/npow/oxicop)** — 2–30× faster RuboCop-compatible linter in Rust with native parallelism.
- 📉 **[perpscan](https://github.com/npow/perpscan)** — Cross-chain perpetual DEX analytics — unified positions, liquidations, and funding rates.
- 🔮 **[predictle](https://github.com/npow/predictle)** — Endless Wordle-style game ranking live Manifold prediction markets by probability.
- 🏜️ **[sandrun](https://github.com/npow/sandrun)** — Run code in fast, isolated cloud sandboxes — swap execution providers with zero integration rewrites.

## 🧠 ML Research

- 🏠 **[centris](https://github.com/npow/centris)** — Montreal real estate valuation and price prediction pipeline.
- 📺 **[friends-chatbot](https://github.com/npow/friends-chatbot)** — Generative conversational agent trained on TV dialogue.
- 🧠 **[MemN2N](https://github.com/npow/MemN2N)** — End-to-end Memory Networks in Theano.
- 💡 **[MemNN](https://github.com/npow/MemNN)** — Memory Networks for question answering in Theano.
- 🧬 **[RNN-EM](https://github.com/npow/RNN-EM)** — Recurrent neural networks augmented with external memory structures.
- 🗣️ **[ubottu](https://github.com/npow/ubottu)** — Ubuntu dialogue corpus next-utterance classification.

![GitHub Contribution Graph](https://ghchart.rshah.org/npow)

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/npow)
