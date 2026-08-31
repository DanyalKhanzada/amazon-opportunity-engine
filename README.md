<div align="center">

# ⚡ Amazon Opportunity Engine

### An evidence-driven discovery, falsification, underwriting and learning system for finding exceptional Amazon opportunities — repeatedly.

![Status](https://img.shields.io/badge/status-active%20research-2ea44f?style=for-the-badge)
![Core](https://img.shields.io/badge/core-v1.4.15-0969da?style=for-the-badge)
![Underwriting](https://img.shields.io/badge/underwriting-frozen-238636?style=for-the-badge)
![Goal](https://img.shields.io/badge/goal-20%20genuine%20GREENs-238636?style=for-the-badge)
![Method](https://img.shields.io/badge/method-discover%20%3E%20falsify%20%3E%20gate%20%3E%20underwrite-6f42c1?style=for-the-badge)

**Discover broadly. Reject aggressively. Preserve evidence. Underwrite only what survives.**

</div>

---

## 🎯 Mission

Most product-research systems optimize for finding *more candidates*.

This system optimizes for something harder:

> **Finding a small number of unusually strong opportunities while rejecting bad capital deployments as early, cheaply and honestly as possible.**

The operating target is a pool of **20 products with genuine GREEN status**. The GREEN standard is not lowered to fill the pool.

The engine is deliberately designed to separate:

- discovery from underwriting;
- evidence from narrative;
- estimates from observations;
- current truth from historical truth;
- research authority from execution authority.

---

## 🧠 Current operating architecture

```text
Opportunity universe
        ↓
Territory + scenario coverage
        ↓
Independent discovery generators
        ↓
Candidate hypothesis
        ↓
Cheap falsification
        ↓
Candidate identity / market resolution
        ↓
Candidate Lock
        ↓
Audit
        ↓
Hard gates
        ↓
Evidence-backed underwriting
        ↓
Decision snapshot
        ↓
Append-only decision history
        ↓
Outcome calibration / learning
```

A promising product is a hypothesis until it survives the governed chain.

A high weighted score cannot rescue a fatal weakness. Missing critical evidence does not become optimism. Historical evidence cannot be silently rewritten after the fact.

---

## 🔭 Discovery engine

Discovery does not rely on one Black Box-style filter or one keyword list.

The engine searches through multiple market situations, including:

- emerging demand;
- incumbent disruption / share migration;
- broken-product customer pain;
- vacated demand;
- premiumization and trade-up;
- supply-side or dimensional unlocks;
- behavior and category migration;
- weak market ownership;
- portfolio / ecosystem wedges.

Those scenarios are explored through independent generators such as customer complaints, young-entrant success, keyword anomalies, supplier innovation, dimensional engineering, replacement friction, external-to-Amazon signals, temporal change, and blind independent exploration.

A protected exploration reserve prevents the engine from searching only where it has already found winners.

### Governing discovery question

> **What changed materially, unexpectedly and persistently — and is that change economically actionable for a new entrant?**

Discovery evidence can create a candidate. It cannot grant underwriting points or bypass normal diligence.

---

## 🧭 Market resolution before market conclusions

A keyword is not automatically a market.

Broad search terms can mix multiple product forms, use cases, pack sizes, materials and customer jobs. The engine therefore treats search results as discovery evidence until the actual competitive market system is resolved.

```text
keyword / ASIN signal
        ↓
product-form resolution
        ↓
JTBD / customer-use resolution
        ↓
parent / variation normalization
        ↓
coherent competitive market
```

This prevents unrelated products from being aggregated into fake demand or fake competition.

---

## 🛡️ Anti-bias design

The engine assumes it can become biased by its own success.

It therefore includes:

- a protected independent-exploration floor;
- append-only candidate-stage history;
- false-negative audits on rejected opportunities;
- blind-random reject sampling;
- explicit scenario-gap observations when the current taxonomy may be incomplete;
- seller-identity normalization before declaring incumbent displacement;
- zero scoring authority for discovery provenance;
- explicit separation between UNKNOWN and negative evidence.

A scenario gap may be observed repeatedly and recommended for controlled testing, but it cannot silently rewrite the canonical scenario registry.

---

## 🔒 Candidate and evidence custody

Modern governed runs preserve the identity of the opportunity being researched.

The system binds together, at progressively deeper stages:

- hunt / marketplace provenance;
- candidate identity and market wedge;
- candidate lock;
- audit context and replayed audit result;
- hard-gate evidence and authority;
- evidence-backed underwriting assessments;
- exact underwriting model reference;
- decision snapshot;
- append-only persisted decision package.

The goal is not merely to produce a recommendation. The goal is to be able to answer later:

> **What exactly did we believe, based on what evidence, under which model, at which point in time?**

---

## 💰 Economics are normalized before they become decision inputs

The engine treats economic input semantics as part of decision integrity.

Examples of hardened boundaries include:

- Amazon fee inputs must be normalized before contribution economics use them;
- supplier unit labels such as `piece`, `set` or `pair` do not determine sellable-unit economics;
- supplier-trade-unit to retail-sellable-unit relationships must be explicit before a factory quote can be normalized;
- a normalized supplier factory quote is **not** automatically landed COGS;
- estimates, calculated values, observed values and unknowns must remain distinguishable.

The engine deliberately avoids inventing universal landed-cost or dimensional-weight rules before repeated real-world evidence justifies them.

---

## 🧾 Decision history and replayability

Current state is a derived view over history rather than the only truth retained.

Modern governed decisions preserve:

- the recommendation at the time;
- the final decision;
- assumptions and blockers;
- forecasts;
- model identity;
- evidence-backed dimension assessments;
- supersession history;
- later actual outcomes without rewriting the original forecast.

This creates the foundation for prediction-versus-outcome calibration once enough real operating data exists.

---

## 🚦Research is not execution

The engine now has an explicit operating boundary between research and outside-world actions.

During research it may search, compare, falsify, inspect supplier catalogs, analyze patents, model economics and preserve evidence.

It does **not** automatically gain authority to contact suppliers, order samples, commit capital, change live listings or modify advertising simply because a candidate looks promising.

External execution requires a separate deliberate transition and human authorization.

See [`RESEARCH_EXECUTION_BOUNDARY.md`](RESEARCH_EXECUTION_BOUNDARY.md).

---

## 🔄 Reality-driven engineering loop

The engine is not improved by continuously adding features.

```text
live hunt / real failure
        ↓
attack the conclusion
        ↓
does existing architecture already handle it?
   YES ─────────────→ do not change core
    NO
        ↓
isolate smallest violated invariant
        ↓
red / adversarial test
        ↓
minimal implementation
        ↓
attack the implementation itself
        ↓
full regression
        ↓
versioned release
        ↓
freeze
        ↓
return to live hunts
```

The preferred outcome of many reviews is **NO CHANGE**. Avoiding an unnecessary rule is itself a successful engineering decision.

---

## 📈 Architecture evolution

The project has moved through several distinct maturity layers:

| Era | Primary improvement |
|---|---|
| **v1.0** | Frozen underwriting architecture, hard gates, economics and disciplined product selection baseline |
| **v1.1** | Discovery-quality hardening: temporal change, workarounds, false-negative auditing, independent exploration, incumbent displacement |
| **v1.2** | Discovery observability: Hunt Manifest, territories, scenarios, generators, coverage, memory and frontier |
| **v1.3** | The engine can detect gaps in its own discovery taxonomy without self-modifying it |
| **v1.4** | Institutional custody: decision history, deterministic run coordination, identity binding, model replay, evidence-backed dimensions, persistence, temporal integrity, hard-gate authority and supplier-unit evidence custody |

The underwriting scoring model has intentionally remained frozen while surrounding evidence, governance, replayability and failure resistance have improved.

---

## 🧪 Engineering principles

| Principle | Meaning |
|---|---|
| **Gates before scores** | Fatal weaknesses cannot be averaged away. |
| **Evidence over narrative** | Observed, calculated, estimated and unknown facts stay distinct. |
| **Market before keyword** | One query or one ASIN does not define the competitive system. |
| **Identity before underwriting** | Candidate and market wedge cannot silently change mid-run. |
| **Post-ad economics** | Attractive gross margin alone is insufficient. |
| **Capital efficiency matters** | Profit is evaluated against capital consumed. |
| **Replayability matters** | Important decisions should be reproducible from their stored inputs. |
| **Version everything material** | Meaningful model or architecture changes receive explicit change control. |
| **Learn from rejects** | A dead product can reveal a live customer problem, failure mode or adjacency. |
| **Memory before adaptation** | Observe recurring patterns before changing allocation or scoring policy. |
| **Research ≠ execution** | Evidence may justify more research without authorizing outside-world actions. |

---

## 🧩 Public showcase + private core

```text
PUBLIC — amazon-opportunity-engine
├── architecture
├── philosophy
├── sanitized progress
├── operating boundaries
└── non-proprietary learnings

PRIVATE — amazon-opportunity-engine-core
├── exact scoring / gate mechanics
├── evidence and custody schemas
├── discovery implementation
├── model registry
├── deterministic run coordination
├── decision persistence
├── regression tests + CI
└── proprietary research mechanics
```

The public repository explains **what the system is and why it is designed this way**. The private core preserves the exact implementation and competitive logic.

---

## 🚦What GREEN means

GREEN is not “interesting.”

GREEN means the opportunity has survived the required structural, economic, competitive, operational, legal/compliance, differentiation, confidence and capital-efficiency tests at the current diligence stage.

<div align="center">

## **20 genuine GREEN products → then compare the survivors.**

No quota filling. No threshold drift. No winner by storytelling.

</div>

---

## 🧭 Broader operating system

- **Private engine core** → deterministic logic, governance, tests and decision custody
- **Research records** → evidence, candidate history, rejects and unresolved questions
- **Data providers / web research** → current external evidence
- **Public repository** → sanitized architecture and progress
- **Human judgment** → final capital allocation and execution authorization

The long-term objective is not an engine that is never wrong.

It is an engine that makes its assumptions visible, preserves its mistakes, learns from outcomes and becomes **progressively harder to fool**.

---

<div align="center">

### Build a system that gets harder to fool every time reality disagrees with it.

**Amazon Opportunity Engine** · Evidence-driven discovery · Adversarial underwriting · Institutional memory

</div>
