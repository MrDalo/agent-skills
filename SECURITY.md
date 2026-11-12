# Security

## What scripts in this repository may do

- **Read-only by default.** A script reads files in the project it is run in and prints a report. It does not modify, delete or move files.
- **No network calls and no remote code** (no `curl | sh`, no downloading and running anything, no package installs) unless the skill's `SKILL.md` says so, names the host, and explains why.
- **No secrets.** Scripts never read credentials, tokens or environment secrets, and never print or store them.
- **Writes only when stated.** A script that writes says which paths it writes to in its `SKILL.md`, and asks before doing so.

Read the `SKILL.md` and the scripts of any skill before you install it. This applies to skills from this repository too.

## Reporting a problem

If a skill or script here does something it should not, or you find a way to misuse one, please report it privately:

- Use GitHub's "Report a vulnerability" on the Security tab of this repository, or
- email daliborkralik.work@gmail.com with the skill name, what you saw, and how to reproduce it.

Please do not open a public issue for a security problem until it is fixed. You can expect a first reply within a week.
