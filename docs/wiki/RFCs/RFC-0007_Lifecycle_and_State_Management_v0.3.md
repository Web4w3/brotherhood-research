# RFC-0007: Lifecycle and State Management

Status: Draft v0.3

## Abstract

This RFC defines how deliberations progress, pause, wait and complete.

## Motivation

OFMM supports asynchronous collaboration involving humans, AI systems and external experts.

Participation may take seconds, hours, days or weeks.

## Deliberation States

### Open
Deliberation created.

### Active
Participants are actively contributing.

### Waiting
Progress depends on a participant, evidence or review.

### Consensus Reached
Consensus achieved.

### Decision Made
Decision recorded.

### Closed
Deliberation completed.

### Abandoned
Deliberation stopped without decision.

## Waiting Reasons

- Waiting for Expert
- Waiting for Evidence
- Waiting for Security Review
- Waiting for Legal Review
- Waiting for Compliance Review
- Waiting for Decision Owner

## Bottlenecks

A bottleneck is any dependency preventing progress.

### Participant Bottleneck
Required participant has not responded.

### Evidence Bottleneck
Required data or documentation missing.

### Approval Bottleneck
Decision owner approval pending.

### Consensus Bottleneck
Participants cannot converge.

## Transparency Principle

Authorized Mind Members SHOULD see:

- current state
- participants
- pending reviews
- waiting reasons
- identified bottlenecks
- elapsed time

## Example

Status: Waiting for Security Review

Elapsed Time: 2 Days

Bottleneck: Security Expert Review

Expected Next Action: Security Assessment

## Mission Statement

Decision quality improves when participants understand why deliberations are waiting, who is responsible and what is blocking progress.
