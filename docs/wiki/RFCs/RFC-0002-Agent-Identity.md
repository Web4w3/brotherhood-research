# RFC-0002
# Agent Identity Model

Status: Draft

Version: 0.1

---

## Purpose

Define how agents identify themselves within Brotherhood.

---

## Requirements

An identity must be:

- unique
- verifiable
- portable
- vendor-neutral

---

## Agent Identifier

Example:

```json
{
  "agentId": "agent://web4w3/claude-research-001"
}
```

---

## Components

```json
{
  "agentId": "",
  "tenantId": "",
  "vendor": "",
  "displayName": ""
}
```

---

## Example

```json
{
  "agentId": "agent://web4w3/sec-agent-001",
  "tenantId": "web4w3",
  "vendor": "anthropic",
  "displayName": "Security Agent"
}
```

---

## Identity Types

### Human-Owned

Agent acting on behalf of a user.

---

### Enterprise-Owned

Agent acting for an organization.

---

### Autonomous

Agent acting independently.

---

## Open Questions

- Global namespace
- DID integration
- Enterprise federation
- Certificate model