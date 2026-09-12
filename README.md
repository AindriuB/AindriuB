# Andrew Bannister

### Senior Software Engineer · Technical Lead · Solutions Architect

**Java · Distributed Systems · Software Architecture · Payments · AI Infrastructure**

Senior software engineer and technical lead with experience designing, building and
supporting large-scale production software.

My background spans financial technology and large enterprise systems, working across
software development, architecture, distributed systems, production engineering and
technical leadership.

I enjoy difficult engineering problems — particularly distributed systems,
integration, automation and systems where correctness and reliability matter.

---

## What I bring

- **Software engineering** — designing and building production systems in Java and
  other modern languages.
- **Architecture** — turning complex requirements and system constraints into
  practical designs and implementation plans.
- **Distributed systems** — working with asynchronous processing, messaging,
  distributed state and persistence.
- **Production engineering** — investigating difficult failures and building tools
  to make operational problems easier to solve.
- **Automation** — replacing repetitive manual processes with reusable frameworks
  and developer tooling.
- **Payments** — payment processing, integrations and ISO-8583.
- **Enterprise AI** — exploring practical LLM and MCP architectures around sensitive
  enterprise data.
- **Technical leadership** — mentoring developers, establishing engineering
  approaches and helping teams solve difficult problems.

---

## Selected projects

### [Data Prism](https://github.com/AindriuB/data-prism)

**Privacy-preserving AI infrastructure for enterprise systems.**

An exploration of how LLMs and AI agents can work with sensitive enterprise
information through controlled interfaces rather than unrestricted access to
underlying systems.

The project explores:

- MCP-based AI investigation
- Controlled enterprise API access
- Pseudonymisation
- Identity correlation
- Authorisation
- Auditability
- Secure boundaries between AI systems and sensitive data

**Technology:** Java · Spring Boot · MCP · Hazelcast · OAuth2 · mTLS

---

### [JResolve](https://github.com/AindriuB/jresolve)

**Java entity resolution and record-linkage library.**

A reusable library for matching external records against internal identities using
normalisation, blocking, fuzzy matching and confidence scoring.

Designed as a Java library rather than a framework-specific application, with an
emphasis on extensibility and explainable matching decisions.

**Technology:** Java · Maven · Fuzzy Matching · Probabilistic Matching

---

### [F1 Simulator Engine](https://github.com/AindriuB/f1-simulator-engine)

**On-device probabilistic Formula 1 championship simulation.**

A computational simulation engine combining championship mathematics, scenario
analysis, Monte Carlo simulation and constraint-based title analysis.

Designed around local computation on iPhone rather than relying on a backend for
simulation.

**Technology:** Swift · SwiftUI · Swift Concurrency · SwiftData

---

# Engineering experience

## Senior Software Engineer · Technical Lead

Experience designing, building and supporting large-scale production software,
working across application development, complex domain logic, distributed systems,
messaging, persistence, integration and production engineering.

Recent engineering work has included:

- Core financial calculation and reconciliation services
- Real-time and event-driven processing
- Java and Spring Boot services
- Kafka-based messaging and asynchronous processing
- REST APIs and service integration
- Distributed caching and state management
- HBase-based persistence
- Docker-based application environments
- Production investigation and data recovery
- Developer tooling and automation
- Technical leadership and mentoring

### Core financial calculation

Designed and developed a **core financial calculation engine** forming part of a
large-scale real-time processing platform.

The engine implemented complex domain rules to calculate an individual's financial
position and determine whether the resulting position was balanced, underpaid or
overpaid.

The calculation formed part of downstream **reconciliation and settlement
processing**, where correctness directly affected financial outcomes.

The wider platform used **Java, Spring Boot, Kafka, Docker, Hazelcast and HBase**,
with the calculation logic integrated into a distributed processing architecture.

The work involved translating complex domain rules into deterministic software
calculations, integrating the engine with surrounding services and dealing with
the practical challenges of executing financial calculations within a distributed
system.

### Distributed systems & production engineering

Worked extensively with distributed processing and persistence using technologies
including **Kafka, Hazelcast and HBase**.

Investigated complex production incidents by tracing behaviour across asynchronous
processing, distributed state and persistence layers.

In one significant incident, investigation of application behaviour and production
logs identified a failure involving **Hazelcast write-behind processing and
downstream HBase persistence**, where data could be evicted from the write-behind
queue before reaching its destination.

I helped establish the failure mechanism, worked with the relevant engineering
teams on the underlying issue and contributed to **data-recovery tooling** to
restore affected data.

### Production automation

Identified an opportunity to replace recurring manual production-support activities
with reusable engineering solutions.

Designed and developed a **common scripting SDK and automation framework** providing
a standard foundation for rapidly building and deploying operational tooling.

The framework allowed developers to turn recurring production problems into
reusable automated solutions rather than repeatedly performing manual interventions.

The approach changed the workflow from:

**Manual investigation → manual resolution**

to:

**Identify → automate → deploy → reuse**

I also coached other developers in using the SDK and helped establish a more
consistent approach to production automation.

The important part of the work was not simply writing scripts, but creating a
reusable engineering capability that allowed developers to solve a wider class of
operational problems quickly and consistently.

### Enterprise AI / MCP

Developed an **MCP-based investigation service** exploring how LLMs can interact
with enterprise systems through controlled interfaces.

The architecture explores:

- Controlled access to enterprise APIs
- Privacy-preserving data handling
- Pseudonymisation
- Identity correlation
- Authorisation
- Auditability
- AI-assisted investigation

This work led to **Data Prism**, an independent open-source exploration of these
ideas.

---

# Payments & Financial Technology

## Solutions Architect

Previous experience as a **Solutions Architect within global payments technology**.

Worked across payment-processing and integration solutions involving multiple
payment providers, gateways and processors.

Experience included:

- **ISO-8583** payment messaging and transaction processing.
- Payment gateway and processor integrations.
- Authorisation, capture and settlement.
- Reversals and refunds.
- Transaction failure handling and recovery.
- Integration architecture across payment platforms.
- Designing systems requiring high availability and transactional integrity.
- Translating payment-processing requirements into implementable software
  architecture.
- Working across the boundary between payment processing, integration and
  application architecture.

---

# Technology

### Languages

**Java · Swift · TypeScript · JavaScript · SQL**

### Backend & distributed systems

**Spring Boot · Kafka · REST · Distributed Systems · Asynchronous Processing**

### Data & infrastructure

**PostgreSQL · HBase · Hazelcast · Docker**

### AI & integration

**MCP · LLM Integration · OAuth2 · mTLS · API Integration**

### Mobile

**SwiftUI · Swift Concurrency · SwiftData**

### Engineering

**Maven · Git · Linux · Automated Testing · CI/CD**

---

# Current interests

I'm particularly interested in the intersection of:

**Distributed Systems · Software Architecture · Java · Payments · Secure Data ·
AI/LLMs · Developer Tooling**

Recent personal projects explore these areas through practical implementations
rather than purely theoretical prototypes.

---

# Open to interesting opportunities

Interested in opportunities and collaborations involving:

**Senior Software Engineering · Technical Leadership · Software Architecture ·
Principal-level Engineering · Distributed Systems · Payments · Enterprise AI**

If you're working on a technically difficult problem, I'd be happy to talk.