# Phil Marcus
**Senior Data Scientist — Simulation, Optimization & Uncertainty Quantification | AI Agent Systems**  
Greater Boston | Open to relocation (US & UK)

[LinkedIn](https://www.linkedin.com/in/phil-marcus/) · philipgmarcus@gmail.com

---

## What I Do
I build simulations, evaluation frameworks, and measurement systems to reason carefully about uncertainty — then communicate actionable results. My work spans Monte Carlo methods, stochastic optimization, and autonomous agent systems, always focused on making tradeoffs explicit and conclusions defensible.

---
## Featured Projects

### Autonomous Agent Observatory — Autonomy + Analog Home
An autonomous AI agent system designed to test whether self-modifying feedback loops produce coherent emergent behavior or collapse into drift.

**Highlights**
- Dual-process architecture (conscious deliberation + subconscious daemon) with multi-model LLM orchestration (6 providers)
- 27+ self-modifiable runtime controls the agent can read, adjust, or have locked by the operator
- Telemetry pipeline (JSONL → Parquet → DuckDB) with a Streamlit monitoring dashboard
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
- **Python:** pandas, NumPy, matplotlib, Jupyter, FastAPI, Streamlit
- **Java:** simulation engines + tooling
- **SQL:** DuckDB, Postgres
- **Data:** Parquet, JSONL, ETL pipelines
- **Infra:** Fly.io, Vercel, Neon Postgres, Git
- **LLM Integration:** Gemini, Claude, GPT, Mistral, HuggingFace (local)

---

## Contact
philipgmarcus@gmail.com · [LinkedIn](https://www.linkedin.com/in/phil-marcus/)
