# agent-skills

Agent skills for software engineering, built to be read before they are run. Each skill is a folder with a `SKILL.md` that tells an AI coding agent when to use it and what to check, plus any scripts it runs and the evals that test it. The skills here accompany the short videos by [Dalibor Kralik](https://dalibor-kralik-knowledge.vercel.app/), and every skill is small enough to review in a few minutes.

## Skills

| Skill | Use when | Scripts it runs |
|---|---|---|
| | | |

## Install

Copy a skill folder from `skills/` into `~/.claude/skills/` (all projects) or `.claude/skills/` in your project (one project). Read its `SKILL.md` and any scripts first.

No skill runs network calls or remote code unless stated.

## Layout

- `skills/`: one folder per skill.
- `evals/`: the checks each skill is tested against.
- `SECURITY.md`: what scripts may do and how to report a problem.
- `CHANGELOG.md`: what changed, by release.

## License

MIT, see `LICENSE`.
