# AI YouTube Monthly

A monthly curated list of the top 10 must-watch YouTube videos for AI-native developers.

## Topics

Each monthly issue covers three verticals:

| Track | Scope |
|-------|-------|
| **Claude Coding** | Claude Code, Anthropic official, agentic workflows, hooks/skills/subagents |
| **Codex & OpenAI** | OpenAI Codex CLI, ChatGPT coding, GPT-based agents, Assistants API |
| **Open-Source AI Agents** | LangChain, CrewAI, AutoGen, OpenDevin, SWE-agent, community frameworks |

## Selection Criteria

Videos are selected based on:

1. **Recency** - published within the calendar month or very recently before
2. **Depth** - advanced content, not beginner tutorials or hype
3. **Community signal** - Reddit upvotes, HN discussion, view velocity
4. **Source quality** - official channels, conference talks, known practitioners
5. **Actionable value** - teaches something you can apply immediately

Beginner "vibe coding" tutorials are explicitly excluded.

## Structure

```
ai-youtube-monthly/
├── README.md
├── templates/
│   └── issue.html         # HTML template for each month
├── scripts/
│   └── research-prompt.md # Research methodology and prompts
└── 2026/
    └── 06/
        ├── index.html     # Rendered page (open in browser)
        └── README.md      # Markdown version (renders on GitHub)
```

## How to Use

- Browse monthly issues in `YYYY/MM/` directories
- Open `index.html` in any browser for the designed reading experience
- Read `README.md` on GitHub for quick scanning

## Publishing Schedule

New issue drops on the last Friday of each month.

## Contributing

Research is done via web search with specific methodology documented in `scripts/research-prompt.md`. PRs welcome for:

- Suggesting videos that were missed
- Fixing broken links
- Improving the HTML template

## License

CC BY 4.0
