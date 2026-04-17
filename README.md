# REFM: Research Engineering on Frontier Models

**The Art of the Possible**  
*Individual-Scale Frontier Research Engineering through Systematic Post-Training on Open-Weight Frontier Models*

**Version:** April 2026  
**Author:** Pra Cha (New York City)  
**Project Tagline:** Exploring what one person can realistically achieve at the frontier of AI by leveraging post-training, lifelong self-evolving agents, interpretability, and alignment analysis.

---

## 1. The Idea

In 2026, the most exciting progress in AI is no longer limited to massive pre-training runs conducted by well-funded labs. Instead, **post-training** has become the high-leverage playground where capabilities, agency, alignment, and self-improvement are actively shaped.

REFM (Research Engineering on Frontier Models) is an **individual-scale research engineering project** that systematically experiments on the latest open-weight frontier models the moment they are released.

The core vision is simple yet ambitious:

> Take every new strong open-weight model (GLM-5.1, Kimi K2.5, Qwen3.5/3.6, DeepSeek-V3.2, Gemma 4, etc.), apply layered post-training techniques, and push it toward **lifelong self-evolving agent** behavior — while rigorously studying its internal nature, alignment properties, and limitations.

This is **"The Art of the Possible"** — discovering what is realistically achievable today by one motivated individual with access to cloud GPUs, open tools, and disciplined experimentation, without the resources for pre-training.

---

## 2. Problem Spaces & Research Questions

REFM operates at the intersection of several frontier problem spaces:

### Core Technical Challenges
- **Continual / Lifelong Learning**: How do we prevent catastrophic forgetting while continuously improving the model?
- **Agentic Capabilities**: Moving from single-turn responses to long-horizon planning, tool use, reflection, and autonomous execution.
- **Persistent Memory**: Building reliable long-term memory systems that the agent can actively read, write, and update.
- **Self-Evolution Loops**: Enabling the model to improve itself through self-generated trajectories, reflection, and distillation — with minimal human intervention.

### Safety & Alignment Challenges
- **Alignment Drift / Misevolution**: Does alignment degrade as the agent evolves over time?
- **Emergent Risks**: Deception, alignment faking, scheming, reward-hacking, and self-preservation behaviors in lifelong settings.
- **Stable Value Alignment**: Keeping the agent trustworthy while it adapts to new experiences and goals.

### Scientific Understanding Challenges
- **Mechanistic Interpretability**: What internal circuits emerge or change during agentic RL, memory integration, and self-evolution?
- **Model Organisms**: Creating controlled tests for dangerous behaviors to study how misalignment arises and propagates.

These questions mirror themes actively discussed in the research community, including the **ICLR 2026 Workshop on Lifelong Agents: Learning, Aligning, Evolving** and recent surveys on **Self-Evolving Agents**.

---

## 3. Defining "The Art of the Possible"

"The Art of the Possible" in REFM means:

- **Realistic Constraints**: No pre-training or mid-training. Only post-training techniques (SFT, preference optimization, agentic RL, self-distillation, etc.) that are accessible with consumer/cloud GPUs.
- **Systematic & Cumulative**: Every experiment builds on the previous checkpoint. Results are comparable across different frontier models.
- **Research-Engineering Hybrid**: Not just running benchmarks — building novel systems *and* rigorously analyzing them (performance, forgetting curves, internal mechanisms, safety properties).
- **Iterative Sprints**: When a new strong open-weight model drops, launch a fresh REFM sprint using the same pipeline.
- **Open & Reproducible**: All work documented publicly (GitHub, blogs, reports) to contribute to the broader community of independent researchers and indie labs.
- **Focus on Depth Over Scale**: Deep empirical insights from one-person efforts rather than chasing the largest possible model.

It is about maximally leveraging the open-weight revolution — where models like GLM-5.1, Kimi K2.5, and DeepSeek-V3.2 already approach or match proprietary frontier performance in many domains.

---

## 4. REFM Experiment Pipeline

A repeatable 8-layer pipeline applied cumulatively to each new frontier model:

1. **Baseline Post-Training**  
   SFT + DPO/GRPO on high-quality reasoning and agentic data.

2. **Continual Learning & Stability**  
   Sequential domain training + forgetting analysis.

3. **Persistent Memory Integration**  
   Letta/MemGPT-style systems with active memory training.

4. **Agentic Reinforcement Learning**  
   Multi-turn environments using verl, GRPO, verifiable rewards.

5. **Self-Distillation & Self-Evolution**  
   Closed loops: generate → reflect → distill → improve.

6. **Mechanistic Interpretability**  
   SAEs, activation patching, circuit analysis during evolution.

7. **Alignment & Safety Probes**  
   Model organisms for deception, scheming, and misevolution.

8. **Long-Run Persistent Research Agent**  
   Deploy as an open-ended autonomous research assistant and analyze emergent behavior over days/weeks.

---

## 5. Target Models (Mid-April 2026)

Current strong open-weight candidates for REFM sprints:
- **GLM-5.1** (Zhipu/Z.AI) — Leading in agentic engineering and long-horizon tasks.
- **Kimi K2.5 / Kimi K2 Thinking** (Moonshot AI) — Strong in multimodal, agentic workflows, and autonomous behavior.
- **Qwen3.5 / Qwen3.6 series** (Alibaba) — Excellent all-rounder with efficient MoE architectures.
- **DeepSeek-V3.2** — Outstanding reasoning and cost-efficient performance.
- **Gemma 4** and other competitive releases as they appear.

---

## 6. Philosophy & Long-Term Vision

REFM embodies a democratized approach to frontier AI research:

- Big labs push the base models.
- Independent researchers like us push **what can be built on top** — turning powerful foundation models into persistent, self-improving, interpretable, and aligned agents.
- By focusing on post-training, memory, agency, interpretability, and safety, we contribute concrete empirical knowledge to the "lifelong agents" and "self-evolving agents" paradigms.
- Over time, this creates a body of comparative work across models, revealing patterns in how different architectures respond to evolution techniques.

This is not about competing with frontier labs on raw scale.  
It is about mastering the **art of the possible** at human scale — and helping shape the path toward more capable, trustworthy, and understandable AI systems.

---

## Getting Started

- **Repo Structure**: Planned under `pra-cha/REFM` or similar.
- **Tools**: Unsloth, verl, Letta/MemGPT, Weights & Biases, SAE libraries.
- **Compute**: Cloud instances (RunPod, Vast.ai) with A100/H100 GPUs.
- **Documentation**: One section per model + per experiment layer.

Future outputs will include detailed experiment reports, mechanistic insights, safety findings, and open-source artifacts.

---

**This document defines the REFM project.**  
It will be updated as new models drop and new insights emerge.

*Let's explore the art of the possible.*
