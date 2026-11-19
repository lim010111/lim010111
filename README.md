### About

I'm an AI engineer working toward **Agentic Engineering** — not vibe-coding. Grounded in solid
NLP and LLM fundamentals, I understand how agents actually work and oversee them with that
understanding. In a field changing faster than ever, I learn aggressively and aim to be
AI-native — but solving the problem always comes first.

### Stack

<div align="center">

![Claude Code](https://img.shields.io/badge/Claude_Code-d97706?style=for-the-badge&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-111111?style=for-the-badge&logo=openai&logoColor=white)
![Antigravity CLI](https://img.shields.io/badge/Antigravity_CLI-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

</div>

### Selected Work

**🗓 [autocolor-calendar](https://github.com/lim010111/autocolor-calendar)**
A multi-tenant SaaS that auto-classifies Google Calendar events and color-codes them through a
two-stage classifier — a fast kNN match over event embeddings first, with a lightweight LLM
fallback for what similarity can't settle. Solo-built on Cloudflare Workers; in Google OAuth review.

**<img src="https://cdn.simpleicons.org/obsidian" height="16"/> [noteforge](https://github.com/lim010111/noteforge)**
A privacy-first static-site generator that turns an Obsidian vault into a blog — only notes you
explicitly opt in ever get published. Powers my blog at [woohyun.dev](https://woohyun.dev).

**<img src="https://cdn.simpleicons.org/claude" height="16"/> [keel](https://github.com/lim010111/keel)**
A harness on native Claude Code with one gate at each point where agent work reaches a wider
audience: **alignment → verification → merge**. `third-party-review` sends a session to outside
models (Codex, Gemini) to catch human↔agent drift, TDD hooks block implementation written before
its tests, and a STATUS board keeps shared state. The Codex+Claude merge gate blocked 6 of 15
measured pushes, all judged over-blocks, so I moved it from a hard block to advisory.

**<img src="https://cdn.simpleicons.org/python" height="16"/> [pykeel](https://github.com/lim010111/pykeel)**
A coding-agent harness that implements LLM calls, the agent loop, and session management without
SDKs or agent frameworks, built to measure how closely a harness interface is fitted to specific
models. Plan and ADRs are written; v0 (Responses loop, one bash tool, run traces, bwrap sandbox)
is next.

### Currently

- Building **pykeel** — v0 agent loop
- Shipping **autocolor-calendar** — in Google OAuth review
- Evolving **keel** — agentic-engineering harness project
- Writing at **[woohyun.dev](https://woohyun.dev)**

### Connect

[![Blog](https://img.shields.io/badge/Blog-woohyun.dev-58A6FF?style=flat&logo=astro&logoColor=white)](https://woohyun.dev)
[![Portfolio](https://img.shields.io/badge/Portfolio-woohyun.dev%2Fportfolio-58A6FF?style=flat)](https://woohyun.dev/portfolio/)
[![Email](https://img.shields.io/badge/Email-limwoohyun01-D14836?style=flat&logo=gmail&logoColor=white)](mailto:limwoohyun01@gmail.com)

<div align="center">

![Activity graph](https://github-readme-activity-graph.vercel.app/graph?username=lim010111&theme=github-compact&hide_border=true&area=true)

</div>
