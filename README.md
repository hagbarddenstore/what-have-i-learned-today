# What Have I Learned Today?

A collection of daily learning notes. Each day has one Markdown file named
`YYYY-MM-DD.md`, with a matching top-level heading and individually titled
entries for things learned that day.

## Notes format

```markdown
# YYYY-MM-DD

## A concise entry title

Text describing what was learned.
```

Add new entries to that date's existing file. Create a file with the date
heading when adding the first entry for a day. See [AGENTS.md](AGENTS.md) for
the repository's note-taking conventions.

## Example

The notes include an entry about how rootless Podman maps the running host user
to `root` inside a container, allowing container-created files in a bind mount
to retain the host user's ownership. The entry includes a command example and a
link to its source.

## OpenCode skill

This repository includes an OpenCode project skill named `learned` at
`.opencode/skills/learned/SKILL.md`. OpenCode can use it when you say you
learned something or ask to record a learning. It adds a titled entry to the
current day's note, creating the date-named file if needed, while following the
notes format above.
