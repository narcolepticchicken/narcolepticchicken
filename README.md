# Hi — I build legal AI you can actually trust

I'm a practicing technology lawyer and ML engineer. I work on the unglamorous
half of "legal AI": making a model's output **verifiable**, **auditable**, and
**safe to rely on unsupervised** — not just fluent.

The through-line across everything here is **deterministic verifiers and honest
evaluation over vibes.** A legal answer you can't check is a liability, so I
build the checkers.

---

### 🧪 Verifiable legal environments
- **[gdpr-dpa-art28-env](https://github.com/narcolepticchicken/gdpr-dpa-art28-env)** — a deterministic, verifiable reward environment that scores GDPR Article 28(3) Data Processing Agreements clause-by-clause, with evidence spans and adversarial evasion tests. A worked example of RL-with-verifiable-rewards over legal text.

### ⚖️ Legal AI, built with guardrails
- **[counselbridge](https://github.com/narcolepticchicken/counselbridge)** — grounded legal chat with enforced citations, fail-closed attorney-review routing, and a hash-chained audit trail.
- **[LeBlox](https://github.com/narcolepticchicken/LeBlox)** — a privilege-preserving workbench: per-matter isolation, encryption, and DLP that blocks cross-matter leakage.
- **[plainclause](https://github.com/narcolepticchicken/plainclause)** — local-first contract-clause explanations and guarded rewrites, no cloud required.
- **[legal-prompt-router](https://github.com/narcolepticchicken/legal-prompt-router)** — a deterministic router mapping a legal-workflow prompt library to a firm's actual negotiating positions.

### 🤖 Agent & platform infrastructure
- **[leto](https://github.com/narcolepticchicken/leto)** — a local-first, Telegram-first Python agent framework (typed reasoner, delegation, 56 tools), runnable fully keyless.
- **[deep-agent-lab](https://github.com/narcolepticchicken/deep-agent-lab)** — a small, safety-hardened research agent (LangGraph), exposed as both a CLI and an API.
- **[onboard](https://github.com/narcolepticchicken/onboard)** — a wiki compiler for company knowledge (not a RAG chatbot).
- **[highland](https://github.com/narcolepticchicken/highland)** — Mission Control for long-horizon, AI-assisted software builds (Elixir / Phoenix LiveView).
- **[reactor-lite](https://github.com/narcolepticchicken/reactor-lite)** — AI-driven cyber crisis simulations for security & compliance teams.

---

### How I work
- **Honest metrics.** If a number can't be reproduced from the repo, it doesn't go in the README.
- **Deterministic where it counts.** Verifier/regex gates over LLM judgment for anything safety-critical — auditable and reproducible by construction.
- **Abstention over confident-wrong.** The trustworthy primitive is knowing when *not* to answer.
