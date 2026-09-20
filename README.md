# Elias Cherrou

**AI & machine learning engineering student in Stockholm — looking for an LIA placement.**

I build LLM systems and the tooling around them: agents that use tools safely, guardrails that get tested against real attacks, and developer tools that make what a model is doing visible. Most of what I build starts because I wanted the thing to exist.

### 🎯 Available for LIA (internship)

| Period | Dates |
|---|---|
| **LIA 1** | 26 Oct 2026 – 1 Jan 2027 |
| **LIA 2** | 11 Jan – 2 Apr 2027 *(degree project running in parallel)* |

Studying **AI and Machine Learning Engineering** at Teknikhögskolan Stockholm (higher vocational education, HT25–VT27). Based in Stockholm.

---

### What I've built

| Project | What it is |
|---|---|
| **[llm-guardrails](https://github.com/Lullow/llm-guardrails)** | Three layers of prompt-injection defence in front of local LLMs, measured against 22 attacks. All layers together reached 0 % attack success — then I wrote adaptive attacks that got past them anyway, and wrote up why. |
| **[subagent-watch](https://github.com/Lullow/subagent-watch)** | VS Code extension that shows AI subagents while they run. Reads only documented local files, stores nothing sensitive, and the collector has a written security contract. |
| **[personal-dev-assistant](https://github.com/Lullow/personal-dev-assistant)** | A terminal coding assistant with safety-checked file tools, sub-agent coordination and token budgeting. Dockerised. |
| **[multi-agent-hub](https://github.com/Lullow/multi-agent-hub)** | An agent that collaborates over a shared hub while treating every remote message as untrusted input — remote messages can never reach local tools. |
| **[tokeniser](https://github.com/Lullow/tokeniser)** | VS Code extension that makes LLM token and context usage visible. SQLite indexing, atomic writes, permission-checked file handling. |
| **[deadline-bot](https://github.com/Lullow/deadline-bot)** | Discord bot that tracks course deadlines. Running in production on a cloud VM under systemd; 85 tests. Built for my class, and used by it. |

More in [my repositories](https://github.com/Lullow?tab=repositories) — including database design, ETL pipelines and neural networks built up from a single neuron to ResNet-50 transfer learning.

---

### How I work

- **I read the source when the docs are wrong.** In the guardrails project I found that LiteLLM's documented `similarity_check` setting doesn't exist in the code and is silently ignored — which changed the whole design.
- **I write down what I couldn't make work.** Every project has a limitations section. I'd rather state a weakness than have someone find it.
- **I treat input as untrusted by default.** Most of my projects have an explicit threat model, because most of them handle data that something else produced.

### Tech

`Python` `TypeScript` `SQL` · `PyTorch` `pandas` `FastAPI` `Docker` `SQLite` `PostgreSQL` `pytest` · LLM agents, tool use, prompt-injection defence, evaluation suites

### Education

**Teknikhögskolan Stockholm** — AI and Machine Learning Engineering (HVE), HT25–VT27

Applied AI · Machine Learning · Python Frameworks · Databases · DevOps · Python Programming

Graded *Väl Godkänd* (Pass with Distinction) in Applied AI, with a special recognition for contributing course material and building the class's deadline bot.

### Contact

[LinkedIn](https://www.linkedin.com/in/elia-cherrou/) · elias-cherrou@live.se
