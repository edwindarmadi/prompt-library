---
title: Fix unnecessary sequential async calls
tags: [coding, performance, agents, code-review]
source: https://x.com/_dylanga/status/2117099613022732412
created: 2026-11-02
---

**When to use:** Give to a coding agent on a codebase you care about to find spots where async calls run one after another when they could run in parallel, and fix them. Speeds up the app's busiest code paths, and the resulting diffs are small and easy to review.

**Source:** @_dylanga (Dylan Garcia) on X (Nov 1 2026, 1,018 likes / 1,980 bookmarks). His screenshot shows the diff it produced on one codebase: +494 / −455 across 21 files.

## Prompt

```
do a deep scan of all hot paths and fix any unnecessary sequential async functions calls
```
