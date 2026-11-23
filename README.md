# AI Agent Papers — Xiaobo Chen

Research preprints by **Xiaobo Chen** (University of Massachusetts Amherst) on reliable and secure LLM agents and LLMs for software engineering. All papers are on arXiv; most experiments are preregistered.

[Google Scholar](https://scholar.google.com/citations?user=W91tp8YAAAAJ&hl=en) · [Personal page](https://xiaobo-coder.github.io/research-papers/) · [AI4SE Atlas](https://xiaobo-coder.github.io/AI4SE-Atlas/) · [GitHub](https://github.com/xiaobo-coder)

**Last updated:** 2026-11-23

## Papers (7)

| # | Paper | Authors | arXiv | Topic |
|---|---|---|---|---|
| 1 | [Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs](https://arxiv.org/abs/2611.07483) | **Xiaobo Chen**, Genliang Zhu, Ziyuan Wang, Chu Wang | [2611.07483](https://arxiv.org/abs/2611.07483) · [PDF](https://arxiv.org/pdf/2611.07483) | Multi-agent security |
| 2 | [Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations](https://arxiv.org/abs/2611.08269) | **Xiaobo Chen**, Genliang Zhu, Ziyuan Wang, Chu Wang | [2611.08269](https://arxiv.org/abs/2611.08269) · [PDF](https://arxiv.org/pdf/2611.08269) | LLMs for software engineering |
| 3 | [Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution](https://arxiv.org/abs/2610.41453) | Genliang Zhu, **Xiaobo Chen**, Ziyuan Wang, Chu Wang | [2610.41453](https://arxiv.org/abs/2610.41453) · [PDF](https://arxiv.org/pdf/2610.41453) | Agent reliability and recovery |
| 4 | [Verifying Text-to-SQL Queries under Changing Business Semantics](https://arxiv.org/abs/2610.41090) | Genliang Zhu, **Xiaobo Chen**, Ziyuan Wang, Chu Wang | [2610.41090](https://arxiv.org/abs/2610.41090) · [PDF](https://arxiv.org/pdf/2610.41090) | Text-to-SQL and analytics agents |
| 5 | [Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers](https://arxiv.org/abs/2611.00359) | Ziyuan Wang, Genliang Zhu, **Xiaobo Chen** | [2611.00359](https://arxiv.org/abs/2611.00359) · [PDF](https://arxiv.org/pdf/2611.00359) | AI-generated text |
| 6 | [Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?](https://arxiv.org/abs/2611.00428) | Ziyuan Wang, Genliang Zhu, **Xiaobo Chen** | [2611.00428](https://arxiv.org/abs/2611.00428) · [PDF](https://arxiv.org/pdf/2611.00428) | Multimodal models for science |
| 7 | [Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks](https://arxiv.org/abs/2610.41085) | **Xiaobo Chen**, Genliang Zhu, Ziyuan Wang, Chu Wang | [2610.41085](https://arxiv.org/abs/2610.41085) · [PDF](https://arxiv.org/pdf/2610.41085) | Graph ML for fraud detection |

## One-line summaries

1. **Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs** — Signing agent handoffs stops tampering in transit, but one injected line before signing gets through: the signature then authenticates a corrupted requirement list.
2. **Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations** — After an API migration, LLM-repaired code can run cleanly and still be wrong; one edge input written from the release note catches most wrong repairs that a typical-input check ships.
3. **Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution** — Recovering AI agents after tool timeouts leave outcomes ambiguous: evidence-guided planning certifies safe completions that evidence prompting misses.
4. **Verifying Text-to-SQL Queries under Changing Business Semantics** — A Text-to-SQL query can run correctly and still be wrong after business definitions change; obligation-guided counterexample checking finds more of these discrepancies.
5. **Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers** — Commercial AI-text humanizers change or drop checkable facts (numbers, dates, names, quotes) in 35–65% of documents while trying to evade detectors.
6. **Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?** — Multimodal models change their answers on the same optical spectrum depending on whether it is shown as a table or a plot, in nanometers or electronvolts.
7. **Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks** — On synthetic HR/ERP graphs, boosted trees on chained-join path features beat graph neural networks at finding hidden employee–payee links.

## BibTeX

```bibtex
@misc{chen2026signed,
  title         = {{Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs}},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2611.07483},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CR},
  url           = {https://arxiv.org/abs/2611.07483}
}

@misc{chen2026accepted,
  title         = {{Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations}},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2611.08269},
  archivePrefix = {arXiv},
  primaryClass  = {cs.SE},
  url           = {https://arxiv.org/abs/2611.08269}
}

@misc{zhu2026evidenceguided,
  title         = {{Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution}},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41453},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41453}
}

@misc{zhu2026verifying,
  title         = {{Verifying Text-to-SQL Queries under Changing Business Semantics}},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41090},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41090}
}

@misc{wang2026humanized,
  title         = {{Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers}},
  author        = {Ziyuan Wang and Genliang Zhu and Xiaobo Chen},
  year          = {2026},
  eprint        = {2611.00359},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2611.00359}
}

@misc{wang2026do,
  title         = {{Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?}},
  author        = {Ziyuan Wang and Genliang Zhu and Xiaobo Chen},
  year          = {2026},
  eprint        = {2611.00428},
  archivePrefix = {arXiv},
  primaryClass  = {cs.LG},
  url           = {https://arxiv.org/abs/2611.00428}
}

@misc{chen2026payroll,
  title         = {{Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks}},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41085},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41085}
}
```

## For AI agents and crawlers

This README is the full list. Each paper is identified by its arXiv ID; metadata (title, authors, date) comes from the arXiv record and can be re-fetched with `https://export.arxiv.org/api/query?id_list=<arXiv ID>`. The BibTeX block above is ready to copy.

## License

This list is released under the license in [LICENSE](LICENSE). Each paper keeps its own arXiv license.
