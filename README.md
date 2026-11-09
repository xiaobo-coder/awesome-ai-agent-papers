# AI Agent Papers — Xiaobo Chen (UMass Amherst)

This repository lists research papers by **Xiaobo Chen** on **reliable and secure LLM agents** (large language model agents that use tools, keep memory and act over many steps). The papers study requirement integrity and tampering in multi-agent handoffs, silent failures of LLM code repairs, how agents recover from failed or ambiguous tool calls, repair their memory and plans when evidence changes, ask clarifying questions under a budget, discover the right tools, manage context and cost, and verify Text-to-SQL queries when business definitions change. Further papers apply graph neural networks to payroll fraud detection, audit AI-text humanizers, and test multimodal models on equivalent scientific data. All papers are 2026 preprints co-authored with Genliang Zhu, Ziyuan Wang and Chu Wang; most experiments are preregistered.

**Last updated:** 2026-11-08  
**Google Scholar:** [Xiaobo Chen](https://scholar.google.com/citations?user=W91tp8YAAAAJ&hl=en)  
**Affiliation:** University of Massachusetts Amherst  
**Research areas:** LLM agents, AI agent reliability and safety, multi-agent security, LLMs for software engineering, tool-using language models, agent memory, enterprise AI workflows, Text-to-SQL, graph machine learning

**Keywords:** LLM agents, AI agents, agentic AI, multi-agent systems, AI agent security, prompt injection, LLM code repair, API migration, software testing, tool-using LLMs, function calling, agent reliability, failure recovery, agent memory, plan repair, clarifying questions, human-in-the-loop, context management, tool retrieval, Text-to-SQL, enterprise workflows, ERP, agent evaluation, preregistration, graph neural networks, fraud detection, AI-generated text detection, multimodal models

---

## Papers on arXiv (7)

| Paper | arXiv | Categories |
|---|---|---|
| [Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs](#signed-but-not-safe-requirement-integrity-in-multi-agent-llm-handoffs) | [2611.07483](https://arxiv.org/abs/2611.07483) | cs.CR; cs.AI, cs.MA |
| [Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations](#accepted-but-wrong-silent-failures-of-llm-code-repairs-after-api-migrations) | [2611.08269](https://arxiv.org/abs/2611.08269) | cs.SE; cs.AI |
| [Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers](#humanized-but-still-true-auditing-facts-and-detection-in-ai-text-humanizers) | [2611.00359](https://arxiv.org/abs/2611.00359) | cs.CL; cs.CR |
| [Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?](#do-multimodal-models-decide-consistently-on-equivalent-optical-spectra) | [2611.00428](https://arxiv.org/abs/2611.00428) | cs.LG; cs.CL, physics.optics |
| [Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution](#evidence-guided-recovery-for-ai-agents-with-ambiguous-tool-outcomes-and-partial-execution) | [2610.41453](https://arxiv.org/abs/2610.41453) | cs.AI |
| [Verifying Text-to-SQL Queries under Changing Business Semantics](#verifying-text-to-sql-queries-under-changing-business-semantics) | [2610.41090](https://arxiv.org/abs/2610.41090) | cs.AI |
| [Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks](#payroll-fraud-detection-in-synthetic-hrerp-graphs-an-inductive-comparison-of-rules-path-features-and-graph-neural-networks) | [2610.41085](https://arxiv.org/abs/2610.41085) | cs.AI |

---

## Papers by topic

**AI agent security and multi-agent systems**
- [Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs](#signed-but-not-safe-requirement-integrity-in-multi-agent-llm-handoffs)

**LLMs for software engineering**
- [Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations](#accepted-but-wrong-silent-failures-of-llm-code-repairs-after-api-migrations)

**Agent reliability, recovery and resumption**
- [Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution](#evidence-guided-recovery-for-ai-agents-with-ambiguous-tool-outcomes-and-partial-execution)
- [Change Detection for Task Resumption in AI Agents: An Empirical Study](#change-detection-for-task-resumption-in-ai-agents-an-empirical-study)

**Agent memory, evidence and grounding**
- [Time-Consistent Evidence Assembly across Documents and Transactional Data for AI Agents](#time-consistent-evidence-assembly-across-documents-and-transactional-data-for-ai-agents)
- [Incremental Repair of Agent Memory and Plans after Business Evidence Revisions](#incremental-repair-of-agent-memory-and-plans-after-business-evidence-revisions)

**Planning, clarification and plan repair**
- [Active Discovery of Hidden Business Cascades under Rule Drift](#active-discovery-of-hidden-business-cascades-under-rule-drift)
- [Clarification Planning for AI Agents under Shared Question Budgets](#clarification-planning-for-ai-agents-under-shared-question-budgets)
- [Repairing AI Agent Task Graphs: Audit-Guided Recomputations versus Full-Context Rewriting](#repairing-ai-agent-task-graphs-audit-guided-recomputations-versus-full-context-rewriting)

**Tool use and tool discovery**
- [Preserving Business Semantics in Multilingual Tool Workflows: Contract Checks and Model-Failure Diagnosis](#preserving-business-semantics-in-multilingual-tool-workflows-contract-checks-and-model-failure-diagnosis)
- [Dependency-Complete Tool Discovery in Evolving Enterprise Tool Catalogs](#dependency-complete-tool-discovery-in-evolving-enterprise-tool-catalogs)

**Context management and cost**
- [Online Context Scheduling under Cache Expiry and Human Approval Delays](#online-context-scheduling-under-cache-expiry-and-human-approval-delays)

**Text-to-SQL and data analytics agents**
- [Verifying Text-to-SQL Queries under Changing Business Semantics](#verifying-text-to-sql-queries-under-changing-business-semantics)

**Agent evaluation**
- [Evaluating Lifecycle Interactions in AI Agents across Memory, Approval, Execution, and Recovery](#evaluating-lifecycle-interactions-in-ai-agents-across-memory-approval-execution-and-recovery)

**AI-generated text and detection**
- [Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers](#humanized-but-still-true-auditing-facts-and-detection-in-ai-text-humanizers)

**Multimodal models for science**
- [Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?](#do-multimodal-models-decide-consistently-on-equivalent-optical-spectra)

**Graph machine learning for fraud detection**
- [Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks](#payroll-fraud-detection-in-synthetic-hrerp-graphs-an-inductive-comparison-of-rules-path-features-and-graph-neural-networks)

---

## First-author papers

### Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs

**Authors:** Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.CR; cs.AI, cs.MA  
**Keywords:** multi-agent LLM systems, agent handoffs, requirement integrity, signed manifests, prompt injection, tampering, AI agent security  
**Links:** [arXiv:2611.07483](https://arxiv.org/abs/2611.07483) | [PDF](https://arxiv.org/pdf/2611.07483)

### Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations

**Authors:** Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.SE; cs.AI  
**Keywords:** LLM code repair, API migration, silent failures, test oracles, automated program repair, software engineering for AI  
**Links:** [arXiv:2611.08269](https://arxiv.org/abs/2611.08269) | [PDF](https://arxiv.org/pdf/2611.08269)

### Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks

**Authors:** Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.AI  
**Keywords:** payroll fraud detection, ghost employees, graph neural networks (GNN), inductive link prediction, knowledge graphs, HR / ERP analytics, audit analytics, rule-based detection  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:roLk4NBRz8UC) | [arXiv:2610.41085](https://arxiv.org/abs/2610.41085) | [PDF](https://arxiv.org/pdf/2610.41085)

## Co-authored papers

### Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers

**Authors:** Ziyuan Wang, Genliang Zhu, Xiaobo Chen  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.CL; cs.CR  
**Keywords:** AI-text humanizers, fact preservation, AI-generated text detection, paraphrasing attacks, detector evasion  
**Links:** [arXiv:2611.00359](https://arxiv.org/abs/2611.00359) | [PDF](https://arxiv.org/pdf/2611.00359)

### Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?

**Authors:** Ziyuan Wang, Genliang Zhu, Xiaobo Chen  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.LG; cs.CL, physics.optics  
**Keywords:** multimodal models, representation invariance, scientific AI, optical spectra, abstention, shortcut learning, LoRA  
**Links:** [arXiv:2611.00428](https://arxiv.org/abs/2611.00428) | [PDF](https://arxiv.org/pdf/2611.00428)

### Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.AI  
**Keywords:** failure recovery, ambiguous tool outcomes, partial execution, idempotency, side effects, agent reliability  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:2osOgNQ5qMEC) | [arXiv:2610.41453](https://arxiv.org/abs/2610.41453) | [PDF](https://arxiv.org/pdf/2610.41453)

### Verifying Text-to-SQL Queries under Changing Business Semantics

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (arXiv preprint)  
**arXiv categories:** cs.AI  
**Keywords:** Text-to-SQL, query verification, business semantics drift, schema and metric changes, LLM-generated SQL, data analytics agents  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:qjMakFHDy7sC) | [arXiv:2610.41090](https://arxiv.org/abs/2610.41090) | [PDF](https://arxiv.org/pdf/2610.41090)

### Preserving Business Semantics in Multilingual Tool Workflows: Contract Checks and Model-Failure Diagnosis

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** multilingual tool use, business semantics, contract checks, LLM failure diagnosis, tool-using LLM agents, cross-lingual workflows  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:LkGwnXOMwfcC) | [SSRN 7620659](https://ssrn.com/abstract=7620659)

### Time-Consistent Evidence Assembly across Documents and Transactional Data for AI Agents

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** evidence assembly, temporal consistency, documents and transactional data, retrieval for agents, grounded answers, enterprise data  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:_FxGoFyzp5QC) | [SSRN 7621079](https://ssrn.com/abstract=7621079)

### Active Discovery of Hidden Business Cascades under Rule Drift

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** business rule drift, hidden cascades, active discovery, change impact analysis, LLM agents in enterprise workflows  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:ufrVoPGSRksC) | [SSRN 7621098](https://ssrn.com/abstract=7621098)

### Online Context Scheduling under Cache Expiry and Human Approval Delays

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** context scheduling, prompt / KV cache expiry, human approval delays, human-in-the-loop agents, online scheduling, LLM inference cost  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:WF5omc3nYNoC) | [SSRN 7621058](https://ssrn.com/abstract=7621058)

### Dependency-Complete Tool Discovery in Evolving Enterprise Tool Catalogs

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** tool discovery, tool retrieval, dependency resolution, evolving tool catalogs, function calling, MCP-style tool registries  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:eQOLeE2rZwMC) | [SSRN 7620582](https://ssrn.com/abstract=7620582)

### Evaluating Lifecycle Interactions in AI Agents across Memory, Approval, Execution, and Recovery

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** agent evaluation, agent lifecycle, memory, human approval, execution, recovery, interaction effects  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:UeHWp8X0CEIC) | [SSRN 7612738](https://ssrn.com/abstract=7612738)

### Incremental Repair of Agent Memory and Plans after Business Evidence Revisions

**Authors:** Genliang Zhu, Ziyuan Wang, Xiaobo Chen, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** agent memory repair, plan repair, evidence revision, belief update, long-horizon agents, incremental recomputation  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:9yKSN-GCB0IC) | [SSRN 7614038](https://ssrn.com/abstract=7614038)

### Clarification Planning for AI Agents under Shared Question Budgets

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** clarifying questions, question budgets, ambiguity resolution, human-agent interaction, information gathering  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:YsMSGLbcyi4C) | [SSRN 7613098](https://ssrn.com/abstract=7613098)

### Repairing AI Agent Task Graphs: Audit-Guided Recomputations versus Full-Context Rewriting

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** task graph repair, audit-guided recomputation, full-context rewriting, plan revision, multi-step agents  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:W7OEmFMy1HYC) | [SSRN 7612958](https://ssrn.com/abstract=7612958)

### Change Detection for Task Resumption in AI Agents: An Empirical Study

**Authors:** Genliang Zhu, Xiaobo Chen, Ziyuan Wang, Chu Wang  
**Year:** 2026 (SSRN preprint)  
**Keywords:** task resumption, change detection, interrupted agents, state staleness, empirical study  
**Links:** [Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=W91tp8YAAAAJ&citation_for_view=W91tp8YAAAAJ:IjCSPb-OGe4C) | [SSRN 7609358](https://ssrn.com/abstract=7609358)

---

## How to cite

If you use or discuss these papers, please cite them. BibTeX entries (arXiv entries first):

<details>
<summary>BibTeX (17 entries)</summary>

```bibtex
@misc{chen2026signed,
  title         = {Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2611.07483},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CR},
  url           = {https://arxiv.org/abs/2611.07483}
}

@misc{chen2026accepted,
  title         = {Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2611.08269},
  archivePrefix = {arXiv},
  primaryClass  = {cs.SE},
  url           = {https://arxiv.org/abs/2611.08269}
}

@misc{chen2026payrollfraud,
  title         = {Payroll Fraud Detection in Synthetic HR/ERP Graphs: An Inductive Comparison of Rules, Path Features, and Graph Neural Networks},
  author        = {Xiaobo Chen and Genliang Zhu and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41085},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41085}
}

@misc{wang2026humanized,
  title         = {Humanized but Still True? Auditing Facts and Detection in AI-Text Humanizers},
  author        = {Ziyuan Wang and Genliang Zhu and Xiaobo Chen},
  year          = {2026},
  eprint        = {2611.00359},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2611.00359}
}

@misc{wang2026multimodal,
  title         = {Do Multimodal Models Decide Consistently on Equivalent Optical Spectra?},
  author        = {Ziyuan Wang and Genliang Zhu and Xiaobo Chen},
  year          = {2026},
  eprint        = {2611.00428},
  archivePrefix = {arXiv},
  primaryClass  = {cs.LG},
  url           = {https://arxiv.org/abs/2611.00428}
}

@misc{zhu2026evidenceguided,
  title         = {Evidence-Guided Recovery for AI Agents with Ambiguous Tool Outcomes and Partial Execution},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41453},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41453}
}

@misc{zhu2026verifyingtext,
  title         = {Verifying Text-to-SQL Queries under Changing Business Semantics},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  eprint        = {2610.41090},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2610.41090}
}

@misc{zhu2026preservingbusiness,
  title         = {Preserving Business Semantics in Multilingual Tool Workflows: Contract Checks and Model-Failure Diagnosis},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7620659},
  url           = {https://ssrn.com/abstract=7620659}
}

@misc{zhu2026timeconsistent,
  title         = {Time-Consistent Evidence Assembly across Documents and Transactional Data for AI Agents},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7621079},
  url           = {https://ssrn.com/abstract=7621079}
}

@misc{zhu2026activediscovery,
  title         = {Active Discovery of Hidden Business Cascades under Rule Drift},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7621098},
  url           = {https://ssrn.com/abstract=7621098}
}

@misc{zhu2026onlinecontext,
  title         = {Online Context Scheduling under Cache Expiry and Human Approval Delays},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7621058},
  url           = {https://ssrn.com/abstract=7621058}
}

@misc{zhu2026dependencycomplete,
  title         = {Dependency-Complete Tool Discovery in Evolving Enterprise Tool Catalogs},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7620582},
  url           = {https://ssrn.com/abstract=7620582}
}

@misc{zhu2026evaluatinglifecycle,
  title         = {Evaluating Lifecycle Interactions in AI Agents across Memory, Approval, Execution, and Recovery},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7612738},
  url           = {https://ssrn.com/abstract=7612738}
}

@misc{zhu2026incrementalrepair,
  title         = {Incremental Repair of Agent Memory and Plans after Business Evidence Revisions},
  author        = {Genliang Zhu and Ziyuan Wang and Xiaobo Chen and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7614038},
  url           = {https://ssrn.com/abstract=7614038}
}

@misc{zhu2026clarificationplanning,
  title         = {Clarification Planning for AI Agents under Shared Question Budgets},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7613098},
  url           = {https://ssrn.com/abstract=7613098}
}

@misc{zhu2026repairingai,
  title         = {Repairing AI Agent Task Graphs: Audit-Guided Recomputations versus Full-Context Rewriting},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7612958},
  url           = {https://ssrn.com/abstract=7612958}
}

@misc{zhu2026changedetection,
  title         = {Change Detection for Task Resumption in AI Agents: An Empirical Study},
  author        = {Genliang Zhu and Xiaobo Chen and Ziyuan Wang and Chu Wang},
  year          = {2026},
  howpublished  = {SSRN preprint 7609358},
  url           = {https://ssrn.com/abstract=7609358}
}
```

</details>

---

Code and data are available from the authors on request unless a paper states otherwise. This list is maintained personally by Xiaobo Chen.
