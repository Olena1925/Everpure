---
id: doc2
title: Everpure Resilience: Simple Cyber Recovery
sidebar_label: Everpure Resilience
---

## What is Everpure Resilience?

**Everpure Resilience** helps a company recover VMware systems after a cyberattack or disaster.

> **Simple meaning:** It helps bring important systems back safely.

## Main Security Benefits

1. Keeps a protected copy of virtual machines.
2. Creates an isolated recovery area.
3. Allows recovery testing.
4. Helps restore systems from a selected recovery point.

| Step | Purpose |
|---|---|
| Protect | Keep a recovery copy |
| Isolate | Keep recovery work away from live systems |
| Test | Check that the recovered system is safe |
| Restore | Return the system to service |

## Recovery Workflow

```mermaid
flowchart LR
    A[Cyberattack] --> B[Isolate system]
    B --> C[Restore clean copy]
    C --> D[Test system]
    D --> E[Return to service]
```

## Example Recovery Plan

The following example is for learning. It is **not an official configuration**.

```yaml
recovery:
  system: finance-app
  target: isolated-area
  security-scan: required
  approval: required
```

## Quick Checklist

- [ ] Select a clean recovery point.
- [ ] Restore the system in an isolated area.
- [ ] Scan the system for threats.
- [ ] Test the application.
- [ ] Get approval before returning to production.

## Summary

Everpure Resilience supports safe testing and recovery after a security incident.

[Learn more about Everpure Resilience](https://www.everpuredata.com/products/cyber-recovery.html)
