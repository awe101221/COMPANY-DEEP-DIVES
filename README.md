# Company Deep Dives

A structured research repository containing independent knowledge bases for individual publicly traded companies.

## Organization

Each covered company has its own folder under `companies/`, identified by its primary stock ticker.

```text
companies/
├── MELI/
├── TICKER-2/
└── TICKER-3/
```

Every company folder contains its own research, financial history, KPI definitions, investment thesis, risks, source records, unresolved questions, and dated intelligence updates.

## Company folder standard

```text
companies/TICKER/
├── README.md
├── company-dossier.md
├── financial-history.md
├── kpi-dictionary.md
├── thesis-ledger.md
├── risk-register.md
├── source-ledger.md
├── open-questions.md
└── updates/
```

## Research rules

- Keep each company's research completely inside its assigned folder.
- Do not modify another company's knowledge base unless explicitly instructed.
- Cite material claims and include an as-of date for time-sensitive information.
- Preserve dated thesis changes rather than silently rewriting prior conclusions.
- Distinguish reported facts, management statements, estimates, calculations, and analyst inferences.
- Do not create updates when no substantive research has been completed.

## Current coverage

| Ticker | Company | Exchange | Status |
|---|---|---|---|
| MELI | MercadoLibre, Inc. | Nasdaq | Active |

## Using Cursor

### Interactive MELI analyst

1. Open this repository in Cursor.
2. Start a new Agent chat.
3. Type `/meli-analyst` and select the skill if Cursor shows a menu.
4. Ask any MercadoLibre research or investment question.

The specialist workflow lives in `.cursor/skills/meli-analyst/SKILL.md`. It tells Cursor to load the durable knowledge base in `companies/MELI/`, browse current evidence, challenge the thesis, and update the repository only when the work adds verified, reusable knowledge.

### Scheduled MELI research

Use Cursor Automation to keep the knowledge base current. The automation should use this short instruction:

> Read and follow `.cursor/skills/meli-analyst/SKILL.md`. Review `companies/MELI/` and perform an incremental MELI intelligence update since the last successful run. Use current primary sources, update only verified material changes, write only within `companies/MELI/`, and avoid a commit when nothing substantive changed.

The skill is the analyst's operating system; the automation is only the recurring trigger.

## Purpose

The repository is designed to create cumulative, auditable, company-specific institutional research that improves over time.
