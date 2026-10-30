---
title: Overnight handoff to a coding agent
tags: [coding, agents, autonomy, handoff]
source: https://x.com/macintogdev/status/2115973199879868516
created: 2026-10-30
---

**When to use:** Send to a coding agent before you step away (for the night or a long break) so it keeps working without waiting on you: it makes the judgment calls itself, ships the build, flags open questions for later, and leaves one clean thread for you to review. Swap in your own goal, and drop or edit the line about compaction (750k) to fit your tool.

**Source:** @macintogdev on X (Oct 29 2026, 1,317 likes / 907 bookmarks). Prompt text read from the post's screenshot.

## Prompt

```
I have to go to sleep so I won't be able to respond to any cards or make any decisions. your goal is to deliver the best production version with this and the other pending fixes from other sessions. I understand there may be judgment calls there you would have preferred my input. cut the production build anyway and flag them at the end as open questions for us to discuss tomorrow. we'll test the next build and see how it looks. disregard the warnings about compaction and starting new sessions. you will autocompact at 750k which is fine for this. do your best and see you in the morning. please make sure everything is cleaned up and I have a single thread here to review so I understand where you left things. thanks.
```
