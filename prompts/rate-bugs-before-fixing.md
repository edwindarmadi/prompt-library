---
title: Rate bugs before fixing
tags: [coding, code-review, agents]
source: https://x.com/voxyz_ai/status/2115518965443076573
created: 2026-10-29
---

**When to use:** Add to a code-review prompt, skill, or AGENTS.md so a reviewer agent stops flagging bugs that are possible in theory but almost never happen, and the fixer agent stops over-building. Tune the threshold of 5 to your project.

**Source:** @voxyz_ai on X (Oct 28 2026, 1,188 likes / 1,758 bookmarks)

## Prompt

For the reviewer:

```
Rate each bug from 1 to 10 on how often it would happen and how bad it would be. If the two scores multiplied are below 5, just file it as an issue and leave the code alone.
```

For the coder fixing the code (CLAUDE.md or AGENTS.md):

```
Do not design for rare or future cases nobody asked about.
```
