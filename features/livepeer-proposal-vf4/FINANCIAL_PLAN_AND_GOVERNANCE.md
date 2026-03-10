# Livepeer Proposal VF4 Financial Plan And Governance

This document explains the financial shape of VF4 in plain language. It sits between the short forum post and the deeper [wallet governance packet](../livepeer-grant-wallet-governance-v0/2026-03-07-contract-ledgers-packet.md).

Related docs:

- [Technical architecture](TECHNICAL_ARCHITECTURE.md)
- [Roadmap and deliverables](ROADMAP_AND_DELIVERABLES.md)
- [Wallet governance packet](../livepeer-grant-wallet-governance-v0/2026-03-07-contract-ledgers-packet.md)

## Financial Goal

The financial goal is simple: keep the forum ask legible, keep the treasury path reviewable, and tie each spend lane to visible outputs.

This document sits alongside the wallet governance packet. It explains:

1. what the five budget packages are for
2. how each package is managed during the four-month grant
3. how those packages map to the roadmap
4. which treasury facts are already locked
5. how progress is reported during the grant

## Budget Summary

The public appendix keeps the budget in USD terms.

| Package | Amount (USD) | Why it exists |
|---|---:|---|
| Team compensation | 40,000 | Covers core delivery work across demand validation on the Embody lane, WEAVE delivery, and handover work during the four-month window. |
| Network incentives | 30,000 | Supports the operator/testing cohort and early workload-participation incentives needed to prove the WEAVE path with real network use. |
| Operational costs | 10,000 | Covers infrastructure, runtime, measurement, and support costs for the proving workload during the grant window. |
| Agent security bounties | 10,000 | Funds external review and hardening incentives once the supported WEAVE surface is clear enough to test responsibly. |
| Consumer hackathon | 10,000 | Funds public-consumer adoption incentives and hackathon support for the first public workload lanes. |
| Total | 100,000 | |

## How Each Package Is Managed

The five packages are simple spendable grant budgets. They are not staking programs, compounding pools, or automated treasury strategies.

| Package | Operating rule | Spend starts when | Evidence and reporting | Handover position |
|---|---|---|---|---|
| Team compensation | Fixed disbursement over the four-month delivery window. | Month 1 kickoff. | Team payout references plus milestone outputs tied to the roadmap. | Any remaining balance stays visible at package level and follows the grant handover policy at the end of the period. |
| Network incentives | Spendable program budget for operator incentives, workload-participation incentives, and release-cohort support. | The first operator and consumer incentive rules are published in Month 1. | Incentive rules, recipient criteria, cohort notes, payout references, and usage-facing program notes. | Remaining balance can be handed to the governed system in Month 4 or returned to the treasury through governed action at the end of the period if needed. |
| Operational costs | Spendable operating budget for infrastructure, runtime, measurement, and support tied to the proving workload and WEAVE delivery. | Month 1 kickoff. | Major spend-category summaries and milestone support references. | Remaining balance stays visible in the final package summary and follows the grant handover policy at the end of the period. |
| Agent security bounties | Spendable review budget for audits, accepted findings, mitigation support, and other bounded hardening work on supported WEAVE surfaces. | Once the supported surface, review scope, and submission path are published. | Published scope, accepted findings, mitigation references, or audit outputs. | Remaining balance can be handed to the governed system in Month 4 or returned to the treasury through governed action at the end of the period if needed. |
| Consumer hackathon | Spendable program budget for public-consumer adoption incentives, awards, and lightweight participation support around the first public workload lanes. | Once public workload lanes and participation rules are published. | Participation rules, submission records, award references, and public outcome summaries. | Remaining balance can be handed to the governed system in Month 4 or returned to the treasury through governed action at the end of the period if needed. |

## How The Budget Maps To The Roadmap

The five packages are spend lanes that support the roadmap milestones.

| Package | Primary roadmap support | Expected evidence |
|---|---|---|
| Team compensation | Months 1-4 | packet and doc revisions, release notes, tagged artifacts, lifecycle delivery, demand instrumentation, and handover output |
| Network incentives | Month 1 onward | incentive rules, recipient criteria, cohort notes, operator onboarding evidence, release-cohort reports |
| Operational costs | Months 1-4 | baseline metrics, runtime/control-plane artifacts, usage reports, and milestone support logs |
| Agent security bounties | Month 2 onward | published review scope, accepted findings, mitigation references, or audit outputs |
| Consumer hackathon | Public-release period onward | published participation rules, submissions or usage reports, award references, and public release follow-up |

## Spend Principles

1. The forum post stays simple; detailed package logic lives here and custody mechanics live in the separate wallet governance packet.
2. Spend starts when the supporting milestone surface is ready and publicly legible.
3. Security-bounty and hackathon spend follows published scope and participation rules.
4. Operational costs support the proving workload lane, measurement path, and WEAVE delivery during the grant window.
5. The public appendix keeps the ask in USD terms.
6. v1 treasury operations stay under explicit human approval and do not include auto-convert or auto-swap logic.

## Treasury Flow Summary

The high-level treasury flow is:

1. grant funds arrive on Arbitrum into a proposal-facing multisig
2. the signer composition is listed below and the operating threshold is `3/5`
3. treasury actions proceed through that multisig governance path
4. if funds need to be returned, the remaining grant balance can be sent back to the Livepeer treasury through the same governance path

### Multisig Composition

- **Orchestrator tiebreaker:** one signer
- **Embody team:** two signers
- **Foundation:** two signers

The team cannot move funds unilaterally. Any treasury action requires at least one non-team signer, and the two Foundation signers together with the orchestrator representative can block a transaction if the grant drifts from its approved use. The deeper role graph, return conditions, and execution details are specified in the separate wallet governance packet. This document is the budget and review bridge.

## Reporting Cadence

During the grant window, the public reporting cadence is:

1. weekly updates in Discord
2. monthly updates in the Livepeer forum

## Why Split Budget Review From Wallet Governance

These are different review questions:

1. Budget review asks:
   - are the five packages understandable?
   - do they map to the roadmap?
   - does the ask look proportional to the proving workload?
2. Wallet governance review asks:
   - where does custody live?
   - who can authorize treasury actions?
   - what onchain facts must later be evidenced?

Keeping those lanes separate reduces drift and makes it easier for a reviewer to challenge either the economics or the custody design without having to parse both at once.

## Evidence Expected During The Grant

If VF4 advances, the financial side should eventually produce evidence like:

1. the proposal-facing multisig deployment and signer references
2. treasury transaction references, including any return-to-treasury transactions if used
3. milestone reports tying spend lanes to outputs
4. a simple package-level summary of what was spent, handed over, or left unused

## Scope Boundary

1. This document defines the five package lanes and their operating rules.
2. The separate wallet governance packet remains the custody source of truth.
3. Treasury automation beyond multisig governance stays outside v1.
4. Package activation follows roadmap readiness and published rules.
