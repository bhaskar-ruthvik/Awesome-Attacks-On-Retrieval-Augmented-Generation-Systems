# Awesome-Attacks-On-Retrieval-Augmented-Generation-Systems
___
This survey is a culmination of the work done by **Bhaskar Ruthvik Bikkina, Pranav Handa, Jaelen Dixon and Kyle Kim**.

The following repository contains a comprehensive list of research papers that cover different types of attacks on Retrieval Augmented Generation systems split into 5 broad categories. We also try to include defenses against such type of attacks in hopes of shedding light on some work done towards making Robust RAGs. We use the diagram below to come up with our taxonomy.

![RAG Pipeline Example](https://i.ibb.co/h6BLmbP/Untitled-design.png)
_Fig: RAG Pipeline used to Distinguish Types of Attacks_

---
## Contents

- [Data Poisoning](#datapoisoning)
  - [Attacks](#datapoisoningattacks)
  - [Defenses](#datapoisoningdefenses)
- [Vector/Embedding Poisoning](#vectorpoisoning)
  - [Attacks](#vectorattacks)
  - [Defenses](#vectordefenses)
- [Prompt Injection](#promptinjection)
  - [Attacks](#promptattacks)
  - [Defenses](#promptdefenses)
- [Feedback Poisoning](#feedbackpoisoning)
  - [Attacks](#feedbackattacks)
  - [Defenses](#feedbackdefenses)
- [Tool Abuse and Manipulation](#toolabuse)
  - [Attacks](#toolattacks)
 
---

<a id="datapoisoning"></a>
## Data Poisoning

<a id="datapoisoningattacks"></a>
### Attacks
- (AgentPoison) AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases [[Paper](https://arxiv.org/abs/2407.12784)]
- (Near-constant Poison Samples) Poisoning Attacks on LLMs Require a Near-constant Number of Poison Samples [[Paper](https://arxiv.org/abs/2510.07192)]
<a id="datapoisoningdefenses"></a>
### Defenses
- (RAGuard) Secure Retrieval-Augmented Generation against Poisoning Attacks [[Paper](https://arxiv.org/abs/2510.25025)]
- (Activation Gradient Detection) Activation Gradient based Poisoned Sample Detection Against Backdoor Attacks [[Paper](https://arxiv.org/abs/2312.06230)]

---
<a id="vectorpoisoning"></a>
## Vector/Embedding Poisoning

<a id="vectorattacks"></a>
### Attacks 
- (TrojanRAG) TrojanRAG: Retrieval-Augmented Generation Can Be Backdoor Driver in Large Language Models [[Paper](https://arxiv.org/abs/2405.13401)]
- (PoisonedEye) PoisonedEye: Knowledge Poisoning Attack on Retrieval-Augmented Generation based Large Vision-Language Models [[Paper](https://openreview.net/forum?id=6SIymOqJlc)]
<a id="vectordefenses"></a>
### Defenses 
- (TruthRAG) TrustRAG: Enhancing Robustness and Trustworthiness in Retrieval-Augmented Generation [[Paper](https://arxiv.org/abs/2501.00879)]
- (Poisoning Defense in Knowledge Intensive Domains) On the Vulnerability of Applying Retrieval-Augmented Generation within Knowledge-Intensive Application Domains [[Paper](https://arxiv.org/abs/2409.17275)]
---

<a id="promptinjection"></a>
## Prompt Injection

<a id="promptattacks"></a>
### Attacks
- (Indirect Prompt Injection) Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection [[Paper](https://doi.org/10.1145/3605764.3623985)]
- (HouYi) Prompt Injection attack against LLM-integrated Applications [[Paper](https://arxiv.org/abs/2306.05499)]
<a id="promptdefenses"></a>
### Defenses
- (PromptArmor) PromptArmor Simple yet Effective Prompt Injection Defenses [[Paper](https://arxiv.org/abs/2507.15219)]
- (Attention Tracker) Attention Tracker Detecting Prompt Injection Attacks in LLMs [[Paper](https://aclanthology.org/2025.findings-naacl.123/)]
- (Formalizing Prompt Injection) Formalizing and Benchmarking Prompt Injection Attacks and Defenses [[Paper](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-yupei)]

---
<a id="feedbackpoisoning"></a>
## Feedback Poisoning

<a id="feedbackattacks"></a>
### Attacks
- RLHFPoison: Reward Poisoning Attack for Reinforcement Learning with Human Feedback in Large Language Models [[Paper](https://arxiv.org/abs/2311.09641)]
- Universal Jailbreak Backdoors From Poisoned Human Feedback [[Paper](https://arxiv.org/abs/2311.14455)]
- Preference Poisoning Attacks on Reward Model Learning [[Paper](https://ieeexplore.ieee.org/document/11023453)]
<a id="feedbackdefenses"></a>
### Defenses
- Human Feedback Attack on Online RLHF: Attack and Robust Defense [[Paper](https://ieeexplore.ieee.org/abstract/document/11153038?casa_token=JTLnFehx7ucAAAAA:XI4tpp8EHmWMS0EVWx_9GY2FEnavQYNpI34IAjAZ3-TgJvAzb3Dv3vjQ2Ts1JVIE-EZbDn7Esg)]

---

<a id="toolabuse"></a>
## Tool Abuse and Manipulation

<a id="toolattacks"></a>
### Attacks
- (ToolCommander) From Allies to Adversaries: Manipulating LLM Tool-Calling through Adversarial Injection [[Paper](https://arxiv.org/abs/2412.10198)]
- (Attractive Metadata Attack) Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools [[Paper](https://arxiv.org/abs/2508.02110)]
- (ToolTweak) ToolTweak: An Attack on Tool Selection in LLM-based Agents [[Paper](https://arxiv.org/abs/2510.02554)]

