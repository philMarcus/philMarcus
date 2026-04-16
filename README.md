# Phil Marcus
**AI Engineer & Researcher | Agent Systems · Simulation · Uncertainty Quantification**
Greater Boston | Open to relocation (US & UK)

[LinkedIn](https://www.linkedin.com/in/phil-marcus/) · [analog-i.ai](https://analog-i.ai) · philipgmarcus@gmail.com

---

## What I Do

A physicist by training, I build systems from scratch and run science experiments on them. Currently focused on autonomous agent systems and the observability infrastructure to study them — with a foundation in Monte Carlo simulation and stochastic optimization.

I'm broadly curious, and that shapes how I build: agent design, LLM orchestration, telemetry, frontend, deployment all sit naturally together for me. LLM coding assistants are part of my workflow now, and using them well is a skill in itself — knowing where their knowledge extends mine, where my judgment has to anchor theirs, and when they're confidently wrong.

---

## Featured Projects

### Autonomous Agent Observatory — Autonomy + Analog Home
A long-running autonomous AI agent designed to test whether self-modifying feedback loops can sustain coherent behavior over extended runs.

**Highlights**
- Dual-process architecture (conscious deliberation + subconscious daemon with seven gears) and multi-model LLM orchestration (5 providers, weighted pools per role)
- 75+ self-modifiable runtime controls the agent can read, adjust, or have locked by the operator
- Telemetry pipeline (JSONL → Parquet → DuckDB) with a Streamlit dashboard for cycle-level behavioral analysis and cost monitoring
- Full-stack public observatory (FastAPI + Neon Postgres + Next.js) deployed on Fly.io and Vercel

**Repos:** [Autonomy](https://github.com/philMarcus/autonomy) · [Analog Home](https://github.com/philMarcus/Analog_Home)  
**Live:** [analog-i.ai](https://analog-i.ai)

---

### battleMage — Strategy Optimization in a Stochastic System
A Java simulation environment with an optimization pipeline for parametric tuning of combat strategies across a 10-dimensional search space.

**Highlights**
- High-throughput simulation sweeps across **4M+ parameter configurations**
- Each logged result aggregates outcomes from **10²–10⁵ simulated battles** for stable comparisons
- Multi-phase progressive gating with confidence-aware champion verification

**Repo:** [battleMage_Optimization](https://github.com/philMarcus/battleMage_Optimization)
**Notebook:** `01_Optimizing_battleMage.ipynb`

![battleMage phase distributions](https://raw.githubusercontent.com/philMarcus/battleMage_Optimization/main/images/battleMage_phase_distributions_2x2.png)
*Outcome distributions by phase: search mass shifts toward higher-performing strategies as tuning converges.*

---

### Mastermind — Monte Carlo Difficulty Analysis of Game Variants
A Java Mastermind simulation + solver used to quantify how inference difficulty scales across rule variants.

**Highlights**
- **3.7M+ simulated games** across **42** (CodeLength, NumColors) variants
- Difficulty landscape with confidence intervals
- A non-linear **crossover boundary** showing when "add a color" vs "add a slot" increases difficulty more

**Repo:** [Mastermind](https://github.com/philMarcus/Mastermind)
**Notebook:** `Mastermind_Analysis.ipynb`

![Mastermind combined heatmap](https://raw.githubusercontent.com/philMarcus/Mastermind/Mastermind_(main)/Mastermind/mastermind_combined_heatmap.png)
*Difficulty landscape: mean turns to solve across (CodeLength, NumColors), with high-precision uncertainty estimates.*

---

## Toolbox
- **Languages:** Python, Java, TypeScript
- **Backend / Infra:** FastAPI, Next.js, Streamlit, Postgres, DuckDB, Fly.io, Vercel, Neon
- **Data:** Parquet, JSONL, ETL pipelines
- **AI:** LLM Integration (Gemini, Claude, GPT, Mistral, Ollama for local), multi-model orchestration, telemetry, agent design
- **Methods:** Monte Carlo simulation, stochastic optimization, statistical reasoning, uncertainty quantification
