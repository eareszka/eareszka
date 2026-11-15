# Emery Reszka

Computer Science student at Florida Gulf Coast University (B.S. expected Dec 2027) and former NCAA Division I swimmer at the University of Wisconsin–Milwaukee on a four-year athletic scholarship. I build and ship full-stack web and mobile apps, with a focus on payments, AI integration, and disciplined engineering process.

[Portfolio](https://eareszka.github.io) · [LinkedIn](https://www.linkedin.com/in/emery-reszka/)

## Featured work

### [Pay My Bill](https://github.com/eareszka/pay-my-bill): Community giving app
*Python, Flask, SQLAlchemy, PostgreSQL (Neon), Stripe Connect, Render*

- Added card payments with Stripe Connect. Stripe rejected the first setup because the platform would be liable for losses, so I moved to Stripe's Managed Risk with direct charges to recipients. The app never holds money, and card payments are live.
- Ran a solo project like a team: one-week Scrum sprints, a Definition of Ready/Done, architecture decision records, and required CI (lint, type checks, tests, dependency audit, secret scan) on `main`. I directed AI agents on each story and reviewed every PR, merging 89 PRs across 7 sprints in 16 days.

### WingIt!: AI texting coach ([backend](https://wingit-backend.fly.dev/))
*React Native (Expo), TypeScript, Python, Claude API, Ollama, PyTorch, Docker, Fly.io*

- To cut API costs and keep users' chats off third-party servers, moved the AI backend from Claude to self-hosted models on my own GPU (Ollama behind a Cloudflare Tunnel, with Claude as a fallback). I made the switch only after my eval suite showed 98.8% speaker accuracy vs. 87% for Claude Haiku on 60 test screens, at half the latency.
- Built iOS, Android, and web from one Expo codebase, with App Store subscriptions and a free tier, and submitted the app to the App Store.

### [Campus Event Management System](https://github.com/eareszka/campus-event-mgmt): Team lead
*Python, Django, HTML/CSS*

- Led a 4-person team: split the project into tasks on Trello and ran weekly check-ins.
- To keep the team on pace, took on most of the front-end and back-end work, including role-based access, admin event approval, and capacity-aware registration with waitlists. Delivered on time.

## Tools and practice

- **Languages:** Python, TypeScript, JavaScript, Java, C++, SQL, HTML/CSS
- **Frameworks:** Flask + SQLAlchemy, Django, React Native (Expo), PyTorch
- **AI:** Claude API, Ollama, QLoRA fine-tuning (Unsloth, TRL)
- **AI-Assisted Development:** Claude Code, Codex; parallel agent orchestration with herdr, branch-per-task isolation, cross-agent code review, and human approval on every merge
- **Infrastructure:** Linux (Ubuntu via WSL2 and a home GPU server), Docker, GitHub Actions, Fly.io, Render, Neon Postgres, Stripe Connect
