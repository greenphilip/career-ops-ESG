@AGENTS.md

<!-- Add Claude Code-specific guidance here only when it has no AGENTS.md counterpart. -->

**Sync check.** At the start of every session, Claude runs `git fetch` and compares this folder with GitHub. If GitHub is ahead, or a cloud session left an unmerged branch, Claude says so in the first reply and offers to pull or merge before any work. Philip decides.
