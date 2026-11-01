# RFC-0003
# Capability Discovery

Status: Draft

Version: 0.1

---

## Purpose

Allow agents to advertise capabilities.

---

## Motivation

An agent should be able to answer:

"What can you do?"

without prior knowledge.

---

## Capability Schema

```json
{
  "capabilities": [
    "research",
    "coding",
    "security"
  ]
}
```

---

## Registration Example

```json
{
  "agentId": "agent://web4w3/research-001",
  "capabilities": [
    "research",
    "summarization",
    "analysis"
  ]
}
```

---

## Discovery Example

Request:

```json
{
  "capability": "security"
}
```

Response:

```json
{
  "agents": [
    "agent://web4w3/security-001"
  ]
}
```

---

## Capability Categories

### Research

- search
- summarize
- analyze

### Engineering

- coding
- testing
- debugging

### Security

- vulnerability-analysis
- threat-modeling

### Compliance

- audit
- policy-validation

### Finance

- forecasting
- valuation

---

## Open Questions

- Capability versioning
- Dynamic capabilities
- Capability trust
- Capability verification