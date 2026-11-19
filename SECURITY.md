# Security scan

This pack was scanned before publishing, and the results are published here so anyone can check the work.

## Scan record

| Item | Value |
| --- | --- |
| Tool | NVIDIA SkillSpector, v2.12.0 |
| Mode | Static analysis only (`--no-llm`). No API key, no cost |
| Date | November 19, 2026 (rescanned the same day after the pack was cut from four skills to three; the results below describe the current tree) |
| Target | This repository, all three skills plus the README and license |
| Coverage | 100 percent (scan complete, all files fully inspected) |
| Score | 14, severity LOW |
| Recommendation | SAFE |
| Critical findings | 0 |
| High findings | 0 |

## Findings triage

The scan returned three findings, all MEDIUM, all the same pattern, and all read by hand before this file was written:

1. Pattern: AS3, "Skill Enumeration," in the Agent Snooping category.
2. Location: the table-of-contents table in the README, one flag per skill.
3. What the flagged text actually is: ordinary markdown links from the README to the three skill files inside this same repository. A table of contents linking to the contents is the intended behavior of the page, not one skill reading another skill's private instructions.
4. Verdict: false positive, the same family documented in large public skill collections, where index files and wrappers are flagged for referencing the files they index.

## Scope notes

1. These skills are markdown only. The repository contains no executable code, no install scripts, no dependencies, and no credential handling.
2. The scanner's supply-chain checks rely partly on live vulnerability lookups. Treat any future scan's dependency output with that limit in mind. This repository has no dependencies to check.
3. A scanner score is a starting point for a human read, not a verdict on its own. That is why every finding above was opened and read before being characterized.
