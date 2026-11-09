<img src="assets/webmethods-dr-tile.png" alt="webMethods DR on Azure" width="160"/>

# webMethods 12.1 on Azure – Disaster Recovery Design v1.5

Scope: Integration Server, Universal Messaging, My webMethods Server, Azure SQL Database and Azure Key Vault, plus the Azure infrastructure they need.

Audience: technical managers and architects. Date: 9 Nov 2026 (Europe/Berlin).

| Document | Contents |
|---|---|
| [01-solution-design.md](01-solution-design.md) | Overview, executive summary, components, design choices and rationale, RPO/RTO, alternative paths, failover/failback, risks |
| [02-region-variant-australia.md](02-region-variant-australia.md) | Australia East (primary) / Australia Southeast (DR), New Zealand North option |
| [03-region-variant-paired-zonal.md](03-region-variant-paired-zonal.md) | Generic paired regions with zones in both (e.g. North Europe / West Europe) and how to choose regions |
| [azure-service-validation.xlsx](azure-service-validation.xlsx) / [.csv](azure-service-validation.csv) | Each Azure service used, the capability relied on, and the Microsoft doc that confirms it |
| [diagrams/](diagrams/) | draw.io sources (`.drawio`, editable in diagrams.net or draw.io Desktop) with exported PNG and SVG |

Status legend used in the documents: **Confirmed** = checked against IBM or Microsoft documentation (link given). **Not verified** = could not be confirmed from the docs; check before relying on it.

Diagram PNGs and SVGs have white backgrounds. Solid black arrows show active paths; dashed black arrows show failover-only paths. Editable `.drawio` sources are included.
