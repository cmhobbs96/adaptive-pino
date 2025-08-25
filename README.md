# Adaptive Low-Rank Physics-Informed Neural Operators for Multiscale PDEs

The project investigates **operator learning with low-rank approximations** and **reinforcement learning (RL)-driven adaptivity** to improve the efficiency, accuracy, and stability of Physics-Informed Neural Operators (PINO) applied to **multiscale partial differential equations (PDEs)**.

---

## Project Objectives

### Baseline
- Implement a **vanilla PINO** for canonical PDEs (e.g., 1D Burgers equation, 2D Navier–Stokes).  
- Introduce **low-rank operator approximations** (SVD truncation, Fourier/wavelet bases).  
- Benchmark performance vs. full-rank PINO in terms of:
  - L2 error  
  - Stability/conservation  
  - Runtime and FLOPs  

### Reach
- Integrate a **reinforcement learning controller** (PPO/bandits) to:
  - Adaptively select collocation points (active sampling).  
  - Adjust operator rank or basis dynamically.  
  - Tune PDE constraint weights during training.  
- Evaluate **Pareto tradeoffs** between accuracy and compute.  

### Long-Term Vision
- Develop a **general RL-driven PINO framework** for multi-fidelity scientific simulation.  
- Provide theoretical guarantees of **stability and convergence**.  
- Deploy on **HPC infrastructure** for scientific digital twins in climate, fluid dynamics, and aerospace design.
