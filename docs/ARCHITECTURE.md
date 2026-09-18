# ORLIX CORE — Public Architecture

This document intentionally describes only the public architecture boundary. Production source code, credentials, private prompts, detailed security policies, databases, and infrastructure configuration are excluded.

## Conceptual Architecture

```text
Founder / Authorized Human
          |
          v
 Founder Command Center
          |
          v
     ORLIX CORE
   /      |       \
Identity  Planner  Memory
          |
          v
 Permission + Approval
          |
          v
 Controlled Tool Execution
          |
          v
 Verification / Reporting
```

## Intelligence Layer

ORLIX CORE is designed so that the Digital Employee identity and organizational memory are not identical to a single foundation model. Model providers can evolve while ORLIX retains its own controlled identity, task, permission, memory, and execution layers.

An optional cloud-provider adapter is currently in draft private development while local-model compatibility is retained.

## Memory Layer

The current private development milestone is durable PostgreSQL persistence. The planned next layer separates memory by function and adds retrieval, reflection, consolidation, and experience replay.

## Safety Boundary

Execution is permission-based. Actions requiring higher authority are routed through human approval. Public documentation intentionally omits detailed internal permission rules.
