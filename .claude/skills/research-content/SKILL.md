---
name: research-content
description: Deep research for content creation across Twitter/X, GitHub, social media, and blogs. Use this skill whenever the user wants to research a topic before writing, needs content strategy, wants audience analysis, competitive research, trend analysis, hashtag/keyword research, or platform-specific strategy. Also use when the user mentions content planning, audience research, or wants to understand what performs well in a niche.
allowed-tools: Read Grep Glob WebSearch WebFetch
---

# Research Content

Conduct deep research to inform content creation. This skill gathers context, finds relevant information, analyzes trends, and produces structured briefs that feed directly into content writing.

## Step 1: Understand the research request

Ask the user:

1. **Topic** — what are we researching?
2. **Platform** — Twitter, GitHub, blog, LinkedIn, other?
3. **Goal** — announce a project, share insight, grow audience, educate, sell?
4. **Audience** — developers, crypto community, founders, general tech, investors?
5. **Sector** — dev, crypto, AI/ML, startup, open source, design?
6. **Existing content** — any references, repos, or content to build on?
7. **Competition** — want to see what similar projects/people are doing?

Skip questions you can confidently infer. If someone says "research my new Rust CLI tool for dev Twitter," you already know the platform, sector, and audience.

## Step 2: Conduct the research

### Project research
If there's a specific project, repo, or product:
- Analyze the repo (README, code structure, tech stack, stars, activity)
- Read documentation and changelogs
- Identify the unique value prop — what makes this different?
- Find the "aha moment" that would hook the target audience
- Note installation complexity (one-liner? multi-step?)

### Audience research
- What content performs well in this community?
- What vocabulary does the audience use? (see [sector-profiles.md](references/sector-profiles.md))
- What are they frustrated about? Excited about?
- Who are the key voices? What do they post about?
- What content gaps exist — what's NOT being said that should be?

### Competitive research
- How do similar projects/products communicate?
- What README formats are competitors using?
- What tweet styles perform best for similar announcements?
- What can we do differently to stand out?

### Trend research
Use WebSearch to find:
- Current trending topics in the relevant sector
- Recent news or developments the content could hook into
- Upcoming events, launches, or milestones to time against
- Hashtags and keywords with momentum

### Platform-specific research

**For Twitter/X:**
Read [twitter-algorithm.md](references/twitter-algorithm.md) for the current algorithm mechanics. Key points:
- Replies are weighted 27x a like, reply-to-reply 150x
- Bookmarks and dwell time are 20x a like
- External links get 30-50% reach reduction — use link-in-reply strategy
- First 30-60 minutes are the critical engagement window
- 2-5 quality tweets/day, spaced 30-60 min apart
- Premium subscribers get roughly 10x more reach per post

Research for the specific content:
- High-performing tweet formats for this sector
- Key accounts to engage with (for reply strategy)
- Optimal thread length for this topic
- Whether to use Premium long-form vs thread vs single tweet

**For GitHub:**
- Similar projects and their README approaches
- What makes top repos in this space successful (stars, forks, contributor count)
- Badge and shield recommendations for credibility
- Documentation patterns that work in this niche
- Community engagement strategies (discussions, issues, contributing guides)

**For LinkedIn:**
- Professional framing of the same content
- Post length sweet spots (1300 chars for feed posts)
- Hook patterns that work on LinkedIn (first 2 lines visible)
- Carousel/document post potential

**For Blog/Newsletter:**
- SEO keyword research
- Content format (tutorial, opinion, case study, comparison)
- Linking strategy
- Distribution plan

## Step 3: Produce the research brief

Output a structured brief the user can act on immediately:

### Key findings
5-10 bullet points of actionable insights. Not vague observations but specific things the user can use.

### Content angles
3-5 different approaches to the topic. Each angle should have a one-sentence pitch and a note on expected engagement type (likes vs replies vs bookmarks vs shares).

### Audience insights
Who cares about this and why. Specific pain points, desires, knowledge level. What vocabulary they use.

### Competitive landscape
What others are saying. Gaps and opportunities. What's overplayed and what's underserved.

### Recommended format
Best content format for this topic + platform combo. Thread vs single tweet, short README vs detailed, etc. With reasoning.

### Key terms and phrases
Vocabulary the target audience uses naturally. Community-specific slang, jargon, and references.

### Risks and things to avoid
What NOT to say or do. Sensitive topics, overplayed angles, common mistakes in this niche.

### Sources
All URLs and references consulted.

## Step 4: Offer next steps

After delivering the brief, suggest:
- "Want me to draft content based on this research?" (triggers write-content skill)
- "Want me to dig deeper into any angle?"
- "Want me to research competitor accounts for reply strategy?"

The research brief should be detailed enough that the write-content skill can produce high-quality content from it without additional research.
