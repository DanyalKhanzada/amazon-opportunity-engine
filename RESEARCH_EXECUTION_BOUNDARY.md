# Research → Execution Authority Boundary

## Purpose

The Amazon Opportunity Engine is a research, falsification and underwriting system before it is an execution system.

A promising candidate must not silently create operational authority.

> **Research evidence can justify deeper research. It cannot by itself authorize external business actions.**

This boundary exists to prevent candidate enthusiasm, missing data, or tool availability from turning an unfinished research hypothesis into supplier outreach, procurement, advertising changes, listing changes or capital deployment.

## Default mode: research-only

Until a separate execution workflow is explicitly entered, the system may:

- search and read marketplace, provider, supplier-catalog, patent and public-web evidence;
- generate and compare candidates;
- perform cheap falsification and adversarial review;
- model economics using clearly labeled observed / calculated / estimated / unknown inputs;
- inspect publicly available supplier capabilities and prices;
- analyze packaging, dimensions, FBA fees, logistics, IP and compliance risk;
- maintain internal candidate, evidence, rejection and learning records;
- prepare internal questions or specifications for later diligence.

The system must **not** by default:

- contact suppliers, brands, customers or other external parties;
- send or queue outreach on the user's behalf;
- order samples or inventory;
- negotiate or accept commercial terms;
- create purchase orders or financial commitments;
- alter live Amazon listings, advertising or account settings;
- treat a public supplier price as a verified quote for the intended sellable unit;
- convert research-stage evidence into execution authority.

## Promotion is explicit

External action requires a deliberate transition into a later execution workflow and human authorization for the action being taken.

Candidate quality and action authority are separate concepts:

```text
DISCOVERY / RESEARCH
        ↓
cheap falsification
        ↓
market + customer + economics + risk evidence
        ↓
hard gates / underwriting
        ↓
research verdict / survivor pool
        ↓
explicit execution decision
        ↓
ONLY THEN: supplier contact / samples / procurement / launch actions
```

A GREEN or other strong research verdict may make an execution step reasonable, but it does not silently perform or authorize that step.

## Why this is an operating-layer rule

The deterministic private core governs candidate identity, evidence, gates, underwriting and durable decisions. External side effects occur outside that domain through email, supplier portals, seller accounts, advertising systems and other tools.

Therefore this rule belongs to the operating/orchestration layer rather than to scoring weights or underwriting thresholds.

It has:

- **zero score authority**;
- **zero gate authority**;
- **zero threshold authority**;
- **zero discovery-budget authority**.

Its only purpose is to keep research and execution from being accidentally conflated.

## Failure rule

If the system discovers that it has drifted toward external execution while still operating in research mode:

1. stop the external action;
2. preserve any useful research evidence internally;
3. return to the current research stage;
4. determine whether the drift exposed a missing operating invariant;
5. change scoring/model architecture only if the decision logic itself—not merely orchestration—was actually wrong.

This keeps the engine aggressive about learning without allowing research momentum to become unauthorized execution.
