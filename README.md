# Awesome-Attacks-On-Retrieval-Augmented-Generation-Systems
___
This survey is a culmination of the work done by **Bhaskar Ruthvik Bikkina, Pranav Handa, Jaelen Dixon and Kyle Kim**.

The following repository contains a comprehensive list of research papers that cover different types of attacks on Retrieval Augmented Generation systems split into 5 broad categories. We also try to include defenses against such type of attacks in hopes of shedding light on some work done towards making Robust RAGs. We use the diagram below to come up with our taxonomy.

![RAG Pipeline Example](https://i.ibb.co/h6BLmbP/Untitled-design.png)
_Fig: RAG Pipeline used to Distinguish Types of Attacks_

---
## Contents

- Data Poisoning
  - Attacks
  - Defenses
- [Vector/Embedding Poisoning](#vectorpoisoning)
  - [Attacks](#vectorattacks)
  - [Defenses](#vectordefenses)
- Prompt Injection
  - Attacks
  - Defenses
- [Feedback Poisoning](#feedbackpoisoning)
  - [Attacks](#feedbackattacks)
  - [Defenses](#feedbackdefenses)
- Tool Abuse and Manipulation
  - Attacks
  - Defenses
 
---

## Data Poisoning

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

## Prompt Injection

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
