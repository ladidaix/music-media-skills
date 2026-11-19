# Music Journalism Skills for Claude

Four production-tested Claude skills for music journalists and indie artist teams: a weekly New Music Friday column, a social carousel builder, an interview production pipeline, and an outreach intelligence workflow.

These are not prompts. Each skill is a complete working method, with the format rules, the quality checks, and the failure modes already baked in, extracted from a real weekly publishing operation and rewritten so any music journalist, editor, podcaster, or indie artist team can run them.

## Who this is for

1. Music journalists and editors running a weekly releases column.
2. Podcasters and video hosts who tape interviews and need an editor-ready package fast.
3. Indie artists and small teams doing their own social content and sponsor outreach.
4. Anyone using Claude who would rather hand it a proven workflow than a blank prompt.

## The skills

| Skill | What it does | Reach for it when |
| --- | --- | --- |
| [New Music Friday Column](skills/new-music-friday-column/SKILL.md) | Builds a weekly NMF column in a consistent format, with a genre-balanced title, first-mention hyperlink rules, a scrapbook collage cover, and a Thursday copy, Friday links schedule that works around release-day catalog lag | It is release week and the column needs to ship on Friday |
| [Carousel Builder](skills/carousel-builder/SKILL.md) | Builds Instagram, LinkedIn, and TikTok carousels with face-safe crops, an identity badge system, platform-safe footers, a glossy editorial template, and an A+ layout audit (one margin grid, measured-ink alignment, shared baselines) | You need a multi-slide post that looks designed, not generated |
| [Interview Production](skills/interview-production/SKILL.md) | Turns a recording into docx and markdown transcripts, sentence-boundary SRT captions, a stitched 15-second cold open, and social clip selects with timestamps, searchable titles, and tags | You just taped an interview and your editor needs a package, not a raw file |
| [Outreach Intel](skills/outreach-intel/SKILL.md) | Triages an email draft pileup into still live, dead, needs nudge, and needs review buckets, then mines past threads and sheets into a ranked, verified, warm-first contact list for sponsors and partners | You are starting a sponsorship or partnership push and refuse to pitch from guesses |

## Install

### All four skills (Claude Code)

```bash
git clone https://github.com/ladidaix/music-journalism-skills.git
cp -R music-journalism-skills/skills/* ~/.claude/skills/
```

### One skill only

```bash
git clone https://github.com/ladidaix/music-journalism-skills.git
cp -R music-journalism-skills/skills/carousel-builder ~/.claude/skills/
```

### Other Claude surfaces

Copy the contents of any `SKILL.md` into your project's instructions or custom skill slot. The skills are plain markdown with YAML frontmatter, and they carry no code, no dependencies, and no credentials.

## One example per skill

### New Music Friday Column

Ask: "Build this week's New Music Friday column from these 14 releases."

You get a titled column (`New Music Friday (June 6): Maya Rivers, Kade, The Hollow Pines, and More`, genre-mixed on purpose), clean bold headers with no links in them, hyperlinks on the first body mention of every artist, an "also out" line that still links everyone it names, a scrapbook collage cover built only from photos you have the rights to use, and a link pass scheduled for Friday morning, because the catalog pages do not exist on Thursday night.

### Carousel Builder

Ask: "Turn this album review into a five-slide Instagram carousel."

You get a cover with a face-safe crop and a serif italic accent word in the headline, interior slides on one margin grid with type aligned by measured ink, a footer handle placed to clear the platform's action buttons, lossless images, and a self-audit that fails the build if a baseline jumps or a bottom margin drifts.

### Interview Production

Ask: "Produce the package for the interview I taped yesterday."

You get transcripts in docx and markdown, SRT captions cut at sentence boundaries, a 15-second cold open stitched from three timestamped moments, three social clips with searchable titles and tags, and a note that says exactly what is ready for your editor and what is waiting on you. No rendered clips. Selects only, so the editor stays the editor.

### Outreach Intel

Ask: "Triage my drafts and build me a sponsor list for next month's push."

You get every draft sorted into still live, dead, needs nudge, needs review, or keep as note (private notes are flagged, never read aloud), plus one ranked contact list where every name, title, and email was verified against a real thread or sheet, warm relationships first, stale entries flagged instead of silently included. Drafts only. Nothing is ever sent for you.

## The principles baked into all four

1. Never invent quotes, facts, contacts, or relationships. If it cannot be verified against a source, it does not ship.
2. Match the established format before innovating. Consistency is the brand.
3. Check the actual rendered result, at full size, before calling anything done.
4. Draft, do not send. The human reviews, decides, and hits send.
5. Private material stays private. Notes, credentials, and off-the-record moments are flagged and protected, never surfaced.

## Security

This pack was scanned before publishing with [NVIDIA SkillSpector](https://github.com/NVIDIA/SkillSpector) v2.12.0, static analysis only (`--no-llm`). Results: score 14 (LOW), recommendation SAFE, 100 percent coverage, with zero CRITICAL and zero HIGH findings. The only findings were four MEDIUM "Skill Enumeration" flags on this README's own table-of-contents links to the skill files in this repository, each one read and confirmed as a false positive. Full details are in [SECURITY.md](SECURITY.md). The skills are markdown only. There is no executable code in this repository.

## Contributing

Found a failure mode the skills should know about, or adapted one for a different beat? Open an issue or a pull request. Keep examples generic: no real contact details, no private workflow data.

## License

MIT. Use them, adapt them, ship your column.

## Credit

Built and maintained by [@ladidaix](https://github.com/ladidaix), from the working workflows behind a weekly music column, an interview series, and an indie media operation.
