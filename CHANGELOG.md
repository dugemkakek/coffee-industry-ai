# Changelog

All notable changes to the coffee-industry-ai skill are documented here.

Format: `[YYYY-MM-DD] Version X.X — Description`

---

## [2026-06-01] v2.0 — Major Refinement Release

### Added
- **Agent Roles section** — 6 scoped agent roles (Store Ops, Content, Research, Operations, Compliance, Archive) with routing table, inputs/outputs, trigger keywords, and escalation rules
- **Indonesian Origins** — Full profiles for 6 islands (Sumatra, Java, Sulawesi, Flores, Bali, Papua) with regional flavor summary table; detailed Giling Basah technical deep-dive
- **Indonesia Ops** — WhatsApp order parsing with Bahasa/English intent classification; WooCommerce API endpoints; order fulfillment checklist; IDR pricing guide
- **Indonesian Regulatory** — BPOM registration, SNI 01-3542:2019, MUI Halal certification, export/import requirements, HACCP food safety
- **Indonesia Roasting Notes** — Giling Basah behavior in roaster, per-origin charge temp/drying/DTR adjustments, troubleshooting table
- **Error & Fallback Playbook** — Per-agent error codes, fallback actions, and escalation rules for all 6 agents
- **CATALOG.md** — 18-SKU product reference with origin, process, roast level, weight options, IDR pricing, stock status
- **SCHEMAS.md** — Archive agent data models: CuppingLog, SeasonalPerformance, SupplierScorecard, ProductPerformance
- **Output Format Standards** — JSON schemas for cupping scores, supply chain status, sourcing recommendations
- **Trigger Keywords** — Bilingual (Bahasa/English) keyword list for skill activation

### Fixed
- QUICKREF pricing formula: $13/lb example now correct ($0.0059/g, $0.11/shot at 18g — was $1.01/g)
- QUICKREF ECAE ghost acronym removed entirely
- QUICKREF Light DTR harmonized to 20–25% (SCA-aligned, matches SKILL.md)
- QUICKREF Indonesia origin row expanded to 6 island profiles matching SKILL.md depth
- QUICKREF workflow step 3 stray Chinese character (`等待`) replaced with `await`
- README stray asterisk on SCA Score row
- README "Hermes agent profile" reference made generic
- AGENT_SOURCES.md Luke/Wing Trading AI references made generic
- SKILL.md Wing Trading AI internal reference made generic

### Changed
- SKILL.md overall structure reorganized to put Agent Roles early for discoverability
- QUICKREF origin table reorganized to group Indonesian islands together

---

## [2026-05-31] v1.0 — Initial Release

- SKILL.md core knowledge base (16 sections)
- QUICKREF.md one-page cheat sheet
- EXAMPLE_PROMPTS.md task templates
- AGENT_SOURCES.md (formerly REI_RESEARCH_DIGEST.md) — AI in coffee supply chain research
- README.md with repository structure and contribution guidelines