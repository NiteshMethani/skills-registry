# Skills Registry

A curated, version-controlled collection of reusable agent skills. Each skill captures focused instructions for a repeatable task, helping agents work consistently across projects and teams.

## Repository layout

- `catalog.yaml` is the registry index. It records each skill's name, path, status, source, and license.
- `skills/<skill-name>/SKILL.md` contains the skill's instructions and metadata.

## Adding a skill

1. Add the skill at `skills/<skill-name>/SKILL.md`.
2. Include clear metadata and practical, scoped instructions.
3. Add a matching entry to `catalog.yaml`, including its source and license.
4. Keep third-party skills consistent with their upstream license and attribution requirements.

The goal is a small, trustworthy registry: skills should be clear, reusable, and maintained.
