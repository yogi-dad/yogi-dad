
# Abhishek Garg

Technical Founder · Behavioral Systems Architect

18+ years in production software engineering.
Psychology graduate building structured behavioral modeling infrastructure.

Founder of **Echos of Mind** — a signal-based behavioral intelligence platform.

---

## What I’m Building

### Echos of Mind

A deterministic behavioral signal engine designed to model longitudinal emotional patterns without relying on engagement manipulation.

Most mental health apps optimize retention.
Echos of Mind optimizes signal precision.

---

## Current System (Early Stage Metrics)

* Rolling window analysis: 24h / 7d / 30d
* Core detectors implemented: frequency spike, volatility shift, clustering, intensity deviation
* Signal cooldown + deduplication: enforced
* Cron-based idempotent execution layer
* Infrastructure cost: <$100/month
* Target: 1000 real active users (weekly signal-density sufficient) within 18 months

Active = ≥3 meaningful entries/month sustained ≥3 months.

---

## Architecture Approach

Behavioral modeling must be deterministic before it becomes adaptive.

System design:

* Modular NestJS backend
* Prisma schema-first modeling
* Indexed MySQL for window queries
* Detector abstraction interface
* Per-user baseline tracking
* RBAC with granular permissions
* Token lifecycle management
* Dockerized dev/prod parity

AI interpretation is layered above the signal engine — not embedded inside it.

---

## 3-Phase System Evolution

**Phase 1 — Structured Journaling**
Pattern detection based on rolling deviations.

**Phase 2 — Adaptive Calibration**
Per-user baseline refinement and sensitivity tuning.

**Phase 3 — Behavioral Operating System**
Longitudinal multi-domain behavioral abstraction.

Compounding asset: personal baseline evolution over time.

---

## Design Principles

* Signal density over streaks
* Precision over frequency
* Restraint over engagement pressure
* Longitudinal modeling over reactive feedback

The system should send fewer insights as it becomes more accurate.

---

## Monetization Direction

Aligned with depth of behavioral clarity:

* Premium adaptive calibration layer
* Longitudinal behavioral reports
* Institutional behavioral infrastructure (long-term)

No ads. No retention engineering.

---

## Long-Term Thesis

Clarity compounds when behavior is structured over time.

Echos of Mind begins as a journaling platform.
It evolves into adaptive behavioral infrastructure.
