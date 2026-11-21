# Architecture

Pipeline:

1. Fetch market data (Massive + CBOE)
2. Compute signals (Python)
3. Classify market regime
4. Generate AI summary (OpenRouter)
5. Generate charts (matplotlib)
6. Update README
7. Commit to repository

Design principles:

- Deterministic signals
- AI used only for narrative
- Fully auditable via repo data

The report reads `OPENROUTER_API_KEY` from the process environment. For GitHub
Actions, configure it as a repository Actions secret with that exact name. For
local runs, export it in the shell before running the report. Never commit the
key to the repository.