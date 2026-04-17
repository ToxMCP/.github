# ToxMCP

**ToxMCP** is a suite of **guardrailed, auditable MCP servers** for computational toxicology, exposure science, mechanistic reasoning, and downstream kinetic workflows.

It is built for teams who want **structured scientific tools for agents** without giving up traceability, explicit assumptions, or professional reviewability.

## 🧭 Start Here

- **Suite hub:** [ToxMCP/toxmcp](https://github.com/ToxMCP/toxmcp)
- **Best first run:** [CompTox MCP](https://github.com/ToxMCP/comptox-mcp)
- **Public exposure module:** [Direct-Use Exposure MCP](https://github.com/ToxMCP/direct-use-exposure-mcp)
- **Preprint:** [bioRxiv DOI 10.64898/2026.02.06.703989](https://doi.org/10.64898/2026.02.06.703989)

## ✨ What Makes ToxMCP Different

- **Auditable by design** with explicit assumptions, provenance, and structured outputs.
- **MCP-native** so tools are usable from agent frameworks, notebooks, and orchestrated workflows.
- **Scientifically bounded** so each module is clear about what it does and does not claim.
- **Modular across domains** so exposure, hazard, ADMET, AOP, QSAR, and PBPK workflows can interoperate cleanly.

## 🧪 Public Modules

| Module | Best for | Status |
| --- | --- | --- |
| [CompTox MCP](https://github.com/ToxMCP/comptox-mcp) | EPA CompTox-backed identity, hazard, exposure, and bioactivity workflows | Public |
| [Direct-Use Exposure MCP](https://github.com/ToxMCP/direct-use-exposure-mcp) | Auditable deterministic exposure-scenario construction and PBPK-ready handoff | Public |
| [PBPK MCP](https://github.com/ToxMCP/pbpk-mcp) | Toxicokinetic simulation, qualification, and dossier-facing outputs | Public |
| [AOP MCP](https://github.com/ToxMCP/aop-mcp) | AOP discovery, mechanistic reasoning, and scientific draft support | Public |
| [O-QT MCP](https://github.com/ToxMCP/oqt-mcp) | OECD QSAR Toolbox automation, grouping, read-across, and reports | Public |
| [ADMETlab MCP](https://github.com/ToxMCP/admetlab-mcp) | Rapid ADMET utility workflows and prediction support | Public |

## 🚧 Modules In Progress

| Module | Intended focus |
| --- | --- |
| `Dietary Exposure MCP` | Food-mediated oral exposure and dietary intake workflows |
| `Environmental Fate MCP` | Release, transport, concentration, and multimedia exposure surfaces |
| `Bioactivity-PoD MCP` | Bioactivity-to-point-of-departure workflows |

## 🔎 Recommended Entry Points

- Start with **CompTox MCP** if you want the most recognizable toxicology data integration first.
- Use **Direct-Use Exposure MCP** when you need a reviewable exposure object with explicit provenance and fit-for-purpose framing.
- Add **PBPK MCP** when the workflow needs internal-dose translation or TK simulation.
- Add **AOP MCP** or **O-QT MCP** when you need mechanistic or QSAR-centered reasoning layers.

## 📚 Acknowledgements / Origins

ToxMCP was developed, in part, in the context of the **VHP4Safety** project and related
research and engineering efforts in computational toxicology and next-generation risk
assessment.

Funding: Dutch Research Council (NWO) — `NWA.1292.19.272` (`NWA` programme)

This suite integrates with third-party data sources and services, including EPA CompTox,
ADMETlab, AOP resources, OECD QSAR Toolbox, and Open Systems Pharmacology. Those upstream
resources are owned and governed by their respective providers, and users remain responsible
for meeting the access, API key, rate limit, and license or EULA requirements described by
each module.

- [VHP4Safety](https://github.com/VHP4Safety)
- [Suite hub and docs](https://github.com/ToxMCP/toxmcp)
- [Preprint](https://doi.org/10.64898/2026.02.06.703989)

If you want the best overview of the current public surface, start with the [ToxMCP suite repo](https://github.com/ToxMCP/toxmcp).
