# Awesome-Dispatch-Management

## Top Dispatch Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Field Service Dispatch, Technician Scheduling & Work Order Management*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Dispatch Management**. These tools help field service businesses assign jobs to technicians, optimize routes, track work orders, and manage the full lifecycle from customer call to invoicing.



**Examples** include ServiceTitan, Housecall Pro, Jobber, Workiz, Zuper, FieldPulse, Commusoft, FieldEdge, FieldEZ, and Kickserv (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom dispatch boards, and transparent field operations — ideal for HVAC, plumbing, electrical, and general service businesses seeking vendor independence. The open-source ecosystem is anchored by **open-fieldservice** (self-hostable scheduler with dispatch board), **Nexus Field Service** (framework-agnostic engine), and **Resgrid Core** (CAD for first responders), with strong coverage in CMMS platforms and ERPNext integrations.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceTitan](https://www.servicetitan.com/)**  

  Enterprise-grade field service platform for HVAC, plumbing, and electrical contractors. The industry standard for established operations with $5M+ revenue, handling complex dispatch, maintenance contracts, and multi-location operations . Pricing ranges from $100–400 per user/month .



- **[Housecall Pro](https://www.housecallpro.com/)**  

  Popular field service management platform for small to mid-sized home service businesses. Competes directly with Jobber, offering scheduling, dispatching, GPS tracking, invoicing, and credit card processing . Pricing starts around $79–279 per user/month .



- **[Jobber](https://getjobber.com/)**  

  Leading field service management software for SMEs with 5–30 technicians. Known for fast setup, low learning curve, and predictable pricing ($69–279/user/month) . Covers scheduling, dispatching, invoicing, and customer communication .



- **[Workiz](https://www.workiz.com/)**  

  Field service management platform particularly popular for locksmith and cleaning businesses. Pricing $65–198 per user/month . Features cloud-based invoicing, scheduling, SMS messaging, and CRM .



- **[Zuper](https://www.zuper.co/)**  

  AI-powered field service management platform targeting emerging markets including India and Africa. Pricing $35–99 per user/month . Features automated scheduling, dispatching, route optimization, and mobile field execution .



- **[FieldPulse](https://www.fieldpulse.com/)**  

  All-in-one field service platform with scheduling, dispatching, estimating, invoicing, and customer management (CRM) .



- **[Commusoft](https://www.commusoft.co.uk/)**  

  Field service management software for service contractors with job management, scheduling, and invoicing.



- **[FieldEdge](https://www.fieldedge.com/)**  

  Field service management platform designed for residential HVAC, plumbing, and electrical contractors. Supports 30-day deployment for small platforms and integrates natively with QuickBooks .



- **[FieldEZ](https://www.fieldez.com/)**  

  Field service management software with scheduling, dispatching, and mobile workforce management.



- **[Kickserv](https://www.kickserv.com/)**  

  Field service software providing sales, estimates, job tracking, and invoicing for mobile field service teams .



## Open-Source GitHub Projects



- **[open-fieldservice](https://github.com/clawnify/open-fieldservice)**  

  Open-source, self-hostable field-service scheduler positioned as an alternative to ServiceTitan or Jobber for pest control, HVAC, plumbing, and similar industries . Built with Preact + TypeScript + Vite on the front end, a Hono REST API on the back, and Cloudflare D1 for storage. Ships with the full back office: jobs, customer CRM, technicians, invoices, materials, and a weekly calendar. The **Atlas** fork adds a visual reskin and a **Dispatch board** — technician rows crossed with a 7am–7pm timeline where unassigned jobs sit in a left rail and drag-and-drop assigns and schedules them in one motion .



- **[Nexus Field Service](https://packagist.org/packages/azaharizaman/nexus-field-service)**  

  Framework-agnostic field service management engine for work orders, technician dispatch, mobile job execution, service contracts, and SLA tracking . Provides work order lifecycle management (NEW → SCHEDULED → IN_PROGRESS → COMPLETED → VERIFIED), intelligent technician assignment based on skills, proximity, and capacity, service contract management with SLA deadline tracking, mobile job execution with offline sync, parts consumption with van stock waterfall logic, and customer signature capture. Three tiers: Basic (manual assignment), Service Contracts (preventive maintenance automation), and Enterprise (ML-powered assignment, VRP route optimization, cryptographic timestamp signing) .



- **[Resgrid Core](https://github.com/Resgrid/Core)**  

  Complete open-source computer aided dispatch (CAD), personnel, shift management, AVL, and emergency management platform powering Resgrid.com . Features personnel management with certifications and status, unit support for apparatus and teams, computer aided dispatch for creating calls/incidents and dispatching personnel, duty shift system with signup shifts and switch trading, inventory management, mobile apps for Google Play and Apple App Store, and a full API . Apache-2.0 licensed. While designed for first responders, its dispatch and scheduling architecture is adaptable for field service operations .



- **[FSM for ERPNext](https://github.com/github.com/fsm)**  

  100% open-source Field Service Management app for ERPNext — a simple, modern, and powerful solution designed to manage end-to-end field service operations . Integrates natively with ERPNext's accounting, inventory, and CRM modules.



- **[Geoclarity](https://github.com/babupriyavrat/Geoclarity)**  

  Open-source Field Service Management System intended to run on your own enterprise without external vendor requirements . Includes mobile Android code (built in Eclipse) and web interface code under RoofZouk-1.0. Designed for enterprises that want full control over customer-centric data .



- **[FieldOps AI](https://github.com/DanielDemoz/fieldops-ai)**  

  Smart scheduling, job costing, and field-service management platform for Canadian SMBs (construction, HVAC, electrical, plumbing) . FastAPI backend with Streamlit dashboard, OR-Tools routing for intelligent job scheduling, GPS-aware time tracking, inventory alerts, automated PDF invoicing, and Prophet-based cash-flow forecasting. SQLite for development with PostgreSQL-ready architecture .



- **[Field Service App (Laravel/Flutter)](https://github.com/topics/field-service-management)**  

  Field service management app for task tracking, reporting, and analytics built with Laravel and Flutter . Mobile-first design for technicians with backend for dispatch and reporting.



- **[Field Operations MCP](https://github.com/topics/field-service-management)**  

  Field operations over MCP (Model Context Protocol) with constraint-based scheduling on a deterministic solver, manageable from Claude or ChatGPT . Matches crews to jobs by location, skills, and availability for booking, work orders, dispatch, CRM, and fleet management (HVAC, plumbing, electrical, home services).



- **[Desktop Field Service App](https://github.com/topics/field-service-management)**  

  Desktop field service management app with job board, wizard, draft auto-save, proof attachments, dispute/resolve workflow, and overdue detection. Built with Tauri v2, SvelteKit 5, and SQLite .



### Additional Strong Open-Source Options



- **Atlas CMMS** — Open-source CMMS with work orders, preventive maintenance, asset management, inventory control, and mobile app . Features work request system via QR code scanning, automated PM scheduling, and parts inventory tracking. GPLv3 licensed with self-hosted or cloud options .

- **Shesha Framework** — Open-source low-code framework for .NET developers that can be configured to build field service management applications with drag-and-drop form builder, dynamic CRUD APIs, and admin panels . GPLv3 or Apache 2.0 licensed depending on version .

- **Platelet** — Offline-first, cloud-backed dispatch software for couriers and coordinators, developed for Blood Bikers in the UK. Can be deployed to AWS using Amplify or used fully offline .



**Frameworks for building custom dispatch solutions**: Combine **open-fieldservice** for a self-hosted scheduler with a drag-and-drop dispatch board, **Nexus Field Service** for framework-agnostic work order and SLA engine capabilities, and **FSM for ERPNext** for ERP-integrated field operations. Use **FieldOps AI** for route optimization (OR-Tools) and cash-flow forecasting. For first-responder-grade CAD, **Resgrid Core** provides battle-tested dispatch and personnel management. Note that true enterprise dispatch platforms with complex maintenance contract hierarchies, multi-location operations, and deep QuickBooks integration remain primarily commercial territory; open-source stacks provide strong scheduling, dispatch board, and work order foundations that require integration for complete field service management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Dispatch management tools handle customer data, service histories, and payment information. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA).

- Open-source dispatch platforms are significantly less mature than commercial offerings for complex HVAC/plumbing service businesses. Evaluate gaps in maintenance contract management, multi-location hierarchies, and accounting integrations before deployment.

- The open-source ecosystem provides strong dispatch boards, work order engines, and route optimization foundations, but full enterprise field service management with complex contract hierarchies and deep accounting integration remains primarily a commercial offering.



---



**Made for field service managers, dispatchers, HVAC/plumbing contractors, and service business operators.**  

Let's make dispatch management more open, transparent, and efficient.
