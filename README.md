# Dark Luxury Editorial Web Skill

A reusable Codex skill for turning travel briefs, route guides, and first-person travel notes into polished dark editorial microsites.

This skill is tuned for the kind of travel pages that need:

- a full-screen photographic Hero
- the same cover reused as the blurred page background
- a seamless Hero-to-second-screen transition
- structured itinerary or memoir layouts
- restrained place and food tags
- mobile-first typography and motion
- Pixabay-first media sourcing with explicit fallback rules
- optional BGM workflow guidance

## What This Skill Is For

Use this skill when you want to build or refine:

- travel route-guide websites
- multi-day itinerary pages
- first-person travel memoir pages
- editorial lifestyle landing pages
- dark luxury / Kinfolk-like microsites with photography-led composition

It is especially useful when the input starts as raw travel text and needs to become a real interactive web page.

## What Is Included

- `dark-luxury-editorial-web-skill/`
  The full skill source.
- `dark-luxury-editorial-web-skill/SKILL.md`
  The core workflow and guardrails.
- `dark-luxury-editorial-web-skill/references/`
  Supporting references for benchmarking, itinerary planning, media sourcing, implementation recipes, and writing guidance.
- `dist/dark-luxury-editorial-web-skill.skill`
  A packaged installable artifact.

## Key Capabilities

- Hero and next-screen continuity rules
- mobile-first layout and optical centering guidance
- route-guide and memoir content normalization
- itinerary planning structure for cold-start travel requests
- timeline and section design rules
- concrete place / food tag rules
- media sourcing workflow with fallback chain
- font payload control guidance for Vite travel projects
- audio direction and playback UX guidance

## Benchmark Family

The skill is calibrated against this design family:

- Xishuangbanna route guide: `https://dark-luxury-travel-itinerary.vercel.app`
- Jingshan route guide: `https://wuhan-jingshan-travel-guide.vercel.app`
- Jingshan memoir: `https://youji.travel-itinerary-jingshan.online`

## Install Artifact

The packaged artifact is available at:

- `dist/dark-luxury-editorial-web-skill.skill`

## Repository Structure

```text
.
├── dark-luxury-editorial-web-skill/
│   ├── SKILL.md
│   ├── agents/
│   └── references/
└── dist/
    └── dark-luxury-editorial-web-skill.skill
```

## Version

This repository is being released with the initial public tag:

- `v1.0.0`
