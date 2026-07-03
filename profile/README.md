# AnthropicBots

**Open-source systems for AI alignment research, developer automation, and local-first agentic tooling.**

[![Repos](https://img.shields.io/badge/repositories-11-informational)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()
[![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)]()
[![Last Commit](https://img.shields.io/github/last-commit/AnthropicBots/hiero-bot-py?label=last%20activity)]()

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=Building+local-first+agentic+tooling;Researching+LLM+alignment+(DPO+vs+RLHF);Automating+open-source+maintainer+workflows" alt="typing animation" />

---

## Table of Contents

- [About](#about)
- [Featured Projects](#featured-projects)
- [Tech Stack](#tech-stack)
- [GitHub Trophies](#github-trophies)
- [Activity & Stats](#activity--stats)
- [Star History](#star-history)
- [Roadmap](#roadmap)
- [Philosophy](#philosophy)
- [Contributing](#contributing)
- [Connect](#connect)
- [Contact](#contact)

---

## About

This organization hosts research and engineering projects built by **Mohit Yadav**, spanning LLM alignment research, GitHub automation, developer productivity tools, and local-first multi-agent systems.

Projects emphasize reproducibility, maintainability, honest documentation, strong engineering practices, and practical software that runs on accessible hardware whenever possible.

---

## Featured Projects

| Repository | Description | Stack | Stars | Forks |
|---|---|---|---|---|
| **[dpo-vs-rlhf-alignmet-study](https://github.com/AnthropicBots/dpo-vs-rlhf-alignmet-study)** | Empirical comparison of DPO vs. RLHF alignment on GPT-2, trained on the 160,800-pair Anthropic HH-RLHF dataset. Full pipeline, results, and paper draft (targeting EMNLP/COLING) included. | Python, PyTorch, HuggingFace | ![Stars](https://img.shields.io/github/stars/AnthropicBots/dpo-vs-rlhf-alignmet-study?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/dpo-vs-rlhf-alignmet-study?style=flat-square&label=) |
| **[hiero-bot-py](https://github.com/AnthropicBots/hiero-bot-py)** | Production FastAPI GitHub App for maintainer automation: PR health scoring, reviewer recommendations, stale-issue management, and a live analytics dashboard. 76+ tests, deployed. | Python, FastAPI, SQLAlchemy, APScheduler | ![Stars](https://img.shields.io/github/stars/AnthropicBots/hiero-bot-py?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/hiero-bot-py?style=flat-square&label=) |
| **[mats-compute-admin](https://github.com/AnthropicBots/mats-compute-admin)** | Compute resource administration toolkit for research fellowship programs — scholar provisioning, budget tracking, API key lifecycle, Slurm/HPC monitoring, and IAM auditing. 41 passing tests. | Python (stdlib-first) | ![Stars](https://img.shields.io/github/stars/AnthropicBots/mats-compute-admin?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/mats-compute-admin?style=flat-square&label=) |
| **[HydraNet / Loopcutter](https://github.com/AnthropicBots/HydraNet)** | Local-first multi-agent coding assistant focused on one problem: detecting when an agent loops on a broken fix, rolling back, and forcing a genuinely different approach. Runs on consumer GPUs, no cloud calls. | Python, LangGraph, Tree-sitter, Docker | ![Stars](https://img.shields.io/github/stars/AnthropicBots/HydraNet?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/HydraNet?style=flat-square&label=) |
| **[IssueScout](https://github.com/AnthropicBots/IssueScout)** | Full-stack GitHub contribution discovery platform that analyzes repositories, identifies contributor-friendly issues, detects linked pull requests, and ranks opportunities using evidence-driven confidence scoring. | FastAPI, React, TypeScript, Python | ![Stars](https://img.shields.io/github/stars/AnthropicBots/IssueScout?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/IssueScout?style=flat-square&label=) |
| **[ptet-web](https://github.com/AnthropicBots/ptet-web)** | Informational website providing PTET-related resources in a clean, user-friendly format. | HTML | ![Stars](https://img.shields.io/github/stars/AnthropicBots/ptet-web?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/ptet-web?style=flat-square&label=) |
| **[E-commerce](https://github.com/AnthropicBots/E-commerce)** | Responsive e-commerce platform with product browsing and cart functionality. | JavaScript | ![Stars](https://img.shields.io/github/stars/AnthropicBots/E-commerce?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/E-commerce?style=flat-square&label=) |
| **[makemore](https://github.com/AnthropicBots/makemore)** | Character-level language modeling exercises exploring autoregressive generation fundamentals. | Python | ![Stars](https://img.shields.io/github/stars/AnthropicBots/makemore?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/makemore?style=flat-square&label=) |
| **[AI-Resume-Builder](https://github.com/AnthropicBots/AI-Resume-Builder)** | Tool for generating and formatting resumes with AI assistance. | — | ![Stars](https://img.shields.io/github/stars/AnthropicBots/AI-Resume-Builder?style=flat-square&label=) | ![Forks](https://img.shields.io/github/forks/AnthropicBots/AI-Resume-Builder?style=flat-square&label=) |

> Star/fork counts update live via shields.io — no manual maintenance needed.

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,react,typescript,vite,pytorch,postgres,docker,githubactions,git,nodejs" />

</div>

`Python` · `FastAPI` · `React` · `TypeScript` · `Vite` · `PyTorch` · `SQLAlchemy` · `Docker` · `PostgreSQL` · `GitHub Actions` · `Tree-sitter`

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=mohityadav8&theme=radical&no-frame=true&row=1&column=6" />

</div>

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

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-mohityadav8-181717?style=for-the-badge&logo=github)](https://github.com/mohityadav8)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-6C63FF?style=for-the-badge&logo=vercel)](#)
[![Instagram](https://img.shields.io/badge/Instagram-@tech__to__tech__-E4405F?style=for-the-badge&logo=instagram)](#)

*(swap the `#` placeholders above for your actual LinkedIn / portfolio / Instagram links)*

</div>

---

## Activity & Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mohityadav8&show_icons=true&count_private=true&theme=radical&hide_border=true" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=mohityadav8&theme=radical&hide_border=true" height="165" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mohityadav8&theme=react-dark&hide_border=true" width="100%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohityadav8&layout=compact&theme=radical&hide_border=true" height="165" />

</div>

> Rendered live from GitHub's contribution data — updates automatically, no manual edits required.

---

## Star History

<div align="center">

<a href="https://star-history.com/#AnthropicBots/hiero-bot-py&AnthropicBots/dpo-vs-rlhf-alignmet-study&AnthropicBots/mats-compute-admin&Date">
  <img src="https://api.star-history.com/svg?repos=AnthropicBots/hiero-bot-py,AnthropicBots/dpo-vs-rlhf-alignmet-study,AnthropicBots/mats-compute-admin&type=Date" width="80%" />
</a>

</div>

---

## Roadmap

- [x] Release **IssueScout v1.0** with a production-ready React + FastAPI architecture
- [x] Ship `hiero-bot-py` v2 with live dashboard and PR health scoring
- [x] Publish DPO vs. RLHF empirical results and paper draft
- [x] Build `mats-compute-admin` with full test coverage
- [ ] Take `Loopcutter` (HydraNet) from single-machine loop to multi-node coordination
- [ ] Run Loopcutter against a real slice of SWE-bench Lite
- [ ] Submit the DPO vs. RLHF paper to EMNLP / COLING
- [ ] Expand `hiero-bot-py` reviewer recommendation with embedding-based file similarity

---

## Contact

Reach out via GitHub Issues on the relevant repository, or [anthropicbots@gmail.com](mailto:anthropicbots@gmail.com).

---

<div align="center">

<sub>© 2026 AnthropicBots · Maintained by <a href="https://github.com/mohityadav8">Mohit Yadav</a> · Individual repositories are licensed under MIT unless otherwise noted.</sub>

[⬆ Back to top](#anthropicbots)

</div>
