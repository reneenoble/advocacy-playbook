# Measuring Success

Measuring the impact of advocacy work helps teams understand what is working, justify investment, and improve over time. This page covers the key metrics and methods for tracking advocacy effectiveness.

## Why Measure?

- **Demonstrate impact** – Show the value of advocacy work to leadership and stakeholders.
- **Improve** – Identify what content, channels, and techniques are most effective.
- **Prioritise** – Focus effort on the activities that drive the most value.
- **Align with goals** – Connect advocacy outcomes to product adoption and developer success metrics.

---

## Metric Categories

### 1. Reach

Reach measures how many people are exposed to your content.

| Metric | Description | Where to Find |
|---|---|---|
| Impressions | Number of times content was displayed | Social media analytics, blog analytics |
| Unique views | Number of individual viewers/readers | Blog analytics, YouTube analytics |
| Video views | Total plays of video content | YouTube Studio, LinkedIn Analytics |
| Email reach | Number of subscribers receiving a newsletter | Newsletter platform |
| Event attendance | Number of people at talks or workshops | Event platform, organizer data |

**Reach target-setting tip:** Set baseline benchmarks from the first 3 months, then aim for growth of 10–20% per quarter.

### 2. Engagement

Engagement measures how your audience interacts with your content.

| Metric | Description | Where to Find |
|---|---|---|
| Likes, reactions | Positive engagement signals | Social media platforms |
| Comments and replies | Conversation started by content | Social media, blog comments |
| Shares / reposts | Content amplified by others | Social media analytics |
| Click-through rate (CTR) | % of viewers who click a link | Link tracking, analytics |
| Watch time | Average duration viewers watch a video | YouTube Analytics |
| Session duration | Time spent on blog/learn content | Web analytics |

**Engagement target-setting tip:** A CTR of 2–5% is generally considered good for developer-focused content. Comments and shares are stronger signals than passive views.

### 3. Adoption

Adoption measures whether advocacy is driving actual use of the product or tool.

| Metric | Description | Where to Find |
|---|---|---|
| GitHub stars | Stars on sample/demo repositories | GitHub repository insights |
| GitHub forks | Forks of sample repositories | GitHub repository insights |
| GitHub Codespace opens | Times a sample was opened in Codespaces | GitHub repository insights |
| Documentation page views | Views of product docs and tutorials | Microsoft Learn analytics |
| Product sign-ups via advocacy links | Sign-ups attributed to tracked links | UTM link tracking |
| Active users (product) | Users who start using the product | Product team data |

**Note:** Adoption metrics often require coordination with product and data teams to connect advocacy activity to downstream product usage.

### 4. Community Growth

Community growth measures the growth and health of the developer community around the product.

| Metric | Description | Where to Find |
|---|---|---|
| Social followers | Growth in followers over time | Social media platforms |
| GitHub watchers | Watchers on the main product repo | GitHub repository |
| Forum members | Members of community forums | Respective platform |
| GitHub Discussion activity | Questions, answers, participation | GitHub Discussions |
| Contributors | External contributors to sample repos | GitHub repository insights |

---

## Tracking and Reporting

### UTM Link Tracking

Use UTM parameters to track the performance of links shared across channels. This allows you to attribute traffic and sign-ups to specific pieces of content or campaigns.

Example:
```
https://learn.microsoft.com/en-us/azure/...?utm_source=twitter&utm_medium=social&utm_campaign=build2025
```

| Parameter | Description | Example |
|---|---|---|
| `utm_source` | Where the traffic comes from | `twitter`, `linkedin`, `newsletter` |
| `utm_medium` | The marketing medium | `social`, `email`, `blog` |
| `utm_campaign` | The campaign name | `build2025`, `launch-copilot` |
| `utm_content` | Specific content (for A/B testing) | `demo-video`, `how-to-post` |

### Regular Reporting Cadence

| Frequency | What to Report |
|---|---|
| Weekly | Key content published, top performing posts, notable community activity |
| Monthly | Reach and engagement trends, adoption highlights, feedback summary |
| Quarterly | Full metrics review, goal progress, retrospective, next quarter plan |

---

## Setting Goals

### OKR Framework

Use Objectives and Key Results (OKRs) to set and track advocacy goals:

**Example Objective:** Grow developer awareness and adoption of [Product] among GitHub users.

**Key Results:**
- KR1: Publish 8 blog posts with a combined 50,000 views by end of quarter.
- KR2: Deliver 3 conference talks reaching a combined audience of 2,000+ developers.
- KR3: Grow the main sample repository to 1,000+ GitHub stars.
- KR4: 500 product sign-ups attributed to advocacy content via UTM tracking.

---

## Developer Sentiment

Quantitative metrics tell you *how much* reach you have; qualitative signals tell you *how well* you are resonating.

### Sources of Qualitative Feedback

- **Social media comments and replies** – Read and categorize the sentiment in responses.
- **GitHub Discussions and Issues** – What questions, bugs, and suggestions are developers raising?
- **Event Q&A and hallway conversations** – What do developers ask after your talk?
- **Direct messages and emails** – Unsolicited feedback is often the most honest.
- **Community surveys** – Periodically survey your audience about their experience.

### Sharing Feedback Internally

Regularly summarize developer sentiment and share it with the product and engineering teams. This closes the loop and reinforces the value of the advocacy function beyond promotion.
