---
id: doc1
title: Purity: Simple Data Protection
sidebar_label: Purity
---

## What is Purity?

**Purity** is a storage operating environment from Everpure. It helps a company manage and protect its data.

> **Simple meaning:** Purity helps keep business data safe and available.

## Main Security Features

- Encrypts stored data
- Controls who can access data
- Creates protected copies called snapshots
- Helps restore data after an attack

| Feature | Benefit |
|---|---|
| Encryption | Makes data harder to read if stolen |
| Access control | Allows only approved users |
| Protected snapshots | Keeps recovery copies safe |
| Fast recovery | Helps reduce downtime |

## Simple Workflow

```mermaid
flowchart LR
    A[Store data] --> B[Protect data]
    B --> C[Create snapshot]
    C --> D[Restore if needed]
```

## Example Policy

The following example is only for explanation. It is **not an official command**.

```yaml
security:
  encryption: enabled
  snapshots: daily
  access: approved-users-only
```

## Important Note

Purity is one security layer. A company should also use strong passwords, monitoring, firewalls, and security training.

## Summary

Purity helps protect data through encryption, access control, snapshots, and recovery.

[Learn more about Purity](https://www.everpuredata.com/products/array-management.html)
