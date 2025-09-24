# PHARMA Problem Statement – EY Techathon 6.0

## About the Problem
A multinational pharmaceutical company wants to repurpose existing approved molecules for new indications, dosage forms, or patient populations. Literature reviews for this take 2–3 months. The challenge is to design an **Agentic AI solution** with a Master Agent + Worker Agents to accelerate this process.

---

## Existing Tools / Research & How They Compare

| Name / Project | What it does | Overlap with our concept | Limitations / Gaps |
|---|---|---|---|
| [DrugAgent: Explainable Drug Repurposing Agent](https://arxiv.org/abs/2408.13378) | Multi-agent framework combining literature search, knowledge graphs, and prediction. | Very close to Worker Agents idea. | Lacks patent/regulatory/enterprise integration. |
| [PharmaSwarm / LLM Agent Swarm](https://arxiv.org/abs/2504.17967) | Ensemble of agents for hypothesis-driven drug discovery. | Similar orchestration to Master + Worker Agents. | More research-focused; not enterprise-ready. |
| [DrugMCTS](https://arxiv.org/abs/2507.07426) | Uses multi-agent systems + Monte Carlo Tree Search for drug repurposing. | Agent-based decomposition of tasks. | Theoretical; lacks deployment focus. |
| [AGATHA](https://pubmed.ncbi.nlm.nih.gov/40674898/) | Literature mining tool for hidden associations. | Covers the literature search worker. | Doesn’t cover patents, market, trials. |
| [IQVIA + NVIDIA Orchestrator Agents](https://blogs.nvidia.com/blog/iqvia-ai-agents-clinical-research/) | Master agent delegating tasks in clinical ops. | Shows feasibility of orchestration. | Not specific to drug repurposing. |
| [AI-based Drug Repurposing Review](https://pmc.ncbi.nlm.nih.gov/articles/PMC11984889/) | Summarizes AI applications in drug repurposing. | Validates market trend. | Mostly literature review, not agentic systems. |
| [Agilisium Agentic AI Solutions](https://www.agilisium.com/agentic-ai-solutions) | Provides agentic AI frameworks for life sciences. | Could serve as infrastructure. | Not specific to repurposing workflow. |

---

## Gaps & Opportunities
- End-to-end orchestration across **patents, trials, markets, regulatory & internal data**.
- **UI for non-technical users** (natural prompts → structured reports).  
- **Governance & auditability** (critical in pharma).  
- Scalable **enterprise-ready deployment**.  

---

## Deliverables for Techathon
- Live demo or 4-min video showing:  
  - Search for a molecule.  
  - Unmet needs.  
  - Clinical trials.  
  - Patent status.  
  - Market analysis.  
  - Final PDF report.  

