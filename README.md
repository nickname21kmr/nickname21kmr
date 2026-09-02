# Data Analytics · Data Systems · Applied AI

I build evidence-first analytics systems with explicit metric definitions, safe data access, reproducible evaluation, and clear human-review boundaries.

## Featured work

### [AgentFlow / HiveMind — AutoGen Integration](https://github.com/Emiyaaaaa/HiveMind)

Contributed an AutoGen adapter to a 1k+ star upstream multi-agent runtime. The contribution was merged into upstream `main` and covers single-agent and team execution, streaming and tool-event translation, documentation, and unit tests.

[Merged PR #80](https://github.com/Emiyaaaaa/HiveMind/pull/80) · [Upstream implementation](https://github.com/Emiyaaaaa/HiveMind/blob/main/integrations/autogen/src/agentflow_autogen/adapter.py) · [Unit tests](https://github.com/Emiyaaaaa/HiveMind/tree/main/integrations/autogen/tests) · [Integration guide](https://github.com/Emiyaaaaa/HiveMind/blob/main/integrations/autogen/README.md)

`Python` · `AutoGen` · `Agent integration` · `Testing`

### [GameOps Investigator](https://github.com/nickname21kmr/gameops-investigator)

A reproducible game-operations investigation agent with metric contracts, read-only SQL/MCP tools, cohort comparison, anomaly detection, and citation-checked reports.

[Demo](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/demo.gif) · [Architecture](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/architecture.png) · [Safety boundary](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/SECURITY.md) · [40-case evaluation set](https://github.com/nickname21kmr/gameops-investigator/blob/main/evals/cases.jsonl)

`Python` · `SQL` · `Pandas` · `SQLite` · `Streamlit` · `Plotly` · `MCP`

**Validation:** 17 automated tests · 40/40 deterministic evaluation cases · explicit safety and evidence checks

### [FGO JP LiveOps Public-Data Analysis](https://github.com/nickname21kmr/fgo-liveops-public-data-analysis)

An evidence-first LiveOps case study that models public attention without relabeling it as DAU, retention, revenue, or causal uplift. It combines event-master governance, a blocked 2022–2025 model evaluation, residual anomaly review, and an internal data-product design.

[Case study](https://github.com/nickname21kmr/fgo-liveops-public-data-analysis/blob/main/docs/case_study.md) · [29-page report](https://github.com/nickname21kmr/fgo-liveops-public-data-analysis/blob/main/report/FGO_JP_LiveOps_Public_Data_Case_Study_CN.pdf) · [Reproducible core](https://github.com/nickname21kmr/fgo-liveops-public-data-analysis/tree/main/src) · [Evidence boundary](https://github.com/nickname21kmr/fgo-liveops-public-data-analysis/blob/main/config/analysis_source_policy.json)

`Python` · `Pandas` · `NumPy` · `SciPy` · `Time series` · `Data product`

**Validation:** 2022–2023 train · 2024 model selection/calibration · untouched 2025 test · 10 automated checks in CI

### [Event Quality Gate](https://github.com/nickname21kmr/event-quality-gate)

A zero-runtime-dependency data contract and quality gate for JSONL event streams. It validates records line by line, enforces schema and business rules, and produces deterministic JSON, Markdown, or text reports with CI-ready exit codes.

[Contract example](https://github.com/nickname21kmr/event-quality-gate/blob/main/examples/contracts/liveops-event-v1.json) · [Validation engine](https://github.com/nickname21kmr/event-quality-gate/blob/main/src/event_quality_gate/validator.py) · [Regression tests](https://github.com/nickname21kmr/event-quality-gate/tree/main/tests) · [Roadmap](https://github.com/nickname21kmr/event-quality-gate/blob/main/ROADMAP.md)

`Python` · `Data contracts` · `Data quality` · `JSONL` · `CLI` · `GitHub Actions`

**Validation:** 10 automated tests · Python 3.11/3.12/3.13 CI · passing and failing quality-gate fixtures

### [EPUB Studio](https://github.com/nickname21kmr/epub-studio)

A zero-dependency, local-first browser tool for arranging text and images into EPUB 3 books, with project save/restore and structural validation.

[EPUB/ZIP core](https://github.com/nickname21kmr/epub-studio/blob/main/epub-core.js) · [Validation tests](https://github.com/nickname21kmr/epub-studio/tree/main/tests) · [Project README](https://github.com/nickname21kmr/epub-studio#readme)

`JavaScript` · `HTML` · `CSS` · `EPUB 3`

## Working principles

- Define metrics and evidence requirements before presenting conclusions.
- Keep analytical access read-only, bounded, and auditable.
- Separate deterministic validation from model performance claims.
