<div align="center">

# Sairam S

**Differential Privacy · ML Robustness · Research**

Final-year CS (AI&ML) @ PES University · Research Intern @ [WSAI, IIT Madras](https://wsai.iitm.ac.in/) with [Prof. Krishna](https://krishnap25.github.io/)

[![Email](https://img.shields.io/badge/email-sairam.sundararaman2005%40gmail.com-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:sairam.sundararaman2005@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-sairam--s-000000?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sairam-s-22062027s/)
[![Scholar](https://img.shields.io/badge/scholar-sairam--s-000000?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=FFQdp-YAAAAJ)

</div>

<br>

### About

I work on the theoretical and empirical edges of ML: privacy guarantees for transformer models, and failure modes of optimization/quantization methods. I prefer questions where the analysis constrains the answer rather than the other way around.

<br>

### Current focus

- Differentially private mechanisms for transformer LLMs — sensitivity analysis, Gaussian mechanism calibration, zCDP composition. Preprint in preparation.

<br>

### Selected work

**[bit-collapse-geometry](https://github.com/sairam-sundararaman/bit-collapse-geometry)** — Diagnosed a geometric failure mode in Int8 post-training quantization (loss-basin narrowing, eigenvalue spikes) via a custom Hessian spectrum visualizer; showed SAM restores stability beyond the FP32 baseline.

**[sam-optimizer](https://github.com/sairam-sundararaman/sam-optimizer)** — Clean-room reimplementation of Sharpness-Aware Minimization from the paper; reproduced reported accuracy and identified an unaccounted-for interaction between SAM's perturbation objective and weight decay.

**[loss-landscape-calculus](https://github.com/sairam-sundararaman/loss-landscape-calculus)** — NumPy Hessian-geometry engine for visualizing 2D loss landscapes and diagnosing SGD oscillation in high-curvature regions.

**[micrograd](https://github.com/sairam-sundararaman/micrograd)** — Reverse-mode autodiff engine from scratch, verified against PyTorch to <1e-6.

<br>

### Publication

**The Final-Stage Bottleneck: A Systematic Dissection of the R-Learner for Network Causal Inference**
Sairam S, Sara G, Shivam S — *TMLR, 2026*
[paper](https://arxiv.org/abs/2511.13018) · [code](https://github.com/sairam-sundararaman/final-stage-bottleneck) · [openreview](https://openreview.net/forum?id=QIE0FVSn0p)

<br>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sairam-sundararaman&theme=github-dark-blue&hide_border=true&background=00000000" width="450" alt="GitHub commit streak" />

</div>
