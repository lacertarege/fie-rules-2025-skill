# FIE Rules 2025 Skill

Codex-compatible skill for answering questions about the official FIE fencing rules published on the FIE rules page as of December 2025.

## What It Covers

- technical rules for foil, epee, and sabre
- material and equipment conformity rules
- organisation rules for pools, direct elimination, and team events
- `t.170` offences and penalties

## Install

```bash
npx skills add https://github.com/lacertarege/fie-rules-2025-skill --skill fie-rules-2025
```

## Example Prompts

```text
Use $fie-rules-2025 to explain right of way in sabre.
Use $fie-rules-2025 to summarize FIE equipment rules for foil.
Use $fie-rules-2025 to tell me what card applies for leaving the piste.
```

## Repository Layout

```text
skills/
  fie-rules-2025/
    SKILL.md
    agents/openai.yaml
    references/
```

## Sources

The skill points to official FIE documents, including:

- Technical Rules, December 2025
- Material Rules, December 2025
- Organisation Rules, December 2025
- Article `t.170` offences and penalties

## Notes

- The skill is focused on the FIE international ruleset, not national federation variations.
- The references are structured so agents can route a question to the correct source quickly.
