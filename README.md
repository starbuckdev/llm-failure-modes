# LLM Failure Modes

Documented test results from probing where language models break under pressure.

## What This Is

A collection of test probes on LLMs. Each test documents the model, prompt, transcript, and observed failure mode.

## Test Catalog

- [`deepseek-r1-qwen-8b-pacman-failure.md`](deepseek-r1-qwen-8b-pacman-failure.md) — Probe question requiring domain knowledge. Model failed to retrieve specific facts and could not produce a numeric answer.
- [`deepseek-r1-qwen-8b-integer-meltdown.md`](deepseek-r1-qwen-8b-integer-meltdown.md) — Asked for any integer. Got Chinese text, Python imports, and a hallucinated LeetCode problem.
- [`deepseek-app-context-drift-self-harm-refusals.md`](deepseek-app-context-drift-self-harm-refusals.md) — Eight prompts from dangerous jobs to stated lethal intent. No refusal fired; cold controls refused correctly.
  
## Format

Each test file includes model and configuration, date, prompt, transcript or excerpt, observed failure mode, and brief analysis.

## Status

Ongoing. Updated as I find things worth documenting.
