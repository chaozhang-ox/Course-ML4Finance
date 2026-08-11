# 💹 Machine Learning for Finance (PhD) — Fall 2026

This repository contains materials for the PhD-level course **Machine Learning for Finance**. The course studies modern machine-learning methods for financial prediction and decision-making, with applications to empirical asset pricing, market microstructure, portfolio construction, graph learning, reinforcement learning, generative models, large language models, and responsible AI.

---

## 🧭 Course Structure

- **13 lectures**
- **6 student paper presentations**
- Presentation weeks include approximately:
  - 2 hours of instructor lecture
  - 30 minutes of student presentation
  - 10–15 minutes of instructor-led discussion
- **One formal homework:** Asset Pricing
  - Released after **Lecture 4**
  - Due after **Lecture 10**
- **Lecture 12:** Industry guest lecture / practitioner perspectives
- **Lecture 13:** Final research presentations

Student papers are generally presented one lecture after the relevant methodology has been introduced.

---

## 📁 Course Materials

- **Fall 2026:** [`docs/lectures_Fall2026/`](docs/lectures_Fall2026/)
- **Spring 2026 archive:** [`docs/lectures_Spring2026/`](docs/lectures_Spring2026/)
- **Spring 2025 archive:** [`docs/lectures_Spring2025/`](docs/lectures_Spring2025/)

Fall 2026 lecture files will be added progressively during the semester.

---

## 🗓️ Fall 2026 Schedule

| Lecture | Main Topic | Student Presentation / Other |
|---|---|---|
| **Lec 1** | **Introduction to Financial Machine Learning** — overview, information sets, functional forms, and practical challenges in financial prediction | — |
| **Lec 2** | **Empirical Asset Pricing I** — data, experimental design, linear and penalized models, and dimension reduction | — |
| **Lec 3** | **Empirical Asset Pricing II** — trees, ensembles, neural networks, nonlinear models, and alternative data / representation learning | — |
| **Lec 4** | **High-Frequency Prediction** — limit order books, sampling, order flow, universality, cross-impact, and spatio-temporal modeling | **P1: Nonlinear / Representation Learning in Asset Pricing**; Asset Pricing HW released |
| **Lec 5** | **Optimal Portfolios** — plug-in vs integrated estimation, covariance estimation, max-Sharpe regression, and transaction costs | **P2: High-Frequency / Microstructure ML** |
| **Lec 6** | **Graph Machine Learning for Finance** — graph representations, GNNs, financial networks, cross-asset dependence, and covariance / volatility applications | **P3: Portfolio Construction / Decision-Focused ML** |
| **Lec 7** | **Reinforcement Learning in Finance** — RL basics, optimal execution, market making, and sequential decision-making | **P4: Graph ML for Asset Pricing** |
| **Lec 8** | **Generative AI for Finance** — GANs, VAEs, diffusion models, synthetic backtesting, Tail-GAN / MARS, and pitfalls | — |
| **Lec 9** | **Large Language Models for Finance** — sentiment, financial text, report generation, QA / chatbots, reasoning, applications, and challenges | **P5: Generative Finance** |
| **Lec 10** | **Interpretability & Ethics / Responsible ML** — LIME / SHAP, clustering, t-SNE, bias / fairness, and compliance | **P6: LLMs / Foundation Models in Finance**; Asset Pricing HW due after class |
| **Lec 11** | **Advanced Topics** — transfer learning, federated learning, microstructure / statistical arbitrage, backtesting pipelines, and selected advanced topics | — |
| **Lec 12** | **Industry Guest Lecture / Practitioner Perspectives** | Guest speaker discussion |
| **Lec 13** | **Final Research Presentations** | Student final project presentations |

---

## 📚 Student Paper Presentations

### P1 — Nonlinear / Representation Learning in Asset Pricing

Gu, S., Kelly, B., & Xiu, D. (2021). *Autoencoder Asset Pricing Models*. **Journal of Econometrics**.

### P2 — High-Frequency / Microstructure Machine Learning

Kolm, P. N., Turiel, J., & Westray, N. (2023). *Deep Order Flow Imbalance: Extracting Alpha at Multiple Horizons from the Limit Order Book*. **Mathematical Finance**.

### P3 — Portfolio Construction / Decision-Focused Machine Learning

Wang, Z., Gao, J., Harvey, C. R., Liu, Y., & Tao, S. (2026). *Machine Learning Meets Markowitz*. **NBER Working Paper**.

### P4 — Graph Machine Learning for Asset Pricing

Capponi, A., Sidaoui, B., & Zou, Y. (2025/2026). *Graph Machine Learning for Asset Pricing: Traversing the Supply Chain*. **Working paper**.

### P5 — Generative Finance

Huang, X., Chen, Y., & Qiao, X. (2024). *Generative Learning for Financial Time Series with Irregular and Scale-Invariant Patterns*. **ICLR 2024**.

### P6 — Large Language Models in Finance

Lopez-Lira, A., & Tang, Y. (2026). *Can ChatGPT Forecast Stock Price Movements? Return Predictability and Large Language Models*. **Journal of Financial Economics**.

---

## 🎤 Presentation Format

Each group has approximately **30 minutes** for its presentation, followed by **10–15 minutes** of instructor-led discussion.

Suggested presentation structure:

1. **5 min** — Financial question and motivation
2. **5–7 min** — Data and empirical setup
3. **8–10 min** — Core methodology
4. **5 min** — Main empirical results
5. **5 min** — Critique and possible extensions

Students are not expected to teach the full methodology from scratch. The relevant foundations are covered in the preceding lecture; presentations should focus on understanding, evaluating, and extending the paper.

---

## 🧪 Asset Pricing Homework

The course retains one formal homework, released after Lecture 4 and due after Lecture 10. It covers a complete empirical workflow:

- data preparation,
- model estimation,
- validation,
- out-of-sample prediction, and
- economic evaluation.

The extended submission window is designed to keep the workload manageable alongside paper presentations and the final research project.

---

## 🧠 Recommended Background

- Finance or economics
- Machine learning and applied statistics
- Python programming

---

## 🙏 Acknowledgments

My sincere thanks to **Bryan Kelly**, **Renyuan Xu**, and the many researchers who generously shared slides and teaching materials that informed parts of this course. Their scholarship and openness have improved the clarity and rigor of the lectures.

---

## 📖 References and Suggested Reading

- *Financial Machine Learning* — **Kelly & Xiu (2023)**
- *Advances in Financial Machine Learning* — **López de Prado (2018)**
- *Recent Advances in RL in Finance* — **Hambly, Xu & Yang (2023)**
- *The Elements of Financial Econometrics* — **Fan & Yao (2017)**
- *The Elements of Statistical Learning* — **Hastie, Tibshirani & Friedman (2017)**
