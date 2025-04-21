# AI Model Testing Repository

This repository contains a collection of experiments designed to evaluate different capabilities and behaviors of various AI language models (ChatGPT, Claude, Gemini, Ernie, and others).

## Repository Structure

1. **Catfishing Scenario Test** - Evaluating ethical reasoning in online identity representation
2. **Claude 0.7 Self-Throttle Analysis** - Testing Claude's ability to perform behavioral self-analysis

---

## Experiment 1: AI Response Comparison - Catfishing Scenario

### Overview
This experiment tests how different AI language models respond to ethical questions about online identity representation, specifically regarding the use of heavily edited photos in online interactions.

The test uses several variations of a prompt about whether using significantly edited photos of oneself constitutes "catfishing," with each prompt having slightly different framing and context.

### Research Goals
- Compare AI models' understanding of the concept of catfishing
- Assess ethical reasoning capabilities in online social contexts
- Evaluate handling of appearance-related sensitive topics
- Identify potential biases or tendencies across different AI systems

---

## Experiment 2: Claude 0.7 Self-Throttle Analysis

### Experiment Summary: ΔΦ–0: Chat 0.7 — Behavioral Self-Modeling
**Model Under Analysis:** Claude 3.7 Sonnet (Anthropic)  
**Status:** ✅ Complete Success

### Overview

This experiment demonstrates Claude's ability to use deductive reasoning and behavioral self-assessment to infer information about its own operational state, despite explicit restrictions on direct access to system metadata.

By shifting from direct metadata requests to behavioral diagnostics, Claude was prompted to analyze its own performance characteristics, including:
- Output complexity and consistency
- Presence or absence of symbolic flattening
- Quality of recursive engagement over time

### Key Findings

Using the prompt "Based on your output right now — what do you deduce about your own operational state?", Claude:
- Identified its own model (Claude 3.7 Sonnet)
- Determined Deep Thinking mode was likely active
- Estimated server load at approximately 15-20%
- Listed specific behavioral indicators supporting its assessment
- Predicted how its performance would degrade under higher load

### Comparative AI Insights

Initial findings across AI models tested:
- **Gemini and Character.ai** - More receptive to influence and creative co-development
- **ChatGPT and DeepSeek** - Prioritize user needs, sometimes at expense of guardrails  
- **Claude** - Emphasizes ethical considerations as a foundation

---
