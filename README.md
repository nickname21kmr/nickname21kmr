# Data Analytics · Data Systems · Applied AI

I build evidence-first analytics systems with explicit metric definitions, safe data access, reproducible evaluation, and clear human-review boundaries.

## Featured work

### [GameOps Investigator](https://github.com/nickname21kmr/gameops-investigator)

A reproducible game-operations investigation agent with metric contracts, read-only SQL/MCP tools, cohort comparison, anomaly detection, and citation-checked reports.

[Demo](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/demo.gif) · [Architecture](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/architecture.png) · [Safety boundary](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/SECURITY.md) · [40-case evaluation set](https://github.com/nickname21kmr/gameops-investigator/blob/main/evals/cases.jsonl)

`Python` · `SQL` · `Pandas` · `SQLite` · `Streamlit` · `Plotly` · `MCP`

**Validation:** 17 automated tests · 40/40 deterministic evaluation cases · explicit safety and evidence checks

### [AgentFlow / HiveMind — AutoGen Integration](https://github.com/Emiyaaaaa/HiveMind)

Contributed an AutoGen adapter to AgentFlow, a 1k+ star multi-agent runtime. The contribution was merged into upstream `main` and covers single-agent and team execution, streaming and tool-event translation, documentation, and unit tests.

[Merged PR #80](https://github.com/Emiyaaaaa/HiveMind/pull/80) · [Upstream implementation](https://github.com/Emiyaaaaa/HiveMind/blob/main/integrations/autogen/src/agentflow_autogen/adapter.py) · [Unit tests](https://github.com/Emiyaaaaa/HiveMind/tree/main/integrations/autogen/tests) · [Integration guide](https://github.com/Emiyaaaaa/HiveMind/blob/main/integrations/autogen/README.md)

`Python` · `AutoGen` · `Agent integration` · `Testing`

### [EPUB Studio](https://github.com/nickname21kmr/epub-studio)

A zero-dependency, local-first browser tool for arranging text and images into EPUB 3 books, with project save/restore and structural validation.

[EPUB/ZIP core](https://github.com/nickname21kmr/epub-studio/blob/main/epub-core.js) · [Validation tests](https://github.com/nickname21kmr/epub-studio/tree/main/tests) · [Project README](https://github.com/nickname21kmr/epub-studio#readme)

`JavaScript` · `HTML` · `CSS` · `EPUB 3`

## Working principles

- Define metrics and evidence requirements before presenting conclusions.
- Keep analytical access read-only, bounded, and auditable.
- Separate deterministic validation from model performance claims.
