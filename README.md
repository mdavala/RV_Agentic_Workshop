# RV_Agentic_Workshop

Hands-on workshop notebooks for building agentic AI workflows with [Hermes Agent](https://hermes-agent.nousresearch.com/), Skills, and MCP tools — progressing from a free local LLM to GPU-hosted models.

## Notebooks

- **`01_hermes_skills_lab_free_llm.ipynb`** — Install Hermes Agent, run a local model via Ollama (no API keys, no GPU), learn the Skills format, then reconfigure Hermes to an 8B model on an L4 GPU for a live Gmail spam-detector use case.
- **`02_hermes_neysa_velocis.ipynb`** — Advanced agentic workflows: Hermes connected to Qwen2.5-32B-Instruct on an H100 GPU, using a real research-paper MCP server for agentic deep research, including sequential and parallel multi-request usage-metrics tracking.

## Before you run these

Both notebooks have `# 🔑 FILL IN ...` cells where you'll need to supply your own:
- GPU VM endpoint URL, port, and API key (for the L4 and H100 sections)
- Gmail address and an [App Password](https://myaccount.google.com/apppasswords) (only needed for the live Gmail demo — a demo mode with sample emails is also included)

No real credentials are committed to this repo — placeholder values are used throughout.

