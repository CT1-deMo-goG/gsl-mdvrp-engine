# GSL Engine: MDVRP Module 🚀

A proprietary deterministic routing framework designed for the Multi-Depot Vehicle Routing Problem (MDVRP).

**Core Module:** `GSL_MDVRP_MASTER_V28`

This repository serves as a performance and benchmark portfolio for the MDVRP architecture, showcasing large-scale routing experiments, deterministic feasibility validation, and mobile-edge execution behavior.

⚠️ **Disclaimer:**  
Source code is proprietary and not publicly available. This repository is intended for research visibility, benchmark documentation, and industrial collaboration discussions.

---

# ⚙️ Execution Environment

Unlike many traditional Operations Research studies evaluated on server-class infrastructure, this framework was tested under constrained mobile-edge hardware conditions to study deterministic routing behavior and computational scalability.

* **Platform:** Android (Mobile Edge)
* **Runtime:** Python via Pydroid 3
* **CPU:** Snapdragon Architecture
* **Constraint Handling:** Deterministic feasibility validation

---

# 📊 Benchmark & Performance Portfolio

The `GSL_MDVRP_MASTER_V28` framework was evaluated under a **Zero-Tuning Policy**, meaning a unified execution configuration was applied across multiple problem scales without instance-specific parameter tuning.

The evaluation portfolio includes:

## 1. Extreme-Scale Stress Experiment

A custom large-scale MDVRP scenario containing:

- **10,000 customer nodes**
- **100 depots**

was processed in approximately:

- **8.9 seconds**
  under mobile-edge execution conditions.

## 2. Cordeau Benchmark Evaluation

The framework was evaluated on standard academic MDVRP benchmark instances from the Cordeau p-series and pr-series datasets.

Observed results demonstrated:

- deterministic feasibility validation
- stable routing execution behavior
- sub-second runtime behavior across many benchmark instances under the tested environment

---

🎥 **Proof of Execution:**  
[Watch the 10,000-Node Stress Test on YouTube](https://youtu.be/qPmY3S6LM7I)

📄 **Benchmark Summary:**  
See [RESULT_SUMMARY.md](./Benchmark_MDVRP/MDVRP_RESULT_SUMMARY.md)

📄 **Technical Notes & Architecture Overview:**  
See [TECHNICAL_REPORT.md](./Docs/Technical_Report.md)

---

# 🌍 Research Direction

The GSL framework explores deterministic routing execution across multiple deployment scales:

- mobile-edge execution environments
- large-scale routing benchmarks
- reproducible feasibility-oriented routing
- scalable logistics optimization architectures

The long-term direction includes:
- mobile-to-server deployment scaling
- real-world logistics integration
- deterministic dispatch infrastructure
- industrial routing optimization systems

---

# GSL-Solver Platform

## Deterministic Routing Platform

Access the routing platform here:

🔗 https://gsl-solver.com

---

# Professional Contact

**Independent Researcher:**  
Chonmapoohm Thamsuwan (CTSuwan)

📧 ctsuwan@proton.me

---

# Services & Collaboration

Open to collaboration in areas including:

- Logistics-as-a-Service (LaaS)
- Deterministic routing systems
- Large-scale routing experiments
- Constraint-based logistics optimization
- Routing benchmark analysis
