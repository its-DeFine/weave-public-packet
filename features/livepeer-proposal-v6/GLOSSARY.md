# Livepeer Proposal v6 Glossary

This glossary locks the working vocabulary for the v6 proposal so the proposal does not drift between different names for the same concept.

## Public Workload Pipelines

WEAVE is the proposed implementation. Public Workload Pipelines is the broader category of system it belongs to.

Public Workload Pipelines are agent-operated systems that automate the path from stakeholder intent to researched, engineered, tested, maintained, and distributed workloads.

## WEAVE

An open-source, semi-autonomous agentic orchestration tool with a human-in-the-loop design for Livepeer workloads.

WEAVE is designed to turn intent into live workloads by compressing the lifecycle from months to days or even hours. It connects the fragmented lifecycle stages that currently slow workload creation and distribution across the network.

## Workload Lifecycle

The full path a workload must travel before it generates value for the network:

1. research
2. engineering
3. maintenance
4. QA
5. orchestrator release
6. consumer distribution

## Lifecycle Handoff

The transition from one workload-lifecycle stage to the next.

This is a core problem in the proposal. Even when AI helps within one stage, the handoff between stages is often still manual, slow, and dependent on a person carrying context forward.

## Workload Lifecycle And Handoff Bottleneck

The proposal's name for the current growth bottleneck.

This means Livepeer does not only need more compute supply. It also needs a faster, clearer way to research, build, validate, release, and distribute new workloads without losing speed at each stage transition.

## Workload Facilitator

The actor who engineers and maintains the workloads that orchestrators run. Workload facilitators generally fall into two subcategories: startups seeking capital to pay for compute and build a consumer base, and established organizations that already possess capital and consumers.

## Lifecycle Agents

The centralized lifecycle agents operated by the Embody team that power WEAVE during this phase.

They operate outside orchestrator runtimes and assist with research, engineering, QA, maintenance, and distribution under bounded rules and human review. All workloads are automatically inspected by these agents and require manual review before registry deployment.

## Stakeholder Intent

The demand signal or direction given by Livepeer participants about what workloads should be prioritized, improved, or maintained.

The proposal assumes pipelines should respond to stakeholder intent, not operate as an isolated autonomous system.

## Steering Layer

The governance path through which Livepeer stakeholders influence which workload pipelines get prioritized.

In v6, this is the long-term public-good direction tied to token-holder steering, not a claim that the full steering system is complete on day one.

## Control Plane

The mediated layer that handles session management, policy, allocation, and reporting between the public consumer interface and the runtime infrastructure.

## Runtime Plane

The orchestrator-managed infrastructure that actually executes the workload.

For the first proving case, this is the embodied avatar runtime path.

## Consumer

The user, developer, or agent that wants to use a workload through the public interface. This includes app developers building applications on top of existing Livepeer workloads.

The proposal uses `consumer` instead of `customer` because the immediate scope is broader than a traditional paid SaaS relationship.

## App Developer

A sub-category of Consumer who builds applications on top of existing Livepeer workloads. App developers integrate through public contracts such as `SKILL.md` and can be eligible for incentive rewards through the App Developer Incentive Packet.

## Economic Incentive Packets

Three perpetual financial packets that utilize accrued inflation to reward network participants:

1. **Workload Facilitator Hackathon Packet** — incentivizes the creation of new workloads.
2. **App Developer Incentive Packet** — incentivizes developers who build applications on top of WEAVE workloads.
3. **Orchestrator Incentive Packet** — rewards orchestrators who run WEAVE workloads on their hardware.

These packets are designed to compound over time: a portion of accrued inflation value is used for rewards while the remaining value feeds back into the principal.

## Registry

A repository maintained by the Embody team where WEAVE users can post workloads for orchestrators to deploy via a single command. All workloads require automatic inspection and manual review before they are approved for registry deployment.

## BYOC (Bring Your Own Compute)

The Livepeer component utilized by WEAVE for workload deployment to orchestrators.

## SKILL.md

The published consumer-facing contract that instructs consumers on how to start, control, and end a workload through a mediated public control surface. This is one of the primary release artifacts produced by WEAVE.
