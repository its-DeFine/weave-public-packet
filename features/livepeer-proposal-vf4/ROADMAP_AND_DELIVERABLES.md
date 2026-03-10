# Livepeer Proposal VF4 Roadmap And Deliverables

This roadmap turns VF4 into concrete deliverables with required evidence.

It covers two linked outputs across the same four-month window:

1. demand validation and public release work on the Embody proving lane
2. extraction of WEAVE as a reusable public workload path for Livepeer

Principle: a milestone is complete when there is a visible output and matching evidence.

Months are relative to grant kickoff.

Related docs:

- [Technical architecture](TECHNICAL_ARCHITECTURE.md)
- [Financial plan and governance](FINANCIAL_PLAN_AND_GOVERNANCE.md)
- [Wallet governance packet](../livepeer-grant-wallet-governance-v0/2026-03-07-contract-ledgers-packet.md)

## Milestone Summary

| Month | Focus | Primary output |
|---|---|---|
| Month 1 | Expose and instrument the first lane | Baseline operating surface plus Embody as the first working WEAVE user case |
| Month 2 | Tighten from real usage | Improved consumer and rollout path plus support for the next workload lane |
| Month 3 | Public release and evidence | Public operator onboarding plus the first public usage and fee evidence |
| Month 4 | Lightweight steering and handover | First public steering cycle plus governed budget handover and handover packet |

## Month 1: Expose And Instrument The First Lane

### Goal

Make the existing Embody lane publicly legible, release it as the first working WEAVE user case, and put the first measurement and lifecycle surfaces around it.

### Outputs

1. a published baseline operating surface for the Embody lane and its measurement path
2. Embody released as the first working WEAVE user case on the team-operated path
3. the first operator and consumer incentive rules and cohort launch
4. the bounded lifecycle tooling used to carry research, engineering, maintenance, and QA on the proving lane

### Evidence

1. the documented baseline operating surface, current consumer path, and measurement path
2. release notes or equivalent walkthrough for the Embody user case
3. published incentive rules, cohort notes, and early participation records
4. sample public stage artifacts across research, engineering, and QA

### Acceptance Criteria

1. the Embody user case is usable through the documented consumer path and existing operator lane
2. the measurement path for usage, operators, distribution, and fees is publicly legible
3. the lifecycle tooling can carry at least one bounded stage sequence with public artifacts and review points
4. incentive rules are published before incentive spend begins

## Month 2: Tighten From Real Usage

### Goal

Use what the first lane teaches to improve the consumer path, broaden the operator release path, and support the next workload lane through the same review surface.

### Outputs

1. an improved consumer interface and `SKILL.md` distribution path shaped by live usage on the Embody lane
2. an adapted orchestrator rollout path beyond Unreal-specific assumptions
3. support for the next workload lane through the same public release and review path

### Evidence

1. updated consumer-facing docs or interface artifacts showing what changed from live usage
2. rollout notes or implementation references for the broadened release path
3. proof material for the next workload lane, including scope, artifacts, or release-preparation output

### Acceptance Criteria

1. the supported consumer path is improved from real usage on the first lane
2. the operator rollout path is documented for both the Embody lane and the next supported workload lane
3. the supported WEAVE review surface is clear enough to open external hardening work responsibly

## Month 3: Public Release And Evidence

### Goal

Open the WEAVE path to public orchestrator onboarding and publish the first public usage, adoption, and fee evidence for the live lanes.

### Outputs

1. operator onboarding docs, release notes, and compatibility notes for the WEAVE path
2. public orchestrator onboarding for the WEAVE path
3. the first public usage, adoption, and fee evidence for the live lanes

### Evidence

1. published onboarding docs, release notes, and compatibility notes
2. public onboarding attempt reports, operator cohort notes, or equivalent release evidence
3. public usage, adoption, and fee evidence for the live lanes

### Acceptance Criteria

1. at least one non-core operator can follow the public onboarding path, or the blocker is written down explicitly
2. the public docs are sufficient to explain the supported WEAVE release path without private operator knowledge
3. the public evidence is sufficient for a reviewer to judge whether demand is appearing on the live lanes

## Month 4: Lightweight Steering And Handover

### Goal

Run the first lightweight public steering cycle for a next workload opportunity and move the grant-supported programs into the governed treasury path with clear operating documentation.

### Outputs

1. the first public steering cycle for a next workload opportunity through a lightweight review channel
2. governed handover of the network incentives, agent security bounties, and consumer hackathon budgets
3. handover docs covering roles, runbooks, and remaining centralized dependencies
4. a residual-risk, next-step, and deferred-scope list grounded in the grant evidence

### Evidence

1. public steering records, review notes, or equivalent steering evidence
2. treasury transaction references for governed handover actions
3. published handover and runbook docs
4. a final milestone report comparing planned and completed outputs

### Acceptance Criteria

1. treasury operations follow the documented multisig governance path throughout the grant
2. the governed handover is backed by transaction evidence and operating docs
3. the steering cycle and final report make it clear what should be generalized next and what remains outside the current scope

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
