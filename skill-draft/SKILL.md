---
name: agent-gpu-runtime-colab
description: Draft workflow for using Google Colab CLI as an agent-managed remote GPU runtime.
---

# Agent GPU Runtime via Colab CLI

Trigger when a local agent task needs a temporary GPU/TPU runtime.

## Steps
1. Confirm task, dataset, success metric, and artifact path.
2. Provision a named Colab runtime with the smallest acceptable accelerator.
3. Install dependencies explicitly and log versions.
4. Execute one script/notebook remotely.
5. Download artifacts and logs.
6. Stop the runtime.
7. Record cost/runtime evidence and decide promote / iterate / hold.

## Pitfalls
- Do not leave runtimes running.
- Do not claim validation until a real job has completed.
- Keep secrets out of notebooks and logs.
