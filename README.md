# Drew Burt — AI Governance & Control Systems

[![DiffWall PR Firewall](https://github.com/dburt-proex/dburt-proex/actions/workflows/diffwall.yml/badge.svg)](https://github.com/dburt-proex/dburt-proex/actions/workflows/diffwall.yml)
[Portfolio](https://drew-burt-portfolio.dburt30.chatgpt.site/) ·
[Systems](https://drew-burt-portfolio.dburt30.chatgpt.site/systems) ·
[Governance Lab](https://drew-burt-portfolio.dburt30.chatgpt.site/lab) ·
[Work Log](https://drew-burt-portfolio.dburt30.chatgpt.site/work-log)

I build deterministic control layers for AI systems: evidence intake, policy
gates, human review, and audit-ready decision records before an action reaches
a real system.

## Control model

```text
Signals and evidence → controlled instruction and reasoning → authorization
                              ↓
                    ALLOW · REVIEW · HALT
                              ↓
                 execution, change control, and audit evidence
```

The systems below are independent control surfaces, not implied runtime
dependencies. Together, they make AI-assisted work more inspectable, bounded,
and reviewable.

## Current ecosystem

### Core control systems

| System | Control surface | Public proof |
| --- | --- | --- |
| [CASA](https://github.com/dburt-proex/casa) | Deterministic runtime governance for proposed actions | Closed `ALLOW` / `REVIEW` / `HALT` routing, policy boundaries, replayable decisions, and audit records |
| [VIL — Verified Intelligence Layer](https://github.com/dburt-proex/VIL_deterministic_scoring_engine) | Signal intake and evidence-capped routing | Deterministic scoring, explicit routes, audit ledger, API, and operator dashboard |
| [PromptBP](https://github.com/dburt-proex/PromptBP) | Instruction and output governance | Capability-based workflows, schemas, objective output scoring, and bounded improvement loops |
| [DiffWall](https://github.com/dburt-proex/diffwall) | Change-time and structured-action enforcement | Pinned `v0.2.0` PR/action firewall with explainable routes, policy packs, CI integration, and controlled validation evidence |

### Assurance, application, and delivery layers

| System | Role | Current boundary |
| --- | --- | --- |
| [Cognitive Routing Layer](https://github.com/dburt-proex/Cognitive-routing-layer) | Produces structured, auditable reasoning receipts | `v0.1` locked; pre-commercial validation |
| [Guardian Agent](https://github.com/dburt-proex/guardian-agent) | Reference governed-execution runtime | Combines signal, policy, and hash-chained audit gates; deterministic rules are a floor, not a guarantee |
| [CASA Construction Gatekeeper](https://github.com/dburt-proex/casa_construction_gatekeeper) | Construction-document intake and routing prototype | Deterministic `ALLOW` / `REVIEW` / `HALT` decisions with a documented pilot integration path |
| [Operator Intelligence](https://github.com/dburt-proex/operator-intelligence) | Evidence-to-decision assessment and delivery system | Commercial v1.0 content, scoring, findings, routes, and release controls |
| [Governance Harness Toolkit](https://github.com/dburt-proex/governance-harness-toolkit) | Deterministic regression evidence | Pinned dependency and machine-readable regression suite |

## Proof, not promises

- This profile repository runs its own [DiffWall PR firewall](.github/workflows/diffwall.yml) on pull requests.
- The [portfolio evidence layer](https://github.com/dburt-proex/DDBPORTFOLIO.git.io) maintains public claims, maturity boundaries, and links to project-specific evidence.
- Every system above links to its canonical public repository, where its source, tests, releases, or stated limitations can be reviewed.
- Maturity is stated per project. These systems do not claim universal safety, automatic compliance, or unattended production autonomy.

## Working principles

- Evidence cannot outrank its verifiability.
- Confidence does not grant authorization.
- Unknown or high-risk conditions route to human review or halt.
- Policy decisions should be deterministic, traceable, and replayable.
- Human authority remains separate from automation.

## Work with me

Available for compliance and risk roles in the Rochester, Minnesota area,
fixed-scope governance implementations, and fractional AI-governance retainers.

- Portfolio: <https://drew-burt-portfolio.dburt30.chatgpt.site/>
- Email: <drewburt4@gmail.com>
- LinkedIn: [burtdrew0047](https://www.linkedin.com/in/burtdrew0047)
