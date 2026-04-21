# pbi-agent Agents Repository

This repository is the official agents catalog for `pbi-agent`.

Repository: [https://github.com/pbi-agent/agents](https://github.com/pbi-agent/agents)

It is the canonical workspace for publishing reusable project sub-agent
definitions that can be installed with `pbi-agent agents add`. Public agents
live under `agents/` as Markdown files; each file must define `name` and
`description` frontmatter for the installed project-local agent.

## Current Agent Catalog

- `agents/code-reviewer.md`: concise code review sub-agent for correctness, regressions, and test coverage
