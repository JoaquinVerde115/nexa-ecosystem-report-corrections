<div align="center">

<br/>

<img src="https://raw.githubusercontent.com/upc-pre-202610-1asi0730-12242-king/nexa-website/main/docs/assets/nexa-logo.svg" alt="Nexa Logo" width="160"/>
<h2>Nexa B2B Cold-Chain Logistics Platform</h2>
<p><strong>Real-Time Visibility, Cold-Storage Traceability, Routing & B2B Billing</strong></p>

<div>

[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://daringfireball.net/projects/markdown/)
[![Docs-as-Code](https://img.shields.io/badge/Docs--as--Code-Academic-2563EB?style=for-the-badge)](https://en.wikipedia.org/wiki/Documentation_as_code)
[![UPC](https://img.shields.io/badge/UPC-Ingenieria%20Software-CE1126?style=for-the-badge)](https://www.upc.edu.pe)
[![GitFlow](https://img.shields.io/badge/GitFlow-Academic%20Traceability-38BDF8?style=for-the-badge)](https://nvie.com/posts/a-successful-git-branching-model/)
[![Milestone](https://img.shields.io/badge/Academic%20Report-AV2%20Documentation%20Review-22C55E?style=for-the-badge)](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-ecosystem-report)

</div>

<br/>

</div>

---

## Academic Deliverable

| Field | Value |
|---|---|
| Course | 1ASI0730 Aplicaciones Web |
| Academic Term | 2026-10 |
| Startup | KING |
| Product | Nexa |
| Current Milestone | AV2 |
| Report Format | Markdown / Docs-as-Code |
| Main Output | Final Project Documentation Report |

---

## Visual Report Architecture & Chapters

The academic report is divided into five core chapters, mapping progress from B2B business discovery to controlled implementation evidence:

| Chapter | Purpose | Structural Files | Key Rubric Evidence |
| :--- | :--- | :--- | :--- |
| **Chapter 1: Introduction** | Startup Profile & Solution Overview | `1-1-startup-profile.md`, `1-2-solution-profile.md` | Lean UX hypothesis, solution canvas, target segments. |
| **Chapter 2: Elicitation** | Customer Research & Needfinding | `2-2-interviews.md`, `2-4-big-picture-event-storming.md` | User Personas, Big Picture EventStorming, ubiquitous language. |
| **Chapter 3: Specification** | B2B Requirements Specification | `3-1-user-stories.md`, `3-3-product-backlog.md` | User stories, Gherkin scenarios, impact mapping, prioritized product backlog. |
| **Chapter 4: Product Design** | UX Prototyping & DDD Tactical Architecture | `4-4-web-applications-ux-ui-design.md`, `4-8-database-design.md` | Figma wireframes and mockups, C4 model, database design. |
| **Chapter 5: Implementation** | SCM, Validation & Deployment | `5-1-software-configuration-management.md`, `5-2-landing-page-services-and-applications-implementation.md` | GitFlow evidence, release traceability, Render deployment notes, pending validation evidence. |

---

## The King Team & Domain Ownership

Consistent with professional academic collaboration, each B2B sub-domain context is assigned to primary engineering owners:

| Team Member | GitHub Identity | Primary Responsibility | Email |
| :--- | :--- | :--- | :--- |
| **Joaquín Verde** | [JoaquinVerde115](https://github.com/JoaquinVerde115) | Warehouse & Cold-Storage Monitoring Bounded Context | `u20241a054@upc.edu.pe` |
| **Gino Torrejón** | [R0obxdnt-bit](https://github.com/R0obxdnt-bit) | Product Catalog & Customer Portals Bounded Context | `u202416289@upc.edu.pe` |
| **César Marín** | [Cmarin2802](https://github.com/Cmarin2802) | Logistics, Routing & Shipment Dispatch Bounded Context | `cesarmarin2802@gmail.com` |
| **Gerard Rojas** | [GerardRojasMancilla](https://github.com/GerardRojasMancilla) | Invoicing Business Documents Bounded Context | `u202413142@upc.edu.pe` |
| **Diego Sandoval** | [DiegoS284](https://github.com/DiegoS284) | Sales, Purchase Orders & Report Coordination | `diego64g284@gmail.com` |

---

## Nexa Visual Identity Color System

| Token | Hex Code | Visual Preview | Usage |
| :--- | :---: | :---: | :--- |
| **Nexa Blue** | `#2563EB` | ![#2563EB](https://img.shields.io/badge/%20-2563EB-2563EB?style=flat-square) | Primary actions, headings, and key UI markers. |
| **Ice Blue** | `#38BDF8` | ![#38BDF8](https://img.shields.io/badge/%20-38BDF8-38BDF8?style=flat-square) | Primary highlights, accent bars, and cold markers. |
| **Navy Contrast** | `#0F172A` | ![#0F172A](https://img.shields.io/badge/%20-0F172A-0F172A?style=flat-square) | Dark backgrounds, sidebar menus, and solid text. |
| **Slate Gray** | `#64748B` | ![#64748B](https://img.shields.io/badge/%20-64748B-64748B?style=flat-square) | Secondary descriptions and meta indicators. |
| **Ice White** | `#FFFFFF` | ![#FFFFFF](https://img.shields.io/badge/%20-FFFFFF-FFFFFF?style=flat-square) | Surface layouts and high contrast text. |

---

## PDF Generation & Local Builds

This repository is optimized for Pandoc and XeLaTeX. The document can be built locally into a PDF:

```bash
bash scripts/build-pdf.sh
```

Generated PDFs are expected to be stored as GitHub Actions artifacts when the report build workflow is executed.

---

## Nexa Repository Navigation Matrix

Below is the repository mapping for the Nexa ecosystem, tracking purpose, versions, and deployment evidence at the AV2 documentation review cut:

| Repository | Purpose | AV2 Status / Version | Links |
| :--- | :--- | :---: | :--- |
| **Nexa Report** | Academic report, product research, requirements elicitation, architecture documentation, implementation evidence and annexes. | `v3.0.0` documentary release for the AV2 academic report, consolidating evidence, annexes, version history, collaboration, implementation and delivery preparation. | [Repo](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-ecosystem-report) \| [PDF Build Actions](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-ecosystem-report/actions) |
| **Nexa Website** | Public B2B landing website and product value entry point. | `v3.0.0` | [Repo](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-website) \| [Live Deployment](https://upc-pre-202610-1asi0730-12242-king.github.io/nexa-website/) |
| **Nexa WebApp** | Single-page operational frontend for inventory, dispatch, orders, catalog, IAM and invoicing workflows. | `v2.0.0` | [Repo](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-webapp) \| [Render Deployment](https://nexa-webapp.onrender.com) |
| **Nexa Platform** | ASP.NET Core Web API with EF Core, PostgreSQL persistence configuration and Render deployment setup for the AV2 controlled backend cut. | `v1.0.0` | [Repo](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-platform) \| [Render API](https://nexa-platform-api.onrender.com) |

> Note. The AV2 ecosystem closeout is documented with `nexa-ecosystem-report v3.0.0`, `nexa-website v3.0.0`, `nexa-platform v1.0.0` and `nexa-webapp v2.0.0`. The Render WebApp and Platform API URLs are recorded as controlled academic deployment evidence, not as a declaration of final production operation.
