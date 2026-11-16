---
name: learned
description: Add a learning entry to this repository's daily Markdown notes. Use when the user says they learned something, asks to record or save a learning, or invokes the learned skill.
---

# Learned

Use this skill to record learning entries in this repository's daily Markdown
notes.

## Format

- Keep one Markdown file per day, named with the date as `YYYY-MM-DD.md`.
- The file's top-level heading must be that same date, such as `# 2026-11-16`.
- Give every learning entry its own title and text.
- Keep all entries for a date in that date's existing file.

## Adding an entry

1. Use the current local date to determine the filename and top-level heading.
2. If today's file exists, read it and append a new entry without changing existing entries.
3. If it does not exist, create it with the date heading, followed by the new entry.
4. Give the entry a concise title and write its text based on what the user shared. Preserve the user's meaning; ask a focused question if there isn't enough information to make a useful entry.
5. Confirm the entry was recorded and mention the file path.

Use this entry structure:

```markdown
## Entry title

Entry text.
```
