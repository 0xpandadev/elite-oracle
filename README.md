# Elite Oracle V2

**Deep multilingual research, signal aggregation, and elite strategy synthesis for founders, investors, operators, analysts, and builders.**

Elite Oracle V2 is a reusable agent skill that turns messy information into decision-grade insight. It combines public-output patterns from top strategy consultancies, venture capital firms, analyst houses, investment banks, asset managers, macro research shops, and management thinkers into a practical reasoning system.

It is not an impersonation of any firm. It does not claim proprietary access. It is a public-pattern-based analytical operating system.

## Languages

- [Japanese README](README.ja.md)
- [Chinese README](README.zh-CN.md)

## What Changed In V2

V2 upgrades Elite Oracle from a strategy synthesis skill into a deeper research and signal intelligence system.

New capabilities:

- multilingual research across English, Japanese, and Chinese when relevant
- official-source-first investigation
- GitHub, docs, filings, reports, X, Reddit, forums, and operator-signal awareness
- evidence aggregation before analysis
- actor maps, claim maps, issue trees, timelines, and contradiction lists
- top-VC-style trend sensing
- hidden bottleneck and control-point detection
- executive-grade recommendations with risks, KPIs, and failure signals

## What It Does

Elite Oracle helps answer:

1. What is changing?
2. Why now?
3. What is the deeper driver beneath the visible trend?
4. Who wins, who loses, and who gains control points?
5. What evidence supports this?
6. What contradicts it?
7. What should the decision-maker do next?
8. What would change our mind?

## Source Universe

Elite Oracle V2 can reason across:

- company sites, official blogs, product docs
- filings, annual reports, investor decks, earnings materials
- government, standards, regulatory, and court materials
- GitHub repos, changelogs, issues, RFCs, model cards, papers
- consulting reports, VC essays, analyst notes, investment bank public research
- reputable business, technology, financial, and trade media
- X, Reddit, Hacker News, forums, and expert operator posts

## Core Archetypes

Elite Oracle combines public-facing patterns from:

- strategy consulting: issue trees, MECE, market structure, operating model
- venture capital: why now, wedge, distribution, defensibility, category timing
- analyst firms: taxonomies, maturity curves, buyer criteria, adoption timing
- investment banks: capital flows, valuation, margin drivers, M&A paths
- macro and management research: systems dynamics, productivity, incentives, diffusion curves

## Output Modes

- Executive Brief
- VC Thesis
- Consulting Deck Narrative
- Analyst Landscape
- Investment / Macro Memo
- Deep Signal Map
- Market Map
- Board Memo

## Installation

### Codex

Copy the `skill/` folder to:

```text
~/.codex/skills/elite-oracle
```

Then restart Codex and invoke:

```text
$elite-oracle
```

### Manual Use

Use `skill/SKILL.md` as the core instruction file in any agent environment that supports skill-style workflows.

## Quick Start

```text
$elite-oracle

Analyze whether vertical AI agents will become a new enterprise software category.
Use official sources, VC essays, market reports, GitHub signals, and operator commentary.
Produce a VC thesis with hidden bottlenecks, control points, risks, and experiments.
```

## Repository Structure

```text
.
├── README.md
├── README.ja.md
├── README.zh-CN.md
├── skill/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   ├── assets/executive-report-template.md
│   └── references/
├── colleague/
│   ├── work.md
│   ├── persona.md
│   └── meta.json
├── knowledge/
│   ├── elite_output_library.md
│   ├── source_digest.md
│   └── v2_methodology.md
└── examples/
    └── prompts.md
```

## Safety And Integrity

Elite Oracle:

- does not impersonate McKinsey, BCG, Bain, a16z, Sequoia, Goldman Sachs, Gartner, or any other real institution
- does not claim access to private or proprietary methods
- labels assumptions, uncertainty, and inferred claims
- uses public patterns and user-provided sources only
- prioritizes decision usefulness over impressive-sounding prose

## SEO Keywords

AI strategy, elite research, VC thesis, market research, strategy consulting, McKinsey style analysis, BCG strategy, venture capital analysis, startup thesis, investment memo, analyst landscape, AI market map, deep research agent, signal intelligence, multilingual research, Codex skill, agent skill, business frameworks, decision intelligence.

## License

MIT License. See [LICENSE](LICENSE).
