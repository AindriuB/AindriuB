## Professional experience

### Public-sector technology

**Senior Software Engineer · Technical Lead**

Experience working on large-scale public-sector digital services involving high-volume financial and transactional processing.

My recent work has included:

- Designing and developing Java-based services and applications.
- Working across distributed systems, APIs, databases and integration platforms.
- Supporting systems through production and investigating complex operational issues.
- Building tooling to automate recurring production-support activities.
- Developing reusable engineering frameworks and SDKs.
- Coaching developers and establishing more consistent approaches to production automation.
- Investigating failures across distributed components and developing data-recovery solutions.
- Exploring secure applications of LLMs and MCP to enterprise systems containing sensitive information.

#### Production automation

I identified that recurring production problems were being resolved through manual processes and individual, ad-hoc scripts.

I developed a **common scripting SDK and automation framework** that allowed developers to rapidly build and deploy reusable solutions to these problems.

The framework changed live support from a predominantly manual activity into a more engineering-oriented process:

**Identify recurring problem → codify solution → deploy automation → reuse**

I also coached junior developers in using the SDK and helped address inconsistencies and security problems present in earlier implementations.

#### Distributed systems

Worked on a significant production incident involving data loss across a distributed processing pipeline.

Investigation of application behaviour and production logs identified an issue involving **Hazelcast write-behind processing and downstream HBase persistence**, where data could be evicted from the write-behind queue before reaching its destination.

I helped establish the failure mechanism, worked through the underlying platform issue and contributed to recovery tooling used to restore affected data.

#### Enterprise AI

Developed an MCP-based investigation service exploring how LLMs can safely interact with sensitive enterprise information through controlled API boundaries.

The work focuses on privacy-preserving access, pseudonymisation, identity correlation, authorisation and auditability.

This work subsequently led to the development of **Data Prism**, an open-source exploration of the architecture.