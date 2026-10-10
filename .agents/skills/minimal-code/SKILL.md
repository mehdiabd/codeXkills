---
name: minimal-code
description: Make the smallest sound code change for a requested fix or feature. Use when explicitly invoked with $minimal-code.
---

# Minimal code

Make only the changes needed to satisfy the user's request. Prefer editing the target script in place and preserving its structure, naming, behavior outside the request, and existing conventions. Minimize changed files and lines, but do not sacrifice correctness, clarity, or required verification just to reduce a diff. Avoid unrelated refactors, new abstractions, dependencies, configuration, and helper scripts unless they are necessary. Run only focused checks relevant to the change. In the final answer, briefly identify what changed and how it was verified.
