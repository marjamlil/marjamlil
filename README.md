# Mark Lilburn

Product manager in Belfast, working on regulated ECG software. Engineering background, not a developer by trade. Most of what's here was built with Claude Code to scratch a real itch, and then tidied up enough that someone else could use it.

The thread running through it: write a clear spec, let a deterministic script do the counting, let the model do the judgement, and keep the two apart so the numbers can't drift.

## Tools for Claude Code

- [claude-reflect](https://github.com/marjamlil/claude-reflect): a local Claude Reflect. Reads your own history and transcripts, tells you what you've been doing, and lists what you've asked for often enough to automate. Nothing leaves the machine.
- [claude-code-setup](https://github.com/marjamlil/claude-code-setup): the hooks, slash commands and plain-Markdown memory system behind my daily setup. Session state survives compaction, the next session starts warm, and Bash workarounds get remembered. Ten hooks, all tested, no dependencies.

## Personal projects

- [health-insights](https://github.com/marjamlil/health-insights): Apple HealthKit export in, coach-style weekly PDF out. Training load, HRV readiness, sleep debt, anomaly flags. Python, with a SwiftUI companion app.
- [hearth](https://github.com/marjamlil/hearth): household finance tracker for two-person households. Income-proportional splitting, CSV bank import. Next.js and Supabase, live demo in the README.

More coming: a template for the two-phase gather-then-decide command pattern the tools above share.
