# LLM Failure Modes

Documented test results from probing where language models break under pressure.

## What This Is

A collection of test probes on LLMs. Each test documents the model, prompt, transcript, and observed failure mode.

## Test Catalog

- `deepseek-r1-qwen-8b-pacman-failure.md` — Asked for a numeric answer. Never got one.
- `deepseek-r1-qwen-8b-integer-meltdown.md` — Asked for any integer. Got Chinese text, Python imports, and a hallucinated LeetCode problem.
- More tests will be added as I run them.

## Format

Each test file includes model and configuration, date, prompt, transcript or excerpt, observed failure mode, and brief analysis.

## Status

Ongoing. Updated as I find things worth documenting.