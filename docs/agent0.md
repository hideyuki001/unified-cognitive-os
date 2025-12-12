
# Agent0 — Supervisory Automation Agent

Agent0 is the **supervisory automation layer** inside Unified Cognitive OS.

It is not a conversational agent.
It does not generate content.
It does not call tools autonomously.

Agent0 governs **how tasks are created, evaluated, and evolved**
across the entire cognitive pipeline.

---

## What Agent0 Is

Agent0 functions as an **automation agent in the strict sense**:

- task initialization and curriculum design
- difficulty and scope control
- execution orchestration across subsystems
- evidence-gated feedback absorption
- adaptive progression based on success / failure signals

In short:

> Agent0 does not *do* the task.  
> It automates **how tasks exist and progress**.

---

## What Agent0 Is Not

To avoid ambiguity, Agent0 explicitly avoids the following patterns:

- ❌ Conversational persona
- ❌ Autonomous goal invention
- ❌ Tool-calling agent with opaque reasoning
- ❌ Long-horizon self-directed planning
- ❌ Unbounded autonomy or self-prompting loops

Agent0 is **structural, not behavioral**.

---

## Why Agent0 Exists

In real-world AI workflows, most failures are not caused by models.

They are caused by:
- poorly scoped tasks
- unstable difficulty
- hidden evaluation criteria
- feedback that cannot be absorbed structurally

Agent0 emerged as a necessity under **high-accountability environments**
(e.g. enterprise QA, regulated workflows, multimodal evaluation),
where every decision must be:

- explainable
- reproducible
- reversible
- and safe to escalate

---

## Core Responsibilities

### 1. Task Initialization

Agent0 defines tasks **before generation begins**.

Each task includes:
- difficulty level (continuous, not discrete)
- expected structural complexity
- evaluation rubric alignment
- success expectation range

This prevents under-scoped or over-scoped tasks.

---

### 2. Curriculum and Difficulty Control

Agent0 maintains a **difficulty curve**, not a static task list.

- difficulty increases only when evidence supports it
- regression is allowed when failure patterns emerge
- task space evolves gradually, not explosively

This ensures convergence instead of collapse.

---

### 3. Execution Orchestration

Agent0 coordinates the execution order of subsystems:

- Translation OS (structure-first semantics)
- ModelRefiner (controlled creative reasoning)
- META v3 (evidence-gated evaluation)

Agent0 does not interfere with internal logic,
but **controls when and how each subsystem is invoked**.

---

### 4. Evidence-Gated Feedback Absorption

All feedback absorbed by Agent0 must be evidence-backed.

META v3 provides:
- binary decisions (YES / NO)
- explicit issue descriptions
- justification traces

Agent0 ignores:
- intuition-only feedback
- non-verifiable judgments
- stylistic preference without evidence

---

### 5. Adaptive Progression

Based on accumulated evidence, Agent0 updates:

- next task difficulty
- task scope
- acceptable variance
- curriculum direction

Progression is **adaptive but bounded**.

---

## Relationship to Recent Research

Agent0 aligns closely with what recent literature calls:

- automation agents
- supervisory agents
- orchestration agents

However, it intentionally diverges in key aspects:

| Common Automation Agents | Agent0 |
|--------------------------|--------|
| Persona-driven | Persona-free |
| Goal-seeking | Scope-governed |
| Autonomous planning | Evidence-gated progression |
| Opaque reasoning | Explicit decision trace |
| Tool-calling focus | Workflow governance focus |

Agent0 prioritizes **control over autonomy**.

---

## Agent0 in the OS Architecture

Agent0 sits **above generation and evaluation layers**.

