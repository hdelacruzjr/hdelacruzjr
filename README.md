## Horacio De La Cruz Jr.

I build measurement into machine learning systems. Retrieval and LLM evaluation, applied
modeling, and sensor analytics at the edge — with the eval harness published alongside the
model, because a result nobody can re-run isn't a result.

Doctoral research at Capitol Technology University on adversarial and multi-agent
retrieval-augmented generation. M.S. Data Science, MBA Technology Management, four
peer-reviewed publications. Miami, FL — open to fully remote.

### What I work on

**Applied ML** — model selection under real decision costs, calibration, and the gap between
the metric a model wins on and the choice it's actually making.

**Retrieval and LLM evaluation** — cross-lingual retrieval, adversarial robustness, and
harnesses that survive contact with a corpus somebody tampered with.

**Sensor and edge analytics** — anomaly detection under hard bandwidth and power budgets, on
telemetry from a lab I built and run.

### Research index

| Question | Approach | Finding | Repo |
|---|---|---|---|
| Does the model with the better score make the cheaper decisions? | Cost-sensitive threshold selection swept across cost ratios 1–1000 on AI4I 2020, against a no-information control | **No.** The better-PR-AUC model is the costlier choice for C = 30–1000 on raw probabilities — and Platt scaling removes the flip entirely. Calibration matters more than model choice. | [predictive-maintenance-eval](https://github.com/hdelacruzjr/predictive-maintenance-eval) |

<!-- Add a row as each study lands. Never before the number exists.

| How little can you transmit before anomaly detection stops working? | Detection F1 and latency across sampling, quantization and aggregation budgets | | [lorawan-sensing-budget](https://github.com/hdelacruzjr/lorawan-sensing-budget) |
| What do six open-source scanners actually catch on Python? | Precision, recall and overlap on a labeled corpus; the baseline config follows | | [python-security-baseline](https://github.com/hdelacruzjr/python-security-baseline) |
| Does cross-lingual retrieval survive an adversarial corpus? | Poisoning-rate degradation curves on public multilingual benchmarks | | [bilingual-rag-eval](https://github.com/hdelacruzjr/bilingual-rag-eval) |

-->

### How these repos are structured

Each one opens with a question, reports a measured result with its uncertainty, and ends with
what would change the conclusion. Results tables are written by the pipeline from the data and
regenerated in CI — never pasted in by hand — so the numbers in a README are the numbers the
code produced.

Engineering rigor is the mechanism here, not the headline. It's what makes the science
checkable.

### Currently

Building out the portfolio: a bandwidth/accuracy frontier for LoRaWAN sensing, and a measured
comparison of what open-source security scanners actually catch. The bilingual retrieval
evaluation harness is the long one and ties to the doctoral work.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/hdlc) · [veritas-data.io](https://veritas-data.io) · hdelacruzjr@outlook.com
