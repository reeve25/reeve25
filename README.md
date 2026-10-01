# Reeve Masilamani

CS at UC Davis ('27). I build ML and AI systems and measure whether they actually work.
Right now that means LLM evaluation, LLM security tooling, and the cloud infrastructure underneath.
Incoming Analyst, Deloitte Cyber (2027).

### Now

- **[civic-eval](https://github.com/reeve25/civic-eval)**: an evaluation harness for government-services AI assistants. It scores answers against cited state law and tests prompt injection, PII leakage, over-refusal, and cost per model.
- **Contributing to [NVIDIA garak](https://github.com/NVIDIA/garak)**, the open-source LLM vulnerability scanner:
  - [#2258](https://github.com/NVIDIA/garak/pull/2258): the safety report scored a detector that evaluated nothing as a total failure ([#2251](https://github.com/NVIDIA/garak/issues/2251)).
  - [#2260](https://github.com/NVIDIA/garak/pull/2260): three prompt-injection probes ran nearly every prompt with another prompt's generation settings ([#2259](https://github.com/NVIDIA/garak/issues/2259)).

### Projects

| Project | What it does |
|---|---|
| [vulnprio](https://github.com/reeve25/vulnprio) | Ranks container vulnerabilities by real-world exploitation (CISA KEV, EPSS) instead of CVSS alone. Cuts 883 high/critical findings to 140 across four public images. FastAPI on AWS Lambda, Terraform, 61 tests, p95 under 125 ms. [Live demo](https://reeve25.github.io/vulnprio/). |
| [FantasyFootball](https://github.com/reeve25/FantasyFootball) | XGBoost projections with walk-forward validation on 25,903 player-weeks. MAE 4.71, 235 tests. Features that didn't lower error were measured and dropped. |
| [ai-dev-setup](https://github.com/reeve25/ai-dev-setup) | How I run Claude Code and Codex with MCP. One config change cut the per-request prompt from 42.5k to 26.4k tokens (38%). |
| HackDavis 2024 | AI fact-checker: LLM claim extraction, retrieval-augmented evidence lookup, and a RoBERTa classifier. 4th place, Best AI/ML. |

### Tools

Python, TypeScript, SQL, C++ · XGBoost, scikit-learn, pandas · FastAPI, AWS, Terraform, Docker, GitHub Actions · Claude Code, Codex, MCP
