# Process Layer Doctrine

## Reference Statement

The Process Layer Doctrine defines a neutral process layer that sits between governance intent and execution outcomes.

It does not decide what should be funded or governed.  
It defines how decisions are made legible, verifiable, and inspectable.

PLD treats process as infrastructure.

This document provides reference definitions and invariants as used within this framework. It does not claim consensus, endorsement, or authority beyond its own internal coherence.

## Scope

PLD applies to systems where:

- Funds, authority, or resources are allocated
- Multiple actors interact across time
- Decisions must survive institutional turnover
- Accountability depends on artifacts rather than trust

PLD does not assume good faith or bad faith.  
It assumes complexity.

## Core Invariants

Within this framework, PLD specifies the following invariants:

1. Boundary Clarity  
Roles, authority, and custody must be explicitly separated.  
No actor may evaluate, execute, and verify the same work without disclosure.

2. End-to-End Legibility  
A decision must be traceable from intake to resolution using observable artifacts.  
Missing steps are treated as risk, not as discretion.

3. Discretion Is Explicit  
Human judgment is allowed only where verification is impossible or inefficient.  
Discretion must be named, bounded, and owned.

4. Verification Is Preferred  
Where verification is possible, it is favored over narrative justification.  
Verification requires artifacts, not assurances.

5. Continuity Over Individuals  
Processes must remain intelligible after the departure of any single participant.  
Knowledge that only lives in people is considered fragile.

## Artifact Discipline

PLD treats artifacts as first-class objects.

Artifacts include:

- Written proposals and specifications
- Milestone definitions and acceptance criteria
- Decision records and evaluation memos
- Disclosure statements
- Code repositories, commits, and tagged releases
- Milestone reports and delivery evidence
- Verification outputs and reproducible checks

Artifacts do not include:

- Verbal discussions without a written record
- Private communications unless disclosed as part of the process record
- Informal understandings or implied agreements
- Retroactive narratives unsupported by contemporaneous artifacts

Verbal context does not substitute for artifacts.  
Artifacts may reference discussion, but discussion may not replace artifacts.

## Separation of Layers

PLD distinguishes between three layers:

Governance  
Sets intent and constraints.

Execution  
Delivers work under agreed terms.

Custody and Verification  
Holds funds and verifies outcomes.

PLD does not collapse these layers.  
It documents their interfaces.

## Neutrality and Non-Authority

PLD claims no authority.  
It confers no legitimacy.  
It enforces no outcomes.

Its function is to reduce ambiguity so that authority can be exercised with clearer sightlines.

## Failure Modes Addressed

PLD is designed to surface, not eliminate:

- Ambiguous milestones
- Role confusion
- Narrative substitution for evidence
- Silent scope expansion
- Process drift over time

## Versioning and Evolution

The current version of PLD is defined in the repository root.

Versioning intent:

- Patch releases may clarify language or framing without changing invariant meaning
- Any change that alters the meaning of a core invariant requires an explicit version increment and changelog entry
- Applications may reference the PLD version they were derived from when relevant

Deprecated versions remain accessible for historical analysis.

## Reference Rule

Core definitions live only in this document within the context of this framework.  
All applications are descriptive mappings derived from these definitions.

If an application conflicts with this framework, the conflict should be made explicit rather than resolved implicitly.

## Interpretation and Disagreement

Applications of PLD represent one possible interpretation of the doctrine.

Different observers or institutions may interpret PLD differently based on context, constraints, or governance norms.

When interpretations conflict, PLD does not provide a resolution mechanism. Institutions and communities retain full discretion to interpret or disregard PLD as they see fit.

Forks and adaptations of PLD are permitted under CC0 but must use distinct names to avoid confusion.
