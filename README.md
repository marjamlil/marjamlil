# Mark Lilburn

Product manager in Belfast, working on ECG algorithms and software that go through FDA and EU regulatory review. I trained as an engineer and I still work close to the code: reviewing merge requests, writing requirements that engineers can test against, and building the pricing and value models that customers push back on. When I find a gap in how my team or I work, I build the tool rather than wait for one.

The repos here are the ones that have held up in daily use. Each started as a workflow problem I could describe precisely enough to fix. I build them with Claude Code, and every one ships with tests, a README written for the next person, and a clear line between what a script computes and what a model decides.

Find me on [LinkedIn](https://www.linkedin.com/in/mark-lilburn-a0996615b).

## Tools for Claude Code

- [morning-review](https://github.com/marjamlil/morning-review): I was starting each day by checking five systems by hand and still missing things. This runs at nine every weekday: it pulls what's waiting on me from GitHub, GitLab, Jira, Slack, Outlook and a to-do file, classifies it into must-do, can-wait and FYI, then steps me through it one decision at a time. It tracks what I skip and stops asking once the platform shows I've dealt with it. Six pluggable sources, one config file, tests for each.
- [claude-reflect](https://github.com/marjamlil/claude-reflect): Anthropic ship a usage-reflection feature in the Claude app but not in the command line, and I wanted hard data on where my time with the tool goes. This reads the local history and transcripts, produces exact counts, and writes a short report that ends with what I've asked for often enough to turn into a command. It runs entirely on the machine.
- [claude-code-setup](https://github.com/marjamlil/claude-code-setup): Long sessions lose context and every new session starts cold. These ten hooks keep a plain-Markdown ledger current through context compaction, load yesterday's state at startup, and record shell workarounds as they happen so they aren't rediscovered. Includes the slash commands, a settings template and smoke tests for every hook.

## Personal projects

- [health-insights](https://github.com/marjamlil/health-insights): Apple Health collects a great deal of data and shows very little of it usefully. This turns an export into the weekly report a coach would write: training load, HRV-based readiness, sleep debt and anomaly flags, all computed locally. Python, with a SwiftUI companion app.
- [hearth](https://github.com/marjamlil/hearth): A household finance tracker for two people on different incomes. Expenses split in proportion to earnings, bank CSV import, and a tested calculation core. Next.js and Supabase, with a live demo linked in the README.

How I work: define the outcome and the acceptance criteria first, let deterministic code do the counting, let the model do the judgement, and keep the two apart so every number can be checked.
