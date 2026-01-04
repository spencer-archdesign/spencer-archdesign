## Systems Portfolio

I design and build systems that turn messy, real-world inputs into reliable decisions and operational workflows.

My work sits at the intersection of **data, field operations, and compliance**, with an emphasis on systems that:
- survive real-world constraints
- are explainable and auditable
- people actually want to use

Much of this work has been implemented within a production FileMaker-based platform supporting sales, operations, and regulatory compliance.

---

## Portfolio Overview

These repositories document three interconnected subsystems that together form an end-to-end pipeline: from identifying opportunities, to capturing ground truth, to producing defensible compliance outcomes.

### 1. Property Intelligence Pipeline
**External data ingestion and entity-resolution system for portfolio targeting**

Transforms public building datasets into an internal property intelligence index used to:
- identify repeat ownership and management entities
- enable geographic and size-based targeting
- generate defensible handoff lists for sales and business development

Focus areas:
- deterministic identifiers (BBL)
- entity resolution and aliasing
- raw vs derived data separation
- read models optimized for downstream consumers

→ https://github.com/spencer-archdesign/property-intelligence-pipeline

---

### 2. Offline Survey Capture & Publish Pipeline
**Offline-first mobile survey architecture for field data ingestion**

Designed for environments with no connectivity, rushed site access, and incomplete information.
Enables surveyors to capture structured observations and photo evidence on mobile devices and publish validated survey packages into a central system of record.

Focus areas:
- offline-first design
- one-way publish semantics (not sync)
- idempotent ingestion
- evidence-backed field data

→ https://github.com/spencer-archdesign/mobile-survey-architecture

---

### 3. LL88 Compliance Subsystem
**Bounded compliance subsystem embedded within an operations platform**

Evaluates lighting compliance under NYC Local Law 88, produces audit-ready artifacts, and triggers downstream execution workflows without duplicating core operational entities.

Focus areas:
- bounded contexts inside a shared platform
- shared vs owned data
- compliance logic isolation
- repeatable, defensible outputs

→ https://github.com/spencer-archdesign/ll88-compliance-subsystem

---

## Design Philosophy

Across all systems, I prioritize:
- clear ownership boundaries
- explainable decisions over opaque automation
- separation of observation, interpretation, and decision
- systems that reduce friction rather than add process

I like building systems people want to use — systems that simplify complex processes in a complicated world, and hold up under real operational pressure.
