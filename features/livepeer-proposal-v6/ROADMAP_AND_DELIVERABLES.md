# Livepeer Proposal v6 Roadmap And Deliverables

This roadmap turns v6 into concrete deliverables with required evidence.

It advances in three stages: first, deploy Embody as the inaugural workload on WEAVE; second, extend WEAVE to host daydream/scope; third, generalize WEAVE beyond both to support any realtime application, establishing it as a true open-source public good for the Livepeer ecosystem.

The perpetual financial packets are foundational to this progression. **All three launch alongside the Embody workload in Month 1**, ensuring that workload facilitator and consumer incentives are active from the start and that orchestrator expenses are covered from day one.

The roadmap is split across two tracks: **DeFine** (strategy, control plane, WEAVE engineering, governance/runtime delivery) and **Dane** (embodied avatar workload engineering across Unreal Engine and non-Unreal runtime paths). Each monthly tranche is released independently via 3/5 multisig upon confirmation of that month's criteria. A delay or gap in one track does not block the other.

Principle: a milestone is complete when there is a visible output and matching evidence.

Months are relative to grant kickoff.

Related docs:

- [Technical architecture](TECHNICAL_ARCHITECTURE.md)
- [Financial plan and governance](FINANCIAL_PLAN_AND_GOVERNANCE.md)
- [Wallet governance packet](../livepeer-grant-wallet-governance-v0/2026-03-07-contract-ledgers-packet.md)

## Milestone Summary

| Month | Focus | Primary output |
|---|---|---|
| Month 1 | Embody workload, lifecycle automation & incentives launch | First working WEAVE workload live via `SKILL.md`, all three incentive packets deployed |
| Month 2 | Daydream/scope workload path | WEAVE adapted for daydream/scope, first community hackathon workload supported |
| Month 3 | Generalized path & alternative avatar pipeline | Custom-lane workloads on any framework, public orchestrator onboarding |
| Month 4 | Governance and handover | Public governance discussion, incentive operating model documented, handover complete |

---

## Month 1 — Embody Workload, Lifecycle Automation & Incentives Launch

### DeFine

**Deliverables**

* Establish the first bounded lifecycle-agent runtime.
* Automate research, engineering, maintenance, and QA flows on the Embody (non game-dependent) proving lane.
* Release Embody as the first working WEAVE workload, accessible via `SKILL.md` and processing sessions on at least one active orchestrator.
* Deploy all three perpetual incentive packets (Workload Facilitator Hackathon, App Developer, and Orchestrator).

**Success Criteria**

* Lifecycle agent runtime operational and processing intents end-to-end on the Embody lane.
* Embody workload live and accessible via `SKILL.md`, processing sessions on at least one active orchestrator.
* All three incentive packets deployed and accepting participants.
* At least 3 orchestrators enrolled in the WEAVE lane.

### Dane

**Deliverables**

* Automate the Embody/Unreal Engine workload engineering pipeline through DeFine's agent runtime: plugin automation, adding and removing code and features, and game packaging — covering ≥80% of the engineering workflow end-to-end.

**Success Criteria**

* Agent runtime can execute Unreal Engine engineering tasks end-to-end (plugin add/remove, code changes, game packaging) with ≥80% workflow coverage.

---

## Month 2 — Daydream/Scope Workload Path

### DeFine

**Deliverables**

* Adapt WEAVE end to end to accept daydream/scope workloads.
* Bring the orchestrator rollout path online for daydream/scope workloads.
* Support the first new community workload generated from the Month 1 Hackathon.

**Success Criteria**

* WEAVE adapted end to end for daydream/scope workloads.
* Orchestrator rollout path operational for daydream/scope workloads.
* First community hackathon workload supported end-to-end.

### Dane

**Deliverables**

* Deliver a functional prototype of the alternative (non-Unreal Engine) embodied avatar workload demonstrating core session flow.

**Success Criteria**

* Alternative avatar workload prototype operational and demonstrating end-to-end session handling.

---

## Month 3 — Generalized Path & Alternative Avatar Pipeline

### DeFine

**Deliverables**

* Expand WEAVE from scope and daydream to support custom-lane workloads built on any framework or technology stack, including those outside the Embody and daydream/scope ecosystem.
* Package Dane's alternative embodied avatar workload into WEAVE.
* Open WEAVE to public orchestrator onboarding.
* Publish the supported workflow for releasing and maintaining additional workloads through WEAVE.

**Success Criteria**

* WEAVE custom lane operational and accepting at least one workload built on a framework outside Embody and daydream/scope.
* Dane's alternative workload packaged and accessible through WEAVE.
* At least one external orchestrator onboarded through the public path.
* Supported workflow for releasing additional workloads documented and tested.

### Dane

**Deliverables**

* Deliver the alternative (non-Unreal Engine) avatar pipeline, fully operational and documented, ready for DeFine to integrate and automate.
* Deploy the ability to add and edit new avatars and game environments in both the Unreal Engine and the alternative avatar pipeline.

**Success Criteria**

* Alternative avatar pipeline operational, documented, and handed off to DeFine for WEAVE integration.
* Avatar and environment creation and editing operational in both pipelines, with at least one new avatar or environment demonstrably added through the system on each pipeline.

---

## Month 4 — Governance and Handover

### DeFine

**Deliverables**

* Facilitate a public governance discussion with multisig participants and the community on how the incentive packets and lifecycle-agent runtime should be managed post-grant.
* Strategize and document the operating model for the three perpetual incentive packets going forward — how they will run, who will manage them, and what community input shapes their parameters. This decision passes through the community.
* Document the agreed governance path: multisig participants may elect to transition to a decentralized on-chain layer, continue multisig management until a decentralized solution is ready, or confirm another path agreed upon by the group.
* Resolve all pending bugs submitted against WEAVE during the grant period.
* Publish handover documentation and a residual-risk list regardless of the governance decision.

**Success Criteria**

* Governance discussion held and outcome documented publicly.
* Incentive operating model documented and ratified by community input.
* One of the following governance paths confirmed and recorded: (a) decentralized governance contracts deployed and management transitioned, or (b) a clear continuation plan agreed upon by multisig participants with an explicit path toward eventual decentralization.
* All flagged WEAVE bugs resolved or, where blocked by external dependency, documented with root cause and mitigation plan.
* Handover documentation and residual-risk list published.

### Dane

**Deliverables**

* Resolve all bugs flagged across both pipelines during the grant period (Months 1–3).

**Success Criteria**

* All flagged bugs resolved or, where resolution is blocked by external dependency, documented with root cause and mitigation plan.

---

## Review Standard

1. Higher-risk treasury automation remains outside v1.
2. Public release means a supported path with public docs and evidence.
3. Governance handover means documented budget handover backed by transaction references.
4. Each milestone is judged by visible artifacts, not by intention alone.

## Suggested Proof Artifacts

These are the kinds of artifacts that keep the roadmap honest:

1. repo tags or release notes
2. skill or interface version diffs
3. public milestone reports
4. dashboard snapshots or metrics exports
5. transaction hashes and role/address tables
6. blocker packets when a milestone slips
