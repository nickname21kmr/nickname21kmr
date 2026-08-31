# Data Analytics · Data Systems · Applied AI

I build evidence-first analytics systems with explicit metric definitions, safe data access, reproducible evaluation, and clear human-review boundaries.

## Featured work

### [GameOps Investigator](https://github.com/nickname21kmr/gameops-investigator)
A reproducible game-operations investigation agent with metric contracts, read-only SQL/MCP tools, cohort comparison, anomaly detection, and citation-checked reports.

[Demo](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/demo.gif) · [Architecture](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/architecture.png) · [Safety boundary](https://github.com/nickname21kmr/gameops-investigator/blob/main/docs/SECURITY.md) · [40-case evaluation set](https://github.com/nickname21kmr/gameops-investigator/blob/main/evals/cases.jsonl)

`Python` · `SQL` · `Pandas` · `SQLite` · `Streamlit` · `Plotly` · `MCP`

> Verified locally: 17 automated tests and 40/40 deterministic offline cases. These validate tools, safety controls, replay, and evidence checks—not an LLM model score. The project uses synthetic data.

### [HiveMind / AgentFlow — invited upstream contribution](https://github.com/Emiyaaaaa/HiveMind/pull/79)
Invited by the project author to contribute an AutoGen adapter for AgentFlow. Implemented single-agent and team execution, streaming and tool-event translation, integration documentation, and unit tests; submitted as upstream PR #79.

[Pull request](https://github.com/Emiyaaaaa/HiveMind/pull/79) · [Adapter implementation](https://github.com/nickname21kmr/HiveMind/blob/feat/AutoGen/integrations/autogen/src/agentflow_autogen/adapter.py) · [Unit tests](https://github.com/nickname21kmr/HiveMind/blob/feat/AutoGen/integrations/autogen/tests/test_adapter.py) · [Integration guide](https://github.com/nickname21kmr/HiveMind/blob/feat/AutoGen/integrations/autogen/README.md)

`Python` · `AutoGen` · `Agent integration` · `Testing`

### [EPUB Studio](https://github.com/nickname21kmr/epub-studio)
A zero-dependency, local-first browser tool for arranging text and images into EPUB 3 books, with project save/restore and structural validation.

[EPUB/ZIP core](https://github.com/nickname21kmr/epub-studio/blob/main/epub-core.js) · [Validation tests](https://github.com/nickname21kmr/epub-studio/tree/main/tests) · [Project README](https://github.com/nickname21kmr/epub-studio#readme)

`JavaScript` · `HTML` · `CSS` · `EPUB 3`

## Working principles

- Define metrics and evidence requirements before presenting conclusions.
- Keep analytical access read-only, bounded, and auditable.
- Separate deterministic validation from model performance claims.
