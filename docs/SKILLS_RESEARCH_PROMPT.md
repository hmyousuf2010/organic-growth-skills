# MEGA RESEARCH + EXECUTION PROMPT: Human-Like Writing & Content Creation Skills

> **Purpose:** Give this entire prompt to Claude (Claude Code, Claude.ai, or Agent SDK) to research, create, test, and publish 3 interconnected skills for human-like writing, research, and social media/README content creation.
>
> **Output:** 3 production-ready Claude Code skills + `npx skills` project setup + registration guide.

---

## PHASE 1: DEEP RESEARCH (Do ALL of this before writing ANY skill)

You are tasked with building 3 interconnected, best-in-class Claude Code skills. Before writing a single line, you MUST conduct exhaustive research. Do NOT skip any research step. Use WebSearch and WebFetch extensively.

### 1.1 Research: AI Writing Detection Patterns (EXHAUSTIVE)

Search and compile a COMPLETE database of every known AI writing tell. This is the foundation of the "write-like-a-human" skill. Research ALL of the following:

**A) Overused AI Words (compile the full list of 500+):**
Research sources:
- Wikipedia "Signs of AI writing" page — extract EVERY word, phrase, structural pattern
- ContentBeta "300+ AI Words" list — get the complete categorized list
- GPTZero "Top 50 AI Words" — monthly updated rankings with frequency data
- Blake Stockton "Red Flag Words" and "Red Flag Phrases" — full categorized lists
- fomo.ai "Ultimate AI Words to Avoid" — the copy-paste prompt list
- Walter Writes "Most Common ChatGPT Words" — categorized list
- humanizeai.io "Common AI Words" — with frequency analysis

Organize into 3 tiers:
- **TIER 1 — NEVER USE (instant AI flags):** delve, tapestry, vibrant, crucial, comprehensive, meticulous, embark, robust, seamless, groundbreaking, leverage, synergy, transformative, paramount, multifaceted, myriad, cornerstone, reimagine, empower, catalyst, invaluable, bustling, nestled, realm, spearhead, harness, unleash, unlock, foster, underscore, pivotal, intricate, nuanced, landscape (as metaphor), journey (as metaphor), underpinned, underscored, testament, beacon, bedrock, linchpin, clarion call, akin to, in the annals of, etched in, poised to, grappling with, navigating the complexities, at the forefront, pave the way, game-changer, cutting-edge, revolutionize, unprecedented, unparalleled
- **TIER 2 — USE SPARINGLY (max 1 per 1000 words):** furthermore, moreover, paradigm, holistic, utilize, facilitate, illuminate, encompasses, catalyze, proactive, ubiquitous, quintessential, subsequently, accordingly, notably, significantly, consequently
- **TIER 3 — WATCH DENSITY (not inherently AI but suspicious in clusters):** ecosystem, framework, roadmap, touchpoint, pain point, streamline, optimize, scalable, innovative, intersection, dynamic, enhanced, elevated, aligned, actionable, iterative

**B) Overused AI Phrases (compile full list of 200+):**
- "In today's fast-paced world/landscape/environment..."
- "In a world where..."
- "As the [industry] continues to evolve..."
- "Now more than ever..."
- "It's not just X, it's Y"
- "X is more than just Y. It's Z."
- "Let's dive in / Let's delve into"
- "Let's break it down"
- "Here's the thing..."
- "Here's the uncomfortable truth:"
- "The goal?" / "The result?" / "The bottom line?"
- "Forward-thinking companies..."
- "Revolutionizing the way..."
- "That's where [product] comes in."
- "Unlock the power of..."
- "Supercharge your [X]"
- "Transforming X into Y"
- "Future-proof your..."
- "Stay ahead of the curve"
- "Let's face it..."
- "What does this mean for you?"
- "Not all X are created equal."
- "It's no secret that..."
- "Whether you're a [persona A] or [persona B]..."
- "Imagine a world where..."
- "At the end of the day..."
- "[Problem]? Meet [solution]."
- "It's time to..."
- "Why it matters..."
- "Here's what you need to know..."
- "Do X, so you can Y."
- "I hope this message finds you well"
- "Great question!"
- "That's a really interesting point"
- "Absolutely! Let me..."
- "It is important to note that..."
- "It is worth mentioning that..."
- "It is crucial to understand..."
- "Given the fact that..."
- "In light of the fact that..."
- "As a matter of fact..."
- "In order to..." (just say "to")
- "Due to the fact that..." (just say "because")
- "At this point in time..." (just say "now")
- "In the event that..." (just say "if")
- "Prior to..." (just say "before")
- "Despite the fact that..." (just say "although")
- "Thrilled to announce..."
- "Excited to share..."
- "marking a pivotal moment"
- "reflecting the continued relevance"
- "emphasizing the significance"
- "continues to thrive despite challenges"
- "The future looks bright"
- "only time will tell"

**C) AI Structural Patterns to Avoid:**
Research and document:
- **Em dash overuse** — AI uses em dashes (—) at 10x the rate of human writing. GPT-4o uses 10x more than GPT-3.5. Trained on 1800s/1900s books that used 30% more em dashes. NEVER use more than 1 em dash per 500 words.
- **Perfect punctuation** — Humans make punctuation mistakes. AI never does. Flawlessly textbook-correct punctuation is a tell.
- **Uniform sentence length** — AI writes metronomic sentences of similar length. Humans alternate between 3-word punches and 40-word run-ons. Measure: Coefficient of Variation of sentence length. Human: HIGH. AI: LOW.
- **Low burstiness** — Humans write in bursts (short then long then medium then very short). AI maintains even rhythm. Human burstiness: 0.5-1.0. AI burstiness: 0.1-0.3.
- **Low perplexity** — AI text is more predictable (lower perplexity). Humans use unexpected word choices. Human perplexity: higher and variable. AI: consistently low.
- **Rule of three** — AI loves grouping things in threes: "innovation, inspiration, and insights." Humans don't consistently do this.
- **Synonym cycling** — AI's repetition-penalty causes it to cycle through synonyms unnaturally. A person might say "building" 3 times. AI says "building, structure, edifice, construction."
- **Title Case Headings** — AI capitalizes Every Main Word In Headings. Humans often use sentence case.
- **Excessive bolding** — AI mechanically bolds key terms everywhere. Humans bold selectively or not at all.
- **Emoji in headings** — AI decorates section headings with emoji (🚀💡✅). Humans rarely do this in professional content.
- **Formulaic structure** — AI produces rigid: Intro → Point 1 → Point 2 → Point 3 → Conclusion. Humans meander, digress, circle back.
- **Hedging stacks** — "could potentially possibly" — AI stacks qualifiers. Humans pick one.
- **Significance inflation** — AI overstates importance of everything. "marking a pivotal moment in the history of..."
- **Copula avoidance** — AI says "serves as" and "boasts" instead of "is" and "has."
- **False ranges** — "From intimate gatherings to global movements" — sounds comprehensive but means nothing.
- **Negative parallelism** — "It's not just X, it's Y" pattern is AI's signature move.
- **Chatbot artifacts** — "Great question!", "I hope this helps!", "As an AI..."
- **Generic conclusions** — "The future looks bright for X" — vague optimism closing.
- **Passive voice overuse** — AI defaults to passive; humans use active.
- **Missing personal experience** — AI can't share genuine anecdotes, so it creates generic "imagine if" scenarios instead.
- **Curly/smart quotes** — AI tends to use typographic quotes ("") while casual human digital writing uses straight quotes ("").

**D) Statistical Signals of AI Text:**
Research the measurable differences:

| Signal | Human Range | AI Range |
|--------|------------|----------|
| Burstiness (sentence variation) | 0.5–1.0 | 0.1–0.3 |
| Type-token ratio (vocab diversity) | 0.5–0.7 | 0.3–0.5 |
| Sentence length CoV | High (variable) | Low (uniform) |
| Trigram repetition rate | <0.05 | >0.10 |
| Perplexity | Higher, variable | Low, consistent |
| Em dashes per 1000 words | 0–2 | 5–15 |
| Passive voice percentage | 5–15% | 20–40% |
| Contraction rate | 60–80% eligible | 10–30% eligible |

### 1.2 Research: Human Writing Patterns (What TO Do)

**A) Natural Human Writing Characteristics:**
- Contractions everywhere (don't, won't, it's, they're, couldn't)
- Sentence fragments. Used for emphasis. Like this.
- Run-on sentences that go on a bit because the writer is thinking out loud and connecting ideas as they come
- Starting sentences with "And," "But," "So," "Or"
- Parenthetical asides (honestly, this is how people think)
- Rhetorical questions — ever notice how humans ask questions they answer themselves?
- Self-corrections: "actually, no, what I meant was..."
- Colloquialisms and slang appropriate to context
- Opinions stated as opinions ("I think," "in my experience," "from what I've seen")
- Specific anecdotes instead of generic examples
- Incomplete thoughts that trail off...
- Casual transitions: "anyway," "so yeah," "moving on," "the thing is"
- Repetition for emphasis (humans DO repeat words, unlike AI synonym cycling)
- Varied paragraph lengths (1 sentence → 8 sentences)
- Asymmetric lists (not always 3 items — sometimes 2, sometimes 5, sometimes 7)

**B) Cultural/Regional Writing Patterns:**
Research how writing style varies by:
- **South Asian English** — sentence structure influenced by Bengali/Hindi grammar, certain word order preferences, specific idiom translations, mixing of formal English with casual phrases
- **Gen Z** — lowercase everything, no periods (periods feel aggressive), heavy use of "lol," "ngl," "lowkey," "highkey," "fr," "imo," reaction words like "bruh," "deadass," intentional misspellings
- **Tech/Developer culture** — direct, concise, heavy use of jargon when appropriate, self-deprecating humor, references to debugging/shipping, "LGTM," "TIL," "FWIW," "YMMV"
- **Crypto/Web3 culture** — "gm," "wagmi," "ngmi," "lfg," "degen," "ser," "anon," "wen," "probably nothing," "this is the way," "based," fire emojis, laser eyes era references
- **Startup/Founder culture** — "shipping," "building in public," "0 to 1," growth metrics language, fundraising terminology, "we're hiring" energy
- **Academic/Professional** — measured, hedged, citation-heavy, but still can be human with humor and opinion

**C) Personality Injection Techniques (from operator-humanizer skill research):**
1. **Parenthetical asides** — "(honestly, this part gets me every time)" — 1-3 per 500 words
2. **Strategic imperfections** — Not fake typos, but natural informality. Sentence fragments. One-word reactions. "Yeah."
3. **Tangents** — "Speaking of which..." "Wait, this connects to..." — 1-2 per long piece
4. **Genuine uncertainty** — "Honestly didn't think this would work but..." "I'm still figuring this out"
5. **Opinions and reactions** — "I love this approach" vs "This approach is beneficial"
6. **Specific numbers** — "I spent 3 hours on this" not "I spent significant time"
7. **Temporal markers** — "last Tuesday," "a few months ago," "back in 2023" (grounding in real time)

### 1.3 Research: Twitter/X Writing & Algorithm (2025-2026)

**A) Algorithm Mechanics (current as of 2026):**
Research and document:
- **Engagement weight formula:** Likes × 1 + Retweets × 20 + Replies × 13.5 + Profile Clicks × 12 + Link Clicks × 11 + Bookmarks × 10
- **Reply value:** Replies weighted at ~75x the value of likes
- **Time decay:** Half visibility every 6 hours. First 30 minutes are critical.
- **Tweepcred score:** Account credibility 0–100. Below 0.65 = only 3 tweets considered for distribution.
- **External links:** Severely penalized since March 2026. Non-Premium accounts with links get near-zero median engagement. Workaround: link in reply.
- **Video boost:** Native video gets strongest algorithmic push (~10x text-only engagement)
- **Premium advantage:** 4-8x organic reach boost for Premium subscribers
- **Grok-powered ranking:** January 2026 — replaced legacy recommendation with transformer model

**B) Viral Tweet Templates (21+ proven formats):**
1. **Contrarian Take:** "You don't need [popular thing]. You need [better alternative]"
2. **Bold Statement + Proof:** "[Bold claim]. Here's why: [list]"
3. **Resource List:** "[N] [type] for [audience]: [list]"
4. **Myth Buster:** "[Topic] is not about [common belief]. It's about [truth]"
5. **Hard Truth:** "Hard truth about [topic]: [uncomfortable reality]"
6. **Problem-Agitation-Solution:** "[Audience] struggle with [problem]. Smart [audience] [solution]"
7. **Interactive Challenge:** "In one word, describe [topic]"
8. **Unpopular Opinion:** "Unpopular opinion: [controversial but defensible take]"
9. **Drop Your Link:** "Drop your [thing]. I'll [valuable feedback]"
10. **Curiosity Question:** "[Intriguing question]? Answer isn't what you think"
11. **Before/After:** "I went from [start] to [result] in [timeframe]. Here's how:"
12. **Bookmarkable Tease:** "[N] [things] about [topic] I wish I knew [time] ago: thread"
13. **Two-Choice Poll:** "Which is better for [goal]: A) [Option 1] or B) [Option 2]?"
14. **Imagine Formula:** "Imagine if [desirable outcome]. That's [solution]. How to start:"
15. **Trending Topic Hijack:** "Everyone talks about [trend]. Here's [N] lessons for [niche]"
16. **Data-Driven Insight:** "I analyzed [large N] [things]. Found: [insight]"
17. **Stop/Start:** "Stop [bad]. Start [better]. You'll see [benefit]"
18. **Numbered Listicle:** "[N] [things] that [impressive result]"
19. **Vulnerable Share:** "[Time] ago I [struggle]. Today I [achievement]. Difference: [learning]"
20. **How-To with Visual:** "How to [result] in [timeframe]: [steps]"
21. **Specific Numbers:** "I spent [exact]. Made [result]. Breakdown: [details]"

**C) Thread Structure (optimal):**
- 5-10 tweets sweet spot, 7 is ideal
- Hook tweet is EVERYTHING — if it fails, thread dies
- Cliffhanger every 1-2 tweets
- Visual break every 3-4 tweets (+45% completion rate)
- End with engagement driver (question/CTA)

**D) Hook Formulas:**
- **Specificity:** "I [exact result with numbers] in [precise timeframe]"
- **Question:** "Why [surprising observation]? Answer isn't what you think"
- **Bold Claim:** "[Controversial statement]. Here's the proof:"
- **Curiosity Gap:** "Found [N] secrets that [result]. Most don't know #[N]"
- **Vulnerability:** "I was too embarrassed to admit this publicly"
- **Identity Target:** "If you have under [N] followers, read this"

**E) Reply Strategy:**
- 50 replies/day = magic number for growth
- Reply to viral tweets with VALUE (not "great point!")
- Reply-to-reply engagement = 75x algorithmic value vs likes
- Add your unique perspective, not agreement
- Quote tweets boost visibility by creating conversation around existing content

**F) Content by Sector:**
Research specific writing styles for:
- **Dev Twitter:** shipping updates, open source announcements, tech opinions, debugging stories, "TIL" posts, tool recommendations
- **Crypto Twitter (CT):** "gm" culture, alpha calls, project announcements, thread explaining protocols, meme engagement, "degen" energy, commentary on market moves
- **Startup Twitter:** building in public, milestone celebrations, hiring posts, fundraising announcements, founder lessons, failure stories
- **AI/ML Twitter:** paper summaries, demo videos, benchmark comparisons, hot takes on models, "just dropped" energy
- **Design Twitter:** before/after showcases, process breakdowns, critique threads, tool comparisons

**G) Tweet Length Best Practices:**
- **Short (1-60 chars):** Hot takes, one-liners, reactions — highest like ratio
- **Medium (60-180 chars):** Insights, opinions, value bombs — balanced engagement
- **Long (180-280 chars):** Detailed thoughts, stories, context — highest bookmark ratio
- **Thread hook:** Should be self-contained and compelling even without the thread

**H) What KILLS Engagement:**
- Generic advice everyone knows
- Pure self-promotion without value
- Vague/abstract content
- Obvious engagement bait ("RT if you agree")
- External links in main tweet (put in reply)
- Too many hashtags (0-1 max, or none)
- Tagging people in initial tweet

### 1.4 Research: README & Bio Writing

**A) GitHub Project README Structure:**
Research the optimal structure:
1. **Project name + one-line description** — what it does in plain language
2. **Badges** — build status, version, license, coverage (shields.io)
3. **Hero section** — screenshot, demo GIF, or architecture diagram
4. **Highlights / Key Features** — 3-5 bullet points, biggest selling points first
5. **Quick Start** — get running in <60 seconds (copy-paste commands)
6. **Installation** — detailed setup instructions
7. **Usage** — code examples showing common use cases
8. **API Reference** — if applicable
9. **Configuration** — environment variables, options
10. **Contributing** — how to contribute
11. **License** — one line with link
12. **Acknowledgments** — credits, inspiration

**B) GitHub Profile README:**
- Bio: who you are, what you're building
- Skills badges (shields.io) for languages/tools
- GitHub stats cards (github-readme-stats)
- Pinned projects or current work
- Social links (Twitter, LinkedIn, personal site)
- "Currently learning" / "Currently building" section
- Creative touches: ASCII art, custom banners, dynamic elements
- Format bio as code block (yaml/json style) for developer personality

**C) Social Media Bio Formulas (160 char max for Twitter):**
- **Formula 1:** [Role] @ [Company/Project]. Building [what]. [Passion/Interest]. [Location/CTA]
- **Formula 2:** [Achievement]. [What you do]. [What you care about]. [Link]
- **Formula 3:** [Identity] | [Skill 1] + [Skill 2] | Building [project] | [Personal touch]
- **Formula 4:** [Emoji] [Role]. [One unique thing about you]. [What you share here]. [CTA]
- Emojis count as 2 characters each
- Include at most 1 link
- Show personality, not just credentials

### 1.5 Research: Claude Code Skills Architecture

**A) SKILL.md File Structure:**
```yaml
---
name: skill-name          # lowercase, hyphens, max 64 chars
description: |            # What it does + when to trigger (max 200 chars, be "pushy")
  Description here. Use when [trigger contexts].
argument-hint: "[args]"   # shown during autocomplete
disable-model-invocation: false  # true = manual /name only
user-invocable: true      # false = background knowledge only
allowed-tools: Read, Grep, WebSearch, WebFetch  # tools allowed without permission
model: sonnet             # optional model override
context: fork             # optional: run in subagent
agent: general-purpose    # subagent type if context: fork
---

# Skill Instructions (Markdown)

Your detailed instructions here...
```

**B) Skill Directory Structure:**
```
skill-name/
├── SKILL.md              # Required — main instructions
├── references/           # Optional — detailed docs loaded on demand
│   ├── ai-patterns.md    # Reference file for AI patterns database
│   └── templates.md      # Reference file for tweet templates
├── examples/             # Optional — example outputs
│   └── sample-output.md
├── scripts/              # Optional — executable scripts
│   └── helper.py
└── assets/               # Optional — templates, icons, data
    └── word-list.json    # Data file for banned words
```

**C) Best Practices for Skills:**
- Keep SKILL.md under 500 lines
- Move detailed reference material to separate files in references/
- Use `$ARGUMENTS` for user input, `$0`, `$1` for positional args
- Make descriptions "pushy" — Claude undertriggers skills, so be explicit about when to use
- Include realistic examples with Input/Output
- Explain the "why" behind instructions (don't just say NEVER, explain reasoning)
- Use imperative form in instructions
- Test incrementally after each change
- For reference files >300 lines, include table of contents

**D) Invocation Control:**
| Setting | User invokes | Claude invokes | When in context |
|---------|-------------|---------------|-----------------|
| (default) | Yes | Yes | Description always, full on invoke |
| disable-model-invocation: true | Yes | No | Not in context |
| user-invocable: false | No | Yes | Description always |

**E) Dynamic Context:**
- `!`command`` — runs shell commands before skill content is sent, output replaces placeholder
- `$ARGUMENTS` — all arguments passed when invoking
- `$ARGUMENTS[N]` or `$N` — specific positional arguments
- `${CLAUDE_SESSION_ID}` — current session ID

**F) Skills Publishing:**
- **Project skills:** Commit `.claude/skills/` to version control
- **Personal skills:** Store in `~/.claude/skills/`
- **npx skills:** Use `npx skills init [name]` to create, `npx skills add` to install
- **skills.sh:** Central registry/leaderboard for skill discovery
- **npm publishing:** Skills can be published as npm packages

---

## PHASE 2: CREATE THE 3 SKILLS

After completing ALL research above, create these 3 interconnected skills. Each must be production-quality, comprehensive, and based on the research findings.

### SKILL 1: `write-like-human` (Foundation Skill)

**Purpose:** Transform any AI-generated text into authentic human writing, or write new content that is 99.9% indistinguishable from human writing. This is the FOUNDATION skill used by all other skills.

**This skill MUST:**

1. **Gather Context First (ALWAYS):**
   Before writing ANYTHING, the skill must ask the user:
   - Who is the target audience? (developers, crypto community, general public, investors, academics, etc.)
   - What cultural/regional context? (South Asian, Gen Z, professional Western, etc.)
   - What's the writer's persona? (founder, developer, student, thought leader, etc.)
   - What tone? (casual, professional, witty, serious, vulnerable, authoritative)
   - What platform? (Twitter, GitHub, LinkedIn, blog, email, documentation)
   - Any reference writing samples? (links or text showing the desired style)
   - What's the emotional intent? (inform, persuade, entertain, provoke thought, celebrate)

   If the user provides a reference text or existing content, analyze it FIRST to extract:
   - Sentence length patterns
   - Vocabulary level
   - Tone markers
   - Structural preferences
   - Unique phrases/patterns

2. **Apply the 24-Point AI Pattern Detection:**
   Run EVERY piece of output through the full detection checklist:
   1. Significance inflation check
   2. Notability name-dropping check
   3. Superficial -ing analyses check
   4. Promotional language check
   5. Vague attributions check
   6. Formulaic challenges check
   7. Tier 1 vocabulary check (absolute ban list)
   8. Tier 2 vocabulary density check
   9. Tier 3 vocabulary cluster check
   10. Copula avoidance check ("serves as" → "is")
   11. Negative parallelism check ("not just X, it's Y")
   12. Rule of three check
   13. Synonym cycling check
   14. False ranges check
   15. Em dash density check (max 1 per 500 words)
   16. Bold overuse check
   17. Title Case heading check → use sentence case
   18. Emoji in headings check
   19. Curly quotes check
   20. Chatbot artifacts check
   21. Filler phrases check (remove all)
   22. Hedging stack check
   23. Passive voice percentage check (keep under 15%)
   24. Generic conclusion check

3. **Apply Human Writing Patterns:**
   - Vary sentence length dramatically (3 words to 40+ words)
   - Use contractions naturally (60-80% of eligible spots)
   - Include sentence fragments for emphasis
   - Start sentences with And, But, So, Or
   - Add parenthetical asides (1-3 per 500 words)
   - Use specific numbers and anecdotes instead of vague claims
   - Allow natural repetition of key words (don't synonym-cycle)
   - Include rhetorical questions
   - Vary paragraph length (1 sentence to 8 sentences)
   - Use asymmetric lists (not always 3 items)
   - Prefer active voice (85%+)
   - Include temporal markers when relevant ("last week," "in 2024")
   - End with specifics, not vague optimism

4. **Cultural/Sector Adaptation:**
   Based on gathered context, adapt:
   - **Tech/Dev:** Direct, jargon-appropriate, self-deprecating humor, debugging analogies
   - **Crypto/Web3:** CT slang ("gm," "wagmi," "ser"), informal, meme-aware, alpha-sharing energy
   - **Startup:** Building-in-public voice, metrics-aware, optimistic but grounded, founder energy
   - **Gen Z:** Lowercase, no periods, abbreviations, reaction words, ironic tone
   - **South Asian English:** Natural code-switching patterns, certain grammatical influences, warmth
   - **Professional:** Measured but not sterile, hedged appropriately, still has personality
   - **Academic:** Precise, citation-ready, but can still be engaging and opinionated

5. **Quality Verification (Self-Check):**
   After writing, verify:
   - [ ] Em dash count ≤ 1 per 500 words
   - [ ] No Tier 1 banned words
   - [ ] Sentence length CoV is HIGH (varied)
   - [ ] Contraction rate 60-80%
   - [ ] Passive voice < 15%
   - [ ] No formulaic intro/conclusion patterns
   - [ ] No "rule of three" unless natural
   - [ ] Specific examples used (not generic)
   - [ ] Would pass GPTZero/Originality.ai with >85% human score
   - [ ] Reads naturally when read aloud
   - [ ] Has personality and opinion (not neutral/safe)

6. **Filler Phrases Auto-Replace:**
   Always apply:
   - "In order to" → "to"
   - "Due to the fact that" → "because"
   - "At this point in time" → "now"
   - "It is important to note that" → (delete or rephrase)
   - "In the event that" → "if"
   - "Prior to" → "before"
   - "Despite the fact that" → "although"
   - "In terms of" → (rephrase or delete)
   - "It is worth mentioning" → (just mention it)
   - "It goes without saying" → (then don't say it)

### SKILL 2: `research-content` (Research Skill)

**Purpose:** Deep research for development projects, Twitter content, social media strategy. Gathers context, finds relevant information, analyzes trends, and prepares comprehensive briefs for content creation.

**This skill MUST:**

1. **Gather Research Context:**
   Ask the user:
   - What's the research topic/project?
   - What platform is this research for? (Twitter, GitHub, blog, etc.)
   - What's the goal? (announce project, share insight, grow audience, educate, etc.)
   - Who's the target audience?
   - Any existing content or references to build on?
   - What sector? (tech, crypto, AI, startup, open source, etc.)
   - Competitive research needed? (similar projects, similar creators)

2. **Research Capabilities:**
   - **Project Research:** Analyze GitHub repos, documentation, README files, changelogs
   - **Trend Research:** Find current trending topics in the relevant sector
   - **Audience Research:** Analyze what performs well in the target community
   - **Competitor Research:** How similar projects/people communicate
   - **Content Gap Analysis:** What's NOT being said that should be
   - **Hashtag/Keyword Research:** Relevant discovery terms for the platform
   - **Timing Research:** Optimal posting times for the target audience

3. **Output Format:**
   Produce a structured research brief:
   - **Key Findings** — 5-10 bullet points of actionable insights
   - **Content Angles** — 3-5 different angles to approach the topic
   - **Audience Insights** — who cares and why
   - **Competitive Landscape** — what others are saying
   - **Recommended Format** — best content format for this topic + platform
   - **Key Terms/Phrases** — vocabulary the target audience uses
   - **Risks/Avoids** — what NOT to say or do
   - **Sources** — all URLs and references used

4. **Platform-Specific Research:**
   **For Twitter:**
   - Current trending topics in the niche
   - High-performing tweet formats for this sector
   - Key accounts to engage with
   - Optimal thread length and timing
   - Algorithm-friendly content patterns (replies > likes weighting)
   - External link workarounds (link in reply strategy)

   **For GitHub:**
   - Similar projects and their README approaches
   - What makes top repos in this space successful
   - Badge/shield recommendations
   - Documentation patterns that work
   - Community engagement strategies

   **For Other Platforms:**
   - Platform-specific best practices
   - Content format optimization
   - Community norms and culture

### SKILL 3: `write-content` (Content Creation Skill)

**Purpose:** Write Twitter posts (single tweets, threads, replies, quote tweets), GitHub READMEs (project + profile), social media bios, and other content. ALWAYS uses the `write-like-human` skill as its foundation.

**This skill MUST:**

1. **Gather Full Context (CRITICAL — do this FIRST, every time):**

   **Always ask:**
   - What type of content? (tweet, thread, reply, quote tweet, README, bio, etc.)
   - What's the topic/subject?
   - Who is the user? (background, role, expertise — if not already known)
   - What's the goal? (engagement, announcement, education, growth, etc.)

   **For Twitter content, also ask:**
   - Short, medium, or long? (or let skill decide based on content)
   - What section of Twitter? (main feed, reply to specific tweet, quote tweet)
   - User's Twitter persona/voice (or reference to existing tweets)
   - Sector focus? (dev, crypto, startup, AI, general tech, etc.)
   - Any specific angle or hot take?
   - Include media? (screenshot, code snippet, video suggestion)
   - Thread or single tweet?

   **For README content, also ask:**
   - Project or profile README?
   - What does the project do? (in plain language)
   - Tech stack used?
   - What makes it unique?
   - Installation complexity? (one-liner or multi-step)
   - Target audience for the README? (developers, end users, both)
   - What impression do you want to make?

   **For Bio content, also ask:**
   - Which platform? (Twitter, GitHub, LinkedIn, etc.)
   - Character limit awareness (Twitter = 160 chars, emojis = 2 chars each)
   - Professional or personality-forward?
   - Key things to communicate (role, project, passion, location, CTA)
   - Reference bios they admire?

   **If context is missing, ASK. Don't assume.**

2. **Twitter Content Creation:**

   **Single Tweets:**
   Apply the appropriate template from the 21+ viral formats researched above.
   Generate 3-5 variations in different tones/angles.
   For each variation, specify: estimated engagement type (likes, replies, bookmarks, RTs).

   **Short tweets (1-60 chars):**
   - Hot takes, one-liners, reactions
   - No fluff, pure signal
   - Example: "the best code is the code you don't write"

   **Medium tweets (60-180 chars):**
   - Insights with context
   - Opinion + reasoning
   - Example: "Stop optimizing for followers. Start optimizing for replies. The algorithm rewards conversation, not vanity metrics."

   **Long tweets (180-280 chars):**
   - Detailed thoughts with nuance
   - Stories with punchlines
   - Context + insight + CTA

   **Threads:**
   - Hook tweet (self-contained, curiosity gap)
   - 5-7 body tweets (one insight per tweet, numbered)
   - Visual break suggestions every 3-4 tweets
   - Cliffhangers between tweets
   - Engagement driver ending (question)
   - CTA finale (follow/newsletter)

   **Replies:**
   - Add genuine value (not "great point!")
   - Build on the original tweet with new perspective
   - Keep concise but substantive
   - Include your unique expertise/angle
   - Ask a follow-up question to create conversation thread

   **Quote Tweets:**
   - Add unique take, not just agreement
   - "This + [your insight]" format
   - Expand on the original with your experience
   - Respectful disagreement with reasoning

   **Sector-Specific Styles:**

   *Dev Twitter:*
   - Ship updates: "just shipped [feature]. here's what I learned building it:"
   - TIL posts: "TIL [surprising thing]. here's why it matters:"
   - Tool recs: "if you're not using [tool] for [task], you're spending 3x the time"
   - Open source: "just open-sourced [project]. it does [thing] in [impressive metric]"

   *Crypto Twitter:*
   - gm energy: "gm. shipped a new feature overnight. wagmi."
   - Alpha threads: "been researching [protocol] for 2 weeks. here's what most people are missing:"
   - Market commentary: directional, opinionated, not financial advice disclaimer
   - Community engagement: meme awareness, inside jokes, CT culture fluency

   *Startup Twitter:*
   - Building in public: "Month 3 update: [metrics]. Here's what went wrong:"
   - Hiring: "[Role] at [Company]. We're doing [exciting thing]. DM me."
   - Milestone: "From $0 to $[X]k MRR in [time]. No paid ads. Here's the playbook:"
   - Failure stories: "We almost died in Month 2. Here's why, and how we survived:"

3. **README Content Creation:**

   **Project README:**
   Use the researched optimal structure:
   - Clear project name + one-line value proposition
   - Badges (CI, version, license, npm/crate downloads)
   - Hero visual (suggest screenshot, GIF, or ASCII diagram)
   - "Why [Project]?" section — the problem it solves
   - Quick Start (under 60 seconds, copy-paste)
   - Key Features (bullet points, specific, not buzzwordy)
   - Usage examples (real code, not pseudo-code)
   - Installation (step-by-step)
   - Configuration (if applicable)
   - Contributing (welcoming tone)
   - License (one line)

   Write in a human voice — not corporate, not sterile. The README should have personality while being informative.

   **Profile README:**
   - Opening: who you are, what you care about
   - Current focus: "building [X]" or "exploring [Y]"
   - Tech stack badges (shields.io)
   - GitHub stats (optional — only if impressive)
   - Social links
   - Creative element: ASCII art, code-formatted bio, custom banner
   - Keep it authentic — not a resume, a personality

4. **Bio Content Creation:**

   Apply the researched bio formulas:
   - Generate 3-5 variations
   - Count characters precisely (especially for Twitter's 160 limit)
   - Include emoji suggestions (remember: 2 chars each)
   - Match platform culture (Twitter = personality, LinkedIn = professional, GitHub = developer)

5. **ALWAYS Apply `write-like-human` Rules:**
   Every piece of content MUST pass through the complete humanization checklist from Skill 1. No exceptions. Run the 24-point AI pattern detection. Apply human writing patterns. Adapt to cultural context.

6. **Output Format:**
   For every content request, provide:
   - **Option A** (recommended) — your best version
   - **Option B** (alternative angle) — different approach
   - **Option C** (bold/risky) — more provocative take
   - **Analysis** — why you chose the format, expected engagement type
   - **Improvement suggestions** — how the user could customize further
   - **Post-publish strategy** — what to do after posting (for Twitter: reply strategy, engagement window)

---

## PHASE 3: SET UP THE SKILLS PROJECT

After creating all 3 skills, set up the project and guide the user through publishing.

### 3.1 Project Structure

Create this directory structure:

```
human-writing-skills/
├── README.md                           # Project README (written using the skills!)
├── skills/
│   ├── write-like-human/
│   │   ├── SKILL.md                    # Main skill file (<500 lines)
│   │   ├── references/
│   │   │   ├── ai-patterns-database.md # Complete AI patterns to avoid
│   │   │   ├── human-patterns.md       # Human writing characteristics
│   │   │   ├── cultural-styles.md      # Regional/sector writing styles
│   │   │   └── word-tiers.md           # Complete banned/watch word lists
│   │   └── assets/
│   │       └── quality-checklist.md    # Self-check template
│   │
│   ├── research-content/
│   │   ├── SKILL.md                    # Main skill file
│   │   └── references/
│   │       ├── twitter-algorithm.md    # Current algorithm mechanics
│   │       ├── platform-guides.md      # Platform-specific research guides
│   │       └── sector-profiles.md      # Sector-specific audience profiles
│   │
│   └── write-content/
│       ├── SKILL.md                    # Main skill file
│       ├── references/
│       │   ├── tweet-templates.md      # 21+ viral tweet formats
│       │   ├── thread-structures.md    # Thread writing frameworks
│       │   ├── readme-templates.md     # README structure guides
│       │   ├── bio-formulas.md         # Bio writing formulas
│       │   └── hook-formulas.md        # Opening hook patterns
│       └── examples/
│           ├── tweet-examples.md       # Example tweets by sector
│           ├── readme-examples.md      # Example READMEs
│           └── bio-examples.md         # Example bios by platform
```

### 3.2 Installation Methods

Provide instructions for:

**Method 1: Local Installation (Personal)**
```bash
# Clone the skills
git clone [repo-url] /tmp/human-writing-skills

# Copy to personal skills directory
cp -r /tmp/human-writing-skills/skills/write-like-human ~/.claude/skills/
cp -r /tmp/human-writing-skills/skills/research-content ~/.claude/skills/
cp -r /tmp/human-writing-skills/skills/write-content ~/.claude/skills/
```

**Method 2: Project Installation**
```bash
# Copy to project skills directory
cp -r /tmp/human-writing-skills/skills/* .claude/skills/
```

**Method 3: npx skills (Registry)**
```bash
# Initialize as a skills package
cd human-writing-skills
npx skills init

# Install from registry (after publishing)
npx skills add [username]/human-writing-skills
```

### 3.3 Publishing to skills.sh

Guide through:
1. Create GitHub repository for the skills
2. Ensure proper SKILL.md format with frontmatter
3. `npx skills init` in the repo root
4. Push to GitHub
5. Register on skills.sh
6. Add README with installation instructions

### 3.4 Testing

For each skill, verify:
- `/write-like-human` invokes correctly
- `/research-content` invokes correctly
- `/write-content` invokes correctly
- Context gathering questions appear
- Output passes AI detection tools (test with GPTZero, Originality.ai)
- Cultural adaptation works across sectors
- Tweet character counts are accurate
- README structure is complete and professional
- Bio character limits are respected

---

## PHASE 4: QUALITY ASSURANCE

Run these test scenarios:

1. **Test: Dev Twitter Announcement**
   `/write-content` → tweet → announcing open source project → developer audience → medium length
   Verify: No AI patterns, technical accuracy, engaging hook, human voice

2. **Test: Crypto Twitter Thread**
   `/write-content` → thread → explaining a DeFi protocol → CT audience → 7 tweets
   Verify: CT culture fluency, no corporate speak, alpha-sharing energy, proper slang

3. **Test: GitHub Project README**
   `/write-content` → readme → Rust CLI tool → developers → professional but human
   Verify: Complete structure, copy-paste quick start, badges, no buzzwords

4. **Test: Twitter Bio**
   `/write-content` → bio → founder building AI startup → Twitter → personality-forward
   Verify: Under 160 chars, includes personality, not just credentials

5. **Test: Humanize Existing Text**
   Give `/write-like-human` an obviously AI-written paragraph
   Verify: All 24 patterns detected and fixed, output reads naturally

6. **Test: Research Brief**
   `/research-content` → Twitter strategy for developer launching open source project
   Verify: Actionable insights, platform-specific recommendations, competitive analysis

---

## IMPORTANT EXECUTION NOTES

1. **Do NOT start writing skills until ALL Phase 1 research is complete.** The research IS the skill quality.

2. **Every skill must ask for context FIRST.** Never assume the user's background, audience, sector, or tone. The skill's quality depends entirely on understanding the user's specific needs.

3. **The `write-like-human` skill is the foundation.** The `write-content` skill MUST invoke/reference it. Never write content without humanization.

4. **Test with real AI detection tools.** The output must actually pass detection, not just "feel" human.

5. **Be opinionated in the skills.** Good skills have strong opinions about what works. Don't be wishy-washy. State best practices as best practices.

6. **Update the research.** AI detection evolves. The skills should note that word lists and patterns need periodic updates.

7. **Make skills universal.** They must work for any sector, any culture, any platform — by ASKING the right context questions and ADAPTING accordingly.

8. **Quality over everything.** These are not low-effort prompt templates. They are comprehensive, research-backed, production-quality skills that produce genuinely human-like output.

---

## RESEARCH SOURCES TO CONSULT

Use WebSearch and WebFetch on ALL of these:

### AI Writing Detection
- https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing
- https://www.blakestockton.com/red-flag-words/
- https://www.blakestockton.com/red-flag-phrases/
- https://fomo.ai/ai-resources/the-ultimate-copy-paste-prompt-add-on-to-avoid-overused-words-and-phrases-in-ai-generated-content/
- https://gptzero.me/ai-vocabulary
- https://originality.ai/blog/perplexity-and-burstiness-in-writing
- https://playbooks.com/skills/openclaw/skills/operator-humanizer
- Search: "Wikipedia signs of AI writing complete list"
- Search: "AI writing em dash overuse statistics"
- Search: "burstiness perplexity human vs AI writing"
- Search: "ChatGPT Claude overused words 2026 complete list"

### Twitter/X Strategy
- https://www.tweetarchivist.com/viral-tweet-templates-guide
- https://www.tweetarchivist.com/how-to-go-viral-on-twitter-2025
- https://www.tweetarchivist.com/twitter-algorithm-explained-2025
- https://sproutsocial.com/insights/twitter-algorithm/
- Search: "Twitter X algorithm 2026 ranking factors"
- Search: "viral tweet templates formulas"
- Search: "dev twitter writing style"
- Search: "crypto twitter CT culture writing"

### README & Bio
- https://github.com/matiassingers/awesome-readme
- https://github.com/othneildrew/Best-README-Template
- https://www.makeareadme.com/
- https://github.com/abhisheknaiidu/awesome-github-profile-readme
- Search: "GitHub README best practices 2025"
- Search: "Twitter bio formula developer founder"

### Skills Architecture
- https://code.claude.com/docs/en/skills
- https://github.com/anthropics/skills
- https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md
- https://github.com/vercel-labs/skills
- https://mikhail.io/2025/10/claude-code-skills/
- Search: "Claude Code skills best practices SKILL.md"
- Search: "npx skills publish registry"

---

*This prompt was synthesized from research across 50+ sources covering AI detection science, Twitter algorithm mechanics, content creation best practices, and Claude Code skills architecture. March 2026.*
