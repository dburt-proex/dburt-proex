# Drew Burt

### AI Systems Engineer · Agentic AI Governance · Control Infrastructure

I build **control systems for AI that acts** — deterministic policy gates, permission boundaries, human review, execution controls, evidence trails, and operational intelligence for agentic workflows.

My work focuses on a practical engineering problem:

> **How do we give AI systems useful execution authority without giving them uncontrolled authority?**

I build the infrastructure between **AI intent and real-world action**.

[**Portfolio**](https://drew-burt-portfolio.daxxer-os.chatgpt.site) · [**Systems**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems) · [**Governance Lab**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/lab) · [**Work With Me**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-with-me)

---

## What I Build

My work centers on five related capabilities:

* **Agentic AI governance** — deterministic `ALLOW / REVIEW / HALT` controls before consequential actions execute
* **Execution control** — policy enforcement, authority boundaries, tool permissions, and runtime constraints
* **Auditability** — decision ledgers, execution receipts, provenance, checkpoints, and replayable evidence
* **Agentic readiness** — determining which workflows are appropriate for AI automation and what controls are required
* **Operational intelligence** — turning execution history into structured knowledge for better future decisions

The common architecture is:

```text
Intent
  ↓
Governed Directive
  ↓
Authority · Policy · Evidence · Risk
  ↓
ALLOW · REVIEW · HALT
  ↓
Controlled Execution
  ↓
Evidence + Receipt
  ↓
Decision / Event Ledger
  ↓
Operational Intelligence
  ↓
Better Next Decision
```

---

# Featured Systems

## [CASA — Control Awareness System Architecture](https://github.com/dburt-proex/casa)

**Pre-execution governance for AI systems.**

CASA sits between AI reasoning and real-world execution and deterministically routes proposed actions to:

`ALLOW` · `REVIEW` · `HALT`

Current repository proof includes:

* FastAPI governance API
* deterministic gate engine
* policy and risk evaluation
* append-only audit ledger
* decision replay
* policy simulation
* boundary-stress instrumentation
* operator console
* automated validation paths

**Problem addressed:** AI systems should not execute consequential actions merely because a model requested them.

---

## [DiffWall](https://github.com/dburt-proex/diffwall)

**Deterministic enforcement for AI-generated code and structured agent actions.**

DiffWall evaluates pull-request changes and structured actions against repository-local policy before they advance.

Current v0.2.0 evidence includes:

* GitHub pull-request integration
* deterministic `ALLOW / REVIEW / HALT` routing
* TypeScript PR firewall
* structured-action firewall
* SARIF output
* policy packs
* CODEOWNERS-aware reviewer routing
* controlled live PR validation

**Problem addressed:** AI-generated changes require enforceable boundaries before merge or execution—not only after-the-fact review.

---

## [Governance Harness Toolkit](https://github.com/dburt-proex/governance-harness-toolkit)

**Reusable governance primitives for AI-assisted and agentic workflows.**

GHT turns governance requirements into machine-evaluable contracts, policies, schemas, fixtures, and regression tests.

The toolkit currently includes deterministic evaluation of workflow execution and input trust with explicit:

* authority grants
* trust classes
* protected paths
* execution gates
* failure behavior
* evidence-retention requirements
* adversarial regression cases

**Problem addressed:** governance controls should be testable infrastructure rather than prose that execution systems can ignore.

---

## [Verified Intelligence Layer — VIL](https://github.com/dburt-proex/VIL_deterministic_scoring_engine)

**Deterministic signal scoring, verification, and routing.**

VIL evaluates incoming signals before they consume operator attention or trigger downstream automation.

```text
Raw Signal
→ Normalize
→ Score Value
→ Verify Evidence
→ Apply Risk Overrides
→ Route
→ Audit
```

Core invariant:

> **A signal cannot outrank its evidence.**

The current implementation includes a scoring engine, API, browser dashboard, routing decisions, metrics, and persistent audit records.

---

## [PromptBP](https://github.com/dburt-proex/PromptBP)

**Instruction and capability architecture for controlled AI execution.**

PromptBP structures AI work around reusable capabilities, explicit state, workflow composition, output contracts, evaluation, and bounded recursive improvement.

```text
Intent
→ Router
→ State
→ Workflow
→ Capability
→ Evaluation
→ Controlled Improvement
→ Output
```

**Problem addressed:** increasingly capable AI systems need explicit instruction boundaries and execution contracts—not expanding prompt complexity.

---

## [Operator Intelligence](https://github.com/dburt-proex/operator-intelligence)

**Evidence-driven assessment and operational decision infrastructure.**

Operator Intelligence formalizes the path from observation to controlled implementation:

```text
Evidence
→ Score
→ Finding
→ Recommendation
→ Roadmap
→ Decision
→ Controlled Implementation
→ Completion Evidence
```

Its assessment architecture currently contains governed scoring, finding libraries, evidence standards, templates, playbooks, decision records, and implementation-routing controls.

---

# Portfolio & Evidence

For the consolidated view of my work, architecture, demonstrations, and supporting evidence:

### → [View the Portfolio](https://drew-burt-portfolio.daxxer-os.chatgpt.site)

Inside:

* [**Systems**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/systems) — system architecture and public evidence
* [**Governance Lab**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/lab) — execution-control scenarios
* [**Work Log**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-log) — build decisions, receipts, and field notes
* [**Agentic Readiness Audit**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/agentic-readiness-audit) — structured assessment of one AI-enabled workflow
* [**Work With Me**](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-with-me) — roles, scoped implementations, and collaborations

---

# Engineering Thesis

AI governance becomes materially different when AI moves from **producing information** to **changing state**.

When an agent can:

* modify a repository
* call an API
* send communications
* access sensitive systems
* trigger workflows
* make state changes
* initiate downstream automation

governance becomes part of the execution architecture.

My systems explore that boundary through:

**intent → authority → policy → decision → controlled execution → evidence → memory**

The objective is **bounded, observable, auditable autonomy**.

---

# Agentic Readiness Audit

I also apply these systems through a fixed-scope **Agentic Readiness Audit** for organizations evaluating AI-enabled workflows.

The audit examines areas including:

* workflow suitability
* execution authority
* permissions
* human approval requirements
* tool and data exposure
* failure modes
* observability
* evidence requirements
* auditability
* implementation readiness

### [View the Audit](https://drew-burt-portfolio.daxxer-os.chatgpt.site/agentic-readiness-audit)

---

# Work With Me

I’m interested in engineering, architecture, implementation, and collaboration involving:

**Agentic AI · AI Governance · AI Control Planes · AI Platforms · Agent Infrastructure · Runtime Controls · AI Risk Engineering · Governed Automation**

For hiring, scoped implementation work, or technical collaboration:

### [Portfolio →](https://drew-burt-portfolio.daxxer-os.chatgpt.site)

### [Work With Me →](https://drew-burt-portfolio.daxxer-os.chatgpt.site/work-with-me)

---

> **Engineering principle:** AI systems should receive no more execution authority than their evidence, controls, and accountability justify.
