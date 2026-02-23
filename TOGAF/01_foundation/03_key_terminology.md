# TOGAF Key Terminology

**Last Updated:** February 2025  
**Version:** TOGAF Standard, 10th Edition  
**Level:** Foundation

---

## Overview

TOGAF uses precise terminology to ensure clear communication across architecture stakeholders. This glossary covers the essential terms you need to know for working with TOGAF and preparing for certification exams.

Terms are organized thematically rather than alphabetically, so related concepts are grouped together for easier learning.

---

## Architecture Fundamentals

| Term | Definition |
|------|-----------|
| **Enterprise** | The highest level of description of an organization, encompassing all of its capabilities. Can refer to an entire company, a division, or a specific area of interest. |
| **Enterprise Architecture (EA)** | A conceptual blueprint that defines the structure and operation of an organization, with the goal of aligning IT with business goals. |
| **Architecture** | The fundamental organization of a system, embodied in its components, their relationships to each other and the environment, and the principles governing its design and evolution. |
| **Architecture Framework** | A foundational structure, or set of structures, which can be used for developing a broad range of different architectures. |
| **Stakeholder** | An individual, team, or organization with interests in, or concerns relative to, the outcome of the architecture. |
| **Concern** | A key interest that is materially important to a stakeholder in the architecture. |
| **View** | A representation of a system from the perspective of a related set of concerns. |
| **Viewpoint** | A specification of the conventions for constructing and using a view. Defines the perspective from which a view is taken. |

---

## Architecture Development Method (ADM)

| Term | Definition |
|------|-----------|
| **Architecture Development Method (ADM)** | TOGAF's core, iterative method for developing enterprise architecture through a series of defined phases. |
| **ADM Phase** | A defined stage in the ADM cycle (Preliminary, A through H, plus Requirements Management). |
| **Architecture Vision** | A high-level, aspirational view of the end architecture, created in Phase A to communicate the value proposition. |
| **Request for Architecture Work** | A formal document that triggers the start of an ADM cycle, typically from a sponsoring organization. |
| **Statement of Architecture Work** | A document defining the scope and approach of the architecture project, serving as a contract between the architect and the sponsor. |
| **Architecture Principles** | General rules and guidelines intended to be enduring and seldom amended, that inform and support the way in which the organization fulfills its mission. |
| **Gap Analysis** | A technique used in ADM phases to identify differences between the baseline and target architectures. |

---

## Architecture Domains

| Term | Definition |
|------|-----------|
| **Business Architecture** | The business strategy, governance, organization, and key business processes. Developed in Phase B. |
| **Data Architecture** | The structure of an organization's logical and physical data assets and data management resources. Part of Phase C. |
| **Application Architecture** | A blueprint for the individual application systems to be deployed, their interactions, and their relationships to core business processes. Part of Phase C. |
| **Technology Architecture** | The logical software and hardware capabilities required to support the deployment of business, data, and application services. Developed in Phase D. |
| **Information Systems Architecture** | The combined data architecture and application architecture. Addressed in Phase C. |

---

## Architecture Content

| Term | Definition |
|------|-----------|
| **Deliverable** | A formally defined, contractually specified work product. Examples: Architecture Definition Document, Architecture Roadmap. |
| **Artifact** | A specific type of architectural work product that describes an aspect of the architecture. Three types: catalogs, matrices, diagrams. |
| **Catalog** | An artifact that lists things — e.g., an Application Portfolio Catalog listing all applications. |
| **Matrix** | An artifact showing relationships between things — e.g., an Application/Data matrix showing which applications use which data entities. |
| **Diagram** | An artifact that visually represents architecture — e.g., a Business Process Diagram. |
| **Building Block** | A potentially reusable component of enterprise capability. |
| **Architecture Building Block (ABB)** | A building block that captures architecture requirements — defines *what* is needed. |
| **Solution Building Block (SBB)** | A building block representing a specific solution — defines *how* a requirement is met (product, component, implementation). |

---

## Enterprise Continuum & Repository

| Term | Definition |
|------|-----------|
| **Enterprise Continuum** | A classification system for architecture and solution assets, ranging from generic (Foundation) to specific (Organization-Specific). |
| **Architecture Repository** | A storage facility for all architecture assets, reference materials, and standards. Organized according to the Enterprise Continuum. |
| **Reference Architecture** | A generic architecture that provides a template or blueprint for a specific domain or technology area. |
| **Foundation Architecture** | The most generic level of the Enterprise Continuum — universal patterns applicable across all industries. |
| **Common Systems Architecture** | Systems-level architecture patterns shared across multiple industries. |
| **Industry Architecture** | Architecture patterns specific to a particular industry (e.g., banking, healthcare, telecom). |

---

## Governance & Capability

| Term | Definition |
|------|-----------|
| **Architecture Governance** | The practice and orientation by which enterprise architectures are managed and controlled across the organization. |
| **Architecture Board** | A cross-organizational body responsible for architecture governance, establishing standards, and resolving conflicts. |
| **Architecture Compliance** | The process of ensuring that implementations adhere to the defined enterprise architecture. |
| **Architecture Contract** | A formal agreement between a development team and the architecture governance body, specifying deliverables, quality, and conformance. |
| **Architecture Capability** | An organization's demonstrated ability to create, maintain, and govern enterprise architecture. |
| **Architecture Maturity** | An assessment of how well-developed an organization's architecture capability is. |

---

## Transition & Migration

| Term | Definition |
|------|-----------|
| **Baseline Architecture** | The existing architecture at the start of an ADM cycle — the "as-is" state. |
| **Target Architecture** | The desired future architecture — the "to-be" state. |
| **Transition Architecture** | An intermediate architecture that bridges the baseline and target, representing a planned stage of migration. |
| **Work Package** | A set of related work items that can be delivered as a unit, used in migration planning. |
| **Architecture Roadmap** | A time-sequenced list of work packages showing the planned progression from baseline to target architecture. |
| **Implementation and Migration Plan** | A detailed plan for moving from the current to the target architecture, including schedules, resources, and costs. |

---

## Key Takeaways

- TOGAF terminology is precise — using the correct terms ensures clear communication across architecture stakeholders
- **Architecture vs. Solution Building Blocks (ABBs vs. SBBs)** is a critical distinction: ABBs define *what*; SBBs define *how*
- **Baseline → Transition → Target** describes the architecture journey from current to future state
- The **Enterprise Continuum** classifies reusable assets from generic to organization-specific
- Understanding these terms is essential for TOGAF certification exams

## Cross-References

- Related: [ITIL Key Terminology](../ITSM/01_foundation/03_key_terminology.md)
- Related: [COBIT Key Terminology](../COBIT/01_foundation/)
- Previous topic: [Core Concepts](./02_core_concepts.md)

## Sources

- The Open Group — TOGAF Standard, 10th Edition: Glossary
- The Open Group — [TOGAF Definitions](https://pubs.opengroup.org/togaf-standard/)
- Visual Paradigm — "TOGAF Key Terminology Guide"
