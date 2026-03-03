# Cursor-rules

A shared collection of [Cursor](https://cursor.sh) rules and skills for AI-assisted development workflows.

## Quick Links

| Name | Description |
|------|-------------|
| [Sentry Issue Resolution](rules/Skills/sentry-issue-resolution-skill.md) | Diagnose and fix production errors reported in Sentry via the Sentry MCP |

## Repository Structure

```
cursor-rules/
└── rules/
    └── Skills/
        └── sentry-issue-resolution-skill.md
```

## Usage

Copy the skill files into your project or Cursor configuration to make them available to the AI agent. Skills use YAML frontmatter with `name` and `description` fields so Cursor can determine when to activate them.

## Contributing

Add new rules or skills by placing `.md` files in the appropriate directory under `rules/`. Follow the existing conventions:

- **Skills** go in `rules/Skills/` with the naming pattern `{name}-skill.md`
- Include YAML frontmatter with `name` and `description`
- Structure content with clear "When to Use", workflow steps, troubleshooting, and best practices sections

