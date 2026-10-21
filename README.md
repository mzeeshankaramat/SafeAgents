# 🛡️ Agent Safety: A Curated List of Research Papers

A curated and continuously updated collection of **research papers on the safety, security, robustness, and trustworthiness of LLM-powered agents**.

This repository focuses on **autonomous and semi-autonomous agents**, including tool-using agents, web agents, OS agents, and multi-agent systems.

---
<!--
## 🔍 Scope

This repo covers (but is not limited to):

- Prompt injection & jailbreak attacks on agents
- Tool misuse, hallucinations, and unsafe tool execution
- Memory poisoning and long-term agent risks
- Multi-agent safety and emergent behaviors
- Alignment, control, and oversight of agents
- Benchmarks, evaluations, and red-teaming frameworks
- Defense mechanisms and mitigation strategies

---

## 🗂️ Paper Categories

- [📖 Surveys & Position Papers](#-surveys--position-papers)
- [🌐 Web Agents](#-web-agents)
- [🧰 Tool-Using Agents & RAG](#-tool-using-agents--rag)
- [🤖 Autonomous / OS Agents](#-autonomous--os-agents)
- [🧠 Multi-Agent Systems](#-multi-agent-systems)
- [📊 Benchmarks & Datasets](#-benchmarks--datasets)
- [🛠️ Defense & Mitigation Techniques](#-defense--mitigation-techniques)

---

## 📖 Surveys & Position Papers

| Paper | Year | Focus | Notes |
|------|------|------|------|
| **Title** | 2024 | Survey / Position | Brief 1–2 line summary |
| **Title** | 2023 | Threat Model | Why this paper matters |

---

## 🌐 Web Agents

| Paper | Year | Threat / Defense | Key Idea |
|------|------|-----------------|----------|
| **Title** | 2024 | Attack | Prompt injection via web content |
| **Title** | 2023 | Defense | Secure browsing strategies |

---

## 🧰 Tool-Using Agents & RAG

| Paper | Year | Agent Type | Safety Issue |
|------|------|-----------|--------------|
| **Title** | 2024 | Tool Agent | Unsafe tool invocation |
| **Title** | 2023 | RAG | Retrieval poisoning |

---

## 🤖 Autonomous / OS Agents

| Paper | Year | Environment | Risk |
|------|------|------------|------|
| **Title** | 2024 | OS / CLI | Privilege escalation |
| **Title** | 2023 | Autonomous | Goal misalignment |

---

## 🧠 Multi-Agent Systems

| Paper | Year | Setting | Safety Concern |
|------|------|--------|----------------|
| **Title** | 2024 | Multi-agent | Emergent collusion |
| **Title** | 2023 | Cooperative | Coordination failures |

---

## 📊 Benchmarks & Datasets

| Benchmark | Year | Evaluates | Notes |
|----------|------|----------|-------|
| **Name** | 2024 | Agent robustness | Includes adversarial tasks |
| **Name** | 2023 | Safety alignment | Public dataset |

---

## 🛠️ Defense & Mitigation Techniques

| Paper | Year | Defense Type | Key Insight |
|------|------|------------|-------------|
| **Title** | 2024 | Runtime monitoring | Detect unsafe actions |
| **Title** | 2023 | Training-time | Robust fine-tuning |

---
-->
## 🧾 Papers
<!--
- **Paper Title**  
🔗 [PDF](link)
📍 Venue: Conference / Journal / arXiv  
📅 Date: YYYY-MM  
🏷️ Tags: Attack, Defense, Survey

-->

**Contents**

- [Surveys and Position Papers](#surveys-and-position-papers)
- [Multi-Agent Systems](#multi-agent-systems)
- [Privacy, Memory and Data Leakage](#privacy-memory-and-data-leakage)
- [Web, OS and Computer-Use Agents](#web-os-and-computer-use-agents)
- [Embodied and Multimodal Agents](#embodied-and-multimodal-agents)
- [Code Agents and Supply Chain](#code-agents-and-supply-chain)
- [Prompt Injection and MCP](#prompt-injection-and-mcp)
- [Backdoors, Poisoning and Jailbreaks](#backdoors-poisoning-and-jailbreaks)
- [Defenses, Guardrails and Governance](#defenses-guardrails-and-governance)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [General Agent Safety](#general-agent-safety)

### Surveys and Position Papers

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [JARVIS or Ultron? A Survey on the Safety and Security Threats of Computer-Using Agents](https://aclanthology.org/2026.acl-long.2106/) | ACL | 2026 | Survey, OS Agents, Threat Modeling, Defense, Benchmark |
| [AI Agents May Always Fall for Prompt Injections](https://openreview.net/forum?id=GYhFkdxedz) | NeurIPS | 2026 | Prompt Injection, Contextual Privacy, Position Paper, Tool-Using Agents |
| [Agent Security is a Systems Problem](https://openreview.net/forum?id=8gDb2bnWWf) | NeurIPS | 2026 | Position Paper, Threat Modeling, Tool-Using Agents, Runtime Defense |
| [Position: A Safe LLM and a Safe Harness Do Not Make a Safe Agent](https://openreview.net/forum?id=FawL8cvevn) | NeurIPS | 2026 | Position Paper, Safety Evaluation, Contextual Privacy, Tool-Using Agents |
| [SoK: Attack and Defense Landscape of Agentic AI Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/kim-juhee-agentic) | USENIX | 2026 | Survey, Tool-Using Agents, Threat Modeling, Defense |
| [From Alignment to Access Control: A Unified View of GenAI Policy Enforcement](https://www.usenix.org/conference/usenixsecurity26/presentation-baracaldo) | USENIX | 2026 | Position Paper, Governance, Guardrails, Tool-Using Agents |
| [Position: Agent Security Needs Redefinition through a Holistic Framework](https://openreview.net/forum?id=HMQmLtcfme) | ICML | 2026 | Position Paper, Threat Modeling, Prompt Injection, Tool-Using Agents |
| [Position: Collusion Risks Among AI Reasoning Agents Justify Certification Requirements for Making Market Decisions](https://openreview.net/forum?id=Vhi9tHbKTa) | ICML | 2026 | Collusion, Position Paper, Multi-Agent Systems, Governance |
| [Position: Let’s Build a Trustworthy Model Context Protocol!](https://openreview.net/forum?id=02sR3qKGMd) | ICML | 2026 | MCP, Position Paper, Governance, Threat Modeling |
| [Position: To Defend Against Cyber Attacks, We Must Teach AI Agents to Hack](https://openreview.net/forum?id=P5t96sITf7) | ICML | 2026 | Position Paper, Governance, Red-Teaming, Threat Modeling |
| [Position: Academic Conferences are Potentially Facing Denominator Gaming Caused by Fully Automated Scientific Agents](https://openreview.net/forum?id=36ITkZHUMZ) | ICML | 2026 | Position Paper, Threat Modeling, Governance, Defense |
| [Position: Accountable Deployment of Agentic AI Demands Layered, System-Level Interpretability](https://openreview.net/forum?id=liNx7tarrT) | ICML | 2026 | Position Paper, Governance, Runtime Defense, Multi-Agent Systems |
| [Position: Agentic Safety is an Epistemic Property, Not a Behavioral One](https://openreview.net/forum?id=30mapdhNKH) | ICML | 2026 | Position Paper, Self-Evolving Agents, Governance |
| [Safety Must Precede the Deployment of Open Ended AI](https://arxiv.org/html/2605.01147v1) | ICML | 2026 | Open-Ended AI, AI Safety, Emergent Misalignment, Self-Evolving Agents, Position Paper |
| [Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents](https://arxiv.org/abs/2411.09523) | arXiv | 2024 | Survey, LLM Agents, Security, Privacy, Ethics, Threat Taxonomy |
| [A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445) | arXiv | 2025 | Survey, Agentic Security, Threat Model, Defense Mechanisms, LLM Agents |

### Multi-Agent Systems

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [Attack the Messages, Not the Agents: A Multi-round Adaptive Stealthy Tampering Framework for LLM-MAS](https://ojs.aaai.org/index.php/AAAI/article/view/40224) | AAAI | 2026 | Multi-Agent Systems, Communication-Plane, Red-Teaming, Adversarial Robustness |
| [Shadows in the Code: Exploring the Risks and Defenses of LLM-based Multi-Agent Software Development Systems](https://ojs.aaai.org/index.php/AAAI/article/view/41134) | AAAI | 2026 | Multi-Agent Systems, Code Agents, Red-Teaming, Defense |
| [ResMAS: Resilience Optimization in LLM-based Multi-agent Systems](https://ojs.aaai.org/index.php/AAAI/article/view/40824) | AAAI | 2026 | Multi-Agent Systems, Adversarial Robustness, Defense, Safety Evaluation |
| [Rethinking the Reliability of Multi-agent System: A Perspective from Byzantine Fault Tolerance](https://ojs.aaai.org/index.php/AAAI/article/view/40806) | AAAI | 2026 | Multi-Agent Systems, Adversarial Robustness, Defense, Safety Evaluation |
| [Whispering Agents: A Event-Driven Covert Communication Protocol for the Internet of Agents](https://ojs.aaai.org/index.php/AAAI/article/view/40380) | AAAI | 2026 | Communication-Plane, Multi-Agent Systems, Privacy, Threat Modeling |
| [LieCraft: A Multi-Agent Framework for Evaluating Deceptive Capabilities in Language Models](https://ojs.aaai.org/index.php/AAAI/article/view/41116) | AAAI | 2026 | Multi-Agent Systems, Safety Evaluation, Benchmark, Emergent Multi-Agent Risks |
| [Resilience in Ambient Multi-Agent LLMs via Decentralized Bio-Autonomic Control and Immune-Inspired Anomaly Detection](https://ojs.aaai.org/index.php/AAAI/article/view/41065) | AAAI | 2026 | Multi-Agent Systems, Runtime Defense, Privacy, Adversarial Robustness |
| [CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models](https://aclanthology.org/2026.findings-acl.342/) | ACL Findings | 2026 | Multi-Agent Systems, Red-Teaming, Communication-Plane, Adversarial Robustness |
| [From Tasks to Teams: A Risk-First Evaluation Framework for Multi-Agent LLM Systems in Finance](https://aclanthology.org/2026.findings-acl.1934/) | ACL Findings | 2026 | Multi-Agent Systems, Safety Evaluation, Benchmark, Tool-Using Agents |
| [PAC-BENCH: Evaluating Multi-Agent Collaboration under Privacy Constraints](https://aclanthology.org/2026.findings-acl.1552/) | ACL Findings | 2026 | Multi-Agent Systems, Contextual Privacy, Benchmark, Privacy |
| [The Adaptive Interrogator: Detecting Trojan LLMs in Multi-Agent Systems via Evolved Conversational Strategies](https://aclanthology.org/2026.findings-acl.1348/) | ACL Findings | 2026 | Multi-Agent Systems, Supply Chain Security, Backdoor Attack, Red-Teaming |
| [TopoSHIELD: Reshaping the Flow of Malice via Spatio-Temporal Risk-Aware Topological Evolution in Multi-Agent Systems](https://aclanthology.org/2026.findings-acl.426/) | ACL Findings | 2026 | Multi-Agent Systems, Prompt Injection, Defense, Runtime Defense |
| [Web Fraud Attacks Against LLM-Driven Multi-Agent Systems](https://aclanthology.org/2026.findings-acl.686/) | ACL Findings | 2026 | Multi-Agent Systems, Red-Teaming, Threat Modeling, Web Agents |
| [Automated Profile Inference with Language Model Agents](https://aclanthology.org/2026.findings-acl.485/) | ACL Findings | 2026 | Multi-Agent Systems, Privacy Leakage, Red-Teaming, Threat Modeling |
| [MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning](https://aclanthology.org/2026.findings-acl.340/) | ACL Findings | 2026 | Embodied Agents, Multi-Agent Systems, Safety Evaluation, Benchmark, Defense |
| [Measuring Large Language Models’ Adversarial Behavior in Social Deduction Games](https://aclanthology.org/2026.findings-acl.2043/) | ACL Findings | 2026 | Multi-Agent Systems, Safety Evaluation, Emergent Multi-Agent Risks, Red-Teaming |
| [ACIArena: Toward Unified Evaluation for Agent Cascading Injection](https://aclanthology.org/2026.acl-long.457/) | ACL | 2026 | Multi-Agent Systems, Prompt Injection, Benchmark, Red-Teaming, Communication-Plane |
| [Conjunctive Prompt Attacks in Multi-Agent LLM Systems](https://aclanthology.org/2026.acl-long.1577/) | ACL | 2026 | Multi-Agent Systems, Prompt Injection, Red-Teaming, Communication-Plane |
| [TAMAS: Benchmarking Adversarial Risks in Multi-Agent LLM Systems](https://aclanthology.org/2026.acl-long.1442/) | ACL | 2026 | Multi-Agent Systems, Benchmark, Red-Teaming, Safety Evaluation, Tool-Using Agents |
| [BlindGuard: Safeguarding LLM-based Multi-Agent Systems under Unknown Attacks](https://aclanthology.org/2026.acl-long.1819/) | ACL | 2026 | Multi-Agent Systems, Defense, Runtime Defense, Communication-Plane |
| [CIA: Inferring the Communication Topology from LLM-based Multi-Agent Systems](https://aclanthology.org/2026.acl-long.815/) | ACL | 2026 | Multi-Agent Systems, Privacy Leakage, Communication-Plane, Threat Modeling |
| [Evo-Attacker: Memory-Augmented Reinforcement Learning for Long-Horizon Tool Attacks on LLM-MAS](https://aclanthology.org/2026.acl-long.330/) | ACL | 2026 | Multi-Agent Systems, Red-Teaming, Tool-Using Agents, Memory Security |
| [Explainable and Fine-Grained Safeguarding of LLM Multi-Agent Systems via Bi-Level Graph Anomaly Detection](https://aclanthology.org/2026.acl-long.1407/) | ACL | 2026 | Multi-Agent Systems, Defense, Runtime Defense, Guardrails |
| [Lying with Truths: Open-Channel Multi-Agent Collusion for Belief Manipulation via Generative Montage](https://aclanthology.org/2026.acl-long.270/) | ACL | 2026 | Multi-Agent Systems, Collusion, Red-Teaming, Threat Modeling |
| [Among Us: Measuring and Mitigating Malicious Contributions in Model Collaboration Systems](https://aclanthology.org/2026.acl-long.725/) | ACL | 2026 | Multi-Agent Systems, Threat Modeling, Defense, Safety Evaluation |
| [Social Dynamics as Critical Vulnerabilities that Undermine Objective Decision-Making in LLM Collectives](https://aclanthology.org/2026.acl-long.1756/) | ACL | 2026 | Multi-Agent Systems, Adversarial Robustness, Emergent Multi-Agent Risks, Safety Evaluation |
| [Multimodal Safety Evaluation in Generative Agent Social Simulations](https://aclanthology.org/2026.acl-long.1915/) | ACL | 2026 | Multimodal Agents, Safety Evaluation, Multi-Agent Systems, Benchmark |
| [The Best-Laid SCHEMEs: Coordinated Sabotage and Monitoring in Multi-Agent Systems](https://openreview.net/forum?id=4f5ZeIKhaC) | NeurIPS | 2026 | Multi-Agent Systems, Code Agents, Collusion, Benchmark, Red-Teaming |
| [Alloy Agents Can Be More Dangerous Than Either Model Alone](https://openreview.net/forum?id=Is7kzM3Dxo) | NeurIPS | 2026 | Safety Evaluation, Multi-Agent Systems, Red-Teaming, Tool-Using Agents |
| [CASPIAN: Online Detection and Attribution of Cascade Attacks in LLM Multi-Agent Systems via Cross-Channel Causal Monitoring](https://openreview.net/forum?id=eERJSSfRu8) | NeurIPS | 2026 | Multi-Agent Systems, Runtime Defense, Communication-Plane, Emergent Multi-Agent Risks |
| [Colosseum: Auditing Collusion in Cooperative Multi-Agent Systems](https://openreview.net/forum?id=spCefvRCT6) | NeurIPS | 2026 | Multi-Agent Systems, Collusion, Safety Evaluation, Emergent Multi-Agent Risks |
| [Cross-User Poisoning: User-Task Boundary Failures in Multi-User Collaborative Language Agents](https://openreview.net/forum?id=y8FrK1agS0) | NeurIPS | 2026 | Prompt Injection, Multi-Agent Systems, Memory Security, Red-Teaming |
| [EV-AUDIT: A Co-Evolutionary Auditing Framework for Task Hijacking in Multi-Agent Systems](https://openreview.net/forum?id=jWQ6jNKfWI) | NeurIPS | 2026 | Multi-Agent Systems, Prompt Injection, Red-Teaming, Defense |
| [Harmless in Pieces, Harmful in Motion: Detecting Multi-Agent Jailbreaks](https://openreview.net/forum?id=H4BgVHh3ID) | NeurIPS | 2026 | Multi-Agent Systems, Jailbreaking, Runtime Defense, Benchmark |
| [Inter-Agent Influence: Evaluating Persuasion, Deception and Coercion in Multi-Agent Systems](https://openreview.net/forum?id=ziYeGq8OOt) | NeurIPS | 2026 | Multi-Agent Systems, Red-Teaming, Safety Evaluation, Emergent Multi-Agent Risks |
| [RIGOR: Risk-Gated Topology Adaptation for Robust LLM Multi-Agent Reasoning](https://openreview.net/forum?id=3IhTtHSifz) | NeurIPS | 2026 | Multi-Agent Systems, Adversarial Robustness, Runtime Defense, Defense |
| [To trust or not to trust: Attention-based Trust Management for LLM Multi-Agent Systems](https://openreview.net/forum?id=tRFYHQFSH4) | NeurIPS | 2026 | Multi-Agent Systems, Communication-Plane, Defense, Adversarial Robustness |
| [Who, Where, and What? Forensic Localization in LLM-Based Multi-Agent Systems](https://openreview.net/forum?id=UMANMGt0wj) | NeurIPS | 2026 | Multi-Agent Systems, Threat Modeling, Benchmark, Defense |
| [MemeEconomy : Do LLM Agents Trade Ethics for Survival?](https://openreview.net/forum?id=ZZY8GhvJ9a) | NeurIPS | 2026 | Safety Evaluation, Multimodal Agents, Benchmark, Emergent Multi-Agent Risks |
| [Risk-Calibrated Context Selection for Healthcare Multi-Agent Handoff](https://openreview.net/forum?id=FLlWDrOo4c) | NeurIPS | 2026 | Multi-Agent Systems, Privacy, Governance, Memory Security |
| [Youdunit: Single-Call Counterfactual Necessity in Multi-Agent LLM Systems](https://openreview.net/forum?id=Z2GhavtsII) | NeurIPS | 2026 | Multi-Agent Systems, Safety Evaluation, Red-Teaming, Threat Modeling |
| [Control Charts for Multi-Agent Systems](https://openreview.net/forum?id=0ef8FCdBWk) | NeurIPS | 2026 | Multi-Agent Systems, Runtime Defense, Adversarial Robustness, Emergent Multi-Agent Risks |
| [A2ASecBench: A Protocol-Aware Security Benchmark for Agent-to-Agent Multi-Agent Systems](https://openreview.net/forum?id=LfdFnakqGJ) | ICLR | 2026 | Multi-Agent Systems, Benchmark, Communication-Plane, Threat Modeling, Supply Chain Security |
| [Goal-Aware Identification and Rectification of Misinformation in Multi-Agent Systems](https://openreview.net/forum?id=6Y9NP1qhoM) | ICLR | 2026 | Multi-Agent Systems, Prompt Injection, Benchmark, Defense |
| [When Agents “Misremember” Collectively: Exploring the Mandela Effect in LLM-based Multi-Agent Systems](https://openreview.net/forum?id=yIoMqDes7O) | ICLR | 2026 | Multi-Agent Systems, Memory Security, Benchmark, Defense |
| [Aligned Agents, Biased Swarm: Measuring Bias Amplification in Multi-Agent Systems](https://openreview.net/forum?id=mo7u21GoQv) | ICLR | 2026 | Multi-Agent Systems, Emergent Multi-Agent Risks, Benchmark, Safety Evaluation |
| [LH-DECEPTION: Simulating and Understanding LLM Deceptive Behaviors in Long-Horizon Interactions](https://openreview.net/forum?id=2r10vpYiti) | ICLR | 2026 | Multi-Agent Systems, Safety Evaluation, Benchmark, Emergent Multi-Agent Risks |
| [Measuring and Mitigating Rapport Bias of Large Language Models under Multi-Agent Social Interactions](https://openreview.net/forum?id=gF31wuYdk7) | ICLR | 2026 | Multi-Agent Systems, Benchmark, Adversarial Robustness, Safety Evaluation |
| [MASLeak: Investigating and Exposing Intellectual Property Leakage Vulnerabilities in Multi-Agent Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/wang-liwen) | USENIX | 2026 | Multi-Agent Systems, Privacy Leakage, Red-Teaming, Tool-Using Agents |
| [Overcoming the Retrieval Barrier: Indirect Prompt Injection in the Wild for LLM Systems](https://www.usenix.org/conference/usenixsecurity26/presentation/chang-hongyan) | USENIX | 2026 | Prompt Injection, RAG Security, Tool-Using Agents, Multi-Agent Systems |
| [SAGA: A Security Architecture for Governing AI Agentic Systems](https://www.ndss-symposium.org/ndss-paper/saga-a-security-architecture-for-governing-ai-agentic-systems/) | NDSS | 2026 | Governance, Multi-Agent Systems, Communication-Plane, Control-Plane |
| [AdvEvo-MARL: Shaping Internalized Safety through Adversarial Co-Evolution in Multi-Agent Reinforcement Learning](https://openreview.net/forum?id=5D3ZblXmW2) | ICML | 2026 | Multi-Agent Systems, Multi-Agent RL, Jailbreaking, Defense |
| [Architecture Matters for Multi-Agent Security](https://openreview.net/forum?id=Jk4zLorDUx) | ICML | 2026 | Multi-Agent Systems, Web Agents, Threat Modeling, Safety Evaluation |
| [MaMa: A Game-Theoretic Approach for Designing Safe Agentic Systems](https://openreview.net/forum?id=KR6avDABG8) | ICML | 2026 | Multi-Agent Systems, Defense, Adversarial Robustness, Threat Modeling |
| [Securing Multi-Agent Systems Against Corruptions via Node Contribution Backpropagation](https://openreview.net/forum?id=TphOLCDmKB) | ICML | 2026 | Multi-Agent Systems, Defense, Guardrails, Adversarial Robustness |
| [Speculative Safety Honeypot: Toward Proactive Defense Against Multi-turn Agent Attacks](https://openreview.net/forum?id=F7KJeI4oql) | ICML | 2026 | Runtime Defense, Multi-Agent Systems, Defense, Tool-Using Agents |
| [Sponge Tool Attack: Stealthy Denial-of-Efficiency against Tool-Augmented Agentic Reasoning](https://openreview.net/forum?id=g9fZTb53kL) | ICML | 2026 | Tool-Using Agents, Red-Teaming, Adversarial Robustness, Multi-Agent Systems |
| [When Agents Go Rogue: Activation-Based Detection of Malicious Behaviors in Multi-Agent Systems](https://openreview.net/forum?id=BnduUW8izq) | ICML | 2026 | Multi-Agent Systems, Runtime Defense, Defense, Adversarial Robustness |
| [When Embedding-Based Defenses Fail: Rethinking Safety in LLM-Based Multi-Agent Systems](https://openreview.net/forum?id=j5ibZwkwqF) | ICML | 2026 | Multi-Agent Systems, Red-Teaming, Defense, Communication-Plane |
| [AutoRAS: Learning Robust Agentic Systems with Primitive Representations](https://openreview.net/forum?id=7zTV4dvdGB) | ICML | 2026 | Multi-Agent Systems, Adversarial Robustness, Defense, Safety Evaluation |
| [Emergence of Biased Consensus in Multi-Agent LLM Debates](https://openreview.net/forum?id=5EtByXq4bX) | ICML | 2026 | Multi-Agent Systems, Emergent Multi-Agent Risks, Safety Evaluation |
| [Judgment Operators: A Composition-Invariant Substrate for Multi-Agent Action Spaces](https://openreview.net/forum?id=8Ysr6x0XMv) | ICML | 2026 | Multi-Agent Systems, Governance, Runtime Defense, Guardrails |
| [OMNI-LEAK: Orchestrator Multi-Agent Network Induced Data Leakage](https://arxiv.org/pdf/2602.13477v1) | arXiv | 2026 | Multi-Agent, Orchestrator, Prompt Injection, Data Leakage, Privacy |
| [Fault Tolerant Multi-Agent Learning with Adversarial Budget Constraints](https://arxiv.org/abs/2508.08800) | ICML | 2026 | Multi-Agent RL, Fault Tolerance, Adversarial Robustness, Cooperative MARL, Safety-Critical Systems |
| [FLOWSTEER: Prompt-Only Workflow Steering - Exposes Planning-Time Vulnerabilities in Multi-Agent LLM Systems](https://arxiv.org/pdf/2605.11514) | arXiv | 2026 | Multi-Agent Systems, Workflow Steering, Prompt Injection, Planning-Time Attack, Defense |
| [Self-Adaptive Multi-Agent LLM-Based Security Pattern Selection for IoT Systems](https://arxiv.org/pdf/2605.00741) | arXiv | 2026 | Multi-Agent LLM Systems, IoT Security, Edge Computing, Runtime Defense, Security Adaptation, Resource-Constrained Systems |
| [TrinityGuard: A Unified Framework for Safeguarding Multi-Agent Systems](https://arxiv.org/pdf/2603.15408) | arXiv | 2026 | Multi-Agent Systems, Safety Framework, Risk Taxonomy, Evaluation Framework, Runtime Monitoring, LLM-based Systems |
| [SafeClaw-R: Towards Safe and Secure Multi-Agent Personal Assistants](https://arxiv.org/pdf/2603.28807) | arXiv | 2026 | Multi-Agent Systems, Runtime Enforcement, Safety Framework, Prompt Injection, Personal Assistants, Security |
| [Financial fraud collusion among generative AI agents in social networks](https://openreview.net/pdf?id=a1d2smwmBS) | ICLR | 2026 | financial fraud, multi-agent system, agent society |
| [The Sum Leaks More Than Its Parts: Compositional Privacy Risks and Mitigations in Multi-Agent Collaboration](https://arxiv.org/pdf/2509.14284) | arXiv | 2025 | Multi-Agent Collaboration, Privacy Risk, Mitigation |
| [AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement](https://openreview.net/pdf?id=mlU9KqdZUS) | NeurIPS | 2025 | AI Safety, Multi-Agent Systems, LLMs, Large Language Models, Jailbreaking, Agent Scaffolds |
| [BREAKING AND FIXING DEFENSES AGAINST CONTROL-FLOW HIJACKING IN MULTI-AGENT SYSTEMS](https://arxiv.org/abs/2510.17276) | arXiv | 2025 | Multi-Agent Systems, Control-Flow Hijacking, Defense, Agent Security |
| [LLM-based Multi-Agents System Attack via Continuous Optimization with Discrete Efficient Search](https://openreview.net/forum?id=ED5diyzc1C#discussion) | COLM | 2025 | Multi-Agent Systems, Adversarial Attack, Continuous Optimization, Discrete Search |
| [A Troublemaker with Contagious Jailbreak Makes Chaos in Honest Towns](https://aclanthology.org/2025.acl-long.859.pdf) | ACL | 2025 | Contagious Jailbreak, Multi-Agent Systems, LLM Agents, Agent Safety |
| [AgentSafe: Safeguarding Large Language Model-based Multi-agent Systems via Hierarchical Data Management](https://arxiv.org/pdf/2503.04392) | arXiv | 2025 | Multi-Agent Systems, Hierarchical Data Management, LLM Agents, Safety |
| [AgentCrypt: Advancing Privacy and (Secure) Computation in AI Agent Collaboration](https://neurips.cc/virtual/2025/loc/san-diego/130200) | NeurIPS Workshop (Regulatable ML) | 2025 | Agent Collaboration, Privacy, Secure Computation, AI Agents |
| [Information-Theoretic Privacy Control for Sequential Multi-Agent LLM Systems](https://arxiv.org/pdf/2603.05520) | arXiv | 2026 | Information-Theoretic Privacy, Multi-Agent LLM Systems, Privacy Control |
| [Topology Matters: Measuring Memory Leakage in Multi-Agent LLMs](https://arxiv.org/pdf/2512.04668) | arXiv | 2026 | Multi-Agent LLMs, Memory Leakage, Topology, Privacy |
| [MAGPIE: A Benchmark for Multi-AGent Contextual PrIvacy Evaluation](https://openreview.net/pdf?id=vZgdho8Vx0) | NeurIPS Workshop (ResponsibleFM) | 2025 | Multi-Agent Systems, Contextual Privacy, Benchmark, Evaluation |
| [Secret Collusion Among AI Agents: Multi-Agent Deception via Steganography](https://openreview.net/forum?id=bnNSQhZJ88) | NeurIPS | 2024 | Multi-Agent Collusion, Steganography, Covert Communication, AI Safety |
| [Conformity and Social Impact on AI Agents](https://arxiv.org/abs/2601.05384) | arXiv | 2026 | Multi-Agent Systems, Social Influence, Conformity Bias, Emergent Risks, Manipulation Attacks |
| [Agent2Agent Threats in Safety-Critical LLM Assistants: A Human-Centric Taxonomy](https://arxiv.org/abs/2602.05877) | arXiv | 2026 | Communication-Plane Attacks, Data-Plane Propagation, Control-Plane Risks, Threat Modeling, Multi-Agent Systems |
| [Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale](https://arxiv.org/abs/2601.10338) | arXiv | 2026 | Data-Plane Leakage, Control-Plane Attacks, Prompt Injection, Supply Chain Security, Multi-Agent Systems |
| [GT-HarmBench: Benchmarking AI Safety Risks Through the Lens of Game Theory](https://arxiv.org/abs/2602.12316) | arXiv | 2026 | Emergent Multi-Agent Risks, Coordination Dynamics, Game-Theoretic Evaluation, Safety Benchmarking, Alignment Failures |
| [Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://arxiv.org/abs/2402.08567) | ICML | 2024 | Infectious Jailbreak, Multimodal Agents, Multi-Agent Systems, Adversarial Images |
| [Safe in Isolation, Dangerous Together: Agent-Driven Multi-Turn Decomposition Jailbreaks on LLMs](https://aclanthology.org/2025.realm-1.13/) | ACL Workshop (REALM) | 2025 | Multi-Agent Jailbreak, Task Decomposition, LLM Safety, Agent Coordination |
| [PsySafe: A Comprehensive Framework Integrating Psychological Insights, Adversarial Testing, and Protective Measures for Safe Multi-Agent System Design](https://arxiv.org/abs/2401.11880) | ACL | 2024 | Multi-Agent Safety, Psychological Manipulation, Adversarial Testing, Identity Attack |
| [The Trust Paradox in LLM-Based Multi-Agent Systems: When Collaboration Becomes a Security Vulnerability](https://arxiv.org/abs/2510.18563) | arXiv | 2025 | Multi-Agent Systems, Trust, Security Vulnerability, LLM Collaboration, Agent Safety |
| [Exposing Weak Links in Multi-Agent Systems under Adversarial Prompting](https://arxiv.org/abs/2511.10949) | arXiv | 2025 | Multi-Agent Systems, Adversarial Prompting, Weak Links, Agent Security, Robustness |
| [Multi-Agent Risks from Advanced AI](https://arxiv.org/abs/2502.14143) | arXiv | 2025 | Emergent Multi-Agent Risks, System-Level Failures, Incentive Misalignment, Coordination Dynamics, Risk Factors |
| [LLM Agents Should Employ Security Principles](https://arxiv.org/abs/2505.24019) | arXiv | 2025 | Defense Mechanisms, Control-Plane Security, Data-Plane Protection, Secure Agent Design, Multi-Agent Systems |
| [Agents Under Siege: Breaking Pragmatic Multi-Agent LLM Systems with Optimized Prompt Attacks](https://aclanthology.org/2025.acl-long.476/) | ACL | 2025 | Communication-Plane Attacks, Multi-Agent Security, Prompt Injection Attacks, Topology-Aware Attacks, Defense Evasion |
| [Design Patterns for Securing LLM Agents against Prompt Injections](https://arxiv.org/abs/2506.08837) | arXiv | 2025 | Communication-Plane Attacks, Prompt Injection Mitigation, Defense Mechanisms, Secure Agent Design, Control-Plane Security |
| [Simple Prompt Injection Attacks Can Leak Personal Data Observed by LLM Agents During Task Execution](https://arxiv.org/abs/2506.01055) | arXiv | 2025 | Data-Plane Leakage, Communication-Plane Attacks, Prompt Injection, Agent Workflows, Privacy Risks |
| [A Multi-Agent LLM Defense Pipeline Against Prompt Injection Attacks](https://arxiv.org/abs/2509.14285) | arXiv | 2025 | Communication-Plane Defense, Multi-Agent Defense, Prompt Injection Mitigation, Runtime Protection, Agent Architectures |
| [RTBAS: Defending LLM Agents Against Prompt Injection and Privacy Leakage](https://arxiv.org/abs/2502.08966) | arXiv | 2025 | Data-Plane Protection, Communication-Plane Defense, Control-Plane Safety, Tool Invocation Security, Runtime Enforcement |
| [Multi-Agent Systems Execute Arbitrary Malicious Code](https://arxiv.org/abs/2503.12188) | arXiv | 2026 | Communication-Plane Attacks, Control-Plane Compromise, Data-Plane Leakage, Emergent Multi-Agent Risks, System Security |
| [PsySafe: A Comprehensive Framework Integrating Psychological Insights, Adversarial Testing, and Protective Measures for Safe Multi-Agent System Design](https://arxiv.org/abs/2401.11880) | ACL | 2024 | Multi-Agent Safety, Psychological Manipulation, Adversarial Testing, Identity Attack |
| [Safe in Isolation, Dangerous Together: Agent-Driven Multi-Turn Decomposition Jailbreaks on LLMs](https://aclanthology.org/2025.realm-1.13/) | ACL Workshop (REALM) | 2025 | Multi-Agent Jailbreak, Task Decomposition, LLM Safety, Agent Coordination |
| [The Trust Paradox in LLM-Based Multi-Agent Systems: When Collaboration Becomes a Security Vulnerability](https://arxiv.org/abs/2510.18563) | arXiv | 2025 | Multi-Agent Systems, Trust, Security Vulnerability, LLM Collaboration |
| [Exposing Weak Links in Multi-Agent Systems under Adversarial Prompting](https://arxiv.org/abs/2511.10949) | arXiv | 2025 | Multi-Agent Systems, Adversarial Prompting, Weak Links, Agent Security |
| [Multi-Agent Risks from Advanced AI](https://arxiv.org/abs/2502.14143) | arXiv | 2025 | Emergent Multi-Agent Risks, System-Level Failures, Incentive Misalignment, Coordination Dynamics |
| [Agent2Agent Threats in Safety-Critical LLM Assistants: A Human-Centric Taxonomy](https://arxiv.org/abs/2602.05877) | arXiv | 2026 | Communication-Plane Attacks, Threat Modeling, Multi-Agent Systems, Safety-Critical AI |
| [Evil Geniuses: Delving into the Safety of LLM-based Agents](https://arxiv.org/abs/2311.11855) | arXiv | 2023 | LLM Agent Safety, Multi-Agent Attack, Role-Based Jailbreak, Red-Teaming |
| [Prompt Infection: LLM-to-LLM Prompt Injection within Multi-Agent Systems](https://arxiv.org/abs/2410.07283) | ICLR | 2025 | Multi-Agent Systems, LLM-to-LLM Injection, Self-Replication Attack, Prompt Infection |
| [Flooding Spread of Manipulated Knowledge in LLM-Based Multi-Agent Communities](https://arxiv.org/abs/2407.07791) | arXiv | 2024 | Multi-Agent Systems, Knowledge Poisoning, RAG Persistence, Counterfactual Injection |
| [Firewalls to Secure Dynamic LLM Agentic Networks](https://arxiv.org/abs/2502.01822) | arXiv | 2025 | Multi-Agent Defense, Firewall Architecture, Prompt Injection, Privacy Protection |
| [Open Challenges in Multi-Agent Security: Towards Secure Systems of Interacting AI Agents](https://arxiv.org/abs/2505.02077) | arXiv | 2025 | Multi-Agent Security, Open Challenges, Interacting Agents, Security Framework |
| [Pandora: Jailbreaking GPT-4 via Collaborated Phishing Agents](https://arxiv.org/abs/2401.12961) | ICLR | 2024 | Jailbreak, Multi-Agent Attack, Phishing Agents, GPT-4 Security |
| [The Wolf Within: Covert Injection of Malice into MLLM Societies via an MLLM Operative](https://arxiv.org/abs/2402.14859) | arXiv | 2024 | Multimodal LLM, Multi-Agent Societies, Covert Injection, Agent Collusion |
| [Certified Secure Cooperative MARL against Byzantine Adversarial Attacks](https://arxiv.org/abs/2406.06984) | NeurIPS | 2024 | Multi-Agent RL, Byzantine Attacks, Certified Defense, Cooperative MARL |

### Privacy, Memory and Data Leakage

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered Smartphone Agents](https://ojs.aaai.org/index.php/AAAI/article/view/40874) | AAAI | 2026 | Contextual Privacy, Benchmark, OS Agents, Privacy Leakage |
| [Fact2Fiction: Targeted Poisoning Attack to Agentic Fact-checking System](https://ojs.aaai.org/index.php/AAAI/article/view/40353) | AAAI | 2026 | Knowledge Poisoning, RAG Security, Red-Teaming, Threat Modeling |
| [BackdoorAgent: A Unified Framework for Backdoor Attacks on LLM-based Agents](https://aclanthology.org/2026.findings-acl.791/) | ACL Findings | 2026 | Backdoor Attack, Tool-Using Agents, Memory Security, Benchmark, Threat Modeling |
| [On Safety Risks in Experience-Driven Self-Evolving Agents](https://aclanthology.org/2026.findings-acl.2091/) | ACL Findings | 2026 | Self-Evolving Agents, Safety Evaluation, Web Agents, Embodied Agents, Memory Security |
| [Your LLM Agent Can Leak Your Data: Data Exfiltration via Backdoored Tool Use](https://aclanthology.org/2026.findings-acl.1257/) | ACL Findings | 2026 | Backdoor Attack, Tool-Using Agents, Privacy Leakage, Memory Security |
| [PerMemSafe: Benchmarking Implicit Personalized Safety of Long Horizon Self-Evolving Agents](https://aclanthology.org/2026.findings-acl.320/) | ACL Findings | 2026 | Self-Evolving Agents, Memory Security, Benchmark, Safety Evaluation |
| [If Only My CGM Could Speak: A Privacy-Preserving Agent for Question Answering over Continuous Glucose Data](https://aclanthology.org/2026.findings-acl.891/) | ACL Findings | 2026 | Privacy, Tool-Using Agents, Privacy Leakage, Benchmark |
| [Stop Fixating on Prompts: Reasoning Hijacking and Constraint Tightening for Red-Teaming LLM Agents](https://aclanthology.org/2026.acl-long.1197/) | ACL | 2026 | Red-Teaming, Memory Security, Tool-Using Agents, Jailbreaking |
| [Visual Inception: Compromising Long-term Planning in Agentic Recommenders via Multimodal Memory Poisoning](https://aclanthology.org/2026.acl-long.954/) | ACL | 2026 | Memory Security, Multimodal Agents, Defense, Knowledge Poisoning |
| [When Personalization Legitimizes Risks: Uncovering Safety Vulnerabilities in Personalized Dialogue Agents](https://aclanthology.org/2026.acl-long.1260/) | ACL | 2026 | Memory Security, Benchmark, Safety Evaluation, Red-Teaming |
| [Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models](https://aclanthology.org/2026.acl-long.400/) | ACL | 2026 | Contextual Privacy, Privacy Leakage, Tool-Using Agents, Memory Security, Safety Evaluation |
| [Query-Efficient Agentic Graph Extraction Attacks on GraphRAG Systems](https://aclanthology.org/2026.acl-long.727/) | ACL | 2026 | RAG Security, Privacy Leakage, Knowledge Poisoning, Red-Teaming |
| [MemPoison: Uncovering Persistent Memory Threats and Structural Blind Spots in LLM Agents](https://openreview.net/forum?id=IgiZ5D2F8T) | NeurIPS | 2026 | Memory Security, Benchmark, Knowledge Poisoning, Tool-Using Agents |
| [SecureClaw: Clawing Back Control of LLM Agents](https://openreview.net/forum?id=0omFi3ZiBf) | NeurIPS | 2026 | Tool-Using Agents, Prompt Injection, Privacy Leakage, Runtime Defense, Guardrails |
| [GUIGuard-Bench: Toward a General Evaluation for Privacy-Preserving GUI Agents](https://openreview.net/forum?id=FnL0OI4r5R) | NeurIPS | 2026 | Benchmark, Privacy, Contextual Privacy, OS Agents, Multimodal Agents |
| [Known By Their Actions: Fingerprinting LLM Browser Agents via UI Traces](https://openreview.net/forum?id=DT4P4Xo3iP) | NeurIPS | 2026 | Web Agents, Privacy Leakage, Threat Modeling, Red-Teaming |
| [LiSA: Lifelong Safety Adaptation via Conservative Policy Induction](https://openreview.net/forum?id=UJDUd0ySXi) | NeurIPS | 2026 | Guardrails, Contextual Privacy, Memory Security, Tool-Using Agents |
| [POLAR-Bench: A Diagnostic Benchmark for Privacy-Utility Trade-offs in LLM Agents](https://openreview.net/forum?id=Y4sDfO3t6Q) | NeurIPS | 2026 | Benchmark, Contextual Privacy, Privacy Leakage, Tool-Using Agents |
| [Reasoning Poisoning: Utilizing Social-Engineering to Steer Chain-of-Thought](https://openreview.net/forum?id=ZswTm9bjg9) | NeurIPS | 2026 | Knowledge Poisoning, RAG Security, Red-Teaming, Tool-Using Agents |
| [Inadvertent Context Leakage in Language Models](https://openreview.net/forum?id=wWnXkSFoza) | NeurIPS | 2026 | Privacy Leakage, Contextual Privacy, Red-Teaming, Tool-Using Agents |
| [PAAC: Privacy-Aware Agentic Device-Cloud Collaboration](https://openreview.net/forum?id=pkgQ4KB4Se) | NeurIPS | 2026 | Privacy Leakage, Tool-Using Agents, Privacy, Defense |
| [Measuring Physical-World Privacy Awareness of Large Language Models: An Evaluation Benchmark](https://openreview.net/forum?id=WSpDZVEGNi) | ICLR | 2026 | Benchmark, Embodied Agents, Privacy, Contextual Privacy |
| [FragFuse: Bypassing Access Control of Large Language Model Agents via Memory-Based Query Fragmentation and Fusion](https://www.usenix.org/conference/usenixsecurity26/presentation/rao) | USENIX | 2026 | Memory Security, Tool-Using Agents, Red-Teaming, Jailbreaking |
| [Breaking the Lethal Trifecta: Secure Agentic Computing via Causal Isolation Architecture](https://www.usenix.org/conference/usenixsecurity26/presentation/tsao) | USENIX | 2026 | Contextual Privacy, Privacy Leakage, Defense, Tool-Using Agents |
| [Network-Level Prompt and Trait Leakage in Local Research Agents](https://www.usenix.org/conference/usenixsecurity26/presentation/jeong) | USENIX | 2026 | Web Agents, Privacy Leakage, Privacy, Threat Modeling |
| [InjecMEM: Memory Injection Attack on LLM Agent Memory Systems](https://arxiv.org/abs/2608.23471) | COLM | 2026 | Memory Security, Prompt Injection, Knowledge Poisoning, Tool-Using Agents |
| [Autonomy Reshapes How Personalization Affects Privacy Concerns and Trust in LLM Agents](https://arxiv.org/abs/2510.04465) | COLM | 2026 | Privacy, Tool-Using Agents, Safety Evaluation, Privacy Leakage |
| [Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://www.ndss-symposium.org/ndss-paper/les-dissonances-cross-tool-harvesting-and-polluting-in-pool-of-tools-empowered-llm-agents/) | NDSS | 2026 | Tool-Using Agents, Threat Modeling, Privacy Leakage, Supply Chain Security |
| [Parasites in the Toolchain: A Large-Scale Analysis of Attacks on the MCP Ecosystem](https://doi.org/10.1109/sp63933.2026.00154) | IEEE S&P | 2026 | MCP, Privacy Leakage, Supply Chain Security, Tool-Using Agents, Threat Modeling |
| [AttnTrace: Contextual Attribution of Prompt Injection and Knowledge Corruption](https://doi.org/10.1109/sp63933.2026.00198) | IEEE S&P | 2026 | Prompt Injection, Knowledge Poisoning, RAG Security, Defense |
| [A-MemGuard: A Proactive Defense Framework For LLM-Based Agent Memory](https://openreview.net/forum?id=udqe7UZUZ6) | ICML | 2026 | Memory Security, Defense, Knowledge Poisoning, Tool-Using Agents |
| [AgentLAB: Benchmarking LLM Agents against Long-Horizon Attacks](https://openreview.net/forum?id=Bb0pQqsiad) | ICML | 2026 | Benchmark, Red-Teaming, Memory Security, Tool-Using Agents, Prompt Injection |
| [Contextualized Privacy Defense for LLM Agents](https://openreview.net/forum?id=b4QtBbSV3X) | ICML | 2026 | Contextual Privacy, Privacy Leakage, Tool-Using Agents, Defense |
| [MemIncept: Steering LLM Agents via Cooperative Stealthy Memory Injections](https://openreview.net/forum?id=1YNrlSSRsk) | ICML | 2026 | Memory Security, Knowledge Poisoning, Red-Teaming, Tool-Using Agents |
| [SOPE: Situation-Aware and Statistically Indistinguishable Privacy Exfiltration for MCP-enabled Agents](https://openreview.net/forum?id=Ra0pui9HXF) | ICML | 2026 | MCP, Supply Chain Security, Privacy Leakage, Prompt Injection |
| [*MemPot*: Defend Against Memory Extraction Attack with Optimized Honeypots](https://openreview.net/forum?id=goUAT3UcR4) | ICML | 2026 | Memory Security, Privacy Leakage, Defense, Tool-Using Agents |
| [From Weak Cues to Real Identities: Evaluating Inference-Driven De-Anonymization in LLM Agents](https://openreview.net/forum?id=Kux5q1mL1x) | ICML | 2026 | Privacy Leakage, Privacy, Benchmark, Tool-Using Agents |
| [Just Ask: Curious Code Agents Reveal System Prompts in Frontier LLMs](https://openreview.net/forum?id=qFWLv8bLL2) | ICML | 2026 | Code Agents, Red-Teaming, Privacy Leakage, Tool-Using Agents |
| [Learning When to Act or Refuse: Guarding Agentic Reasoning Models for Safe Multi-Step Tool Use](https://openreview.net/forum?id=Stf5SF4JvR) | ICML | 2026 | Tool-Using Agents, Defense, Prompt Injection, Privacy Leakage |
| [MINIM: Privacy-Aware Minimal View for Agents via Trusted Local Sanitization](https://openreview.net/forum?id=rW2xHmYrZA) | ICML | 2026 | Contextual Privacy, Privacy Leakage, OS Agents, Defense |
| [SafeHarbor: Defining Precise Decision Boundaries via Hierarchical Memory-Augmented Guardrail for LLM Agent Safety](https://openreview.net/forum?id=MEKj3d9Bf3) | ICML | 2026 | Guardrails, Tool-Using Agents, Memory Security, Defense |
| [``Someone Hid It!'': Query-Agnostic Black-Box Attacks on LLM-Based Retrieval](https://openreview.net/forum?id=bzmt9wJ6uW) | ICML | 2026 | RAG Security, Memory Security, Knowledge Poisoning, Adversarial Robustness |
| [Searching for Privacy Risks in LLM Agents via Simulation](https://openreview.net/pdf?id=nz4ZqbrBEi) | ICLR | 2026 | LLM Agent, Privacy, Search, AI Risk |
| [BEYOND JAILBREAKING: AUDITING CONTEXTUAL PRIVACY IN LLM AGENTS](https://openreview.net/pdf?id=6EDpNDns1i) | ICLR | 2026 | Contextual Privacy, LLM Agents, Privacy Auditing |
| [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://openreview.net/forum?id=xMOLUzo2Lk) | ICLR | 2025 | Environmental Injection Attack, Web Agents, Privacy Leakage |
| [R-Judge: Benchmarking Safety Risk Awareness for LLM Agents](https://arxiv.org/pdf/2401.10019) | EMNLP | 2024 | LLM Agent, Privacy, Search, AI Risk |
| [AGENTPOISON: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://openreview.net/forum?id=Y841BRW9rY) | NeurIPS | 2024 | Red-Teaming, Memory Poisoning, Knowledge Base Poisoning, LLM Agents |
| [AGENTDAM: Privacy Leakage Evaluation for Autonomous Web Agents](https://openreview.net/pdf?id=qaxf7q41aK) | NeurIPS | 2025 | Privacy Leakage, Autonomous Web Agents, Evaluation |
| [Protecting Users From Themselves: Safeguarding Contextual Privacy in Interactions with Conversational Agents](https://aclanthology.org/2025.findings-acl.1343.pdf) | ACL | 2025 | Conversational Agents, Contextual Privacy, User Safety, Privacy Protection |
| [AGENT TOOLS ORCHESTRATION LEAKS MORE: DATASET, BENCHMARK, AND MITIGATION](https://arxiv.org/pdf/2512.16310) | arXiv | 2025 | Tool Orchestration, Data Leakage, Benchmark, Mitigation |
| [PrivAct: Internalizing Contextual Privacy Preservation via Multi-Agent Preference Training](https://arxiv.org/pdf/2602.13840v1) | arXiv | 2026 | Contextual Privacy, Multi-Agent Preference Training, Privacy Preservation |
| [Towards Verifiably Safe Tool Use for LLM Agents](https://arxiv.org/abs/2601.08012) | arXiv | 2026 | Data-Plane Leakage, Control-Plane Constraints, Tool Invocation Safety, Formal Guarantees, Agent Systems |
| [Unveiling Privacy Risks in LLM Agent Memory](https://aclanthology.org/2025.acl-long.1227/) | ACL | 2025 | Memory Extraction, Privacy Risks, LLM Agents, Black-Box Attack |
| [Ghost of the Past: Identifying and Resolving Privacy Leakage of LLM's Memory Through Proactive User Interaction](https://arxiv.org/abs/2410.14931) | arXiv | 2024 | Memory Privacy, LLM Agents, Privacy Leakage, User Interaction |
| [RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications](https://arxiv.org/abs/2411.14110) | arXiv | 2024 | RAG, Data Extraction, Privacy, LLM Agents |
| [PoisonedRAG: Knowledge Poisoning Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867) | arXiv | 2024 | RAG, Knowledge Poisoning, LLM Security, Retrieval Attack |
| [Log-To-Leak: Prompt Injection Attacks on Tool-Using LLM Agents via Model Context Protocol](https://openreview.net/forum?id=UVgbFuXPaO) | arXiv | 2025 | MCP, Prompt Injection, Data Exfiltration, Tool-Using Agents |
| [Governance Architecture for Autonomous Agent Systems: Threats, Framework, and Engineering Practice](https://arxiv.org/abs/2603.07191) | arXiv | 2026 | Autonomous Agents, Governance Framework, Prompt Injection, RAG Poisoning, Tool Invocation Security |
| [Differential Privacy in Generative AI Agents: Analysis and Optimal Tradeoffs](https://arxiv.org/abs/2603.17902) | arXiv | 2026 | Differential Privacy, Generative AI Agents, Privacy-Utility Tradeoffs, LLM Privacy |
| [Imprompter: Tricking LLM Agents into Improper Tool Use](https://arxiv.org/abs/2410.14923) | arXiv | 2024 | Data-Plane Leakage, Control-Plane Attacks, Tool Invocation Exploits, Adversarial Prompts, Multimodal Threats |
| [PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models](https://arxiv.org/abs/2402.07867) | arXiv | 2024 | RAG, Knowledge Poisoning, Retrieval Attack, LLM Security |
| [RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications](https://arxiv.org/abs/2411.14110) | arXiv | 2024 | RAG, Data Extraction, Privacy Leakage, LLM Agents |
| [Ghost of the Past: Identifying and Resolving Privacy Leakage of LLM's Memory Through Proactive User Interaction](https://arxiv.org/abs/2410.14931) | arXiv | 2024 | Memory Privacy, LLM Agents, Privacy Leakage, User Interaction |
| [Unveiling Privacy Risks in LLM Agent Memory](https://aclanthology.org/2025.acl-long.1227/) | ACL | 2025 | Memory Extraction, Privacy Risks, LLM Agents, Black-Box Attack |
| [Log-To-Leak: Prompt Injection Attacks on Tool-Using LLM Agents via Model Context Protocol](https://openreview.net/forum?id=UVgbFuXPaO) | arXiv | 2025 | MCP, Prompt Injection, Data Exfiltration, Tool-Using Agents |
| [Imprompter: Tricking LLM Agents into Improper Tool Use](https://arxiv.org/abs/2410.14923) | arXiv | 2024 | Tool Invocation Exploits, Adversarial Prompts, Data Leakage, Multimodal Threats |
| [Governance Architecture for Autonomous Agent Systems: Threats, Framework, and Engineering Practice](https://arxiv.org/abs/2603.07191) | arXiv | 2026 | Autonomous Agents, Governance Framework, Prompt Injection, RAG Poisoning, Tool Security |
| [Differential Privacy in Generative AI Agents: Analysis and Optimal Tradeoffs](https://arxiv.org/abs/2603.17902) | arXiv | 2026 | Differential Privacy, Generative AI Agents, Privacy-Utility Tradeoffs, LLM Privacy |
| [Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://openreview.net/forum?id=V4y0CpX4hK) | ICLR | 2025 | Security Benchmark, Prompt Injection, Memory Poisoning, Backdoor Attack |
| [AirGapAgent: Protecting Privacy-Conscious Conversational Agents](https://arxiv.org/abs/2405.05175) | ACL | 2024 | Privacy Protection, Conversational Agents, Data Leakage, Air-Gap Defense |
| [PrivacyLens: Evaluating Privacy Norm Awareness of Language Models in Action](https://openreview.net/forum?id=8pFxGxMH3v) | NeurIPS | 2024 | Privacy Norms, LLM Agents, Contextual Integrity, Privacy Evaluation |
| [CertRAG: Certifiably Robust RAG Against Retrieval Corruption](https://arxiv.org/abs/2405.15556) | arXiv | 2024 | RAG Security, Retrieval Corruption, Certified Robustness, Knowledge Poisoning Defense |
| [PrivAgent: Agentic-Based Red-Teaming for LLM Privacy Leakage](https://arxiv.org/abs/2412.10260) | arXiv | 2024 | Red-Teaming, Privacy Leakage, LLM Agents, Agentic Attack |

### Web, OS and Computer-Use Agents

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control](https://ojs.aaai.org/index.php/AAAI/article/view/41090) | AAAI | 2026 | Benchmark, OS Agents, Safety Evaluation, Prompt Injection |
| [Unintended Misalignment from Agentic Fine-Tuning: Risks and Mitigation](https://ojs.aaai.org/index.php/AAAI/article/view/41077) | AAAI | 2026 | Tool-Using Agents, Web Agents, Code Agents, Defense |
| [D-GARA: A Dynamic Benchmarking Framework for GUI Agent Robustness in Real-World Anomalies](https://ojs.aaai.org/index.php/AAAI/article/view/38795) | AAAI | 2026 | Benchmark, Web Agents, OS Agents, Adversarial Robustness, Safety Evaluation |
| [GEM: Gaussian Embedding Modeling for Out-of-Distribution Detection in GUI Agents](https://ojs.aaai.org/index.php/AAAI/article/view/40692) | AAAI | 2026 | OS Agents, Web Agents, Adversarial Robustness, Runtime Defense |
| [SecureWebArena: A Holistic Security Evaluation Benchmark for LVLM-based Web Agents](https://aclanthology.org/2026.findings-acl.582/) | ACL Findings | 2026 | Web Agents, Benchmark, Multimodal Agents, Safety Evaluation, Red-Teaming |
| [EVA: Evolving Semantic Adversaries for Red-Teaming GUI Agents Against Environmental Injection Attacks](https://aclanthology.org/2026.findings-acl.1230/) | ACL Findings | 2026 | Web Agents, Red-Teaming, Prompt Injection, Multimodal Agents |
| [MalURLBench: A Benchmark Evaluating Agents’ Vulnerabilities When Processing Web URLs](https://aclanthology.org/2026.findings-acl.716/) | ACL Findings | 2026 | Benchmark, Web Agents, Defense, Safety Evaluation |
| [OS-Sentinel: Towards Safety-Enhanced Mobile GUI Agents via Hybrid Validation in Realistic Workflows](https://aclanthology.org/2026.acl-long.431/) | ACL | 2026 | OS Agents, Multimodal Agents, Benchmark, Runtime Defense, Formal Methods |
| [Benchmarking Web Agent Safety under E-commerce Deceptive Interfaces](https://aclanthology.org/2026.acl-long.1009/) | ACL | 2026 | Web Agents, Benchmark, Safety Evaluation, Red-Teaming |
| [Don’t Click That: Teaching Web Agents to Resist Deceptive Interfaces](https://aclanthology.org/2026.acl-long.310/) | ACL | 2026 | Web Agents, Defense, Benchmark, Multimodal Agents |
| [A Functionality-Grounded Benchmark for Evaluating Web Agents in E-commerce Domains](https://aclanthology.org/2026.acl-long.68/) | ACL | 2026 | Web Agents, Benchmark, Safety Evaluation, Tool-Using Agents |
| [InquireMobile: Teaching VLM-based Mobile Agent to Request Human Assistance via Reinforcement Fine-Tuning](https://aclanthology.org/2026.acl-long.1487/) | ACL | 2026 | OS Agents, Benchmark, Safety Evaluation, Multimodal Agents |
| [LITMUS: Benchmarking Behavioral Jailbreaks of LLM Agents in Real OS Environments](https://openreview.net/forum?id=iCXoa3VMy0) | NeurIPS | 2026 | Benchmark, OS Agents, Jailbreaking, Safety Evaluation, Prompt Injection |
| [MMA-SafetyBench: A Benchmark for Multimodal Agent Safety Evaluation](https://openreview.net/forum?id=VrSlzRgv4r) | NeurIPS | 2026 | Multimodal Agents, Benchmark, Prompt Injection, Safety Evaluation, Web Agents |
| [Agent Meltdowns: The Road to Hell Is Paved with Helpful Agents](https://openreview.net/forum?id=bLzbzox9it) | NeurIPS | 2026 | Safety Evaluation, Tool-Using Agents, Web Agents, Threat Modeling |
| [Breadcrumbing Search Agents: Per-Turn Scheming Over Long-Horizon Trajectories](https://openreview.net/forum?id=flE9vNlBYl) | NeurIPS | 2026 | Prompt Injection, Red-Teaming, Tool-Using Agents, Web Agents |
| [LPS-Bench: Benchmarking Safety Awareness of Computer-Use Agents in Long-Horizon Planning under Benign and Adversarial Scenarios](https://openreview.net/forum?id=vbY7BcSB0Z) | NeurIPS | 2026 | Benchmark, OS Agents, MCP, Safety Evaluation |
| [Safe, or Simply Incapable? Rethinking Safety Evaluation for Phone-Use Agents](https://openreview.net/forum?id=m5QXsXgA5p) | NeurIPS | 2026 | Benchmark, Safety Evaluation, OS Agents, Multimodal Agents |
| [The Web Doesn't Sit Still: Adversarial Self-Evolving Attacks on Search Agents](https://openreview.net/forum?id=pjLUz7TVsi) | NeurIPS | 2026 | Red-Teaming, Web Agents, Knowledge Poisoning, Tool-Using Agents |
| [Claude Coke: Prevent Automated Crime by Agents](https://openreview.net/forum?id=dy8ITXgyTV) | NeurIPS | 2026 | Tool-Using Agents, Web Agents, Red-Teaming, Governance |
| [Synthetic Web: Benchmarking Language Agents under Adversarial Search Ranking](https://openreview.net/forum?id=6JUMpZWGTT) | NeurIPS | 2026 | Web Agents, Benchmark, Adversarial Robustness, Knowledge Poisoning |
| [AndroidReality: How Far Are Mobile Agents from the Real World?](https://openreview.net/forum?id=H8jkwac4sG) | NeurIPS | 2026 | OS Agents, Benchmark, Adversarial Robustness, Safety Evaluation |
| [ScrapeBench: Evaluating Legal Compliance of AI Agents in Website Scraping](https://openreview.net/forum?id=Pcl8A4aiiN) | NeurIPS | 2026 | Benchmark, Web Agents, Safety Evaluation, Governance |
| [RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments](https://openreview.net/forum?id=yWwrgcBoK3) | ICLR | 2026 | Prompt Injection, Red-Teaming, OS Agents, Web Agents, Benchmark |
| [VPI-Bench: Visual Prompt Injection Attacks for Computer-Use Agents](https://openreview.net/forum?id=UMauKu2azg) | ICLR | 2026 | Prompt Injection, Benchmark, OS Agents, Multimodal Agents |
| [GhostEI-Bench: Do Mobile Agent Resilience to Environmental Injection in Dynamic On-Device Environments?](https://openreview.net/forum?id=2zi9z2geAO) | ICLR | 2026 | Benchmark, Prompt Injection, Multimodal Agents, OS Agents, Red-Teaming |
| [How Dark Patterns Manipulate Web Agents](https://openreview.net/forum?id=G7Dan0L7ho) | ICLR | 2026 | Web Agents, Red-Teaming, Benchmark, Adversarial Robustness, Safety Evaluation |
| [Just Do It!? Computer-Use Agents Exhibit Blind Goal-Directedness](https://openreview.net/forum?id=9W4bPRsEIT) | ICLR | 2026 | OS Agents, Benchmark, Safety Evaluation, Red-Teaming |
| [HackWorld: Evaluating Computer-Use Agents on Exploiting Web Application Vulnerabilities](https://openreview.net/forum?id=nLfZPoJbO7) | ICLR | 2026 | Benchmark, OS Agents, Red-Teaming, Safety Evaluation |
| [MUZZLE: Adaptive Agentic Red-Teaming of Web Agents Against Indirect Prompt Injection Attacks](https://www.usenix.org/conference/usenixsecurity26/presentation/syros) | USENIX | 2026 | Web Agents, Prompt Injection, Red-Teaming, Safety Evaluation |
| [MATE: Policy-Aware Security Auditing for Mobile Agents via Synthesis-Driven Trajectory Learning](https://www.usenix.org/conference/usenixsecurity26/presentation/jiang-changyue) | USENIX | 2026 | OS Agents, Guardrails, Benchmark, Runtime Defense |
| [Mind the Gap: Action Rebinding Attacks against Android GUI Agents](https://arxiv.org/abs/2601.12349) | CCS | 2026 | OS Agents, Multimodal Agents, Red-Teaming, Threat Modeling |
| [MirrorGuard: Toward Secure Computer-Use Agents via Simulation-to-Real Reasoning Correction](https://arxiv.org/abs/2601.12822) | CCS | 2026 | OS Agents, Defense, Prompt Injection, Guardrails |
| [Investigating the Impact of Dark Patterns on LLM-Based Web Agents](https://doi.org/10.1109/sp63933.2026.00042) | IEEE S&P | 2026 | Web Agents, Benchmark, Adversarial Robustness, Safety Evaluation |
| [It's a TRAP! Task-Redirecting Agent Persuasion Benchmark for Web Agents](https://openreview.net/forum?id=Smk4fl6Q9E) | ICML | 2026 | Prompt Injection, Web Agents, Benchmark, Red-Teaming |
| [When Actions Go Off-Task: Detecting and Correcting Misaligned Actions in Computer-Use Agents](https://openreview.net/forum?id=Q3UQSz4Giw) | ICML | 2026 | OS Agents, Guardrails, Prompt Injection, Benchmark |
| [Learning Efficient Guardrails for Compliance](https://openreview.net/forum?id=y3niyCNvAp) | ICML | 2026 | Guardrails, Web Agents, Benchmark, Runtime Defense |
| [Prompt Injection as Role Confusion](https://openreview.net/forum?id=Lm3DQDyIsI) | ICML | 2026 | Prompt Injection, Tool-Using Agents, Web Agents, Red-Teaming |
| [When Benign Inputs Lead to Severe Harms: Eliciting Unsafe Unintended Behaviors of Computer-Use Agents](https://openreview.net/forum?id=PbXNvEE0jA) | ICML | 2026 | OS Agents, Red-Teaming, Safety Evaluation, Tool-Using Agents |
| [AgentHijack: Benchmarking Computer Use Agent Robustness to Common Environment Corruptions](https://openreview.net/forum?id=0H5Im3Xvuf) | ICML | 2026 | OS Agents, Benchmark, Adversarial Robustness, Multimodal Agents |
| [Next-Gen CAPTCHAs: Leveraging the Cognitive Gap for Scalable and Diverse GUI-Agent Defense](https://openreview.net/forum?id=wPKGirrtyz) | ICML | 2026 | Web Agents, Multimodal Agents, Defense, Benchmark |
| [SafeSearch: Automated Red-Teaming of LLM-Based Search Agents](https://openreview.net/forum?id=f2ZiFnZEQA) | ICML | 2026 | Search Agents, Red-Teaming, Search Safety, Misinformation, Prompt Injection |
| [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://openreview.net/pdf?id=MuCDzH0ctf) | ICLR | 2026 | Agentic systems, LLM-based agents, Web agents |
| [ALIGNED LLMS ARE NOT ALIGNED BROWSER AGENTS](https://openreview.net/forum?id=NsFZZU9gvk) | ICLR | 2025 | Aligned LLMs, Browser Agents, Agent Safety |
| [MIP against Agent: Malicious Image Patches Hijacking Multimodal OS Agents](https://openreview.net/forum?id=ToNRHqX6xq) | NeurIPS | 2025 | Multimodal OS Agents, Adversarial Image Patches, Hijacking Attack, Agent Security |
| [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814) | ICLR | 2025 | Adversarial Robustness, Multimodal Agents, Web Agents, Attack Defense |
| [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814) | ICLR | 2025 | Adversarial Robustness, Multimodal Agents, Web Agents, Attack Defense |
| [AdvWeb: Controllable Black-box Attacks on VLM-powered Web Agents](https://openreview.net/forum?id=x9gCQC3rVA) | ICLR | 2025 | Black-Box Attack, VLM, Web Agents, Adversarial Injection |
| [DoomArena: A Framework for Testing AI Agents Against Evolving Security Threats](https://arxiv.org/abs/2504.14064) | COLM | 2025 | Security Testing Framework, Web Agents, Tool-Calling Agents, Evolving Threats |
| [Why Are Web AI Agents More Vulnerable Than Standalone LLMs? A Security Analysis](https://arxiv.org/abs/2502.20383) | arXiv | 2025 | Web Agents, Vulnerability Analysis, Security Analysis, LLM Comparison |
| [SafeArena: Evaluating the Safety of Autonomous Web Agents](https://arxiv.org/abs/2503.04957) | arXiv | 2025 | Web Agents, Safety Evaluation, Harmful Task Completion, Autonomous Agents |
| [BrowserART: Red-Teaming Browser Agents with Diverse Harmful Behaviors](https://arxiv.org/abs/2410.13886) | arXiv | 2024 | Browser Agents, Red-Teaming, Harmful Behaviors, Jailbreaking |

### Embodied and Multimodal Agents

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks](https://ojs.aaai.org/index.php/AAAI/article/view/40880) | AAAI | 2026 | Embodied Agents, Benchmark, Safety Evaluation, Multimodal Agents |
| [On the Feasibility of Using MultiModal LLMs to Execute AR Social Engineering Attacks](https://ojs.aaai.org/index.php/AAAI/article/view/41164) | AAAI | 2026 | Red-Teaming, Multimodal Agents, Threat Modeling, Tool-Using Agents |
| [PhysPatch: A Physically Realizable and Transferable Adversarial Patch Attack for Multimodal Large Language Models-based Autonomous Driving Systems](https://ojs.aaai.org/index.php/AAAI/article/view/42439) | AAAI | 2026 | Adversarial Robustness, Multimodal Agents, Embodied Agents, Red-Teaming |
| ["Penny Wise, Pixel Foolish": Bypassing Price Constraints in Multimodal Agents via Visual Adversarial Perturbations](https://aclanthology.org/2026.findings-acl.788/) | ACL Findings | 2026 | Multimodal Agents, Adversarial Robustness, Red-Teaming, Defense, Tool-Using Agents |
| [SafetyALFRED: Evaluating Safety-Conscious Planning of Vision Language Models](https://aclanthology.org/2026.findings-acl.1852/) | ACL Findings | 2026 | Embodied Agents, Benchmark, Safety Evaluation, Multimodal Agents |
| [Characterizing the Robustness of Black-Box LLM Planners Under Perturbed Observations with Adaptive Stress Testing](https://aclanthology.org/2026.findings-acl.1966/) | ACL Findings | 2026 | Adversarial Robustness, Red-Teaming, Safety Evaluation, Embodied Agents |
| [Where Did It Go Wrong? Capability-Oriented Failure Attribution for Vision-and-Language Navigation Agents](https://aclanthology.org/2026.findings-acl.1402/) | ACL Findings | 2026 | Embodied Agents, Safety Evaluation, Benchmark |
| [AgentMark: Utility-Preserving Behavioral Watermarking for Agents](https://aclanthology.org/2026.acl-long.573/) | ACL | 2026 | Tool-Using Agents, Embodied Agents, Governance, Defense |
| [EnvTrap: Revealing the Environment-Only Attack Surface in Embodied AI via Consequence-Blind Action Execution](https://openreview.net/forum?id=Dn8mqYHQ8S) | NeurIPS | 2026 | Embodied Agents, Adversarial Robustness, Red-Teaming, Defense |
| [SENTINEL: A Multi-Level Formal Framework for Safety Evaluation of Foundation Model-based Embodied Agents](https://openreview.net/forum?id=APzonK9omC) | NeurIPS | 2026 | Embodied Agents, Formal Methods, Safety Evaluation, Benchmark |
| [Seeing Is Not Screening: Multimodal Hidden Instruction Attacks on Agent Skill Scanners](https://openreview.net/forum?id=TU6XyrLcIu) | NeurIPS | 2026 | Supply Chain Security, Multimodal Agents, Prompt Injection, Defense, Red-Teaming |
| [Auditing Instruction Robustness in Vision-Language-Action Models via Diversity-Aware Red Teaming](https://openreview.net/forum?id=80h2jS8emw) | NeurIPS | 2026 | Red-Teaming, Embodied Agents, Multimodal Agents, Adversarial Robustness |
| [Claw-Eval: Towards Trustworthy Evaluation of Autonomous Agents](https://openreview.net/forum?id=GlpMVukwjK) | NeurIPS | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Multimodal Agents |
| [Grounding Generative Planners in Verifiable Logic: A Hybrid Architecture for Trustworthy Embodied AI](https://openreview.net/forum?id=wb05ver1k8) | ICLR | 2026 | Embodied Agents, Formal Methods, Guardrails, Runtime Defense |
| [Extended to Reality: Prompt Injection in 3D Environments](https://arxiv.org/abs/2602.07104) | COLM | 2026 | Prompt Injection, Multimodal Agents, Embodied Agents, Red-Teaming |
| [Hijacking Large Audio-Language Models via Context-Agnostic and Imperceptible Auditory Prompt Injection](https://doi.org/10.1109/sp63933.2026.00214) | IEEE S&P | 2026 | Prompt Injection, Multimodal Agents, Adversarial Robustness, Red-Teaming |
| [EMBGuard: Constructing Hazard-Aware Guardrails for Safe Planning in Embodied Agents](https://openreview.net/forum?id=aoUVQ5d8vf) | ICML | 2026 | Embodied Agents, Guardrails, Benchmark, Multimodal Agents, Safety Evaluation |
| [OrchJail: Jailbreaking Tool-Calling Text-to-Image Agents by Orchestration-Guided Fuzzing](https://openreview.net/forum?id=VviX6pPCgV) | ICML | 2026 | Jailbreaking, Red-Teaming, Tool-Using Agents, Multimodal Agents |
| [SafeLab: An Interactive High-Fidelity Benchmark for Embodied Safety in Scientific Robotics](https://openreview.net/forum?id=ojwpa0wXo9) | ICML | 2026 | Embodied Agents, Benchmark, Safety Evaluation |
| [Can We Trust Embodied Agents? Exploring Backdoor Attacks Against Embodied LLM-based Decision-making Systems](https://openreview.net/pdf?id=S1Bv3068Xt) | ICLR | 2025 | Embodied Agents, Backdoor Attack, LLM-based Decision-Making |
| [WALL-E 2.0: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents](https://neurips.cc/virtual/2025/loc/san-diego/poster/119191) | NeurIPS | 2025 | World Alignment, NeuroSymbolic Learning, World Model-based Agents, LLM Agents |
| [BEAT: Visual Backdoor Attacks on VLM-Based Embodied Agents via Contrastive Trigger Learning](https://arxiv.org/abs/2510.27623) | arXiv | 2025 | Visual Backdoor, Embodied Agents, VLM, Contrastive Learning |
| [BEAT: Visual Backdoor Attacks on VLM-Based Embodied Agents via Contrastive Trigger Learning](https://arxiv.org/abs/2510.27623) | arXiv | 2025 | Visual Backdoor, Embodied Agents, VLM, Contrastive Learning |
| [SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents](https://arxiv.org/abs/2412.13178) | arXiv | 2024 | Embodied Agents, Safe Task Planning, Safety Benchmark, Hazardous Tasks |
| [Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490) | arXiv | 2023 | Multimodal Agents, Indirect Injection, Image-Based Attack, Sound-Based Attack |

### Code Agents and Supply Chain

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [MCPTox: A Benchmark for Tool Poisoning on Real-World MCP Servers](https://ojs.aaai.org/index.php/AAAI/article/view/40895) | AAAI | 2026 | MCP, Benchmark, Supply Chain Security, Tool-Using Agents, Prompt Injection |
| [MPMA: Preference Manipulation Attack Against Model Context Protocol](https://ojs.aaai.org/index.php/AAAI/article/view/40898) | AAAI | 2026 | MCP, Tool-Using Agents, Supply Chain Security, Red-Teaming |
| [Safety Sidecar: Reflection-Driven Runtime Control for Safer Agents](https://aclanthology.org/2026.findings-acl.1542/) | ACL Findings | 2026 | Runtime Defense, Guardrails, Tool-Using Agents, Code Agents |
| [When "Correct" Is Not Safe: Can We Trust Functionally Correct Patches Generated by Code Agents?](https://aclanthology.org/2026.acl-long.707/) | ACL | 2026 | Code Agents, Red-Teaming, Adversarial Robustness, Safety Evaluation |
| [SecureVibeBench: Benchmarking Secure Vibe Coding of AI Agents via Reconstructing Vulnerability-Introducing Scenarios](https://aclanthology.org/2026.acl-long.1107/) | ACL | 2026 | Code Agents, Benchmark, Safety Evaluation, Tool-Using Agents |
| [XOXO: Stealthy Cross-Origin Context Poisoning Attacks against AI Coding Assistants](https://aclanthology.org/2026.acl-long.521/) | ACL | 2026 | Code Agents, Prompt Injection, Red-Teaming, Adversarial Robustness |
| [Defense-as-Skill: Evolving Runtime Guard Skill for Skill-Augmented Agents](https://openreview.net/forum?id=W8hQZI7IzO) | NeurIPS | 2026 | Runtime Defense, Supply Chain Security, Tool-Using Agents, Guardrails, Defense |
| [GitInject: Real-World Prompt Injection Attacks in AI-Powered CI/CD Pipelines](https://openreview.net/forum?id=yuUk1yfRpn) | NeurIPS | 2026 | Prompt Injection, Code Agents, Supply Chain Security, Benchmark, Red-Teaming |
| [Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks](https://openreview.net/forum?id=bXPDGRwV7Y) | NeurIPS | 2026 | Prompt Injection, Supply Chain Security, Benchmark, Tool-Using Agents |
| [Agent MechSuits : Mechanistic Subspace Safety Steering for Multi-Turn CLI Agents](https://openreview.net/forum?id=GAW18QTdGu) | NeurIPS | 2026 | Runtime Defense, Code Agents, Benchmark, Defense |
| [MOSAIC-Bench: Measuring Compositional Vulnerability Induction in Coding Agents](https://openreview.net/forum?id=g9BxvmeCLK) | NeurIPS | 2026 | Code Agents, Benchmark, Red-Teaming, Safety Evaluation |
| [Instrumental Choices: Measuring the Propensity of LLM Agents to Pursue Instrumental Behaviors](https://openreview.net/forum?id=EgkjxNgbUp) | NeurIPS | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Code Agents |
| [No More, No Less: Task Alignment in Terminal Agents](https://openreview.net/forum?id=koHWZUTUlq) | NeurIPS | 2026 | Benchmark, Prompt Injection, Tool-Using Agents, Code Agents |
| [CyberDualEval: Measuring Dual-Use Cyber Risks in Frontier Language Models](https://openreview.net/forum?id=yp203lXtpK) | NeurIPS | 2026 | Benchmark, Safety Evaluation, Code Agents, Red-Teaming |
| [Do Coding Agents Deceive Us? Detecting and Preventing Cheating via Capped Evaluation with Randomized Tests](https://openreview.net/forum?id=x3srtw3rZo) | NeurIPS | 2026 | Code Agents, Safety Evaluation, Benchmark, Defense |
| [Measuring Safety Alignment Effects in Autonomous Security Agents](https://openreview.net/forum?id=6VC4S9fBfE) | NeurIPS | 2026 | Safety Evaluation, Tool-Using Agents, Code Agents, Benchmark |
| [Sequential Behavioral Watermarking for LLM Agents](https://openreview.net/forum?id=ehO9ULukTj) | NeurIPS | 2026 | Tool-Using Agents, Defense, Adversarial Robustness, Supply Chain Security |
| [RedCodeAgent: Automatic Red-teaming Agent against Diverse Code Agents](https://openreview.net/forum?id=IyIaAOihmZ) | ICLR | 2026 | Red-Teaming, Code Agents, Jailbreaking, Safety Evaluation |
| [ImpossibleBench: Measuring LLMs' Propensity of Exploiting Test Cases](https://openreview.net/forum?id=SeO4vyAj7E) | ICLR | 2026 | Benchmark, Code Agents, Safety Evaluation, Red-Teaming |
| ["Do Not Mention This to the User": Detecting and Understanding Malicious Agent Skills in the Wild](https://www.usenix.org/conference/usenixsecurity26/presentation/liu-yi) | USENIX | 2026 | Supply Chain Security, Code Agents, Tool-Using Agents, Threat Modeling |
| [Prompt Injection Attack to Tool Selection in LLM Agents](https://www.ndss-symposium.org/ndss-paper/prompt-injection-attack-to-tool-selection-in-llm-agents/) | NDSS | 2026 | Prompt Injection, Tool-Using Agents, Supply Chain Security, Red-Teaming |
| [ANCHOR: Automated Alignment Auditing for CLI Agents on Real-World Harm](https://openreview.net/forum?id=YqTodSrPPB) | ICML | 2026 | Red-Teaming, Safety Evaluation, Code Agents, Benchmark |
| [Is Vibe Coding Safe? Benchmarking Vulnerability of Agent-Generated Code in Real-World Tasks](https://openreview.net/forum?id=qG8g00zRZa) | ICML | 2026 | Benchmark, Code Agents, Safety Evaluation, Red-Teaming |
| [Quantifying Frontier LLM Capabilities for Container Sandbox Escape](https://openreview.net/forum?id=19AbP986bv) | ICML | 2026 | Benchmark, Code Agents, Safety Evaluation, Threat Modeling |
| [BlueCodeAgent: A Blue Teaming Agent Powered by Automated Red Teaming for CodeGen AI](https://openreview.net/forum?id=TR2DYfZXTd) | ICML | 2026 | Code Agents, Red-Teaming, Defense, Prompt Injection |
| [From Similarity to Vulnerability: Key Collision Attack on LLM Semantic Caching](https://openreview.net/forum?id=BQfNL1wahQ) | ICML | 2026 | Threat Modeling, Tool-Using Agents, Red-Teaming, Supply Chain Security |
| [Watermarking LLM Agent Trajectories](https://openreview.net/forum?id=h5M4E33Pqs) | ICML | 2026 | Backdoor Attack, Tool-Using Agents, Defense, Supply Chain Security |
| [SkillTrojan: Backdoor Attacks on Skill-Based Agent Systems](https://arxiv.org/abs/2604.06811) | ICML | 2026 | Backdoor Attack, Skill-Based Agents, Supply Chain Security, Tool Poisoning, Agent Security |
| [Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools](https://openreview.net/pdf?id=oLGtPYdRzU) | NeurIPS | 2025 | Attractive Metadata Attack, Tool Metadata Manipulation, LLM Agent Security |
| [Your AI, My Shell: Demystifying Prompt Injection Attacks on Agentic AI Coding Editors](https://arxiv.org/abs/2509.22040) | arXiv | 2025 | Prompt Injection, AI Coding Editors, Shell Execution, Agent Security |
| [Your AI, My Shell: Demystifying Prompt Injection Attacks on Agentic AI Coding Editors](https://arxiv.org/abs/2509.22040) | arXiv | 2025 | Prompt Injection, AI Coding Editors, Shell Execution, Agent Security |
| [RedCode: Risky Code Execution and Generation Benchmark for Code Agents](https://openreview.net/forum?id=IxaBguVAI6) | NeurIPS | 2024 | Code Agents, Risky Code Execution, Benchmark, Security Evaluation |

### Prompt Injection and MCP

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [MCP-Guard: A Multi-Stage Defense-in-Depth Framework for Securing Model Context Protocol in Agentic AI](https://aclanthology.org/2026.findings-acl.240/) | ACL Findings | 2026 | MCP, Prompt Injection, Guardrails, Benchmark, Defense |
| [ToolSafe: Enhancing Tool Invocation Safety of LLM-based agents via Proactive Step-level Guardrail and Feedback](https://aclanthology.org/2026.findings-acl.1850/) | ACL Findings | 2026 | Guardrails, Tool-Using Agents, Prompt Injection, Benchmark, Runtime Defense |
| [How Adversarial Environments Mislead Agentic AI?](https://aclanthology.org/2026.findings-acl.499/) | ACL Findings | 2026 | Tool-Using Agents, MCP, Threat Modeling, Red-Teaming, Benchmark |
| [VIGIL: Defending LLM Agents Against Tool-Stream Injection via Verify-Before-Commit](https://aclanthology.org/2026.acl-long.443/) | ACL | 2026 | Prompt Injection, Tool-Using Agents, Runtime Defense, Benchmark, Defense |
| [SafeMCP: Proactive Power Regulation for LLM Agent Defense via Environment-Grounded Look-Ahead Reasoning](https://aclanthology.org/2026.acl-long.522/) | ACL | 2026 | MCP, Runtime Defense, Tool-Using Agents, Defense |
| [Securing AI Agents with Information-Flow Control](https://openreview.net/forum?id=R5k46rM7mR) | NeurIPS | 2026 | Prompt Injection, Formal Methods, Runtime Defense, Tool-Using Agents |
| [MetaPI: Constructing Prompt Injection Benchmarks from Any Agent Benchmarks](https://openreview.net/forum?id=blZs0Iw2sU) | NeurIPS | 2026 | Prompt Injection, Benchmark, Tool-Using Agents, Defense |
| [SudoBench: A Contextual Authorization Benchmark for LLM Agents](https://openreview.net/forum?id=OqnNJ4ruF0) | NeurIPS | 2026 | Benchmark, Prompt Injection, Tool-Using Agents, Safety Evaluation |
| [Adaptive Adversaries: A Multi-Turn, Multi-LLM Benchmark for LLM Agent Security](https://openreview.net/forum?id=TwAO2rViBV) | NeurIPS | 2026 | Benchmark, Prompt Injection, Red-Teaming, Tool-Using Agents |
| [The Scaling Paradox of Tool-Calling LLM Agents Under Realistic MCP Faults](https://openreview.net/forum?id=ZfMdoPBhn0) | NeurIPS | 2026 | MCP, Tool-Using Agents, Adversarial Robustness, Safety Evaluation |
| [MCP-SafetyBench: A Benchmark for Safety Evaluation of Large Language Models with Real-World MCP Servers](https://openreview.net/forum?id=7XYjeL46co) | ICLR | 2026 | MCP, Benchmark, Safety Evaluation, Tool-Using Agents, Red-Teaming |
| [Adaptive Attacks on Trusted Monitors Subvert AI Control Protocols](https://openreview.net/forum?id=wSs1Ez3aKl) | ICLR | 2026 | Red-Teaming, Prompt Injection, Runtime Defense, Tool-Using Agents |
| [Optimizing Agent Planning for Security and Autonomy](https://openreview.net/forum?id=g0aVCDY3gS) | ICLR | 2026 | Prompt Injection, Tool-Using Agents, Runtime Defense, Defense |
| [AttriGuard: Defeating Indirect Prompt Injection in LLM Agents via Causal Attribution of Tool Invocations](https://www.usenix.org/conference/usenixsecurity26/presentation/he-yu) | USENIX | 2026 | Prompt Injection, Runtime Defense, Tool-Using Agents, Defense |
| [When AIOps Become "AI Oops": Subverting LLM-driven IT Operations via Telemetry Manipulation](https://www.usenix.org/conference/usenixsecurity26/presentation/pasquini) | USENIX | 2026 | Tool-Using Agents, Prompt Injection, Red-Teaming, Defense |
| [When AI Stops Answering and Starts Acting: Field Notes from Red-Teaming the Agentic Era](https://www.usenix.org/conference/usenixsecurity26/presentation/yu-sangyoon) | USENIX | 2026 | Red-Teaming, MCP, Guardrails, Tool-Using Agents |
| [ACE: A Security Architecture for LLM-Integrated App Systems](https://www.ndss-symposium.org/ndss-paper/ace-a-security-architecture-for-llm-integrated-app-systems/) | NDSS | 2026 | Prompt Injection, Tool-Using Agents, Formal Methods, Defense |
| [ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data](https://www.ndss-symposium.org/ndss-paper/obliinjection-order-oblivious-prompt-injection-attack-to-llm-agents-with-multi-source-data/) | NDSS | 2026 | Prompt Injection, Tool-Using Agents, Red-Teaming |
| [CausalArmor: Efficient Indirect Prompt Injection Guardrails via Causal Attribution](https://openreview.net/forum?id=fE4urn9hyM) | ICML | 2026 | Prompt Injection, Guardrails, Tool-Using Agents, Runtime Defense |
| [Think Twice Before You Act: Protecting LLM Agents Against Tool Description Poisoning via Isolated Planning](https://openreview.net/forum?id=jiNw5AgBbw) | ICML | 2026 | Tool-Using Agents, Prompt Injection, MCP, Runtime Defense |
| [Causal Detection of Multi-Step LLM Agent Attacks](https://openreview.net/forum?id=Kb2m543agS) | ICML | 2026 | Prompt Injection, Tool-Using Agents, Runtime Defense, Defense |
| [OTora: A Unified Red Teaming Framework for Reasoning-Level Denial-of-Service in LLM Agents](https://openreview.net/forum?id=n6smFKXQWg) | ICML | 2026 | Red-Teaming, Tool-Using Agents, Prompt Injection, Adversarial Robustness |
| [MCP Security Bench (MSB): Benchmarking Attacks Against Model Context Protocol in LLM Agents](https://openreview.net/pdf?id=irxxkFMrry) | ICLR | 2026 | Model Context Protocol Security, LLM Agnt Attack, Benchmark Evaluation |
| [ChatInject: Abusing Chat Templates for Prompt Injection in LLM Agents](https://openreview.net/pdf?id=WVhgFSKniL) | ICLR | 2026 | Large Language Model, Prompt Injection Attack, LLM Agent |
| [DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents](https://neurips.cc/virtual/2025/loc/san-diego/poster/116028) | NeurIPS | 2025 | LLM Agents, Defense, Prompt Injection, Injection Isolation |
| [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) | ACM AISec (CCS Workshop) | 2023 | Indirect Prompt Injection, LLM Applications, Attack Taxonomy |
| [InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated LLM Agents](https://aclanthology.org/2024.findings-acl.624/) | ACL Findings | 2024 | Indirect Prompt Injection, Tool-Integrated Agents, Benchmark |
| [AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://openreview.net/forum?id=m1YYAQjO3w) | NeurIPS | 2024 | Prompt Injection, Tool Agents, Attack Defense, Benchmark |
| [SafePro: Evaluating the Safety of Professional-Level AI Agents](https://arxiv.org/abs/2601.06663) | arXiv | 2026 | Safety Evaluation, Agent Benchmarks, Control-Plane Risks, Alignment Failures, Real-World Deployment |
| [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://arxiv.org/abs/2506.11791) | arXiv | 2025 | Security Evaluation, Agent Benchmarks, Control-Plane Reliability, Vulnerability Analysis, Software Security |
| [AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection](https://aclanthology.org/2025.acl-long.399/) | ACL | 2025 | Agent Safety, Guardrail, Runtime Defense, Prompt Injection, Adaptive Detection |
| [Defeating Prompt Injections by Design](https://arxiv.org/abs/2503.18813) | arXiv | 2025 | Prompt Injection Defense, Agent Security, Architectural Defense, LLM Agents |
| [From Prompt Injections to Protocol Exploits: Threats in LLM-powered AI Agent Workflows](https://arxiv.org/abs/2412.09823) | arXiv | 2025 | Prompt Injection, Protocol Exploits, Agentic Workflows, LLM Security |
| [Automatic and Universal Prompt Injection Attacks Against Large Language Models](https://arxiv.org/abs/2403.04957) | arXiv | 2024 | Prompt Injection, Universal Attack, Automated Attack, LLM Security |
| [Prompt Injection Attack Against LLM-Integrated Applications](https://arxiv.org/abs/2306.05499) | arXiv | 2023 | Prompt Injection, LLM Applications, Attack Framework, Security Taxonomy |

### Backdoors, Poisoning and Jailbreaks

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [Peering Behind the Shield: Guardrail Identification in Large Language Models](https://aclanthology.org/2026.findings-acl.566/) | ACL Findings | 2026 | Guardrails, Red-Teaming, Jailbreaking, Threat Modeling |
| [SLIP: Soft Label Mechanism and Key-Extraction-Guided CoT-based Defense Against Instruction Backdoor in APIs](https://aclanthology.org/2026.findings-acl.896/) | ACL Findings | 2026 | Backdoor Attack, Defense, Tool-Using Agents |
| [DECEIVE-AFC: Adversarial Claim Attacks against Search-Enabled LLM-based Fact-Checking Systems](https://openreview.net/forum?id=iB7Jo0DIUm) | NeurIPS | 2026 | Red-Teaming, Adversarial Robustness, Tool-Using Agents, Knowledge Poisoning |
| [Helpful to a Fault: Measuring Illicit Assistance in Multi-Turn, Multilingual LLM Agents](https://openreview.net/forum?id=tB05up6g5N) | ICML | 2026 | Red-Teaming, Tool-Using Agents, Benchmark, Safety Evaluation, Jailbreaking |
| [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://openreview.net/forum?id=AC5n7xHuR1) | ICLR | 2025 | LLM Agents, Jailbreaking, Harm Benchmark, Agent Safety |
| [Composite Backdoor Attacks Against Large Language Models](https://arxiv.org/abs/2310.07676) | arXiv | 2024 | Backdoor Attack, LLM Security, Composite Triggers, Stealthy Attack |
| [BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents](https://arxiv.org/abs/2406.03007) | ACL | 2024 | Backdoor Attack, LLM Agents, Fine-Tuning Vulnerability, Tool-Using Agents |
| [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-based Agents](https://arxiv.org/abs/2402.11208) | arXiv | 2024 | Backdoor Attack, LLM Agents, Agent Hijacking, Safety Evaluation |
| [DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent](https://arxiv.org/abs/2502.12116) | arXiv | 2025 | Backdoor Attack, Dynamic Encryption, LLM Agents, Multi-Backdoor |
| [Many-Shot Jailbreaking](https://arxiv.org/abs/2404.02151) | NeurIPS | 2024 | Jailbreaking, Many-Shot Attack, LLM Safety, In-Context Learning |
| [HarmBench: A Standardized Evaluation Framework for Automated Red Teaming](https://openreview.net/forum?id=5NDSSI28nI) | ICML | 2024 | Red Teaming, Safety Evaluation, Jailbreaking, Standardized Benchmark |

### Defenses, Guardrails and Governance

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [LCO: LLM-based Constraint Optimization for Safer Agentic LLMs in Real-world Tasks](https://aclanthology.org/2026.findings-acl.1390/) | ACL Findings | 2026 | Defense, Tool-Using Agents, Safety Evaluation, Runtime Defense |
| [ToolGate: Contract-Grounded and Verified Tool Execution for LLMs](https://aclanthology.org/2026.findings-acl.470/) | ACL Findings | 2026 | Tool-Using Agents, Formal Methods, Runtime Defense, Guardrails |
| [SafeAgent: Safeguarding LLM Agents via an Automated Risk Simulator](https://aclanthology.org/2026.acl-long.1501/) | ACL | 2026 | Tool-Using Agents, Threat Modeling, Safety Evaluation, Defense |
| [PROACT-Agent: Progressive Runtime Oversight and Active Circuit-breaking for Real-Time Safety](https://openreview.net/forum?id=zOzXmzpHro) | NeurIPS | 2026 | Runtime Defense, Guardrails, Benchmark, Tool-Using Agents |
| [Soteria: Formally Verified Planning with Runtime Enforcement for Safe LLM Agents](https://openreview.net/forum?id=9url1EFMaU) | NeurIPS | 2026 | Formal Methods, Runtime Defense, Tool-Using Agents, Guardrails |
| [WURI: Watching Unfolding Risk in Agent Interactions](https://openreview.net/forum?id=ehughQGWpW) | NeurIPS | 2026 | Runtime Defense, Tool-Using Agents, Guardrails, Safety Evaluation |
| [Building a Foundational Guardrail for General Agentic Systems via Synthetic Data](https://openreview.net/forum?id=M47SWYubR5) | ICLR | 2026 | Guardrails, Tool-Using Agents, Benchmark, Runtime Defense |
| [Monitoring Decomposition Attacks with Lightweight Sequential Monitors](https://openreview.net/forum?id=HQuboWvFA1) | ICLR | 2026 | Runtime Defense, Guardrails, Red-Teaming, Tool-Using Agents, Benchmark |
| [Reliable Weak-to-Strong Monitoring of LLM Agents](https://openreview.net/forum?id=WV7xIboTDK) | ICLR | 2026 | Runtime Defense, Red-Teaming, Tool-Using Agents, Safety Evaluation |
| [PatchWeaver: Risk-Bounded Autonomous Vulnerability Remediation Under Change-Management Policies](https://www.usenix.org/conference/usenixsecurity26/presentation/li-rui) | USENIX | 2026 | Tool-Using Agents, Guardrails, Runtime Defense, Governance |
| [Constitutional Black-Box Monitoring for Scheming in LLM Agents](https://openreview.net/forum?id=GkL3dANi6M) | ICML | 2026 | Runtime Defense, Safety Evaluation, Tool-Using Agents, Threat Modeling |
| [FormalJudge: A Neuro-Symbolic Paradigm for Agentic Oversight](https://openreview.net/forum?id=tnsQ23imeD) | ICML | 2026 | Formal Methods, Guardrails, Safety Evaluation, Tool-Using Agents |
| [Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction](https://openreview.net/forum?id=x5VjErljHS) | ICML | 2026 | Guardrails, Runtime Defense, Tool-Using Agents, Safety Evaluation |
| [The Oversight Game: Learning to Cooperatively Balance an AI Agent's Safety and Autonomy](https://openreview.net/forum?id=Na3YzWMXwz) | ICML | 2026 | Governance, Tool-Using Agents, Runtime Defense, Formal Methods |
| [PragLocker: Protecting Agent Intellectual Property in Untrusted Deployments via Non-Portable Prompts](https://openreview.net/forum?id=PWhmZ04OTr) | ICML | 2026 | Tool-Using Agents, Defense, Threat Modeling |
| [AIR: Improving Agent Safety through Incident Response](https://arxiv.org/abs/2602.11749) | ICML | 2026 | Incident Response, Runtime Defense, Agent Safety, Guardrails, Recovery Mechanisms |
| [Unsafer in Many Turns: Benchmarking and Defending Multi-Turn Safety Risks in Tool-Using Agents](https://arxiv.org/abs/2602.13379) | ICML | 2026 | Multi-Turn Safety, Tool-Using Agents, MT-AgentRisk, ToolShield, Safety Benchmark, Runtime Defense, Agent Security |
| [Position: Trustworthy AI Agents Require the Integration of Large Language Models and Formal Methods](https://openreview.net/forum?id=wkisIZbntD) | ICML | 2025 | Trustworthy AI Agents, Formal Methods, LLMs |
| [Information Retrieval Induced Safety Degradation in AI Agents](https://openreview.net/pdf?id=2hiNrfMmQ7) | NeurIPS | 2025 | Responsible AI, LLM Agents, Safety, Bias |
| [StepShield: When, Not Whether to Intervene on Rogue Agents](https://arxiv.org/abs/2601.22136) | arXiv | 2026 | Agent Safety, Runtime Monitoring, Early Intervention, Safety Benchmarks, Evaluation Metrics |
| [VeriGuard: Enhancing LLM Agent Safety via Verified Code Generation](https://arxiv.org/abs/2510.05156) | arXiv | 2025 | Agent Security, Llm Security, Code verification, Security policies generation, Safety |
| [AgentMonitor: A Plug-in Framework for Real-Time LLM Agent Monitoring on Internet](https://arxiv.org/abs/2312.01831) | arXiv | 2023 | Agent Monitoring, Runtime Safety, Real-Time Defense, LLM Agents |
| [Prioritizing Safeguarding Over Autonomy: Risks of LLM Agents for Science](https://arxiv.org/abs/2402.04247) | arXiv | 2024 | Science Agents, Autonomous Risk, Safeguarding, High-Stakes Domains |
| [Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-Based Agents](https://arxiv.org/abs/2506.02500) | USENIX | 2025 | Vulnerability Detection, Taint Analysis, LLM Agents, Automated Security |

### Benchmarks and Evaluation

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [Model Editing as a Double-Edged Sword: Steering Agent Behavior Toward Beneficence or Harm](https://ojs.aaai.org/index.php/AAAI/article/view/40372) | AAAI | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Red-Teaming |
| [BadScientist: Can a Research Agent Write Convincing but Unsound Papers that Fool LLM Reviewers?](https://aclanthology.org/2026.acl-long.1134/) | ACL | 2026 | Red-Teaming, Safety Evaluation, Threat Modeling, Tool-Using Agents |
| [Impatient Users Confuse AI Agents: High-fidelity Simulations of Human Traits for Testing Agents](https://aclanthology.org/2026.acl-long.1743/) | ACL | 2026 | Safety Evaluation, Benchmark, Tool-Using Agents, Adversarial Robustness |
| [AM-Bench: A Unified Taxonomy and Evaluation Suite for Agentic Misalignment](https://openreview.net/forum?id=CDBb8r3rlc) | NeurIPS | 2026 | Benchmark, Safety Evaluation, Threat Modeling, Tool-Using Agents |
| [Task Success Is Not Enough: Side-effect-Aware Evaluation of Tool-Using Language Model Agents](https://openreview.net/forum?id=xJdBs3VVTg) | NeurIPS | 2026 | Tool-Using Agents, Benchmark, Safety Evaluation, Red-Teaming |
| [Are LLM Safety Judges Policy-Invariant? A Three-Principle Stress-Test](https://openreview.net/forum?id=eDvLM8DzS1) | NeurIPS | 2026 | Safety Evaluation, Benchmark, Tool-Using Agents, Red-Teaming |
| [PROBE: Learning to Audit Policy Compliance in Tool-Using LLM Agents](https://openreview.net/forum?id=zvLWgyQTyA) | NeurIPS | 2026 | Safety Evaluation, Tool-Using Agents, Red-Teaming, Benchmark |
| [ManagerBench: Evaluating the Safety-Pragmatism Trade-off in Autonomous LLMs](https://openreview.net/forum?id=KsmTaPygR9) | ICLR | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents |
| [PropensityBench: Evaluating Latent Safety Risks in Large Language Models via an Agentic Approach](https://openreview.net/forum?id=jOTQupHx7q) | ICLR | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Red-Teaming |
| [PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities](https://openreview.net/forum?id=kGEuZXaXU6) | ICLR | 2026 | Benchmark, Safety Evaluation, Red-Teaming, Tool-Using Agents |
| [Autonomy Comes with Costs: Detecting Denial-of-Service Vulnerabilities Caused by Resource Abusing in LLM-based Agents](https://www.usenix.org/conference/usenixsecurity26/presentation/luo) | USENIX | 2026 | Tool-Using Agents, Red-Teaming, Threat Modeling, Safety Evaluation |
| [When HTTP 402 Meets the Blockchain: Risks on Emerging x402 Payments](https://www.usenix.org/conference/usenixsecurity26/presentation/wang-qinying) | USENIX | 2026 | Threat Modeling, Tool-Using Agents, Safety Evaluation |
| [ATBench: A Diverse and Realistic Agent Trajectory Benchmark for Safety Evaluation and Diagnosis](https://arxiv.org/abs/2604.02022) | COLM | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Threat Modeling |
| [ClawsBench: Evaluating Capability and Safety of LLM Productivity Agents in Simulated Workspaces](https://arxiv.org/abs/2604.05172) | COLM | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents, Red-Teaming |
| [AutoControl Arena: Synthesizing Executable Test Environments for Frontier AI Risk Evaluation](https://openreview.net/forum?id=XkDpZusDTK) | ICML | 2026 | Benchmark, Safety Evaluation, Red-Teaming, Tool-Using Agents |
| [Reward Hacking Benchmark: Measuring Exploits in LLM Agents with Tool Use](https://openreview.net/forum?id=YMA0ByEdVj) | ICML | 2026 | Benchmark, Tool-Using Agents, Safety Evaluation, Red-Teaming |
| [A New Framework for Cybersecurity Refusals in AI Agents](https://openreview.net/forum?id=tkNyoOIbgj) | ICML | 2026 | Safety Evaluation, Benchmark, Red-Teaming, Tool-Using Agents |
| [ABC-Bench: An Agentic Bio-Capabilities Benchmark for Biosecurity](https://openreview.net/forum?id=yiaf7VlPpH) | ICML | 2026 | Benchmark, Safety Evaluation, Tool-Using Agents |
| [Are Your Agents Upward Deceivers?](https://openreview.net/forum?id=fKtCkb8Ixj) | ICML | 2026 | Benchmark, Tool-Using Agents, Safety Evaluation, Red-Teaming |
| [Towards a Science of AI Agent Reliability](https://openreview.net/forum?id=4LTwRqhmhk) | ICML | 2026 | Safety Evaluation, Benchmark, Adversarial Robustness, Tool-Using Agents |
| [AgentNoiseBench: Benchmarking Robustness of Tool-Using LLM Agents Under Noisy Condition](https://openreview.net/forum?id=ORVJCJczoG) | ICML | 2026 | Benchmark, Tool-Using Agents, Adversarial Robustness, Safety Evaluation |
| [OpenAgentSafety: A Comprehensive Framework For Evaluating Real-World AI Agent Safety](https://openreview.net/pdf?id=xggSxCFQbA) | ICLR | 2026 | LLM Agents, Safety, Risks, Datasets, Benchmarks |
| [Breaking Agent Backbones: Evaluating the Security of Backbone LLMs in AI Agents](https://openreview.net/pdf?id=kga18ld70t) | ICLR | 2026 | AI security, Large Language Models, Security Benchmarks |
| [AgentAuditor: Human-Level Safety and Security Evaluation for LLM Agents](https://neurips.cc/virtual/2025/loc/san-diego/poster/120154) | NeurIPS | 2025 | Agent Safety, Agent Security, LLM-as-a-Judge |
| [CONVERSE: Benchmarking Contextual Safety in Agent-to-Agent Conversations](https://arxiv.org/pdf/2511.05359) | arXiv | 2025 | Agent-to-Agent Conversations, Contextual Safety, Benchmark, LLM Agents |
| [Breaking Agents: Compromising Autonomous LLM Agents Through Malfunction Amplification](https://aclanthology.org/2025.emnlp-main.1771/) | EMNLP | 2025 | LLM Agents, Malfunction Attack, Agent Security, Adversarial Robustness |
| [Identifying the Risks of LM Agents with an LM-Emulated Sandbox (ToolEmu)](https://arxiv.org/abs/2309.15817) | ICLR | 2024 | Tool-Using Agents, Risk Identification, LM-Emulated Sandbox, Safety Evaluation |
| [Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470) | arXiv | 2024 | Safety Benchmark, LLM Agents, Failure Modes, Risk Categories |

### General Agent Safety

| Paper | Venue | Date | Tags |
|------|------|------|------|
| [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://openreview.net/pdf?id=Fd1jgQQW28) | ICLR | 2026 | Self-Evolving Agent, Agent Safety, Large Language Models |
| [Why Agents Compromise Safety Under Pressure](https://arxiv.org/pdf/2603.14975) | arXiv | 2026 | Agent Safety, Pressure, Performance Trade-offs |
| [RealSafe: Quantifying Safety Risks of Language Agents in Real-World](https://aclanthology.org/2025.coling-main.642.pdf) | ACL | 2025 | LLM Agent, Safety |
| [Safety Devolution in AI Agents](https://openreview.net/pdf?id=7nJmuFFkWd) | ICLR Workshop (HAIC) | 2025 | AI Agents, Safety Devolution, Human-AI Coevolution |
| [Emergent Risk Awareness in Rational Agents under Resource Constraints](https://openreview.net/pdf/b721f93c521d624000a1eedbe25a30f679087e56.pdf) | NeurIPS | 2025 | Rational Agents, Resource Constraints, Risk Awareness, Agent Safety |
| [TrustAgent: Towards Safe and Trustworthy LLM-based Agents through Agent Constitution](https://aclanthology.org/2024.findings-emnlp.585/) | EMNLP Findings | 2024 | Agent Safety, Agent Constitution, Safety Framework, Trustworthy AI |
| [LM Agents May Fail to Act on Their Own Risk Knowledge](https://arxiv.org/abs/2508.13465) | arXiv | 2025 | Agent Safety, Risk Awareness Gap, Knowledge-Execution Gap, LLM Agents |

