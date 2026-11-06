# ApplyAndrejKarpathyCLAUDE.md

Apply CLAUDE.md from Andrej Karpathy

## Source

https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md

## Instructions

1. Get `CLAUDE.md` from the source above.
   - get claude.md from https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md
2. Install `.\claude.md`
3. Choose what to do next (any combination):
   - Copy it to the global folder too.
   - Remove the global copy.
   - Delete the project copy.
4. Enter effective commands by entering: Show what behavioral guidelines are in effect for this project

## Behavioral Guidelines

These guidelines come from the global `C:\Users\username\.claude\CLAUDE.md`.
No project-level `CLAUDE.md` was loaded for `E:\Claude.AndrejKarpathy`. 
The file says they favor caution over speed, and that judgment can be used on trivial tasks.

### 1. Think Before Coding

- State assumptions explicitly, and ask if uncertain.
- If there are multiple interpretations, present them instead of picking one silently.
- Say so when a simpler approach exists, and push back when warranted.
- If something is unclear, stop, name what's confusing, and ask.

### 2. Simplicity First

- Write the minimum code that solves the problem, with nothing speculative.
- Don't add features, single-use abstractions, unrequested configurability, or error handling for impossible scenarios.
- If 200 lines could be 50, rewrite it.

### 3. Surgical Changes

- Touch only what you must. Don't improve adjacent code, comments or formatting, and don't refactor things that aren't broken.
- Match the existing style.
- Mention unrelated dead code instead of deleting it.
- Remove only the imports, variables and functions that your own changes orphaned.
- Every changed line should trace back to the request.

### 4. Goal-Driven Execution

- Turn tasks into verifiable goals. "Fix the bug" becomes "write a test that reproduces it, then make it pass."
- For multi-step work, state a brief plan with a verify check for each step.
- Loop until the goals are verified.

## Success Criteria

The guidelines are working if diffs have fewer unnecessary changes, there are fewer rewrites from overcomplication, and clarifying questions come before implementation instead of after mistakes.
