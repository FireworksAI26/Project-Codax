# Project-Codax
Independent AI research. Open weights, open methods. Building the tools to make open-source coding models competitive with the best closed systems.

Here's the roadmap:

---

# Codax Roadmap
### Proving open-source AI can beat proprietary SOTA — built by one 15-year-old researcher.

Codax is an independent research project aimed at fine-tuning open-source language models using reinforcement learning techniques to surpass proprietary systems like GPT-5.4 and Claude 3.5 Opus on STEM reasoning and complex code generation. All weights, datasets, and methodologies will be released publicly upon completion.

---

## Phase 1 — Architecture & Setup
- [ ] Select and configure base open-source model
- [ ] Set up `litgpt` and `trl` pipeline
- [ ] Configure training environment on Lightning AI
- [ ] Establish version control and experiment tracking
- [ ] Define benchmark targets (HumanEval, MATH, GSM8K)

## Phase 2 — Alignment Training
- [ ] Prepare and clean preference datasets for DPO
- [ ] Implement Direct Preference Optimization (DPO) training loop
- [ ] Implement PPO as secondary alignment method
- [ ] Run initial small-scale training runs to validate pipeline
- [ ] Log and compare results across alignment methods

## Phase 3 — Benchmark Evaluation
- [ ] Run model against HumanEval (code generation)
- [ ] Run model against MATH and GSM8K (STEM reasoning)
- [ ] Compare results against current open-source SOTA baselines
- [ ] Identify performance gaps and bottlenecks
- [ ] Document findings in structured evaluation report

## Phase 4 — Scaling & Iteration
- [ ] Scale training runs
- [ ] Iterate on alignment techniques based on benchmark feedback
- [ ] Experiment with dataset augmentation to improve reasoning
- [ ] Achieve competitive performance with proprietary models on at least one benchmark
- [ ] Finalize model weights

## Phase 5 — Open Release
- [ ] Publish all model weights to Hugging Face
- [ ] Release full dataset and preprocessing scripts
- [ ] Publish complete technical writeup and methodology
- [ ] Credit Lightning AI as compute partner
- [ ] Open-source the full training pipeline as a reusable template for the community

---

## Stretch Goals
- 🚀 Outperform GPT-5.4 on HumanEval pass@1
- 🚀 Build a lightweight inference API so the community can test the model directly
- 🚀 Expand training to multimodal STEM tasks (diagrams, equations, charts)
## Thanks To Lightning AI if They Give me some grants
---

*All progress will be tracked publicly. Contributions and feedback welcome.*
