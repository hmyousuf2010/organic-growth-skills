# Twitter/X Algorithm Mechanics (2025-2026)

From X's open-sourced algorithm code (March 2023, confirmed in January 2026 xAI release).

## Table of contents

1. [Engagement weights](#engagement-weights)
2. [Negative signals](#negative-signals)
3. [TweepCred and Premium](#tweepcred-and-premium)
4. [External links](#external-links)
5. [Engagement velocity](#engagement-velocity)
6. [Posting frequency](#posting-frequency)
7. [What kills reach](#what-kills-reach)
8. [Reply strategy](#reply-strategy)
9. [Grok integration](#grok-integration)

---

## Engagement weights

| Signal | Raw weight | Relative to like |
|--------|-----------|-----------------|
| Reply engaged by author (reply-to-reply) | +75.0 | 150x a like |
| Reply | +13.5 | 27x a like |
| Profile click + like/reply | +12.0 | 24x a like |
| Conversation click + engagement | +11.0 | 22x a like |
| Dwell time (2+ minutes) | +10.0 | 20x a like |
| Bookmark | +10.0 | 20x a like |
| Retweet/Repost | +1.0 | 2x a like |
| Like (favorite) | +0.5 | 1x (baseline) |
| Video watched 50%+ | +0.005 | Minimal |

Simplified engagement score:
`Score = (Likes x 1) + (Retweets x 20) + (Replies x 13.5) + (Profile Clicks x 12) + (Link Clicks x 11) + (Bookmarks x 10)`

---

## Negative signals

| Signal | Penalty |
|--------|---------|
| "Not interested" click | -100x |
| Block/Mute | -1000x |
| Report | -15 to -35 reputation |
| Offensive text (Grok-detected) | -80% reach |

---

## TweepCred and Premium

**TweepCred:** Hidden 0-100 reputation score. Critical threshold: 65. Below 0.65, only 3 of your tweets are considered for algorithmic distribution.

**Premium advantages:**
- Premium ($8/mo): Blue checkmark, 4x in-network boost, 2x out-of-network boost, priority replies
- Premium+ ($40/mo): All above + no ads, 100K char articles, highest priority
- Buffer study (18.8M posts): Premium = roughly 10x more reach per post vs free accounts

Only about 0.26% of users subscribe, creating a massive competitive advantage for subscribers.

---

## External links

Links are actively penalized:
- 30-50% reach reduction for posts with links
- Zero median engagement for link posts from free accounts (March 2025+)
- Competitor platform links: -60%
- Multiple links: -70%
- Shortened URLs: additional -10%

**Best strategy — link in reply:**
Post valuable native content as main tweet. Add link in first reply. Performance: 270% bump in views, 486% bump in likes vs link in main tweet.

Other strategies:
- Quote tweet your link tweet
- Pin link tweet and drive profile visits
- Extract key points into thread, link at the very end
- Use Premium long-form posts (up to 25K chars) to replace external links

---

## Engagement velocity

First 30-60 minutes are the critical window. Algorithm tests tweet on 5-15% of followers first, then expands or suppresses based on early engagement.

**Time decay:** Tweet loses roughly 50% of visibility score every 6 hours. After 24 hours, minimal algorithmic push.

**What this means:** Engage with replies immediately after posting. Spend 15 minutes replying to every comment — this triggers the 150x reply-to-reply multiplier and tells the algorithm the tweet is generating conversation.

---

## Posting frequency

**Optimal:** 2-5 quality tweets/day, spaced 30-60 min apart.
**Minimum:** 5-7 tweets weekly + 1-2 threads monthly.

Spend 10-15 minutes engaging before posting your own content. This warms up your account in the algorithm.

---

## What kills reach

- 3+ hashtags: -40% penalty. 1-2 relevant hashtags: +21%. Zero is fine (Grok reads semantically).
- All-caps text: Major penalization.
- Offensive/combative tone: -80% reach via Grok sentiment analysis.
- Unknown words/misspellings: 95% penalty (0.01 weight for "unknown language").
- Engagement farming: "Like if you agree" actively suppressed.
- Duplicate/cross-posted content: Detected and suppressed.
- Community Notes on your tweets: -60 to -80% reach, removed from For You.
- Fake followers: -50 to -70% reach, excluded from For You.
- Posting 10+ tweets in 5 minutes: Spam detection trigger.

---

## Reply strategy

**Target:** 50 replies/day for consistent growth. Takes 30-45 minutes with strategy.

Best practices:
- Target tweets with momentum (1000 views/hour beats 10K total from a week ago)
- Reply to accounts 10-100x your follower count
- Stay niche-relevant
- Add genuine value (3+ sentences, unique perspective)
- Reply within first 2 hours of viral tweets
- Spend 10-15 minutes engaging before posting your own content
- After posting, dedicate 15 minutes to reply to every comment (triggers 150x multiplier)

**What makes a good reply:** Not "great point!" but a substantive addition. Share your experience, add data, ask a sharp follow-up question, respectfully disagree with reasoning.

---

## Grok integration (Oct 2025+)

- Algorithm reads text semantically (not just counting engagement signals)
- Watches video content to understand it
- Sentiment analysis: constructive tone = wider distribution; combative = reduced
- Following feed is Grok-sorted by predicted engagement (Nov 2025)
- January 2026: xAI open-sourced the Grok-powered algorithm on GitHub
- Promptable feeds: users can input natural language commands for content preferences

---

## Tweet length performance

| Range | Performance | Best for |
|-------|------------|----------|
| 71-100 chars | 17% higher engagement | Quick hooks, punchy opinions |
| 70-110 chars | Best for retweets | Shareable content |
| 240-259 chars | Most total likes | Thought leadership |
| Full 280 | No penalty | When you need the space |
| Premium long-form | Dwell time boost | Deep dives replacing blog links |

6th-7th grade reading level = most retweetable. Emojis count as 2 characters. Links always count as 23 characters.

---

## Average engagement rate

Average dropped to 0.12% in 2025 (down 48% YoY). This means high-quality content matters more than ever — volume alone doesn't cut it.
