# SBC ERP for Oil & Gas
## Executive Summary

*A controlled system of record for upstream operators, joint-venture partners and their service ecosystems.*

---

### The challenge

Oil & Gas companies run on capital-intensive, partner-funded, highly regulated operations. Spending is authorized through AFEs, shared through participating interests, and audited by partners, regulators and tax authorities. Many ERP landscapes still rely on disconnected modules, duplicate master data and controls that live only in forms. Those weaknesses surface as audit findings, cost overruns and slow month-end closes.

### The answer

SBC ERP for Oil & Gas is a modular, multi-tenant platform built on **SBC Core**. Ten domain modules work as one system of record:

| Financial core | Oil & Gas native | Operations | People and delivery |
| --- | --- | --- | --- |
| Accounting · Budget · Finance | AFE Management · Block Management | Procurement · Inventory · Assets | HR · Project Management |

Each master record has one owner. Modules exchange information only through governed, tenant-scoped integration contracts. Accounting is the single book of record.

### What sets SBC ERP apart

**1. Controls that cannot be bypassed.** Every financial write passes five independent layers: user interface, server action, posting engine, PostgreSQL guards and the audit trail. Double entry, open-period posting, tenant isolation and monetary precision are enforced inside the database itself. More than 440 accounting controls are enforced and covered by automated tests.

**2. Oil & Gas built in, not bolted on.** The platform manages the full AFE lifecycle with technical and finance review. Blocks, parties and effective-dated participating interests and operatorship are first-class records, and contractual economic terms are resolved by date. Budget and AFE commitments are checked before every purchase and validated before every journal.

**3. Local AI and a decision engine for managers.** All AI runs inside the customer's own deployment, and no business data goes to external AI services. A self-hosted decision engine returns typed, confidence-scored answers and sends uncertain cases to a person. Managers get close-readiness scoring, anomaly detection, trend projection, KPI alerts, cash forecasting and instant answers drawn from the authoritative ledgers.

**4. Built for Oman.** The platform supports VAT, withholding tax, Fawtara e-invoicing with immutable submission evidence, Central Bank of Oman reference rates, and the Commercial Companies, Labour and Personal Data Protection laws.

**5. Audit-ready by design.** Every transaction links to its source document, approval history, rule version and posting reference. Maker-checker, delegation of authority, reconciliations and Ledger Health monitoring follow the COSO framework, and reproducible extracts support internal and external audit.

### Standards supported

| Area | Standards |
| --- | --- |
| Financial reporting | IFRS Conceptual Framework, IFRS 1, 6, 8, 9, 10, 11, 15, 16, 18; IAS 1, 2, 7, 10, 16, 21, 34 |
| Oman | VAT Law (RD 121/2020), withholding tax, Fawtara e-invoicing, Commercial Companies Law (RD 18/2019), Labour Law (RD 53/2023), PDPL (RD 6/2022) |
| Control and audit | COSO 2013, IIA Global Internal Audit Standards 2024, ISA system support, record retention |
| Design references | ISO 55001, ISO 14224, ISO 31000, ISO/IEC 27001, NIST CSF 2.0, OWASP ASVS, ISO/IEC 42001 |

### End to end, in one flow

> **Requisition** (block-aware, budget- and AFE-checked) → **Approval** (delegation of authority, segregation of duties) → **Sourcing and order** (commitment recorded) → **Receipt or service entry** (stock and GL posted automatically) → **Invoice match** (idempotent handoff to Accounting) → **Supplier settlement** (open-item allocation) → **Bank reconciliation** → **Period close** (readiness score, governed FX, reconciliations) → **Financial statements** (versioned mapping, no plug values)

### Enterprise-grade operations

- Runs on-premises or in a private cloud. Data, documents, AI models and backups stay in the customer's environment.
- High-availability overlays for PostgreSQL, Redis and object storage.
- Continuous off-site backup with point-in-time recovery to any moment.
- Independently versioned modules, forward-only schema evolution and automated release assurance.

### Outcomes for leadership

| Stakeholder | Outcome |
| --- | --- |
| CEO and board | One trusted view of spend, commitments and performance across blocks, AFEs and assets |
| CFO and controller | Faster, controlled close; governed FX; statements traceable to source |
| Joint-venture partners | Effective-dated interests and an auditable AFE and cost trail |
| Operations and supply chain | Budget-aware procurement, accurate stock, asset reliability data |
| Audit and compliance | Evidence by design, immutable history, reproducible extracts |
| IT and security | Tenant isolation in the database, local AI, no external data exposure |

---

*The full whitepaper, "SBC ERP for Oil & Gas — Standards, Architecture, Governance and Control", details the architecture, integration contracts, workflows, standards coverage and the enterprise control catalog.*
