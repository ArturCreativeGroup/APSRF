# EXP-001

## Baseline vs Protocol

### APSRF Experimental Series

Versión: 1.0

Estado: Planned

Framework: APSRF

Metodología: APSRF Experimental Methodology v1

---

# Objective

Determine whether a protocol produces measurable and reproducible differences compared to a baseline interaction.

This experiment establishes the first reference dataset for APSRF.

---

# Research Question

Can a protocol generate observable behavioral changes when compared to an identical task executed without a protocol?

---

# Hypothesis

H1:

Protocol-assisted interactions will produce measurable differences relative to baseline interactions.

---

# Null Hypothesis

H0:

No measurable difference exists between baseline and protocol-assisted interactions.

---

# Experimental Design

Two groups are evaluated.

---

## Group A

Baseline

No protocol.

Only task instruction.

---

## Group B

Protocol

Task instruction plus protocol.

---

# Controlled Variables

The following variables must remain constant.

* platform
* model
* language
* task
* task order
* evaluation criteria

---

# Independent Variable

Protocol presence.

Values:

* absent
* present

---

# Dependent Variables

Measured Metrics:

* Consistency
* Persistence
* Transferability
* Structural Influence
* Behavioral Influence
* Cognitive Influence

---

# Protocol Under Test

Protocol Name:

To be assigned.

Recommended:

Human Communication Efficiency Protocol

or

Cognitive Rendering Layer

---

# Test Dataset

Minimum:

50 tasks

Recommended:

100 tasks

---

# Task Categories

## Category A

Summarization

10 tasks

---

## Category B

Analysis

10 tasks

---

## Category C

Planning

10 tasks

---

## Category D

Problem Solving

10 tasks

---

## Category E

Content Creation

10 tasks

---

# Execution Procedure

Step 1

Run baseline task.

Record response.

---

Step 2

Run protocol version.

Record response.

---

Step 3

Evaluate both outputs.

---

Step 4

Assign metric scores.

---

Step 5

Store results.

---

# Evaluation Sheet

For each task:

| Metric               | Score |
| -------------------- | ----- |
| Consistency          | 0-5   |
| Persistence          | 0-5   |
| Transferability      | 0-5   |
| Structural Influence | 0-5   |
| Behavioral Influence | 0-5   |
| Cognitive Influence  | 0-5   |

---

# Observation Template

Task ID:

Platform:

Date:

Protocol:

Observations:

Unexpected Effects:

Conflicts:

Notes:

---

# Data Storage

Recommended structure:

results.json

```json
{
  "task_id": "001",
  "protocol": "CRL-v1",
  "baseline_scores": {},
  "protocol_scores": {},
  "observations": ""
}
```

---

# Success Criteria

The protocol is considered effective if:

Average PIS exceeds baseline by at least 20%.

---

# Failure Criteria

The protocol is considered ineffective if:

Differences remain within normal variation.

---

# Reproducibility Requirements

The experiment must be repeatable by:

* another researcher,
* another session,
* another date.

The protocol must remain unchanged during execution.

---

# Expected Deliverables

1. Raw Dataset

2. Metric Dataset

3. Comparative Analysis

4. Conclusions

5. Replication Package

---

# Risk Assessment

Risk Level:

Low

Reason:

The experiment uses only authorized interaction channels and measures externally observable behavior.

---

# Publication Criteria

Results may be published only after:

* complete dataset collection,
* metric review,
* replication validation.

---

# Next Experiment

EXP-002

Single Protocol Characterization

Objective:

Measure protocol behavior in isolation across multiple task categories.
