# ai-eng-lab

Applied AI-backend engineering: LLM clients, RAG, agents and MCP. Built frameworkless first, with **every project measured by and eval**.

## Projects

| # | Project | Status | Eval result |
|---|---|---|---|
| P1 | Provider-agnostic LLM client (raw HTTP, streaming, retries, token accounting) | planned | — |
| P3 | RAG service with retrieval + answer evaluation | planned | — |
| P5 | Single-agent tool-use loop with trajectory eval | planned | — |
| P6 | MCP server | planned | — |

## Run locally

```bash
uv sync
uv run pytest
```

Layout

- src/ai_eng_lab/: shared code (LLM client, eval harness)
- tests/: tests, run in CI on every push