# Livepeer Proposal v6 Financial Plan And Governance

This document explains the financial shape of v6 in plain language. It sits between the short forum post and the deeper [wallet governance packet](../livepeer-grant-wallet-governance-v0/2026-03-07-contract-ledgers-packet.md).

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

## Important Note on Staking

Fully half of the total request will not be spent. It will remain staked as principal within the multisig, specifically to generate inflationary rewards that flow continuously back to orchestrators, workload facilitators, and consumers through the three perpetual incentive packets.

## Budget Summary

| Package | Why it exists |
|---|---|
| Team compensation | Covers core delivery work. DeFine: strategy, control plane, WEAVE engineering, and governance/runtime delivery. Dane: embodied avatar workload engineering across Unreal Engine and non-Unreal runtime paths. Release mechanism: each monthly tranche is held in the multisig and released only after the month's work is complete and its success criteria have been met. Release requires 3/5 multisig confirmation. Each track is independently verified and independently released. |
| Operational costs | Covers infrastructure, runtime, measurement, and support costs for the proving workload during the grant window. Release mechanism: funds are released against submitted receipts as expenses are incurred. No advance disbursement. |
| Orchestrator incentives | Principal for the Orchestrator Incentive Packet, utilizing accrued inflation to reward orchestrators who run WEAVE workloads. Release mechanism: once the program launches in Month 1, the multisig releases weekly or bi-weekly distributions to participating orchestrators according to the published incentive rules. |
| Workload facilitator incentives | Principal for the Workload Facilitator Hackathon Packet, utilizing accrued inflation to reward new workload creation. Release mechanism: once the program launches in Month 1, the multisig releases weekly or bi-weekly distributions to participants who meet the published hackathon criteria. |
| App developer hackathon | Principal for the App Developer Incentive Packet, utilizing accrued inflation to incentivize early application development and integration. Release mechanism: once the program launches in Month 1, the multisig releases weekly or bi-weekly distributions to developers who meet the published incentive terms. |

## How Each Package Is Managed

The three incentive packets (orchestrator, workload facilitator, app developer) are perpetual staking-based programs. A portion of accrued inflation value is used for participant rewards while the remaining value feeds back into the principal, allowing it to compound continuously so that rewards grow over time.

The team compensation and operational costs packages are standard spendable grant budgets managed through the multisig.

| Package | Operating rule | Spend starts when | Evidence and reporting | Handover position |
|---|---|---|---|---|
| Team compensation | Monthly tranche released upon 3/5 multisig confirmation of success criteria. Each track (DeFine/Dane) independently verified and released. | Month 1 kickoff. | Team payout references plus milestone outputs tied to the roadmap. | Any remaining balance stays visible at package level and follows the grant handover policy at the end of the period. |
| Operational costs | Spendable operating budget. Funds released against submitted receipts. | Month 1 kickoff. | Major spend-category summaries and milestone support references. | Remaining balance stays visible in the final package summary and follows the grant handover policy at the end of the period. |
| Orchestrator incentives | Perpetual staking-based program utilizing accrued inflation for weekly/bi-weekly distributions. | Month 1 — all three incentive packets deploy alongside the Embody workload launch. | Incentive rules, recipient criteria, distribution records, and usage-facing program notes. | Post-grant management determined through Month 4 governance discussion. |
| Workload facilitator incentives | Perpetual staking-based program utilizing accrued inflation for weekly/bi-weekly distributions. | Month 1 — all three incentive packets deploy alongside the Embody workload launch. | Published hackathon criteria, participant submissions, distribution records, and completion evidence. | Post-grant management determined through Month 4 governance discussion. |
| App developer hackathon | Perpetual staking-based program utilizing accrued inflation for weekly/bi-weekly distributions. | Month 1 — all three incentive packets deploy alongside the Embody workload launch. | Published incentive terms, submission records, distribution references, and public outcome summaries. | Post-grant management determined through Month 4 governance discussion. |

## How The Budget Maps To The Roadmap

The five packages are spend lanes that support the roadmap milestones.

| Package | Primary roadmap support | Expected evidence |
|---|---|---|
| Team compensation | Months 1-4 | packet and doc revisions, release notes, tagged artifacts, lifecycle delivery, and handover output |
| Operational costs | Months 1-4 | baseline metrics, runtime/control-plane artifacts, usage reports, and milestone support logs |
| Orchestrator incentives | Month 1 onward | incentive rules, recipient criteria, distribution records, operator onboarding evidence |
| Workload facilitator incentives | Month 1 onward | published hackathon criteria, workload submissions, distribution records, completion evidence |
| App developer hackathon | Month 1 onward | published incentive terms, app submissions, distribution references, and public outcome summaries |

## Spend Principles

1. The forum post stays simple; detailed package logic lives here and custody mechanics live in the separate wallet governance packet.
2. Spend starts when the supporting milestone surface is ready and publicly legible.
3. Incentive packet distributions follow published scope and participation rules.
4. Operational costs support the proving workload lane, measurement path, and WEAVE delivery during the grant window.
5. v1 treasury operations stay under explicit human approval and do not include auto-convert or auto-swap logic.

## Fund Return Policy

If the project is not finished in the provided timeframe, all provided funds managed by the multisig will be converted and sent back to the treasury.

## Treasury Flow Summary

The high-level treasury flow is:

1. grant funds arrive on Arbitrum into a proposal-facing multisig
2. the signer composition is listed below and the operating threshold is `3/5`
3. treasury actions proceed through that multisig governance path
4. if funds need to be returned, the remaining grant balance can be sent back to the Livepeer treasury through the same governance path

### Multisig Composition

- **Orchestrator tiebreaker:** One signer — Pon.
- **Embody team:** Two signers.
- **Foundation:** Two signers, including Rick, the Foundation's head engineer.

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

If v6 advances, the financial side should eventually produce evidence like:

1. the proposal-facing multisig deployment and signer references
2. treasury transaction references, including any return-to-treasury transactions if used
3. milestone reports tying spend lanes to outputs
4. a simple package-level summary of what was spent, handed over, or left unused

## Scope Boundary

1. This document defines the five package lanes and their operating rules.
2. The separate wallet governance packet remains the custody source of truth.
3. Treasury automation beyond multisig governance stays outside v1.
4. Package activation follows roadmap readiness and published rules.
