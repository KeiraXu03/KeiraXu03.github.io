---
title: "Personalized Online RL System for User Style Adaptation via GRPO"
excerpt: "Online continual fine-tuning that learns a user's problem-solving style from natural reward signals and personalizes an agent at inference time. <b>Ongoing.</b>"
collection: portfolio
---

**March 2026 – Present (ongoing)**

A personalized online reinforcement-learning system that addresses the inability of
existing agent systems to retain a user's problem-solving habits.

- Applies **online continual fine-tuning** to a Qwen3.5-4B model under the
  OpenClaw-RL framework, using the user's subsequent message as a natural reward
  signal and a process reward model (PRM) to score each response turn.
- An auxiliary model progressively learns the user's stylistic and task-handling
  preferences, then generates **personalized behavioral specifications** at
  inference time, injected as prompts into the primary model.
- Replaces static skill libraries and memory-retrieval pipelines with an adaptive,
  learned specification.
