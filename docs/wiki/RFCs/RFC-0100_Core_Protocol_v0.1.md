# RFC-0100: Core Protocol

Status: Draft v0.1

## Abstract

This RFC defines the foundational protocol concepts supporting OFMM deliberations.

## Objectives

The protocol MUST support:
- Mind Member identification
- Deliberation creation
- Proposal exchange
- Challenge exchange
- Consensus tracking
- Decision recording
- State visibility

## Core Entities

- Mind Member
- Deliberation
- Proposal
- Challenge
- Consensus
- Decision

## Design Principles

### Transport Agnostic
The protocol MUST remain independent of HTTP, WebSocket or future transports.

### Human Compatible
The protocol MUST support Human, Artificial and Hybrid Mind Members.

### Transparency
Protocol objects SHOULD expose state and bottlenecks.

### Traceability
Deliberation history SHOULD remain auditable.

## Future RFCs

- RFC-0101 Capability Discovery
- RFC-0102 Context Exchange
- RFC-0103 Transport
- RFC-0104 Relay
- RFC-0105 Persistence

## Mission Statement

The protocol exists to support transparent collective intelligence rather than simple message exchange.
