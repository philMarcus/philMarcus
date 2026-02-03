# Phil Marcus
**Senior Data Scientist — Simulation, Optimization & Uncertainty Quantification**  
Greater Boston • Open to relocation (US & UK)

[LinkedIn](https://www.linkedin.com/in/phil-marcus/) • [GitHub](https://github.com/philMarcus)

---

## What I do
I build simulation-driven evaluation frameworks to understand complex systems, quantify uncertainty, and make tradeoffs explicit—then clearly communicate actionable results.

Core interests:
- **Monte Carlo simulation** and uncertainty quantification
- **Strategy / policy optimization** in stochastic environments
- **Evaluation design** (benchmarks, metrics, robustness)
- Reproducible analysis artifacts (code + visuals + writeups)

---

### 🧩 Mastermind — Monte Carlo difficulty analysis of game variants
A Java Mastermind simulation + solver used to quantify how difficulty changes across rule variants.

**Highlights**
- **3.7M+ simulated games** across **42** (CodeLength, NumColors) variants
- Difficulty landscape with confidence intervals
- A non-linear **crossover boundary** showing when “add a color” vs “add a slot” increases difficulty more

**Repo:** https://github.com/philMarcus/Mastermind  
**Notebook:** `Mastermind_Analysis.ipynb`

![Mastermind combined heatmap](https://raw.githubusercontent.com/philMarcus/Mastermind/Mastermind_(main)/Mastermind/mastermind_combined_heatmap.png)  
*Difficulty landscape: mean turns to solve across (CodeLength, NumColors), with high-precision uncertainty estimates.*

![Mastermind final comparison](https://raw.githubusercontent.com/philMarcus/Mastermind/Mastermind_(main)/Mastermind/mastermind_final_comparison_plot.png)  
*Crossover result: regimes where increasing NumColors vs CodeLength increases difficulty more, plus confidence in the boundary.*

---

## Toolbox
- **Python:** pandas, NumPy, matplotlib, seaborn, Jupyter
- **Java:** simulation engines + tooling
- **SQL:** DuckDB/Postgres 
- **Workflow:** Git, reproducible pipelines, clear documentation

---

## What I’m working on now
- applying SQL to simulation logs for fast slicing/aggregation
- Packaging projects with “org-ready” artifacts (run scripts, validation checks, short decision memos)

---

## Contact
Best way to reach me: https://www.linkedin.com/in/phil-marcus/
