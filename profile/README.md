# AnthropicBots

**Open-source systems for AI alignment research, developer automation, and local-first agentic tooling.**

[![Repos](https://img.shields.io/badge/repositories-10-informational)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()

---

## About

This organization hosts research and engineering projects built by **Mohit Yadav**, spanning LLM alignment research, GitHub automation, and local-first multi-agent systems. Projects here favor reproducibility, honest documentation, and running on consumer hardware over cloud dependency.

---

## Featured Projects

| Repository | Description | Stack | Status |
|---|---|---|---|
| **[dpo-vs-rlhf-alignmet-study](https://github.com/AnthropicBots/dpo-vs-rlhf-alignmet-study)** | Empirical comparison of DPO vs. RLHF alignment on GPT-2, trained on the 160,800-pair Anthropic HH-RLHF dataset. Full pipeline, results, and paper draft (targeting EMNLP/COLING) included. | Python, PyTorch, HuggingFace | Active — results published |
| **[hiero-bot-py](https://github.com/AnthropicBots/hiero-bot-py)** | Production FastAPI GitHub App for maintainer automation: PR health scoring, reviewer recommendations, stale-issue management, and a live analytics dashboard. 76+ tests, deployed. | Python, FastAPI, SQLAlchemy, APScheduler | Deployed — 44 releases |
| **[mats-compute-admin](https://github.com/AnthropicBots/mats-compute-admin)** | Compute resource administration toolkit for research fellowship programs — scholar provisioning, budget tracking, API key lifecycle, Slurm/HPC monitoring, and IAM auditing. 41 passing tests. | Python (stdlib-first) | Complete |
| **[HydraNet / Loopcutter](https://github.com/AnthropicBots/HydraNet)** | Local-first multi-agent coding assistant focused on one problem: detecting when an agent loops on a broken fix, rolling back, and forcing a genuinely different approach. Runs on consumer GPUs, no cloud calls. | Python, LangGraph, Tree-sitter, Docker | Pre-alpha — building in public |
| **[ptet-web](https://github.com/AnthropicBots/ptet-web)** | Informational website providing PTET-related resources in a clean, user-friendly format. | HTML | Active |
| **[E-commerce](https://github.com/AnthropicBots/E-commerce)** | Responsive e-commerce platform with product browsing and cart functionality. | JavaScript | Active |
| **[makemore](https://github.com/AnthropicBots/makemore)** | Character-level language modeling exercises exploring autoregressive generation fundamentals. | Python | Learning project |
| **[AI-Resume-Builder](https://github.com/AnthropicBots/AI-Resume-Builder)** | Tool for generating and formatting resumes with AI assistance. | — | Active |

---

## Tech Stack

`Python` · `FastAPI` · `PyTorch` · `React` · `SQLAlchemy` · `Docker` · `PostgreSQL` · `GitHub Actions` · `Tree-sitter`

---

## Philosophy

- **Reproducibility over hype** — results are published with numbers, including failures where relevant.
- **Consumer hardware first** — projects are built and benchmarked on hardware anyone can access, not assumed cloud budgets.
- **Honest scope** — READMEs describe what a project actually does before what it aspires to.

---

## Contributing

1. Fork the relevant repository
2. Create a feature branch (`feature/your-feature-name`)
3. Commit your changes with clear messages
4. Open a Pull Request describing the change and motivation

Repository-specific contribution guidelines, where they exist, take precedence over this general note.

---

## Contact

Reach out via GitHub Issues on the relevant repository, or [anthropicbots@gmail.com](mailto:anthropicbots@gmail.com).

---

<sub>© 2026 AnthropicBots. Individual repositories are licensed under MIT unless otherwise noted.</sub>
