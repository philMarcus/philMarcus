## Featured projects

### ⚔️ battleMage — strategy optimization in a stochastic, rule-driven system
A Java simulation environment with an optimization pipeline for tuning combat strategies under uncertainty.

**Highlights**
- High-throughput simulation sweeps across **4M+ parameter configurations**
- Each logged result aggregates outcomes from **10²–10⁵ simulated battles** for stable comparisons
- Clear evidence of optimization dynamics and performance ceilings

**Repo:** https://github.com/philMarcus/battleMage_Optimization  
**Notebook:** `01_Optimizing_battleMage.ipynb`

![battleMage optimization trajectory](https://raw.githubusercontent.com/philMarcus/battleMage_Optimization/main/images/optimization_trajectory.png)  
*Optimization trajectory across phases: broad exploration → focused refinement → exploitation.*

![battleMage phase distributions](https://raw.githubusercontent.com/philMarcus/battleMage_Optimization/main/images/battleMage_phase_distributions_2x2.png)  
*Outcome distributions by phase: search mass shifts toward higher-performing strategies as tuning converges.*

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
