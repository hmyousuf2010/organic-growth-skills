# Organic Growth Skills

Claude Code skills that write content people actually want to read.

Three interconnected skills for researching, writing, and publishing content on Twitter/X, GitHub, and other platforms. Every word passes through an AI detection filter built from GPTZero's 3.3M-document corpus, Wikipedia editor findings, and detection tool databases. The output reads like a person wrote it, because the skill knows exactly what patterns to avoid.

## Why this exists

AI-generated content has tells. Em dash overuse, synonym cycling, "delve" and "tapestry" everywhere, that "It's not just X, it's Y" structure. Detection tools catch these patterns with 97-100% accuracy.

These skills fix that. They carry a database of 500+ flagged words, 200+ banned phrases, and 24 structural patterns that trigger AI detectors. Every piece of content gets checked against all of them before you see it.

## The 3 skills

### `/write-like-human`
The foundation. Turns AI text into human-sounding text, or writes new content from scratch that passes detection. Knows the difference between Dev Twitter voice, Crypto Twitter slang, Gen Z lowercase-everything, and startup build-in-public energy. Adapts to whatever audience you're writing for.

### `/research-content`
Deep research before you write. Analyzes repos, finds trending topics, maps out what competitors are posting, identifies content gaps. Produces a structured brief with specific angles, audience insights, and platform-specific strategy (including current Twitter/X algorithm weights).

### `/write-content`
The writer. Creates tweets, threads, replies, quote tweets, GitHub READMEs, social media bios, and more. Uses 25 proven tweet templates, thread architecture patterns, hook formulas, and README structures. Gives you 3 variations for every request: recommended, alternative angle, and bold/risky.

## Quick start

Copy the skills to your Claude Code project:

```bash
git clone https://github.com/YOUR_USERNAME/organic-growth-skills.git /tmp/ogs

# Project-level (this repo only)
cp -r /tmp/ogs/skills/* .claude/skills/

# Or personal (all your projects)
cp -r /tmp/ogs/skills/* ~/.claude/skills/
```

Then in Claude Code:

```
/write-content
```

That's it. The skill asks what you need and handles the rest.

## What's inside

```
skills/
├── write-like-human/
│   ├── SKILL.md                          # Core humanization rules
│   └── references/
│       ├── ai-patterns-database.md       # 500+ AI tells to avoid
│       ├── word-tiers.md                 # Banned word lists (3 tiers)
│       └── cultural-styles.md            # Voice adaptation by audience
│
├── research-content/
│   ├── SKILL.md                          # Research workflow
│   └── references/
│       ├── twitter-algorithm.md          # Current X algorithm weights
│       └── sector-profiles.md            # Audience profiles by niche
│
└── write-content/
    ├── SKILL.md                          # Content creation workflow
    ├── references/
    │   ├── tweet-templates.md            # 25 viral tweet formats
    │   ├── thread-structures.md          # Thread architecture
    │   ├── hook-formulas.md              # Opening patterns
    │   ├── readme-templates.md           # README structures + badges
    │   └── bio-formulas.md              # Bio formulas by platform
    └── examples/
        └── tweet-examples.md             # Examples by sector
```

## How it works

Every skill follows the same loop:

1. **Ask** — gathers context about your audience, platform, tone, and goals
2. **Research** — pulls in platform-specific data and patterns
3. **Write** — produces content using human writing patterns
4. **Check** — runs the output through 12 detection checks
5. **Deliver** — gives you 3 options with engagement analysis

The detection checklist catches things like:
- Tier 1 banned words (10-269x more common in AI text)
- Em dash density (AI uses 2-5x more than humans)
- Uniform sentence length (humans vary from 3 to 40+ words)
- Synonym cycling (humans just repeat the same word)
- Formulaic structures ("In today's fast-paced world...")
- Missing contractions (AI defaults to "do not" instead of "don't")

## Supported content types

| Type | Platforms | What you get |
|------|-----------|-------------|
| Single tweets | Twitter/X | 3 variations, character count, engagement prediction |
| Threads | Twitter/X | 5-10 tweet architecture, hook, cliffhangers, CTA |
| Replies | Twitter/X | Value-add replies, not "great point!" fluff |
| Quote tweets | Twitter/X | Unique takes, experience-based additions |
| Project READMEs | GitHub | Full structure with badges, quick start, features |
| Profile READMEs | GitHub | Bio, stats widgets, tech badges, social links |
| Bios | Twitter, GitHub, LinkedIn, etc. | 3-5 variations, precise character counts |

## Sector-specific voices

The skills adapt to your community:

- **Dev Twitter** — ship updates, TIL posts, tool recs, open source announcements
- **Crypto/CT** — gm culture, alpha threads, market takes, degen energy
- **Startup** — build-in-public, milestones, hiring posts, honest failure stories
- **AI/ML** — paper summaries, demo reactions, model comparisons, hot takes
- **Academic** — measured, hedged, citation-ready, but still engaging

## Contributing

Found a new AI tell that's not in the database? Know a tweet format that's been crushing it? PRs are welcome.

The reference files in each skill's `references/` directory are where the knowledge lives. Update those and the skills get smarter.

## License

MIT
