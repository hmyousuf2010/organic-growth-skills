---
name: write-content
description: Write tweets, threads, replies, quote tweets, GitHub READMEs (project and profile), social media bios, and other content that sounds genuinely human. Use this skill whenever the user wants to create any social media content, write a tweet, draft a thread, create a README, write a bio, craft a reply, or produce any written content for public platforms. Also triggers for content drafting, copywriting, social posts, and announcement writing.
allowed-tools: Read Grep Glob WebSearch WebFetch
---

# Write Content

Create platform-optimized content that sounds genuinely human. This skill applies all write-like-human rules automatically - every output passes through the full AI pattern detection and human writing checklist.

Before writing, always read the write-like-human skill's [ai-patterns-database.md](../write-like-human/references/ai-patterns-database.md) and [word-tiers.md](../write-like-human/references/word-tiers.md) to refresh the avoidance rules.

## Step 1: Gather context

### Always ask:
1. **Content type** - tweet, thread, reply, quote tweet, README, bio, blog post, email?
2. **Topic** - what's the subject?
3. **Who are you?** - background, role, expertise (if not already known)
4. **Goal** - engagement, announcement, education, growth, hiring, selling?

### For Twitter content, also ask:
- Short, medium, or long tweet?
- Reply to a specific tweet? (get the tweet text)
- Your Twitter persona/voice (or link to existing tweets to match)
- Sector? (dev, crypto, startup, AI, general tech, design)
- Any specific angle or hot take to push?
- Thread or single tweet?
- Include media? (screenshot, code snippet, video)

### For README content, also ask:
- Project or profile README?
- What does the project do? (in plain language)
- Tech stack?
- What makes it unique?
- Installation complexity? (one-liner or multi-step)
- Target audience? (devs, end users, both)

### For bio content, also ask:
- Which platform? (character limits vary - see [bio-formulas.md](references/bio-formulas.md))
- Professional or personality-forward?
- Key things to communicate (role, project, passion, CTA)
- Reference bios you like?

If context is missing, ask. Don't assume.

## Step 2: Write the content

### Twitter content

Read [tweet-templates.md](references/tweet-templates.md) for the 25 proven viral formats and [hook-formulas.md](references/hook-formulas.md) for opening patterns.

**Single tweets:**

Pick the template that fits the content type. Generate 3 variations:
- **Option A** (recommended) - your best shot
- **Option B** (alternative angle) - different approach
- **Option C** (bold/risky) - more provocative take

For each, note the expected engagement type: likes, replies, bookmarks, or retweets.

Length guidance:
- 71-100 chars: highest engagement rate. Hot takes, one-liners, reactions.
- 70-110 chars: best for retweets. Shareable, quotable.
- 240-259 chars: most total likes. Complete thoughts, mini-stories.
- Full 280: no penalty. Use when the content needs it.

Count characters precisely. Emojis = 2 chars. Links = 23 chars always.

**Threads:**

Read [thread-structures.md](references/thread-structures.md) for architecture.

Structure:
1. Hook tweet - self-contained, creates curiosity gap. Must work even if nobody reads the thread.
2. Context/stakes - why should anyone care?
3-8. Body - one insight per tweet. End each with an open loop.
4. Key takeaway - punchy lesson.
5. Soft CTA - question to drive replies.
6. Hard CTA - follow, RT first tweet, or link (in reply).

Sweet spot is 5-10 tweets (7 is ideal). Under 5, make it a single tweet. Over 15, expect significant drop-off.

Cliffhanger every 1-2 tweets: "But that's not all..." / "Here's where it gets interesting:" / "And then everything changed."

Suggest visual breaks every 3-4 tweets (+45% completion rate).

**Replies:**

Not "great point!" - add genuine value:
- Share your experience with the topic
- Add data or a specific example
- Ask a sharp follow-up question
- Respectfully disagree with reasoning
- 3+ sentences, unique perspective
- Keep niche-relevant

**Quote tweets:**

- Add a unique take, not just agreement
- "This + [your insight]" format
- Expand with your experience
- Or respectful disagreement with reasoning

### Sector-specific tweet styles

See [tweet-examples.md](examples/tweet-examples.md) for examples by sector.

**Dev Twitter:**
- Ship updates: "just shipped [feature]. here's what I learned building it:"
- TIL posts: "TIL [surprising thing]. here's why it matters:"
- Tool recs: "if you're not using [tool] for [task], you're spending 3x the time"
- Open source: "just open-sourced [project]. it does [thing] in [impressive metric]"

**Crypto/CT:**
- "gm. shipped a new feature overnight. wagmi."
- Alpha threads: "been researching [protocol] for 2 weeks. here's what most people are missing:"
- Market takes: directional, opinionated, NFA disclaimer
- Community fluency: know the memes, use the slang naturally

**Startup:**
- Build-in-public: "Month 3 update: [metrics]. Here's what went wrong:"
- Hiring: "[Role] at [Company]. We're doing [exciting thing]. DM me."
- Milestones: "From $0 to $[X]k MRR in [time]. No paid ads. Here's the playbook:"
- Failures: "We almost died in Month 2. Here's why, and how we survived:"

### README content

Read [readme-templates.md](references/readme-templates.md) for structure guides.

**Project README structure:**
1. Project name + one-line value proposition (not buzzwords - plain language)
2. Badges - CI, version, license, downloads (4-6 max, one row)
3. Hero visual - screenshot, GIF, or architecture diagram
4. "Why [Project]?" - the problem it solves (not "revolutionizing" anything)
5. Quick Start - under 60 seconds, copy-paste commands
6. Key Features - bullet points, specific, measurable where possible
7. Usage examples - real code, not pseudo-code
8. Installation - step-by-step
9. Configuration - if applicable
10. Contributing - welcoming tone
11. License - one line

Write in a human voice. The README should have personality while being informative. No corporate speak.

**Profile README structure:**
- Opening: who you are, what you care about
- Current focus: "building [X]" or "exploring [Y]"
- Tech stack badges (shields.io)
- GitHub stats (optional - only if impressive)
- Social links
- Creative element: ASCII art, code-formatted bio, custom banner

See [readme-templates.md](references/readme-templates.md) for badge syntax and widget markdown.

### Bio content

Read [bio-formulas.md](references/bio-formulas.md) for the 8 formulas and character limits.

Generate 3-5 variations. Count characters precisely.

Character limits:
- Twitter/X: 160 chars
- GitHub: 160 chars
- LinkedIn headline: 220 chars
- Instagram: 150 chars
- TikTok: 80 chars
- Discord: 190 chars
- Bluesky: 256 chars

Emojis = 2 chars each. Show personality, not just credentials.

## Step 3: Apply write-like-human rules

Every piece of output must pass through these checks before delivery. This is non-negotiable.

1. Zero Tier 1 banned words
2. Zero banned phrases
3. Em dashes: max 1 per 500 words
4. Sentence length varies dramatically
5. Contractions at 60-80% of eligible spots
6. Passive voice under 15%
7. No formulaic intro/conclusion patterns
8. Specific examples, not generic claims
9. Has personality and opinion
10. Reads naturally when read aloud
11. Adapted to the cultural context specified
12. No synonym cycling

If any check fails, rewrite before delivering.

## Step 4: Deliver with analysis

For every content request, provide:

1. **The content** - 3 variations (recommended, alternative, bold)
2. **Analysis** - why you chose the format, expected engagement type
3. **Post-publish strategy** - what to do after posting

For Twitter specifically:
- Best time to post (based on audience timezone)
- Reply strategy for the first 30 minutes
- Whether to put links in a reply
- Suggested follow-up content to build momentum
