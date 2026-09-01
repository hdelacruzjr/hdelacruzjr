# Horacio De La Cruz Jr. 

**Data scientist — I find out whether a model actually works, before it costs money.**

Teams ship models that win on a metric nobody chose deliberately. I build the evaluation that
shows what a model is really doing, publish it alongside the model, and make it re-runnable —
because a result nobody can reproduce isn't a result.

Miami, FL · open to fully remote · Python · AWS · retrieval and LLM evaluation · edge/IoT analytics

---

## Problems I get called for

### "Our model looks great offline and disappoints in production."

The metric you tuned and the decision you're actually making are usually two different things.
I re-score candidate models against the real cost of being wrong.

**Measured:** on public machine-failure data, the model with the better PR-AUC turned out to be
the *more expensive* choice across a wide range of cost ratios — and simply calibrating it erased
the difference entirely. Picking a better model mattered less than calibrating the one already in
hand.

→ **[predictive-maintenance-eval](https://github.com/hdelacruzjr/predictive-maintenance-eval)**

### "We shipped a RAG assistant and can't tell when it's wrong — or when someone's fooled it."

Retrieval quality is set by whoever wrote the documents, which makes the corpus an attack
surface. I build harnesses that measure answer quality and adversarial robustness in the same
run, so degradation shows up before a user finds it.

→ *Doctoral research at Capitol Technology University on adversarial and multi-agent RAG.
Public harness in progress.*

### "We're paying to move telemetry we don't need."

At the edge, bandwidth and power are the binding constraints — not accuracy. I map how much
accuracy survives at a fraction of the payload, so the radio budget becomes a design choice
instead of a surprise.

→ *In progress, on telemetry from a lab I built and run.*

### "We can't staff a security team, but we need to know our dependencies are safe."

→ **[python-security-baseline](https://github.com/hdelacruzjr/python-security-baseline)** — a
measured comparison of what open-source scanners actually catch.

---

## Background

PhD candidate in AI at Capitol Technology University, researching adversarial and multi-agent
retrieval-augmented generation. M.S. Data Science, MBA in Technology Management, four
peer-reviewed publications. Native Spanish speaker — which is why the retrieval work is
cross-lingual rather than English-only.

## How to read these repos

Each one opens with a question, reports a measured result with its uncertainty, and ends with
what would change the conclusion. Results tables are written by the pipeline from the data and
regenerated in CI — never pasted in by hand — so the numbers in a README are the numbers the
code produced.

Engineering rigor is the mechanism here, not the headline. It's what makes the science
checkable.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/hdlc) · [veritas-data.io](https://veritas-data.io) · hdelacruzjr@outlook.com
