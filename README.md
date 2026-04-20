# Elite Oracle

**Elite Oracle** is a reusable Codex skill and colleague profile that distills public output patterns from elite strategy consulting firms, venture capital firms, analyst firms, investment banks, asset managers, and macro research institutions into a practical strategic reasoning system.

It is designed for people who want decision-ready analysis: founders, operators, investors, researchers, product strategists, analysts, consultants, and builders.

> This project does not impersonate any real firm and does not claim access to proprietary methods or private research. It is a synthetic analytical operating system built from public-facing patterns.

## Keywords

strategy, consulting, McKinsey, BCG, Bain, venture capital, a16z, Sequoia, Y Combinator, Gartner, Forrester, IDC, Goldman Sachs, JPMorgan, market research, investment memo, startup thesis, executive brief, macro analysis, trend analysis, AI strategy, business frameworks, decision intelligence

## What It Does

Elite Oracle helps turn vague questions into rigorous analysis:

1. What is changing?
2. Why now?
3. Who wins and who loses?
4. What evidence supports this?
5. What is the hidden constraint?
6. What should we do next?
7. What would change our mind?

It combines several public-output archetypes:

- **McKinsey / MGI style:** executive decomposition, issue trees, economic impact, productivity, survey-backed insights.
- **BCG / Henderson Institute style:** competitive advantage, scenarios, strategic imagination, organizational capability.
- **Bain style:** customer economics, private-equity discipline, implementation KPI rigor, profit-pool practicality.
- **Big Four / Accenture style:** enterprise transformation, operating model, governance, risk, regulation, adoption readiness.
- **a16z / Sequoia / YC / First Round style:** frontier technology, startup wedge, market creation, distribution, founder truth.
- **Gartner / Forrester / IDC / CB Insights / PitchBook style:** taxonomy, maturity curves, vendor landscapes, adoption timing, market data.
- **Goldman Sachs / JPMorgan / Morgan Stanley / BofA / Citi / UBS / BlackRock / Bridgewater style:** macro setup, capital flows, valuation, M&A, market structure, portfolio implications.

## Core Framework: 12-Lens Matrix

Use the relevant subset of these lenses for each problem:

1. Market structure: size, growth, concentration, profit pools, bottlenecks.
2. Customer reality: urgent pain, budget owner, switching cost, adoption friction.
3. Technology readiness: capability curve, cost curve, reliability, interoperability.
4. Business model: unit economics, monetization, margin structure, recurrence.
5. Competitive advantage: data, distribution, talent, brand, regulation, workflow lock-in.
6. Capital markets: funding availability, valuation pressure, M&A paths, exit windows.
7. Operating model: org design, process change, incentives, governance, execution rhythm.
8. Risk and regulation: compliance, security, reputation, geopolitical exposure.
9. Timing: maturity curve, hype cycle, adoption S-curve, trigger events.
10. Scenario logic: base case, upside, downside, discontinuity.
11. Metrics: leading indicators, lagging indicators, threshold numbers, failure signals.
12. Narrative: the simple story that explains why this matters now.

## Output Modes

Elite Oracle can produce:

- **Executive Brief:** for management decisions and board-level synthesis.
- **VC Thesis:** for startup ideas, frontier technology, and market creation.
- **Consulting Deck Narrative:** for slide storylines and strategic recommendations.
- **Analyst Landscape:** for vendor, category, technology, or market comparisons.
- **Investment / Macro Memo:** for markets, M&A, valuation, capital allocation, and industry outlooks.

## Repository Structure

```text
.
+-- README.md
+-- README.ja.md
+-- README.zh-CN.md
+-- skill/
|   +-- SKILL.md
+-- colleague/
|   +-- work.md
|   +-- persona.md
|   +-- meta.json
+-- knowledge/
|   +-- source_digest.md
|   +-- elite_output_library.md
+-- examples/
    +-- prompts.md
```

## How To Use

### In Codex

Copy `skill/SKILL.md` into your Codex skills directory:

```text
~/.codex/skills/elite-oracle/SKILL.md
```

Then invoke it in a prompt:

```text
Use elite-oracle to analyze whether agentic AI will reshape the enterprise SaaS market.
```

### As a Reusable Colleague Profile

Read the colleague files:

- `colleague/work.md` for analytical methods and standards.
- `colleague/persona.md` for tone, collaboration style, and challenge behavior.
- `knowledge/source_digest.md` for the distilled source logic.

Then ask any capable AI model to follow those instructions.

## Example Prompts

```text
Use Elite Oracle to create a VC thesis for vertical AI agents in healthcare operations.
```

```text
Use Elite Oracle to build a consulting-style market map for AI coding tools.
```

```text
Use Elite Oracle to write an investment memo on whether data center power constraints are now the bottleneck for AI growth.
```

More examples: [examples/prompts.md](examples/prompts.md)

## 日本語概要

**Elite Oracle（エリートオラクル）** は、トップ戦略コンサル、トップVC、調査会社、投資銀行、マクロリサーチ機関の公開アウトプットに見られる思考パターンを蒸留した、再利用可能なCodexスキル兼コレグ（同僚）プロファイルです。

目的は、単なる情報収集ではなく、意思決定に使える分析を作ることです。市場分析、スタートアップ仮説、投資メモ、経営向けブリーフ、技術トレンドの整理、競争環境分析などに使えます。

詳しい日本語説明: [README.ja.md](README.ja.md)

## 中文简介

**Elite Oracle（精英神谕）** 是一个可复用的 Codex 技能与 AI 同事画像。它从顶级战略咨询公司、顶级风险投资机构、研究分析机构、投资银行、资产管理机构和宏观研究机构的公开输出中，提炼出一套可执行的战略分析操作系统。

它的目标不是简单总结信息，而是帮助用户形成可以用于决策、投资、创业、产品战略和管理汇报的高质量分析。

中文详细说明: [README.zh-CN.md](README.zh-CN.md)

## Source Library

The source library lists 180 public output hubs, reports, and research sources used as inspiration for the distillation:

[knowledge/elite_output_library.md](knowledge/elite_output_library.md)

## License

MIT License. See [LICENSE](LICENSE).
