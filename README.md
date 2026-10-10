## Max Sheahan

Builder and teacher. I build one specific thing for one specific person, then teach them to run it. I am also Head of Education at [Intent Solutions](https://intentsolutions.io). I taught middle-school English before this, and I started by vibe-coding a classroom tool I did not fully understand. Now most of my work, and a fair amount of my life, runs through a system of my own plugins and skills on Claude Code.

Most of what I build is private. This is the public slice.

### Building now

| Project | What it is | Status |
| --- | --- | --- |
| [Wally Walks](https://wallywalks.app) | A hand-drawn walking guide to San Francisco, a growing map of stairways, views, parks, and neighborhood paths. Also runs inside chat as an MCP app | Live |
| [LITMUS](https://litmustimes.com) ([code](https://github.com/blueandyellow44/litmus)) | A daily news reader that groups coverage into stories and shows how calmly or hotly each outlet told it | Live |
| [LITMUS Live](https://github.com/blueandyellow44/litmus-meter) | A live meter for broadcast speech. It listens to a speech or a debate and moves a needle from proportionate to hyperbolic, one sentence at a time | Public |
| [Literary Engine](https://github.com/blueandyellow44/literary-engine) | A multi-agent pipeline for long-form fiction, from extraction to drafting to judging | Case study |
| [Voice Gate](https://github.com/blueandyellow44/voice-gate) | A diagnostic that checks whether a draft matches a target voice profile | Public |

### My plugins and skills

I write most of the tooling I use. These are the plugin sets I have installed and maintain myself.

| Plugin set | What it does |
| --- | --- |
| Second Brain | Runs my Obsidian vault as an operating system. Daily logs, agenda, weekly review, session wrap, decision records, and capture of every Claude session |
| Voice | Builds evidence-based voice profiles from a corpus, then drafts, audits, and revises against them |
| Literary Engine | The book-writing engine behind the case study above, fronted by one launcher |
| Secure Launch | A security pass before anything ships. Attack-surface map, OWASP ASVS checks, secret and dependency scans, and a gate that refuses to deploy on an open finding |
| MCP Apps | Takes an app from a one-page PRD to a tested Cloudflare Worker that runs inside a chat |
| Skill Forge | Builds and grades skills, and researches a person into a sourced brief |
| Docgen | Documents and PDFs that look designed rather than generated |
| YouTube Recut | Rebuilds a tighter edit from raw footage |

Most of these depend on my own vault and stay private. The ones that stand alone are public at [claude-skills](https://github.com/blueandyellow44/claude-skills), installable as a marketplace, with voice, writing, and document toolkits.

### Also in my setup

I keep a few outside marketplaces installed alongside my own, including [Jeremy Longshore's plugin catalog](https://github.com/jeremylongshore/claude-code-plugins-plus-skills), [benai-skills](https://github.com/naveedharri/benai-skills), [cloudflare/skills](https://github.com/cloudflare/skills), and [Trail of Bits skills](https://github.com/trailofbits/skills).

### How I work

Everything sits on Claude Code and Claude Cowork. Underneath, the stack is React, Vite, and Next.js on the front end, Hono and Drizzle on Cloudflare Workers and D1 for most of what I deploy, Python for data and document pipelines, with Fly.io and Supabase where a project needs them.

I try to share the process and not only the finished thing.

### Reach me

I am open to full-time roles, contract builds, and teaching work.

- [max@sheahan.ai](mailto:max@sheahan.ai)
- [LinkedIn](https://www.linkedin.com/in/max-sheahan-8a7a6249/)
- [maxsheahan.com](https://maxsheahan.com)
