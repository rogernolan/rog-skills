# Skills

Reusable skills developed and maintained with Codex.

## Available skills

- [technical-writing](skills/technical-writing/SKILL.md): Write and revise technical documentation with plain prose, explicit ownership, precise scope, and clear evidence.

## Structure and installation

Each skill lives in `skills/<skill-name>/` and contains a `SKILL.md` entrypoint.
Keep any supporting scripts, references, or assets inside that skill's directory.

To use the repository version directly in Codex, create a symbolic link from
`~/.agents/skills/<skill-name>` to the skill's directory in this checkout.
Edits in the repository then update the installed skill. Codex detects changes
automatically; restart Codex if a new or renamed skill does not appear.
See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills).
