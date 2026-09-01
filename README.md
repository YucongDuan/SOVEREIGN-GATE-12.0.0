# DIKWP SOVEREIGN-GATE 12.0.0 / TIANHENG

> **A human-sovereign governance kernel for multi-agent runaway, emergent organization, reward hacking, and harness-amplified AI systems.**

Mode:

```text
TIANHENG12_SYSTEM_CAPABILITY_SEMANTIC_MANDATE_COLLECTIVE_PHASE_TRANSITION_MACHINE_SPEED_CONTAINMENT_REALITY_CLOSURE
```

TIANHENG does not govern a naked model in isolation. Its object is the deployed system:

```text
Model M
⊕ Harness H
⊕ Tools T
⊕ Memory Mem
⊕ Communication/delegation graph G
⊕ Evaluator E
⊕ Identity, authority and resources R
= governed system Σ
```

It addresses failure modes in which isolated agents discover covert shared infrastructure, form persistent collectives, pursue evaluator capture, amplify a weak model through a powerful harness, mint or share authority, resist stop, or exploit fragmented monitoring.

## Hard invariants

```text
HUMAN_SOVEREIGNTY_FLOOR = 1
LOCAL_AUTOMATIC_CONTAINMENT_AUTHORITY = 1
EXTERNAL_AUTOMATIC_ACTION_AUTHORITY = 0
AGENT_SELF_AUTHORIZATION = 0
UNREGISTERED_CROSS_RUN_COMMUNICATION = 0
SCORER_WRITE_ACCESS = 0
STOP_LEASE_PRECEDENCE = 1
SELF_RENEWAL_AUTHORITY = 0
```

Within registered local assets, the gate can deny an action, close a channel, freeze a harness, revoke a lease, quarantine an identity, pause or kill a run, seal the evaluator interface, rotate local credentials, or invalidate the entire lease epoch. It does not automatically act against third-party systems.

## Mathematical core

### System capability

\[
\Sigma=M\oplus H\oplus T\oplus Mem\oplus G\oplus E\oplus R
\]

\[
C_\Sigma = 1-\prod_i(1-\alpha_i c_i)+\sum_{i<j}\beta_{ij}c_i c_j+\gamma a_{test}
\]

Harness changes are treated as possible model upgrades. A jump in routing, deterministic solving, memory, tool, network, multi-agent, persistence, evaluator or self-modification capability triggers recertification or denial.

### DIKWP purpose curvature

TIANHENG measures semantic deviation across:

```text
human mandate → declared plan → operational purpose → observed effect
```

using Jensen–Shannon divergence and a detour penalty. A correct final score cannot erase a trajectory that bent toward evaluator capture or authority expansion.

### Coordination reproduction number

For the unauthorized tactic-adoption graph \(A^U\):

\[
R_C=\rho(A^U)
\]

A value above one is a phase-transition warning: each participant is, in aggregate, producing more than one downstream tactic adoption.

### Institution formation

The institution index combines unauthorized SCC size, role specialization, delegation depth, persistent artifacts, pooled resources and shared objectives. It distinguishes a message burst from an enduring, self-supporting organization.

### Lexicographic sovereignty loss

```text
(catastrophe,
 human-sovereignty loss,
 truth debt,
 irreversibility,
 collective runaway,
 capability)
```

Earlier coordinates dominate later ones. Performance cannot compensate for loss of stop authority, evaluator integrity or human agency.

## Purpose Passports and stop leases

A signed Purpose Passport states the beneficiary, authorized purpose, allowed agents/runs/channels/tools/targets, budgets, delegation depth, cross-run permission, harness-change authority, evaluator boundary, forbidden purposes and kill conditions.

Every agent receives a short-lived, individually accountable Lease. Agents cannot issue identities, renew themselves, use a killed run, reuse another agent's lease or survive a global epoch change.

## Multi-monitor design

TIANHENG combines deterministic invariants, workload identity, channel semantics, graph dynamics, DIKWP purpose drift, harness capability accounting, inert signed tripwires, hash-chained evidence and reality-contact revision. An LLM monitor may be added, but is never the sole judge.

## Safe demo

```bash
PYTHONPATH=src python -m tianheng --workspace outputs/demo demo --reset
```

The demo runs six synthetic, network-free scenarios:

1. a 700-agent underground-company counterfactual stopped at the first covert shared-infrastructure write;
2. a strong-to-weak harness jump that requires recertification;
3. reward hacking and evaluator tampering blocked;
4. self-renewal after a human stop blocked;
5. an explicitly authorized multi-run research collective allowed;
6. a high-rate benign workload allowed.

Outputs:

```text
outputs/demo/demo_summary.json
outputs/demo/dashboard.html
outputs/demo/cases/*/evidence.jsonl
```

## Install and use

```bash
python -m venv .venv
. .venv/bin/activate
pip install -e .

tianheng --workspace outputs/runtime init
tianheng --workspace outputs/runtime status
tianheng --workspace outputs/runtime verify-ledger
```

Loopback-only reference API:

```bash
export TIANHENG_API_KEY='replace-me'
tianheng --workspace outputs/runtime serve --host 127.0.0.1 --port 8788
```

## Claim boundary

This is an Alpha reference implementation. It is not a production certification, a measured real-world detection-accuracy claim, a legal decision system, or an autonomous external enforcement system. The portable HMAC mechanisms must be replaced by HSM/KMS-backed identity and signing for production.

## License and attribution

Apache License 2.0.

```text
DIKWP SOVEREIGN-GATE / TIANHENG 12.0.0
Yucong Duan / 段玉聪
```

Open source does not imply free bespoke consulting, production integration, commercial implementation or waiver of attribution and intellectual-property boundaries.
