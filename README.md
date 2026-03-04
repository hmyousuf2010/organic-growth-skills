# Organic Growth Skills

**Claude Code skills that write content humans actually want to read — and AI detectors can't flag.**

Three interconnected skills for researching, writing, and publishing content on Twitter/X, GitHub, and other platforms. Built on a research foundation of GPTZero's 3.3M-document corpus analysis, Wikipedia editor findings from 10,000+ flagged articles, and cross-referenced data from 6 detection tools. Every word, phrase, and structural pattern passes through a 24-point detection filter before output.

This is not a prompt template collection. It is a complete writing system with 500+ flagged words organized into 3 severity tiers, 200+ banned phrases mapped to their AI frequency multipliers, 25 proven content formats with engagement data, and cultural adaptation profiles for 8 distinct writing communities.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/Claude_Code-Skills-blueviolet)](https://claude.com/claude-code)
[![Platform](https://img.shields.io/badge/Platform-Claude_Code-orange)](https://claude.com/claude-code)

---

## Table of Contents

- [Why This Exists](#why-this-exists)
- [The Science Behind Detection](#the-science-behind-detection)
- [The 3 Skills](#the-3-skills)
  - [write-like-human (Foundation)](#1-write-like-human--foundation-skill)
  - [research-content (Research)](#2-research-content--research-skill)
  - [write-content (Writer)](#3-write-content--content-creation-skill)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [The Detection Engine](#the-detection-engine)
- [Word Tier System](#word-tier-system)
- [Structural Pattern Detection](#structural-pattern-detection)
- [Statistical Thresholds](#statistical-thresholds)
- [Cultural Adaptation](#cultural-adaptation)
- [Twitter/X Algorithm Intelligence](#twitterx-algorithm-intelligence)
- [Content Formats Reference](#content-formats-reference)
- [Supported Content Types](#supported-content-types)
- [Reference Architecture](#reference-architecture)
- [Research Sources](#research-sources)
- [Contributing](#contributing)
- [License](#license)

---

## Why This Exists

AI-generated content has measurable, statistical tells. Not "vibes" — hard data.

GPTZero analyzed 3.3 million documents and found that words like "delve" appear **10x more often** in AI text than human text. "Play a significant role in shaping" shows up **182x more frequently**. "Objective study aimed" — **269x**. Wikipedia editors flagged over 10,000 articles using AI pattern recognition, and their top finding was the negation-contrast structure ("It's not just X, it's Y") which appears in virtually zero human-written encyclopedia articles but saturates AI output.

Detection tools like GPTZero, Originality.ai, and ZeroGPT achieve **97-100% accuracy** on unmodified AI text. They measure:

- **Perplexity** — how predictable the next word is (AI text is very predictable)
- **Burstiness** — variation in sentence complexity (AI is metronomic, humans spike)
- **Vocabulary distribution** — AI clusters around the same "impressive" words
- **Structural fingerprints** — AI follows rigid patterns humans don't

These skills don't just avoid bad words. They understand *why* AI text reads differently from human text at a statistical level, and they produce output that matches human distributions across every measurable dimension.

---

## The Science Behind Detection

### How AI Detectors Work

Modern AI detection operates on three layers:

**Layer 1: Lexical Analysis**
Detectors maintain databases of words and phrases that appear at abnormal frequencies in AI-generated text. GPTZero's vocabulary analysis found that AI text concentrates around ~500 words that human writers rarely use or use at much lower rates. The frequency multiplier ranges from 10x ("delve," "tapestry," "landscape" as metaphor) to 269x ("objective study aimed").

**Layer 2: Statistical Modeling**
Detectors compute document-level statistics:
- **Perplexity score** — measures how "surprising" the text is to a language model. Human writing has higher perplexity (more unexpected word choices). AI text has low, consistent perplexity.
- **Burstiness score** — measures variation in sentence-level perplexity. Human writing alternates between complex and simple sentences ("bursts"). AI maintains even complexity.
- **Type-Token Ratio (TTR)** — vocabulary diversity. Humans reuse familiar words. AI synonym-cycles to avoid repetition, paradoxically signaling itself.

**Layer 3: Structural Fingerprinting**
AI text follows predictable structural templates:
- Formulaic intros ("In today's fast-paced world...")
- Rigid organization (Intro → Point 1 → Point 2 → Point 3 → Conclusion)
- Consistent paragraph lengths
- Negation-contrast patterns ("It's not just X — it's Y")
- Rule-of-three groupings ("innovation, collaboration, and growth")

These skills address all three layers simultaneously.

---

## The 3 Skills

### 1. `/write-like-human` — Foundation Skill

The core engine. Every other skill routes through this one. It transforms AI-generated text into authentic human writing, or writes new content from scratch that passes detection tools.

**What it does:**

1. **Gathers context** — asks about audience, platform, persona, tone, cultural context, and emotional intent before writing a single word. If you provide reference text, it analyzes sentence patterns, vocabulary level, and structural preferences.

2. **Runs 24-point AI pattern detection** — every output passes through a complete checklist covering vocabulary, structure, statistics, and formatting. Nothing ships until all 24 checks pass.

3. **Applies human writing patterns** — varies sentence length (3-word punches to 40-word run-ons), uses contractions naturally (60-80% of eligible spots), includes sentence fragments, parenthetical asides, rhetorical questions, and specific numbers instead of vague claims.

4. **Adapts culturally** — adjusts voice for Tech/Dev, Crypto/Web3, Gen Z, Startup, South Asian English, Academic, AI/ML, and Professional contexts. Each adaptation is based on documented linguistic patterns from those communities.

5. **Self-verifies** — checks em dash density, banned word presence, sentence variation coefficient, contraction rate, passive voice percentage, and formulaic patterns before delivering output.

**The 24-Point Detection Checklist:**

| # | Check | What It Catches |
|---|-------|----------------|
| 1 | Significance inflation | "marking a pivotal moment in the history of..." |
| 2 | Notability name-dropping | Unnecessary references to famous people/events |
| 3 | Superficial -ing analyses | "showcasing," "highlighting," "emphasizing" |
| 4 | Promotional language | "best-in-class," "next-generation," "game-changer" |
| 5 | Vague attributions | "experts say," "research suggests," "studies show" |
| 6 | Formulaic challenges | "despite facing challenges," "in the face of adversity" |
| 7 | Tier 1 vocabulary | 70+ words that are instant AI flags |
| 8 | Tier 2 vocabulary density | Words allowed once per 1000 words max |
| 9 | Tier 3 vocabulary clusters | Common words that become suspicious in groups |
| 10 | Copula avoidance | "serves as" → "is", "boasts" → "has" |
| 11 | Negative parallelism | "It's not just X, it's Y" — the top AI tell |
| 12 | Rule of three | Forced triplet groupings |
| 13 | Synonym cycling | "building" → "structure" → "edifice" → "construction" |
| 14 | False ranges | "from intimate gatherings to global movements" |
| 15 | Em dash density | Max 1 per 500 words (AI uses 2-5x human rate) |
| 16 | Bold overuse | Mechanical bolding of every key term |
| 17 | Title Case headings | Sentence case is human default |
| 18 | Emoji in headings | Professional content doesn't decorate headers |
| 19 | Curly quotes | Casual digital writing uses straight quotes |
| 20 | Chatbot artifacts | "Great question!", "I hope this helps!" |
| 21 | Filler phrases | "In order to" → "to", "Due to the fact" → "because" |
| 22 | Hedging stacks | "could potentially possibly" → pick one |
| 23 | Passive voice percentage | Keep under 15% (AI defaults to ~50%) |
| 24 | Generic conclusions | "The future looks bright" → specific ending |

**Reference files:**
- [ai-patterns-database.md](skills/write-like-human/references/ai-patterns-database.md) — 200+ banned phrases with frequency multipliers, structural patterns, detection tool thresholds
- [word-tiers.md](skills/write-like-human/references/word-tiers.md) — Complete 3-tier word classification with safe alternatives for every banned word
- [cultural-styles.md](skills/write-like-human/references/cultural-styles.md) — 8 cultural/community writing profiles with linguistic markers, vocabulary, and examples

---

### 2. `/research-content` — Research Skill

Deep research engine for content creation. Analyzes repos, trends, audiences, and competitors before a single word gets written.

**What it does:**

1. **Gathers research context** — topic, platform, goal, audience, sector, competitive scope
2. **Conducts multi-source research** — project analysis (GitHub repos, docs, changelogs), trend research (current sector topics), audience analysis (what performs well), competitor analysis (how similar projects/people communicate), content gap identification (what's missing)
3. **Produces structured briefs** — key findings, content angles, audience insights, competitive landscape, recommended format, vocabulary the target audience uses, risks/avoids, all sources cited

**Platform-specific intelligence:**

For **Twitter/X**, the skill knows:
- Current algorithm engagement weights (reply-to-reply = 150x a like, bookmark = 20x, retweet = 2x)
- External link penalties (30-50% reach reduction) and workarounds (link-in-reply = 270% view increase)
- TweepCred reputation scoring (accounts below 0.65 get ghosted)
- Optimal posting cadence (2-5 quality tweets/day, spaced 30-60 minutes)
- Time decay mechanics (50% visibility every 6 hours, first 30-60 minutes are everything)
- Premium subscriber advantages (roughly 10x reach per post)
- Grok-powered ranking changes (January 2026 transformer model replacement)

For **GitHub**, it analyzes:
- Similar projects and their README approaches
- What makes top repos in the space successful
- Badge and shield recommendations
- Documentation patterns that drive adoption
- Community engagement strategies

**Reference files:**
- [twitter-algorithm.md](skills/research-content/references/twitter-algorithm.md) — Complete X algorithm breakdown with engagement weights, negative signals, reputation scoring, Premium advantages, time decay formulas, posting strategy
- [sector-profiles.md](skills/research-content/references/sector-profiles.md) — 5 detailed audience profiles (Dev, Crypto, Startup, AI/ML, Design) with what performs well, writing style markers, content gaps, and cross-sector patterns

---

### 3. `/write-content` — Content Creation Skill

The writer. Creates any content type using the foundation skill's humanization engine and the research skill's platform intelligence.

**What it does:**

1. **Gathers full context** — content type, topic, persona, goal, and platform-specific details. For tweets: length preference, sector, angle, media suggestions. For READMEs: project details, tech stack, audience, desired impression. For bios: platform, character limit, personality vs credentials balance.

2. **Creates content** with multiple variations:
   - **Option A** (recommended) — safest high-quality version
   - **Option B** (alternative angle) — different approach
   - **Option C** (bold/risky) — more provocative take
   - Plus engagement analysis, customization suggestions, and post-publish strategy

3. **Applies write-like-human rules** to everything — no exceptions, no shortcuts.

**Content capabilities:**

| Type | What You Get |
|------|-------------|
| **Single tweets** | 3-5 variations across tones, character counts, engagement type predictions |
| **Threads** | 5-10 tweet architecture with hook, cliffhangers every 1-2 tweets, visual break suggestions, engagement driver ending |
| **Replies** | Value-add replies with unique perspective, follow-up questions to create conversation chains (replies weighted 27x a like by the algorithm) |
| **Quote tweets** | Unique takes that expand on originals, not just agreement |
| **Project READMEs** | Full structure: name, badges, hero visual suggestion, "why this exists," quick start (<60s), features, usage examples, install, config, contributing, license |
| **Profile READMEs** | Bio, current focus, tech badges, GitHub stats, social links, creative elements (ASCII art, code-formatted bio, custom banners) |
| **Bios** | 3-5 variations with precise character counts per platform (Twitter 160, GitHub 160, LinkedIn 220, Instagram 150, TikTok 80, Bluesky 256) |

**25 proven tweet templates included:**

Hot take, "X things I learned," Thread opener, Personal story, Prediction, Tutorial step-by-step, Before/After transformation, Tier list, Unpopular opinion, Observation humor, Question engagement, Challenge, "Nobody talks about X," List tweet, Quote tweet commentary, "I spent X hours researching," Comparison, Self-deprecating humor, Behind the scenes, Data share, Myth-busting, Resource dump, Problem-Agitation-Solution, Audience call-out, Curiosity gap.

Each template includes format structure, when to use it, expected engagement type, and sector-specific variations.

**Reference files:**
- [tweet-templates.md](skills/write-content/references/tweet-templates.md) — 25 viral tweet formats with structure, usage guidance, and examples
- [thread-structures.md](skills/write-content/references/thread-structures.md) — Thread architecture: hook anatomy (smack + twist + tease), 8 hook types, cliffhanger techniques, visual break strategy, thread enders
- [hook-formulas.md](skills/write-content/references/hook-formulas.md) — 8 hook types: curiosity gap, contrarian, number/stat, story, question, bold claim, credibility + promise, audience call-out
- [bio-formulas.md](skills/write-content/references/bio-formulas.md) — 8 bio writing formulas with platform-specific rules and character counting
- [readme-templates.md](skills/write-content/references/readme-templates.md) — Project and profile README structures with badges, shields.io syntax, section-by-section guidance
- [tweet-examples.md](skills/write-content/examples/tweet-examples.md) — Real-world examples by sector: Dev, Crypto/CT, Startup, AI/ML, Design

---

## Quick Start

### Installation

Copy the skills into your Claude Code setup:

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/organic-growth-skills.git /tmp/ogs

# Option A: Project-level (this repo only)
cp -r /tmp/ogs/skills/* .claude/skills/

# Option B: Personal (all your projects)
cp -r /tmp/ogs/skills/* ~/.claude/skills/
```

### Usage

In Claude Code, invoke any skill directly:

```
/write-like-human    # Humanize existing text or write from scratch
/research-content    # Research before writing
/write-content       # Create tweets, threads, READMEs, bios
```

Each skill asks context questions first. Answer them and it handles the rest.

**Example workflow:**

```
You: /research-content
Skill: What's the research topic?
You: I'm launching an open source Rust CLI tool for log analysis

Skill: [produces research brief with content angles, audience insights, competitive analysis]

You: /write-content
Skill: What type of content?
You: Twitter thread announcing the launch, dev audience, 7 tweets

Skill: [produces 3 thread variations, each passing all 24 detection checks]
```

---

## Project Structure

```
organic-growth-skills/
│
├── README.md                                    # This file
├── docs/
│   └── SKILLS_RESEARCH_PROMPT.md               # Original research methodology (863 lines)
│
├── skills/
│   ├── write-like-human/                        # FOUNDATION SKILL
│   │   ├── SKILL.md                             # Core humanization engine (~400 lines)
│   │   └── references/
│   │       ├── ai-patterns-database.md          # 200+ banned phrases, structural patterns,
│   │       │                                    # detection thresholds, frequency multipliers
│   │       ├── word-tiers.md                    # 500+ words in 3 severity tiers with
│   │       │                                    # safe alternatives for every entry
│   │       └── cultural-styles.md               # 8 cultural/community writing profiles
│   │                                            # with linguistic markers and examples
│   │
│   ├── research-content/                        # RESEARCH SKILL
│   │   ├── SKILL.md                             # Research workflow and brief format
│   │   └── references/
│   │       ├── twitter-algorithm.md             # X algorithm weights, TweepCred scoring,
│   │       │                                    # Premium advantages, time decay, link penalties
│   │       └── sector-profiles.md               # 5 audience profiles: Dev, Crypto, Startup,
│   │                                            # AI/ML, Design — with engagement data
│   │
│   └── write-content/                           # CONTENT CREATION SKILL
│       ├── SKILL.md                             # Content creation workflow
│       ├── references/
│       │   ├── tweet-templates.md               # 25 proven viral tweet formats
│       │   ├── thread-structures.md             # Thread architecture and hook anatomy
│       │   ├── hook-formulas.md                 # 8 hook types with formulas
│       │   ├── bio-formulas.md                  # 8 bio formulas, platform char limits
│       │   └── readme-templates.md              # Project + profile README structures
│       └── examples/
│           └── tweet-examples.md                # Real examples by sector
│
└── .claude/
    └── settings.local.json                      # Claude Code configuration
```

**Total reference material:** ~15,000 words of researched, structured data across 13 reference files.

---

## How It Works

### The 5-Step Loop

Every skill follows this process:

```
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│  1. ASK  │───▶│2. RESEARCH│───▶│ 3. WRITE │───▶│ 4. CHECK │───▶│5. DELIVER│
│          │    │          │    │          │    │          │    │          │
│ Gather   │    │ Pull in  │    │ Produce  │    │ Run 24   │    │ 3 options│
│ context  │    │ platform │    │ content  │    │ detection│    │ + analysis│
│ about    │    │ data and │    │ using    │    │ checks   │    │ + strategy│
│ audience,│    │ patterns │    │ human    │    │ against  │    │          │
│ platform,│    │          │    │ writing  │    │ output   │    │          │
│ tone     │    │          │    │ patterns │    │          │    │          │
└──────────┘    └──────────┘    └──────────┘    └──────────┘    └──────────┘
```

**Step 1: Ask** — Never assumes. Asks about audience, platform, persona, tone, cultural context, emotional intent. If reference text is provided, analyzes it first.

**Step 2: Research** — Loads relevant reference files. For Twitter content, pulls algorithm weights and sector profiles. For READMEs, loads templates and badge guides. For humanization, loads the full pattern database.

**Step 3: Write** — Produces content using documented human writing patterns: varied sentence length, natural contractions, fragments for emphasis, active voice, specific numbers, parenthetical asides, asymmetric lists.

**Step 4: Check** — Runs all 24 detection checks. Verifies em dash count, banned word absence, sentence variation coefficient, contraction rate, passive voice percentage, structural patterns. If anything fails, rewrites.

**Step 5: Deliver** — Provides 3 variations (recommended, alternative, bold), engagement analysis, customization suggestions, and post-publish strategy.

---

## The Detection Engine

### Why Simple Word Lists Don't Work

Replacing "delve" with "explore" isn't enough. Detection tools measure statistical distributions, not individual words. A document can contain zero banned words and still get flagged because:

- Sentence lengths are too uniform (low burstiness)
- Next-word predictions are too accurate (low perplexity)
- Vocabulary diversity is paradoxically too high (synonym cycling)
- Structural patterns match AI templates (formulaic organization)

These skills work at the distribution level. They don't just remove AI words — they reshape the statistical fingerprint of the entire document to match human distributions.

### Detection Tool Thresholds

| Tool | Human threshold | AI threshold | What it primarily measures |
|------|----------------|--------------|--------------------------|
| GPTZero | >85 perplexity | <20 perplexity | Perplexity + burstiness per sentence |
| Originality.ai | >70% human score | <30% human score | Trained classifier on millions of samples |
| ZeroGPT | "Human" classification | "AI" classification | Statistical pattern matching |
| Turnitin AI | <20% AI probability | >80% AI probability | Sentence-level perplexity analysis |
| Copyleaks | "Human" label | "AI" label | Multi-model fingerprint comparison |

The skills target **>85% human score** on Originality.ai and **>85 perplexity** on GPTZero as minimum thresholds.

---

## Word Tier System

### Tier 1 — Never Use (instant AI flags)

These words appear 10-269x more frequently in AI text than human text. Using any one is a detection signal.

**Nouns:** tapestry, landscape (metaphorical), realm, kaleidoscope, interplay, testament, beacon, symphony, roadmap, cornerstone, facet, paradigm, catalyst, milestone, intricacies, synergy, bedrock, linchpin

**Verbs:** delve, foster, underscore, showcase, leverage, harness, embark, illuminate, elevate, curate, empower, unravel, transcend, spearhead, bolster, navigate (metaphorical), streamline, reimagine, catalyze, underpin, unleash, unlock

**Adjectives:** pivotal, multifaceted, groundbreaking, transformative, invaluable, meticulous, seamless, vibrant, robust, comprehensive, commendable, exemplary, innovative, unprecedented, cutting-edge, paramount, myriad, ubiquitous, unparalleled, holistic

**Adverbs:** meticulously, seamlessly, notably, profoundly, intricately, tirelessly, indelibly, crucially, fundamentally

**Transitions:** Moreover, Furthermore, Additionally, Indeed, Subsequently, Accordingly, Consequently, Thus, Therefore, Notably

> Full list with safe human alternatives for every word: [word-tiers.md](skills/write-like-human/references/word-tiers.md)

### Tier 2 — Use Sparingly (max 1 per 1000 words)

elevate/elevated, proactive, dynamic, agile, nuanced, intersection, supercharge, enhanced, powerful, intuitive, tailored, aligned, essential, enable, distinct, strategic, modern, scalable, optimize, thrilled

### Tier 3 — Watch Density (suspicious in clusters)

key, important, significant, compelling, profound, crucial, effective, however, overall, specifically, particularly, ultimately, emphasize, highlight, journey, explore, craft, resonate, diverse, unique, remarkable

**The rule:** Any single Tier 3 word is fine. Three or more Tier 3 words within 200 words triggers detection.

---

## Structural Pattern Detection

### Pattern: Em Dash Overuse

**The data:** Human writers use em dashes at a rate of 0-2 per 1000 words. AI text averages 5-14 per 1000 words — a 2-5x multiplier. GPT-4o uses approximately 10x more em dashes than GPT-3.5, likely because its training data included more 19th/early 20th century books where em dashes were fashionable (30% more frequent than modern writing).

**The fix:** Maximum 1 em dash per 500 words. Use commas, periods, or parentheses instead.

### Pattern: Uniform Sentence Length

**The data:** Human writing has a HIGH coefficient of variation in sentence length. A human paragraph might contain: "No." (1 word) followed by "The whole point of building something in public is that people get to see the messy parts, the wrong turns, the features you shipped at 2am that broke everything." (30 words). AI defaults to ~15-word sentences with minimal variation.

**The fix:** Deliberately alternate between short punches (3-8 words), medium sentences (12-20 words), and long flowing sentences (25-40+ words). One paragraph shouldn't have all similar-length sentences.

### Pattern: Synonym Cycling

**The data:** AI's repetition penalty causes it to use different words for the same concept across paragraphs. A human developer says "building" three times because that's the word they think in. AI says "building," then "constructing," then "crafting," then "developing" — and detectors catch this unnatural vocabulary distribution.

**The fix:** Repeat your key words. Don't artificially vary them. If you're talking about a "tool," call it a "tool" every time.

### Pattern: Negation-Contrast Structure

**The data:** Wikipedia editors identified this as the single most reliable AI tell in encyclopedic writing. The patterns: "It's not just X, it's Y." "Not only X, but also Y." "X isn't about Y — it's about Z." These structures appear in virtually zero human-written Wikipedia articles but saturate AI output.

**The fix:** State what things ARE, not what they're not. "This tool speeds up deployment" instead of "This tool isn't just about deployment — it's about transforming your entire workflow."

### Pattern: Rule of Three

**The data:** AI systematically groups items in threes: "innovation, collaboration, and growth." "speed, security, and scalability." "research, design, and implementation." Humans use asymmetric lists — sometimes 2 items, sometimes 5, sometimes 7.

**The fix:** Vary list lengths. Use 2 items sometimes. Use 4 or 5 other times. The pattern breaks the detector's expectation.

### Pattern: Formulaic Introductions

**The data:** "In today's fast-paced world" appears **107x more frequently** in AI text than human text. Other formulaic openers like "As the [industry] continues to evolve" and "In a world where" are strong AI signals.

**The fix:** Start with something specific. A number, a short statement, a question, or jump straight into the point.

> Complete pattern database with frequency data: [ai-patterns-database.md](skills/write-like-human/references/ai-patterns-database.md)

---

## Statistical Thresholds

These are the measurable differences between human and AI writing that detection tools exploit:

| Metric | Human Range | AI Range | What the skill targets |
|--------|------------|----------|----------------------|
| **Burstiness** (sentence complexity variation) | Mean 83-95 | Mean 64-70 | >80 |
| **Perplexity** (word predictability) | >85, variable | <20, consistent | >85 |
| **Sentence length CoV** (coefficient of variation) | High (0.4-0.8) | Low (0.1-0.3) | >0.4 |
| **Type-Token Ratio** (vocabulary diversity) | 0.5-0.7 | 0.3-0.5 (or >0.8 from synonym cycling) | 0.5-0.7 |
| **Em dashes per 1000 words** | 0-2 | 5-14 | <2 |
| **Passive voice percentage** | 5-15% | ~50% | <15% |
| **Contraction rate** (% of eligible contractions used) | 60-80% | 10-30% | 60-80% |
| **Trigram repetition rate** | <0.05 | >0.10 | <0.05 |

**Filler phrase auto-replacements:**

| AI Filler | Human Replacement |
|-----------|------------------|
| "In order to" | "to" |
| "Due to the fact that" | "because" |
| "At this point in time" | "now" |
| "It is important to note that" | (delete — just state the fact) |
| "In the event that" | "if" |
| "Prior to" | "before" |
| "Despite the fact that" | "although" |
| "In terms of" | (rephrase or delete) |
| "It is worth mentioning" | (just mention it) |
| "It goes without saying" | (then don't say it — delete) |

---

## Cultural Adaptation

The skills adapt voice and style based on who you're writing for. Each profile is based on documented linguistic patterns from that community.

### Tech/Developer

**Markers:** Direct, concise, jargon-appropriate. Self-deprecating humor. References to debugging, shipping, yak-shaving. Heavy use of abbreviations (TIL, LGTM, FWIW, YMMV, RTFM). Code-switching between technical precision and casual commentary.

**Example voice:** "just spent 3 hours debugging a css issue that turned out to be a missing semicolon. classic."

### Crypto/Web3

**Markers:** "gm," "wagmi," "ngmi," "lfg," "ser," "anon," "wen," "probably nothing," "this is the way," "based." Terse conviction statements. Informal capitalization. Meme-aware. Alpha-sharing energy.

**Example voice:** "gm. been digging into [protocol] for 2 weeks. most people are sleeping on this. few."

### Gen Z

**Markers:** Lowercase everything. No periods (periods feel aggressive). Heavy use of "lol," "ngl," "lowkey," "highkey," "fr," "imo." Reaction words: "bruh," "deadass," "no cap." Intentional misspellings and abbreviations.

**Example voice:** "ngl this actually goes hard lowkey been waiting for someone to build this"

### Startup/Founder

**Markers:** "shipping," "building in public," "0 to 1." Growth metrics language. Optimistic but grounded. Fundraising terminology. Honest about failures. "We're hiring" energy.

**Example voice:** "Month 4 update: $12k MRR, 340 users, burned through the pivot. Here's what actually happened."

### South Asian English

**Markers:** Tag questions ("isn't it?", "no?"). "Do the needful." Specific honorific patterns. Warmth and relationship-building before business. Code-switching between formal English and casual phrases.

**Example voice:** "Built this over the weekend actually. Had some issues with the auth flow but sorted it out. Give it a try na?"

### Academic/Professional

**Markers:** Hedged but not sterile ("our results suggest" rather than "we proved"). Citation-ready language. Measured claims. Can still include personality and opinion within disciplinary norms.

### AI/ML Community

**Markers:** Casual + technical hybrid. Paper reference style ("the Anthropic paper shows..."). Benchmark comparisons. Demo energy ("just dropped," "check this out"). Hot takes on models. Memes about training runs and GPU costs.

### Professional/Corporate

**Markers:** Clear and direct without being sterile. Short sentences preferred. Measured tone with room for personality. No slang but not stiff either.

> Full cultural profiles with vocabulary lists, common phrases, and adaptation rules: [cultural-styles.md](skills/write-like-human/references/cultural-styles.md)

---

## Twitter/X Algorithm Intelligence

The research skill maintains current data on X's recommendation algorithm (last updated March 2026, including the Grok-powered ranking change from January 2026).

### Engagement Weights

| Action | Weight | Multiplier vs Like |
|--------|--------|-------------------|
| Reply-to-reply | +75.0 | 150x |
| Reply | +13.5 | 27x |
| Profile click | +12.0 | 24x |
| Link click | +11.0 | 22x |
| Bookmark | +10.0 | 20x |
| Retweet/Quote | +1.0 | 2x |
| Like | +0.5 | 1x (baseline) |

**Key insight:** Replies are worth 27x a like. Reply-to-reply (conversation chains) are worth 150x. The algorithm rewards conversation, not passive engagement.

### Negative Signals

| Signal | Penalty |
|--------|---------|
| Report | -369.0 |
| User unfollows after seeing tweet | -74.0 |
| Mute conversation | -74.0 |
| Block | -74.0 |
| "Not interested" feedback | -50.0 |
| Spam report | -369.0 |

### External Link Penalty

Since March 2023, X penalizes external links with 30-50% reach reduction. Workarounds:
- Post link in first reply (270% view increase vs link in main tweet)
- Use screenshots with "link in reply"
- Premium subscribers face less penalty

### Optimal Posting Strategy

- **Frequency:** 2-5 quality tweets per day, spaced 30-60 minutes apart
- **Critical window:** First 30-60 minutes determine reach
- **Time decay:** 50% visibility loss every 6 hours
- **Reply target:** 50 quality replies per day to other accounts
- **Thread length:** 5-10 tweets (7 is ideal), with hooks that work standalone

### TweepCred Reputation Score

X assigns every account a reputation score from 0 to 100:
- Accounts below 0.65 get only 3 tweets considered for distribution
- Consistent posting, genuine engagement, and low report rates improve score
- Score is invisible to users but determines algorithmic reach

> Full algorithm breakdown: [twitter-algorithm.md](skills/research-content/references/twitter-algorithm.md)

---

## Content Formats Reference

### Tweet Templates (25 formats)

| # | Template | Best For | Expected Engagement |
|---|----------|----------|-------------------|
| 1 | Hot take | Quick reactions | Likes, quote tweets |
| 2 | "X things I learned" | Knowledge sharing | Bookmarks, threads |
| 3 | Thread opener | Long-form content | Follows, bookmarks |
| 4 | Personal story | Authenticity | Replies, likes |
| 5 | Prediction | Thought leadership | Quote tweets, replies |
| 6 | Tutorial step-by-step | Education | Bookmarks, retweets |
| 7 | Before/After | Transformation | Likes, bookmarks |
| 8 | Tier list | Community engagement | Replies, quote tweets |
| 9 | Unpopular opinion | Debate | Replies, quote tweets |
| 10 | Observation humor | Entertainment | Likes, retweets |
| 11 | Question | Discussion | Replies |
| 12 | Challenge | Participation | Replies, tags |
| 13 | "Nobody talks about X" | Gap-filling | Bookmarks, retweets |
| 14 | List tweet | Value packing | Bookmarks |
| 15 | Quote tweet commentary | Conversation | Profile clicks |
| 16 | "I spent X hours" | Research sharing | Bookmarks, follows |
| 17 | Comparison | Decision-making | Bookmarks, replies |
| 18 | Self-deprecating humor | Relatability | Likes, replies |
| 19 | Behind the scenes | Transparency | Likes, follows |
| 20 | Data share | Authority building | Bookmarks, retweets |
| 21 | Myth-busting | Correction | Quote tweets, replies |
| 22 | Resource dump | Value | Bookmarks, retweets |
| 23 | Problem-Agitation-Solution | Marketing | Link clicks, follows |
| 24 | Audience call-out | Targeting | Replies, follows |
| 25 | Curiosity gap | Engagement bait (ethical) | Replies, bookmarks |

> Full templates with structure, examples, and sector variations: [tweet-templates.md](skills/write-content/references/tweet-templates.md)

### Thread Architecture

```
Tweet 1: HOOK (self-contained, curiosity gap)
          ↓
Tweet 2-3: Setup (context, problem, stakes)
          ↓
Tweet 4: VISUAL BREAK (screenshot, diagram, code)  ← +45% completion rate
          ↓
Tweet 5-6: Core insight (the payload)
          ↓
Tweet 7: ENGAGEMENT DRIVER (question, challenge, CTA)
```

**Hook anatomy:** Smack (grab attention) → Twist the knife (create tension) → Tease (promise value)

> Full thread guide: [thread-structures.md](skills/write-content/references/thread-structures.md)

### Tweet Length Performance

| Length Range | Performance |
|-------------|------------|
| 71-100 chars | 17% higher engagement rate (hot takes, one-liners) |
| 70-110 chars | Best for retweets (shareable, quotable) |
| 240-259 chars | Most total likes (complete thoughts, mini-stories) |
| Full 280 chars | No penalty (use when the thought needs space) |

### Bio Formulas (8 types)

1. **Role + Specialty + Personality:** "Backend dev. Building [project]. Coffee-powered."
2. **Building + Previously + Achievement:** "Building [X]. Ex-[company]. [Notable thing]."
3. **What + For Whom + Proof:** "[What you do] for [audience]. [Social proof]."
4. **Mission/Value:** "[What you believe]. Building [how you act on it]."
5. **Audience-First:** "Helping [audience] do [thing]. [How]."
6. **Multi-Hat/Slash:** "[Role 1] / [Role 2] / [Role 3]. Currently [focus]."
7. **Story Arc:** "[Past] → [Present] → [Future]."
8. **Achievement + CTA:** "[Achievement]. [What you share]. Follow for [promise]."

**Platform character limits:**

| Platform | Limit |
|----------|-------|
| Twitter/X | 160 chars (emojis = 2 chars each) |
| GitHub | 160 chars |
| LinkedIn headline | 220 chars |
| Instagram | 150 chars |
| TikTok | 80 chars |
| Discord | 190 chars |
| Bluesky | 256 chars |

> Full bio guide: [bio-formulas.md](skills/write-content/references/bio-formulas.md)

### README Templates

**Project README sections (in order):**
1. Project name + one-line description
2. Badges (CI, version, license, downloads)
3. Hero visual (screenshot, GIF, architecture diagram)
4. "Why [Project]?" — the problem it solves
5. Quick Start (under 60 seconds, copy-paste commands)
6. Key Features (bullet points, specific, no buzzwords)
7. Usage examples (real code, not pseudo-code)
8. Installation (step-by-step)
9. Configuration (if applicable)
10. API reference (if applicable)
11. Contributing (welcoming tone)
12. License (one line)

**Profile README sections:**
1. About me (who you are, what you care about)
2. Current focus ("building X" / "exploring Y")
3. Tech stack badges (shields.io)
4. GitHub stats (optional — only if impressive)
5. Social links
6. Creative element (ASCII art, code-formatted bio, custom banner)

> Full README guide with badge syntax: [readme-templates.md](skills/write-content/references/readme-templates.md)

---

## Supported Content Types

| Content Type | Platforms | What You Get |
|-------------|-----------|-------------|
| Single tweets | Twitter/X | 3-5 variations, character count, engagement prediction, post-publish reply strategy |
| Threads | Twitter/X | 5-10 tweet architecture, hook, cliffhangers, visual break suggestions, CTA |
| Replies | Twitter/X | Value-add replies with unique perspective and follow-up questions |
| Quote tweets | Twitter/X | Unique takes with experience-based additions |
| Project READMEs | GitHub | Full structure with badges, quick start, features, usage examples |
| Profile READMEs | GitHub | Bio, stats widgets, tech badges, social links, creative elements |
| Bios | Twitter, GitHub, LinkedIn, Instagram, TikTok, Discord, Bluesky | 3-5 variations with precise character counts |
| Text humanization | Any platform | AI text → human text conversion with 24-point verification |

### Sector-Specific Voices

| Sector | Style | Example Content Types |
|--------|-------|----------------------|
| **Dev Twitter** | Direct, self-deprecating, jargon-appropriate | Ship updates, TIL posts, tool recs, open source announcements, debugging stories |
| **Crypto/CT** | gm culture, terse conviction, alpha-sharing | gm posts, alpha threads, market takes, community engagement, meme commentary |
| **Startup** | Build-in-public, metrics, honest | Milestones, hiring posts, failure stories, fundraising updates, founder lessons |
| **AI/ML** | Technical + casual hybrid, demo energy | Paper summaries, tool announcements, model comparisons, benchmark hot takes |
| **Design** | Visual, process-focused, craft-obsessed | Before/after showcases, process breakdowns, micro-detail observations |
| **Academic** | Hedged, citation-ready, measured | Research announcements, paper discussions, field commentary |

---

## Reference Architecture

The skills use a layered reference system to keep SKILL.md files under 500 lines while providing deep reference material on demand:

```
SKILL.md (core logic, <500 lines)
    │
    ├── references/          (loaded when skill needs specific data)
    │   ├── data files       (word lists, algorithm weights, templates)
    │   └── guide files      (cultural profiles, structural patterns)
    │
    └── examples/            (loaded for output calibration)
        └── sector examples  (real-world content samples)
```

**Why this matters:** Claude Code loads SKILL.md into context when a skill triggers. Reference files are loaded on demand when the skill needs specific data (e.g., loading tweet-templates.md when creating a tweet, loading twitter-algorithm.md when researching posting strategy). This keeps context efficient while providing deep reference material when needed.

**Total reference corpus:**
- 13 reference files
- ~15,000 words of structured data
- 500+ categorized words
- 200+ banned phrases with frequency data
- 25 tweet templates
- 8 hook formulas
- 8 bio formulas
- 8 cultural profiles
- Complete algorithm weight tables
- 5 sector audience profiles
- Platform character limit tables

---

## Research Sources

This project's reference material was compiled from:

### AI Detection Research
- **GPTZero vocabulary analysis** — 3.3M document corpus, word frequency multipliers (10x-269x)
- **Wikipedia "Signs of AI writing"** — editor-identified patterns from 10,000+ flagged articles
- **Blake Stockton "Red Flag Words/Phrases"** — categorized AI vocabulary lists
- **Originality.ai blog** — perplexity and burstiness research, statistical thresholds
- **ContentBeta "300+ AI Words"** — comprehensive categorized word list
- **fomo.ai "Ultimate AI Words to Avoid"** — copy-paste prompt lists
- **playbooks.com operator-humanizer skill** — personality injection techniques

### Twitter/X Algorithm
- **X/Twitter open-sourced algorithm** (github.com/twitter/the-algorithm) — engagement weight formulas
- **Sprout Social algorithm analysis** — current ranking factors and Grok integration
- **TweetArchivist** — viral tweet templates, algorithm explanation, viral strategies
- **Platform engineering blogs** — TweepCred scoring, time decay mechanics

### Content Creation
- **awesome-readme** (github.com/matiassingers/awesome-readme) — README best practices
- **Best-README-Template** (github.com/othneildrew/Best-README-Template) — template structures
- **awesome-github-profile-readme** — profile README examples and creative elements
- **makeareadme.com** — README writing guide
- **shields.io** — badge generation and syntax

### Claude Code Skills
- **Claude Code documentation** (code.claude.com/docs/en/skills) — SKILL.md format, frontmatter options
- **Anthropic skills repository** (github.com/anthropics/skills) — skill architecture patterns
- **skills.sh** — skill discovery and publishing

---

## Contributing

The reference files are where the knowledge lives. PRs that improve them make every skill smarter.

**High-value contributions:**

- **New AI detection patterns** — found a tell that's not in [ai-patterns-database.md](skills/write-like-human/references/ai-patterns-database.md)? Add it with source and frequency data.
- **Updated algorithm data** — X changes its algorithm regularly. Keep [twitter-algorithm.md](skills/research-content/references/twitter-algorithm.md) current.
- **New tweet templates** — formats that are performing well right now. Add to [tweet-templates.md](skills/write-content/references/tweet-templates.md) with examples.
- **Cultural profiles** — writing communities not yet covered. Add to [cultural-styles.md](skills/write-like-human/references/cultural-styles.md) with linguistic markers and examples.
- **Word tier updates** — detection tools evolve. Words move between tiers. Keep [word-tiers.md](skills/write-like-human/references/word-tiers.md) accurate.
- **Sector examples** — real-world tweet/content examples for sectors. Add to [tweet-examples.md](skills/write-content/examples/tweet-examples.md).

**How to test changes:**

1. Copy updated skills to `~/.claude/skills/` or `.claude/skills/`
2. Invoke the skill in Claude Code
3. Check output against the 24-point detection checklist
4. Optionally test with GPTZero or Originality.ai for detection scores

---

## License

MIT

