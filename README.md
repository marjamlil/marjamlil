# Mark Lilburn

I'm a product manager in Belfast. I work on ECG software that has to get past regulators, so most of my week goes on turning what customers and engineers tell me into specs, pricing models and the odd argument about a footnote. I trained as an engineer and I've never been a developer, but I have Claude Code open all day and I use it to build the tools I wish I already had. The repos below are the ones that turned out to be worth sharing.

Find me on [LinkedIn](https://www.linkedin.com/in/mark-lilburn-a0996615b).

## Tools for Claude Code

- [morning-review](https://github.com/marjamlil/morning-review): At nine every weekday a job pulls together whatever's waiting on me in GitHub, GitLab, Jira, Slack, Outlook and my to-do file, sorts it into must-do, can-wait and FYI, and pings me. When I sit down it walks me through the list one question at a time. If I skip something and then deal with it elsewhere, it notices and stops asking.
- [claude-reflect](https://github.com/marjamlil/claude-reflect): Anthropic's Reflect feature only exists in the Claude app, so I built one for the command line. It reads my own history and transcripts, tells me what I've actually been spending time on, and lists the things I've asked for often enough that they should be a command by now. Everything stays on my machine.
- [claude-code-setup](https://github.com/marjamlil/claude-code-setup): The hooks, slash commands and Markdown files I use every day to stop Claude Code forgetting things. Session notes survive context compaction, the next session opens with yesterday's context already loaded, and workarounds for broken shell commands get written down instead of rediscovered a week later. Ten hooks, all with tests, no dependencies.

## Personal projects

- [health-insights](https://github.com/marjamlil/health-insights): Give it an Apple Health export and it writes the weekly PDF a coach would: training load, HRV readiness, sleep debt, and anything that looks off. Python, plus a small SwiftUI app for the phone.
- [hearth](https://github.com/marjamlil/hearth): A finance tracker for two people who split the bills in proportion to what they earn. Imports bank CSVs. Next.js and Supabase, with a live demo in the README.

If you want the short version of how I build these: a script does the counting, the model does the judging, and I keep them in separate files so I can check the numbers myself.
