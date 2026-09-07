# Decision-Centric Evaluation for Agentic AutoML

[![arXiv](https://img.shields.io/badge/arXiv-2602.22442-b31b1b.svg)](https://arxiv.org/abs/2602.22442)
[![AMLDS 2026](https://img.shields.io/badge/AMLDS%202026-Oral%20Paper-2ea44f.svg)](https://amlds.site/2026.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Official project repository for:

> **A Framework for Assessing AI Agent Decisions and Outcomes in AutoML Pipelines**  
> Gaoyuan Du, Amit Ahlawat, Xiaoyang Liu, and Jing Wu, 2026.

**Accepted for Oral Presentation at the 2026 2nd International Conference on
Advanced Machine Learning and Data Science (AMLDS 2026), Osaka, Japan.**

Agent-based AutoML systems make multi-stage decisions across data processing,
model selection, and evaluation. This project introduces an **Evaluation Agent**
that audits intermediate decisions rather than evaluating only final task
performance.

The framework considers four dimensions:

1. Decision validity
2. Reasoning consistency
3. Model-quality risks beyond accuracy
4. Counterfactual decision impact

## Keywords

Agentic AutoML, AI agents, LLM agents, decision-centric evaluation,
trustworthy AI, AI safety, counterfactual evaluation, model governance, and
autonomous machine learning.

## Status

This repository is currently a project placeholder. Code, evaluation schemas,
example agent traces, and experiment-reproduction instructions are being
prepared for release.

## Planned release

- Evaluation Agent implementation
- Standardized decision-trace schema
- Example AutoML agent trajectories
- Reproduction scripts for the paper experiments
- Documentation and quick-start examples

## Paper

- [arXiv abstract](https://arxiv.org/abs/2602.22442)
- [PDF](https://arxiv.org/pdf/2602.22442)
- DOI: [10.48550/arXiv.2602.22442](https://doi.org/10.48550/arXiv.2602.22442)

## Citation

If this work is useful in your research, please cite:

```bibtex
@misc{du2026framework,
  title         = {A Framework for Assessing AI Agent Decisions and Outcomes
                   in AutoML Pipelines},
  author        = {Du, Gaoyuan and Ahlawat, Amit and Liu, Xiaoyang and Wu, Jing},
  year          = {2026},
  eprint        = {2602.22442},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  note          = {Accepted for Oral Presentation at the 2026 2nd International
                   Conference on Advanced Machine Learning and Data Science
                   (AMLDS 2026)},
  doi           = {10.48550/arXiv.2602.22442},
  url           = {https://arxiv.org/abs/2602.22442}
}
```

## Contact

For questions, suggestions, or collaboration opportunities, please contact
[Gaoyuan Du](mailto:gdu@amazon.com) at `gdu@amazon.com`.
