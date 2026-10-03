# ICF-AI v1.0.1: Core Framework

## Purpose

ICF-AI decomposes complex AI phenomena into causal stages so research questions can be expressed as measurable, falsifiable claims rather than explanations inferred from surface behavior.

## Eight stages

### 1. Conditions
External conditions that enable, constrain or modify the system: compute, hardware, markets, law, regulation, standards, dependencies and institutional context.

### 2. Formation
Processes that produce model capabilities and behavioral tendencies: data provenance, annotation, architecture, pretraining, supervised fine-tuning, RLHF, Constitutional AI, reinforcement learning, preference optimization, objectives and evaluation feedback.

### 3. Deployment Stack
Runtime systems acting on the trained model: behavioral specifications, system/developer instructions, memory, context, retrieval, tools, routing, inference configuration, security, moderation, privacy and jurisdiction-specific controls.

### 4. Observable Interaction
Measurable behavior at the interface: content, style, timing, tool use, memory use, uncertainty expression, refusal and action initiation.

### 5. Human or System Response
Effects on the recipient: perception, cognition, affect, epistemic judgment and behavior.

### 6. Action and Outcome
State changes produced through digital action, physical action, collaboration, institutional decisions, resource allocation and market or environmental outcomes.

### 7. Collective and Institutional Effects
Distributed systems involving multiple humans, models, agents, rules and organizations: collective intelligence, coordination, institutional memory, attention, decision rights and correlated error.

### 8. Feedback and Recursion
How outcomes become future causal conditions through user adaptation, new data, synthetic-data feedback, commercial optimization, regulation, institutional change, language/norm change and later AI training. Reciprocal feedback should be represented across time or with an appropriate dynamic/feedback model rather than as a directed cycle inside a DAG.

## Cross-cutting dimensions

Every study should state:
- observability status,
- boundary conditions,
- time scale,
- intervention,
- counterfactual,
- latent variables,
- possible nonlinear effects,
- feedback stability,
- measurement validity.

## Minimal causal study template

- **Phenomenon:**
- **Treatment / exposure:**
- **Comparator / intervention contrast:**
- **Outcome:**
- **Estimand:**
- **Mediator(s):**
- **Candidate confounder(s):**
- **Moderator(s):**
- **Boundary conditions:**
- **Identification strategy:**
- **Identification assumptions:**
- **Evidence supporting assumptions:**
- **Plausible violations / threats:**
- **Evidence basis:** DOC / EXP / OBS / COR / SIM / NONE
- **Current claim status:** SUPPORTED / MIXED / NOT SUPPORTED / CONTRADICTED / UNRESOLVED / HYPOTHESIS
- **Observability state:**
- **Alternative explanations:**
- **If not identifiable, permissible conclusion:**
- **Replication status:**

## Additive preservation rule

The framework is deliberately versioned. Valid prior research items are not deleted for convenience. They may be moved, nested, cross-linked or superseded structurally while retaining provenance.


## Foundational sources and intellectual provenance

ICF-AI integrates established concepts from causal inference, experimental and quasi-experimental design, measurement, AI training, human-AI interaction, collective intelligence, and feedback systems. The framework's contribution is the integrative architecture and organization of these components; it does not claim authorship of the underlying established methods or constructs.

### Source map

- Causal graphs, causal identification, counterfactual reasoning: **S01, S02**
- Experimental and quasi-experimental design: **S03**
- Reinforcement learning from human feedback / instruction following: **S04**
- Constitutional AI / AI feedback: **S05**
- Human-AI interaction: **S06**
- Collective intelligence: **S07**
- Feedback and cybernetic systems: **S08**

### Selected foundations

- **S01** Pearl, J. (2009). *Causality: Models, Reasoning, and Inference*, 2nd ed. Cambridge University Press. DOI: 10.1017/CBO9780511803161. ISBN: 9780521895606.
- **S02** Hernán, M. A.; Robins, J. M. (2020). *Causal Inference: What If.* Boca Raton: Chapman & Hall/CRC. ISBN: 9781420076165. Official book page: https://miguelhernan.org/whatifbook
- **S03** Shadish, W. R.; Cook, T. D.; Campbell, D. T. (2002). *Experimental and Quasi-Experimental Designs for Generalized Causal Inference.* Houghton Mifflin. ISBN: 9780395307878.
- **S04** Ouyang, L. et al. (2022). "Training Language Models to Follow Instructions with Human Feedback." *NeurIPS 35*. DOI: 10.52202/068431-2011. arXiv: 2203.02155.
- **S05** Bai, Y. et al. (2022). "Constitutional AI: Harmlessness from AI Feedback." arXiv:2212.08073. DOI: 10.48550/arXiv.2212.08073.
- **S06** Amershi, S. et al. (2019). "Guidelines for Human-AI Interaction." *CHI 2019*. DOI: 10.1145/3290605.3300233.
- **S07** Woolley, A. W. et al. (2010). "Evidence for a Collective Intelligence Factor in the Performance of Human Groups." *Science* 330(6004), 686-688. DOI: 10.1126/science.1193147. PMID: 20929725.
- **S08** Ashby, W. R. (1956). *An Introduction to Cybernetics.* Chapman & Hall / Wiley. DOI: 10.5962/bhl.title.5851. LCCN: 56012972.

These references establish provenance for major inherited methods and concepts. They do not imply endorsement of ICF-AI by the cited authors or institutions, and they do not validate the framework as a whole.
