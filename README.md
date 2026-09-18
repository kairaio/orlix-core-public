# ORLIX CORE

ORLIX CORE is the private intelligence foundation behind ORLIX AI Digital Employees.

ORLIX is building a **Living Digital Enterprise** where humans remain in control while AI Digital Employees support planning, execution, monitoring, communication, memory, and operations.

> This repository contains public documentation and portfolio materials only.
> The ORLIX CORE production source code, credentials, private memory, internal prompts, and infrastructure configuration remain private.

## Project Status — September 2026

ORLIX CORE is under active private development.

### Current production foundation

- Li Wei digital identity and runtime
- Founder Command Center interface
- Protected Founder Command Center and internal APIs
- Structured task planning
- Permission-based execution
- Human approval workflow
- Read-only tool execution
- Controlled write-tool execution
- Approved task executor
- Secure Git workflows
- Cloud-safe repository observation

### Persistent Memory — Verification in Progress

A persistent PostgreSQL memory backend is currently being verified in private development.

Completed engineering verification includes:

- PostgreSQL 15 and PostgreSQL 18 CI coverage
- full regression suite: 58 tests passed per PostgreSQL job
- repeated database initialization
- registry upsert behavior
- conversation history ordering and limits
- session isolation
- database credential/failure handling and transaction rollback
- activation UUID/time/status persistence across fresh application containers
- rejection of unsupported non-empty DATABASE_URL values
- SQLite backup-helper validation on synthetic test data

This work is **not yet described as production-complete**. The private implementation remains in draft while live backup/restore, migration rehearsal, Railway cutover, container replacement, and outage/recovery verification are completed.

### Cloud AI Provider — Draft

A cloud-capable AI provider adapter is also under private development. It preserves local-model support while preparing ORLIX CORE for optional cloud inference. Production cloud credentials and protected live chat validation remain pending.

### ORLIX Collective Intelligence (OCI) — Research

OCI v0.1 is an isolated research prototype exploring collective-intelligence mechanisms and fault-injection simulation. It is a research harness only; no AGI, novelty, or real-world performance claim is made.

## Li Wei

Li Wei is the first AI Digital Employee developed inside ORLIX.

| Field | Value |
|---|---|
| Official Name | Li Wei |
| Employee ID | ORX-AI-000001 |
| Position | Chief AI Officer |
| Department | Executive Intelligence Division |
| Generation | Generation I |
| System | ORLIX CORE |
| Current Direction | Persistent, memory-enabled digital employee |

Li Wei is designed to receive structured instructions, support planning and execution, operate through controlled tools, retain organizational context, and work under human authority.

## Development Direction

The next memory milestone is to move beyond basic persistence toward a structured continual-memory architecture:

`Persistent Memory → Retrieval → Episodic/Semantic Memory → Reflection → Consolidation → Experience Replay → Cognitive Loop`

These are development targets, not claims of completed AGI capabilities.

## Human Authority

ORLIX CORE is designed around human control. High-impact actions remain subject to permissions and approval workflows, and final company authority remains with authorized human leadership.

## Security Notice

This public repository intentionally excludes:

- ORLIX CORE production source code
- API keys, tokens, and credentials
- private conversations and memory databases
- internal prompts
- detailed permission policies
- approval-state data
- production environment variables
- private infrastructure and backup data

## Public vs Private Repositories

**Public:** `kairaio/orlix-core-public` — portfolio, architecture summaries, research status, and public development documentation.

**Private:** ORLIX CORE production repository — implementation, tests, internal configuration, memory systems, and operational security controls.

## Website

https://orlix.tech

## License

ORLIX public documentation is provided for portfolio and informational purposes only.
