# dsh-superagent demo

A scratch repository for trying the dsh-superagent agent. Nothing here is production code.

## How to ask the agent for work

Comment `@sandalwoods-agent <request>` on an issue in this repository. The request must come from an account on the allowed list, which today is only `sandalwoods`.

## Good first asks

- Fix a typo or awkward wording in `notes.md`.
- Tighten a sentence in `notes.md` without changing its meaning.
- Add a short section to `notes.md` that lists the questions this repository is meant to answer.

## What the agent does

It works in its own clone, pushes a branch named `agent/<ticket>`, opens a pull request, and comments back on the issue. A person merges the pull request.
