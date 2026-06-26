# Research Methodology

## Monthly Research Process

Run these searches at the end of each month to compile the top 10 per track.

### Step 1: Gather Candidates

For each track, run the following search patterns:

#### Claude Coding Track
```
"claude code" YouTube {month} {year} advanced tutorial
Anthropic official YouTube channel {year} new videos
site:youtube.com "claude code" {year} {month} workshop talk
reddit.com/r/ClaudeCode best video {month}
reddit.com/r/ClaudeAI youtube recommendation {month}
```

#### Codex & OpenAI Track
```
"codex cli" OR "openai codex" YouTube {month} {year}
OpenAI official YouTube DevDay {year}
"chatgpt coding" advanced workflow YouTube {year}
reddit.com/r/OpenAI best coding video {month}
site:youtube.com openai developer conference {year}
```

#### Open-Source AI Agents Track
```
"ai agent" open source YouTube {month} {year} tutorial
LangChain OR CrewAI OR AutoGen YouTube {year} advanced
"swe-agent" OR "opendevin" OR "aider" YouTube {year}
reddit.com/r/LocalLLaMA agent video recommendation
site:youtube.com ai agent framework comparison {year}
```

### Step 2: Score Candidates

For each candidate video, evaluate:

| Signal | Weight | How to Check |
|--------|--------|--------------|
| View velocity (views / days since publish) | 25% | Check view count vs publish date |
| Reddit/HN discussion quality | 25% | Search URL on Reddit, check upvotes + comment quality |
| Speaker credentials | 20% | Official team? Known practitioner? Conference speaker? |
| Content depth (not beginner) | 20% | Skim transcript or first 2 min |
| Production quality | 10% | Clear audio, structured content, timestamps |

### Step 3: Select Top 10

- Pick top 3-4 from each track
- Rank the overall top 3 across all tracks
- Write one-paragraph description for each (in Chinese, targeting experienced developers)

### Step 4: Generate Output

- Use `templates/issue.html` as base
- Fill in video data
- Generate both HTML and README.md versions

## Exclusion Rules

Reject videos that are:
- Under 8 minutes (likely shallow)
- Purely promotional with no technical substance
- Targeted at complete beginners
- Clickbait titles with no matching depth
- Duplicating content from the same creator already in the list

## Quality Bar

Each video must pass: "Would a senior engineer with 2+ years of AI-assisted coding experience learn something new from this?"
