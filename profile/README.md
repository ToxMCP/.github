# ToxMCP

ToxMCP is an open-source suite of chemical-safety tools for AI assistants. Its modules return structured, source-linked results with visible uncertainty and screening limitations.

Each module uses the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP), an open standard that lets compatible AI assistants call external tools. You can use a module directly, combine several modules in a workflow, or review the code and evidence without using an AI assistant.

## Start here

- [ToxMCP suite guide](https://github.com/ToxMCP/toxmcp) — understand the modules and choose a starting point
- [Computational Toxicology (CompTox) tools](https://github.com/ToxMCP/comptox-mcp) — try source-linked chemical identity and screening evidence from the U.S. Environmental Protection Agency
- [Preprint](https://doi.org/10.64898/2026.02.06.703989) — read the scientific background

## Public tools

- **Chemical identity and screening evidence:** [CompTox MCP](https://github.com/ToxMCP/comptox-mcp)
- **Exposure scenarios:** [Direct-Use Exposure MCP](https://github.com/ToxMCP/direct-use-exposure-mcp)
- **Environmental fate:** [Environmental Fate MCP](https://github.com/ToxMCP/environmental-fate-mcp)
- **Kinetics and internal dose:** [Physiologically Based Pharmacokinetic (PBPK) MCP](https://github.com/ToxMCP/pbpk-mcp)
- **Mechanistic pathways:** [Adverse Outcome Pathway (AOP) MCP](https://github.com/ToxMCP/aop-mcp)
- **Chemical grouping and read-across:** [Organisation for Economic Co-operation and Development (OECD) QSAR Toolbox MCP](https://github.com/ToxMCP/oqt-mcp), where QSAR means quantitative structure-activity relationship
- **Rapid property screening:** [ADMETlab MCP](https://github.com/ToxMCP/admetlab-mcp), covering absorption, distribution, metabolism, excretion, and toxicity

## What you should expect

- source links and provenance that can be reviewed by a person
- explicit assumptions, limitations, and uncertainty
- structured results that can move between compatible tools
- clear separation between screening evidence and stronger scientific conclusions

These tools support research and screening. A runnable model or returned result is not automatically scientifically qualified, clinically appropriate, or ready for a regulatory decision. Review important outputs independently and follow each upstream data provider's access, rate-limit, license, and attribution terms.

## Contributing and security

Contributions are welcome. Start with the repository that owns the tool you want to change and read its local guidance. Organization-wide defaults are available in our [contributing guide](../CONTRIBUTING.md) and [security policy](../SECURITY.md).

ToxMCP was developed in part through the [VHP4Safety](https://github.com/VHP4Safety) project and related computational-toxicology research. Funding included the Dutch Research Council (NWO), grant `NWA.1292.19.272`.
