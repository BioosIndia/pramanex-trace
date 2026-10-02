# Reproducibility and Evaluation Boundary

## Current reproducibility status

This repository supports **architecture-level reproducibility and review**, not reproduction of a production deployment. The publication establishes a proposed evidence-control architecture and operating contract; it does not establish a deployed runtime, customer outcome, independent security assessment, or organization-specific validated use.

## What is reproducible from the public artifact

A reviewer can inspect and test the declared control logic, including:

- source authority before content trust;
- permission-aware retrieval;
- exact evidence grounding;
- revision-bound human approval;
- deterministic failure/HOLD transitions;
- adverse-case handling;
- audit/recovery expectations;
- pilot measurement and stop conditions.

## Required package for a future executable pilot

A future implementation should freeze and preserve at minimum:

1. intended use, users, exclusions, source registry, and material-field rules;
2. source and permission decisions with versions and retrieval times;
3. input, retrieval, model, workflow, and tool-policy versions;
4. ordinary, edge, and adverse test cases with expected outcomes;
5. exact candidate revisions and grounding evidence;
6. reviewer identity/authority, rationale, and disposition;
7. monitoring, incident, rollback, and backup/recovery evidence;
8. per-run outputs and logs needed to reconstruct the decision path;
9. a declared baseline and observation window for operational claims.

## Evaluation principle

High average performance does not override a failed critical permission, grounding, safety, privacy, or human-authority gate. HOLD, rollback, incident, and recovery are counted as observable outcomes, not omitted rows.

## Not included in this repository

No production connector credentials, private client matters, restricted source content, security secrets, or organization-specific validation records are included. No synthetic benchmark from ClaimGraph-RD or Bharat-VPop should be interpreted as a performance measurement of TRACE.
