# 🚀 AGENT∞ — The Recursive AI Business Builder

AGENT∞ is a full-stack, LLM-powered platform that spawns **autonomous business agents**. These agents build themselves—landing pages, decision trees, funnels, and course content—using your input and real-world content like YouTube and PDFs. It’s niche-agnostic, SEO-optimized, and deployable via Docker, Replit, or AWS.

---

## 🧠 Vision

> "Build once. Launch forever."

AGENT∞ enables anyone to create decision-making agents that launch and maintain monetizable funnels across info, affiliate, SaaS, content, service, or ecommerce models—fully automated and self-improving.

---

## 📦 Project Structure

```

agent-infinity/
├── frontend/ # Next.js + Tailwind UI
├── backend/ # FastAPI or Node.js API
├── models/ # DeepSeek or other LLMs
├── automations/ # n8n workflows
├── /docs/ # UX specs, prompts, agent templates
│ ├── UX-Copy-Spec.md
│ ├── Prompt-Templates/
│ └── Agent-Examples/
├── docker-compose.yml # Full stack runner
├── .env.example # Local env sample
├── LICENSE # MIT License
└── README.md

```

---

## 🧱 Tech Stack

| Layer      | Tech                       |
| ---------- | -------------------------- |
| Frontend   | Next.js + Tailwind         |
| Backend    | FastAPI or Express.js      |
| Auth + SQL | Supabase                   |
| NoSQL      | MongoDB Atlas              |
| LLM Engine | OpenAI / Claude / DeepSeek |
| Vector DB  | Chroma / Pinecone          |
| RAG        | LangChain / LlamaIndex     |
| Automation | n8n                        |
| Proxy      | Traefik                    |
| Deployment | Docker + AWS / Replit      |

---

## 🛠️ Local Setup (Docker)

1. Clone and enter the project:

```bash
git clone https://github.com/YOUR_USERNAME/agent-infinity.git
cd agent-infinity
```

2. Copy and configure `.env`:

```bash
cp .env.example .env
```

3. Launch with Docker:

```bash
docker-compose up --build
```

4. Access:

- UI: [http://agent.localhost](http://agent.localhost)
- API: [http://api.agent.localhost](http://api.agent.localhost)
- Admin (Traefik): [http://localhost:8080](http://localhost:8080)

> Add `127.0.0.1 agent.localhost api.agent.localhost` to `/etc/hosts`.

---

## 🔄 n8n Automations

| Workflow            | Purpose                                       |
| ------------------- | --------------------------------------------- |
| agent-ingest-source | Transcribe YouTube/PDF → Embed → RAG          |
| weekly-refresh      | Refresh funnel content weekly                 |
| content-delivery    | Push outputs to Notion, Airtable, Email, etc. |

> n8n workflows located in `/automations/n8n-workflows/`

---

## 🧠 UX Philosophy

- **Naval clarity**: Minimal, power-first UX
- **Dan Kennedy persuasion**: Aggressive CTA copywriting
- **Becker dominance**: Emphasis on control, automation, speed

Users should feel like they’re deploying weapons, not filling forms.

---

## 💸 Business Models

| Model     | Agent Output Types                          |
| --------- | ------------------------------------------- |
| Info      | Course, PDF, Email Funnel                   |
| Affiliate | SEO Pages, Offers, Monetized Trees          |
| SaaS      | Auto-MVP Builder + Onboarding Copy          |
| Content   | Script generator, article writer, scheduler |
| Services  | Pricing pages, proposals, offers            |

---

## 🌍 Deployment Options

- **Replit**: Dev & MVP testing (replit.nix included)
- **AWS ECS/S3/Route53**: For scaling agents to subdomains
- **MongoDB Atlas** or **Amazon DocumentDB** for DB
- **Supabase** for user auth and SQL-driven features

---

## 📈 Marketing Ops

| Channel   | Strategy                                 |
| --------- | ---------------------------------------- |
| SEO Blog  | Weekly agent-written posts               |
| YouTube   | Shorts showing auto-agent builds         |
| LinkedIn  | Funnel case studies + insights           |
| Affiliate | Built-in referral links in agent outputs |
| Email     | AI-generated sequences from funnel agent |

---

## 📖 Docs Index

- [`UX-Copy-Spec.md`](./docs/UX-Copy-Spec.md)
- [`Prompt-Templates/`](./docs/Prompt-Templates/)
- [`Agent-Examples/`](./docs/Agent-Examples/)

---

## 🧑‍💻 Contributing

1. Fork the repo
2. Create a feature branch
3. Push + submit PR with clear description
4. Update `/docs` if logic, flows, or agents are added

---

## 🪪 License

MIT — Share freely, build ethically, automate with empathy.

---

## ✊ Author

Created by **Caleb Saunders**, CTO of **Caleb Pierre Ventures LLC**, to help those from the bottom build self-sustaining digital empires.
