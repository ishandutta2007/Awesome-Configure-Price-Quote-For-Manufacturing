# Awesome-Configure-Price-Quote-For-Manufacturing

# Top Configure-Price-Quote (CPQ) for Manufacturing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Product Configuration, Pricing Engines, Quote Generation & Manufacturing Integration*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Configure-Price-Quote (CPQ)** in manufacturing. These tools help manufacturers handle complex product configurations, generate accurate pricing, and produce error-free quotes for configure-to-order (CTO) and engineer-to-order (ETO) environments.

**Examples** include Tacton CPQ, Epicor CPQ, Configure One, KBMax, DriveWorks, Logik.io, Experlogix, PROS Smart CPQ, Sofon, and Conga CPQ (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom configuration logic, and transparent pricing engines — ideal for manufacturers that need full control over their CPQ infrastructure without per-seat SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tacton CPQ](https://www.tacton.com/)**
  Specialist CPQ for complex manufacturing. Focuses on product configuration, pricing, and sales automation for engineer-to-order and configure-to-order environments. Gartner/ISG 2025 grade: B- (Performance 48.0%) .

- **[Epicor CPQ](https://www.epicor.com/)**
  CPQ module within Epicor's ERP ecosystem. Enables manufacturers to configure products, generate quotes, and integrate with production systems. ISG 2025 grade: B (Performance 53.4%) .

- **[Configure One](https://www.configureone.com/)**
  Web-based product configuration and CPQ software for manufacturers. Supports sales and production configurators with 3D visualization and ERP/CRM integration .

- **[KBMax](https://www.kbmax.com/)**
  CPQ platform focused on complex product configuration with 3D visualization. Popular in manufacturing for guided selling and quote generation.

- **[DriveWorks](https://www.driveworks.co.uk/)**
  Design automation and CPQ software for manufacturers. Enables configurable products with rule-based design generation and sales configurator output.

- **[Logik.io](https://www.logik.io/)**
  Headless, composable, API-first CPQ and product configuration engine. Powers guided configuration, pricing, and quoting for complex products across Salesforce CPQ/Commerce and headless frontends . ISG 2025 grade: B- (Performance 48.8%) .

- **[Experlogix](https://www.experlogix.com/)**
  CPQ and document automation for manufacturers. Provides product configurator, pricing engine, and quote generation integrated with Microsoft Dynamics. ISG 2025 grade: C++ (Performance 44.3%) .

- **[PROS Smart CPQ](https://www.pros.com/)**
  AI-driven CPQ platform with pricing optimization and guided selling. Focuses on B2B manufacturing and distribution. ISG 2025 grade: B++ (Performance 61.2%) .

- **[Sofon](https://www.sofon.com/)**
  CPQ and sales configuration platform for manufacturers. Handles complex product rules, pricing, and quote generation.

- **[Conga CPQ](https://conga.com/)**
  Enterprise CPQ platform with strong document generation and contract lifecycle management integration. ISG 2025 grade: B++ (Performance 63.7%) .

## Open-Source GitHub Projects

- **[Carbon](https://github.com/crbnos/carbon)**
  The open-source operating system for manufacturing. **ERP, MES, and QMS** with built-in **Configurator** for configure-to-order manufacturing. Features nested BoM, traceability, MRP, capacity planning, and MCP client/server integration. TypeScript monorepo with Docker deployment. **AGPL-3.0** (commercial license required for private deployments) . 

- **[Lotus](https://github.com/uselotus/lotus)**
  Open-source pricing and packaging infrastructure. While primarily for SaaS, it provides a flexible **pricing engine** that can be adapted for manufacturing quote generation. Supports usage-based pricing, plan management, experimentation, and integrations with payments and CRM. **MIT License** . Self-hosted via Docker.

- **[SwiftCPQ](https://github.com/ekky1328/SwiftCPQ)**
  Open-source, vendor-agnostic proposal tool designed as an accessible alternative to proprietary CPQ solutions like ConnectWise CPQ and Kaseya Quote Manager. Vue-based . 

- **[rule-lite](https://github.com/tejas821/rule-lite)**
  Tiny, dependency-free TypeScript engine for evaluating **JSON-defined conditional rules** (AND/OR/NOT + operators) — built for dynamic forms, feature flags, and **business rules** in enterprise apps. Framework-agnostic, ~1KB gzipped. Rules stored in JSON can be used to drive product configuration constraints and pricing logic . 

- **[datalogic-rs](https://github.com/GoPlasmatic/datalogic-rs)**
  Fast JSONLogic rules engine with bindings for Node.js, Python, Go, Java, .NET, PHP, and browser (WASM). Includes a **React visual rule builder and debugger** (`@goplasmatic/datalogic-ui`) for non-engineers to author rules. Use cases include **pricing logic, eligibility rules, fee schedules, and form validation** . 

- **[product-variants-core](https://lnkd.in/g7YQ4nzj)**
  Type-safe library for product configurators. Handles **variant generation**, **constraints** (e.g., "If A, then not B"), and **modifiers** for dynamic pricing updates. Designed for e-commerce and CPQ tools. Includes interactive playground. Open source, TypeScript . 

### Additional Strong Open-Source Options

- **Configuration Engines**: **rule-lite** (JSON rules, lightweight), **datalogic-rs** (multi-language, visual editor), **product-variants-core** (variant + constraint engine) .
- **Manufacturing Foundations**: **Carbon** (ERP/MES/QMS with built-in configurator) .
- **Pricing Infrastructure**: **Lotus** (pricing engine, adaptable for manufacturing) .
- **CPQ Frontend**: **SwiftCPQ** (Vue-based proposal tool) .

**Frameworks for building custom systems**: Combine **Carbon** for the manufacturing ERP/MES backbone with configurator, **rule-lite** or **datalogic-rs** for configuration constraint logic, **product-variants-core** for variant generation, and **Lotus** for pricing calculations. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CPQ platforms handle sensitive pricing and product data; ensure compliance with internal data policies and relevant regulations.
- **Open-source reality**: The open-source CPQ ecosystem for manufacturing is **still developing**. **Carbon** provides a manufacturing ERP/MES/QMS with a configurator module, but it is not a dedicated CPQ platform . **Rule engines** like `rule-lite` and `datalogic-rs` provide the constraint logic foundation but require significant integration work . For complex, production-grade CPQ requirements, commercial platforms (Tacton, Epicor, PROS) remain the primary choice.

---

**Made for manufacturing engineers, sales operations teams, product managers, and ERP administrators.**
Let's make configure-price-quote more open, transparent, and manufacturable.
