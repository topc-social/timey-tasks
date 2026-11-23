# Timey tasks

Timey's public project repo: tasks and the Neki ledger for Timey. Timey makes time tracking fill itself in: your timer entries get named from what you actually did (your AI sessions, commits and regular calls), so you stop typing task names, and client hours turn into an invoice without a month-end scramble. Idea: https://www.ideato.social/idea/0c2d0fa5-211b-4e7c-b39a-d0260cab1363

First step: a nightly job that names the day's Toggl entries for one client from Claude Code sessions and git commits. Hours are never changed, only the names.

- [Issues](https://github.com/topc-social/timey-tasks/issues): open tasks. Each issue is one task, and its `neki:N` label is the Neki it earns (1 Neki = 1 rupee of work at market price).
- [`LEDGER.md`](LEDGER.md): who has earned what. Your share of Timey = your Neki / all Neki there.

## How it works

1. Pick any open issue. Anyone can hand in, and the best hand-in wins.
2. Do the work however you like, including with your own AI.
3. Hand in by commenting on the issue with a link others can open (usually a pull request) and a line or two on what you did.
4. Kamal accepts the best hand-in, labels the issue `accepted`, and closes it. A workflow then adds the two Neki rows (1% idea, 99% work) to [`LEDGER.md`](LEDGER.md) itself.

## Rules

- Proof must be something others can open, and anyone you quote or record has to agree to it.
- Made-up people, answers or numbers earn nothing.
- Neki is a record of your work and becomes your share in what gets built. Rules: TOPC's NEKI.md.
