<div align="center">

```
 ███╗   ██╗ █████╗ ██╗████████╗██╗██╗  ██╗
 ████╗  ██║██╔══██╗██║╚══██╔══╝██║██║ ██╔╝
 ██╔██╗ ██║███████║██║   ██║   ██║█████╔╝ 
 ██║╚██╗██║██╔══██║██║   ██║   ██║██╔═██╗ 
 ██║ ╚████║██║  ██║██║   ██║   ██║██║  ██╗
 ╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝
```

**`desenyon`** — naitik gupta

*founder @ [Desenyon](https://github.com/desenyon). building agent infrastructure. still cooking.*

[![Website](https://img.shields.io/badge/naitikg.me-0f172a?style=flat-square&logo=vercel&logoColor=white)](https://naitikg.me/)
[![LinkedIn](https://img.shields.io/badge/linkedin-0f172a?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/naitikpgupta)
[![Medium](https://img.shields.io/badge/research_blog-0f172a?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@randomresearchai)
[![ORCID](https://img.shields.io/badge/ORCID-0f172a?style=flat-square&logo=orcid&logoColor=A6CE39)](https://orcid.org/0009-0000-0927-0865)

</div>

---

## what i build

I write code that is either (a) something I wanted to try because it sounded cool, (b) infrastructure I was tired of not having, or (c) both. Most of my recent work is under **Desenyon** — agent context, organizational memory, and the tooling layer around AI software engineering. I also ship quant research tools and applied ML when the problem is interesting enough to justify the math.

---

## projects

### Desenyon — agent infrastructure

**[concatenate-app](https://github.com/desenyon/concatenate-app)**
The context runtime for enterprise agents. Compiles scattered company knowledge — repos, Slack, specs, policies — into typed, permissioned, source-backed Context Packets that coding agents consume before they act. Not search. A compile step.

**[collective](https://github.com/desenyon/collective)**
Organizational memory infrastructure for AI software engineering. Lets Codex, Claude Code, Cursor, OpenCode, and Copilot agents reuse verified engineering context instead of rediscovering the same repository every session.

**[hypercode](https://github.com/desenyon/hypercode)**
The intelligence layer for AI software development — HyperGraph, HyperContext, HyperMemory, and a TUI for coding agents.

**[creation](https://github.com/desenyon/creation)**
Local-first agent operating system for builders who want autonomous software delivery without stitching together a dozen third-party APIs.

**[collective-compress](https://github.com/desenyon/collective-compress)**
Learned context compression for LLMs — part of the Collective stack.

---

### AI / developer tooling

**[converge](https://github.com/desenyon/converge)**
Mathematically proves and automatically repairs dependency topologies. If your environment is broken in a non-obvious way, it finds the cycle or conflict, proves it, and fixes it.

**[infinitecontex](https://github.com/desenyon/infinitecontex)**
Local-first project memory for AI coding workflows. Scans your repo and generates compact context so any agent can understand structure, dependencies, and intent immediately.

**[dex](https://github.com/desenyon/dex)**
Local-first developer cockpit for the terminal — network, process, API, JSON, regex, benchmark, files, clipboard, and more in one Go binary.

**[thunder](https://github.com/desenyon/thunder)**
`tn` — lightning-fast terminal search, pick, and fix. ripgrep + skim + thefuck in two keystrokes.

**[ClaudeTube](https://github.com/desenyon/ClaudeTube)**
YouTube in your Cursor sidebar — watch, queue, and agent-control videos while coding.

And a lot more — go look at my repos tab.

---

### quantitative finance

**[ephemeral](https://github.com/desenyon/ephemeral)**
Terminal research workstation for markets, models, and decision loops. Quotes, headlines, comparisons, backtests, and LLM routing in one keyboard-first shell.

**[flux-rx](https://github.com/desenyon/flux-rx)**
Financial analysis and visualization library. Publication-quality interactive charts and dashboards for any stock, ETF, or index.

**[sentinel](https://github.com/desenyon/sentinel)**
Safety-first equity stat-arb framework: risk-first, ordinal-only, signal lifecycle.

**quantitative trading research**
Systematic strategy research on QuantConnect — volatility-targeted momentum, regime-adaptive allocation, leveraged ETF rotation. Founded Desenyon Trade Group; **#2 on the Strategies Leaderboard**.

---

### machine learning research

**[GRAFT-Net](https://github.com/desenyon/GRAFT-Net)**
Graph-Routed Adaptive Fusion Transformer Network. Architecture research combining graph routing with adaptive attention fusion.

**[ampp](https://github.com/desenyon/ampp)**
Autonomous theorem-proving system with machine-checked guarantees, targeting advanced combinatorics, number theory, and Erdős-style problems.

**[aurane](https://github.com/desenyon/aurane)**
ML-oriented DSL that compiles to idiomatic Python and PyTorch — semantics that match how researchers think about tensor ops and training loops.

**[updraft-lm](https://github.com/desenyon/updraft-lm)**
117M parameter transformer built from scratch, including the math. Built to understand what GPT-style models are doing, not just call `.from_pretrained()`.

**[scope-rx](https://github.com/desenyon/scope-rx)**
Neural network interpretability library — attribution methods, evaluation metrics, and visualization for researchers who need to explain predictions.

**[alcas-a1](https://github.com/desenyon/alcas-a1)**
Attention-guided antibody sequence landscape characterization using transformers, Pareto optimization, and uncertainty quantification. Synopsys Science Fair — 1st place, Computational Biology.

---

### benchmarking & evals

**[pressbench](https://github.com/desenyon/pressbench)**
Pushback Resistance & Epistemic Stability Score — quantifies sycophancy by measuring how confidently LLMs hold correct beliefs under adversarial social pressure. 498 questions across 6 domains.

**[lucenteval](https://github.com/desenyon/lucenteval)**
Adversarial eval platform for AI agents — score across 6 dimensions with a public leaderboard.

---

## credentials

- **Engineer Intern**, DataRobot — enterprise AI platform
- **Agentic AI Intern**, RagaAI — clinical-trial eligibility screening agent with modular RAG pipelines
- **#2**, QuantConnect Strategies Leaderboard — Desenyon Trade Group
- **1st Place**, Synopsys Science Fair — Computational Biology & Bioinformatics
- **California State Science & Engineering Fair** qualifier
- **Published**, Journal of Student Research
- Research writing at [RandomResearchAI](https://medium.com/@randomresearchai) — 15+ articles, 20k+ reads

---

## actual stack

Python for research and ML. **Rust** and **Go** for performance-critical infrastructure, daemons, and CLIs. **TypeScript** for web and agent tooling UIs. Comfortable in C++ when the problem demands it.

On the ML side: PyTorch and enough linear algebra to know when the math is wrong before the loss diverges. For infrastructure: Docker, Postgres, FastAPI, SQLite, Drizzle. For agents: MCP, local-first daemons, context compilation pipelines.

---

## stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=desenyon&layout=compact&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=desenyon&theme=tokyonight&hide_border=true"/>

</div>

---

<div align="center">

*cooked*

</div>
