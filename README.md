# gitquiet

**Memory for coding agents where you can delete a bad memory, so a mistake stops coming back. It also writes zero files to your repo.**

> ⚠️ Not built yet. This repo is a public interest check, not a product.
> No code, no install, no signup. If you want this, ⭐ star the repo.
> We decide by Nov 16 whether to build it.

## The problem
Agent memory tools are useful, but some leave memory files spread across
your project directories. Those files then turn up in diffs, commits and
code reviews. Others need an extra runtime, don't work properly on Windows,
or keep a bad memory that keeps steering the agent the wrong way.

## The promise
| What | How we'd prove it |
|---|---|
| **Prune bad memories** | See what the agent remembers, then delete any one memory |
| **0 files written to your repo** | `git status` stays clean after every session |
| **Memory kept per project, outside the repo** | Nothing to `.gitignore`, nothing to commit by mistake |
| **Works on Windows** | Windows, macOS and Linux are all release targets |

## Not planned
- A hosted service or account. Memory stays on your machine.
- Changes to your agent's prompts or workflow beyond memory.
- A replacement for your coding agent.

## Want this?
- ⭐ **Star the repo.** Stars are how we'll decide.
- **Open an issue** to tell us which agent and which memory tool you use
  today, and what would make you switch (or not).

No email list. We don't collect any personal data.
