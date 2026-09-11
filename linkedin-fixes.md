# LinkedIn Profile Overhaul — Satyam Namdev

Status snapshot from your screenshots (Jun 28, 2026):


| Item              | Current state                           | Verdict |
| ----------------- | --------------------------------------- | ------- |
| Headshot          | Professional, clear face                | Good    |
| Banner            | Generic city skyline at night           | Replace |
| Headline          | 167/220 chars, no remote signal         | Rewrite |
| Open to Work      | ON, Recruiters only, SF / Hybrid+Remote | Good    |
| Website link      | Linked                                  | Good    |
| About section     | Casual tone, opens with "Heyy"          | Rewrite |
| Featured          | Not visible / likely empty              | Add     |
| Recommendations   | Not visible                             | Request |
| Skill Assessments | Not taken                               | Take    |
| Custom URL        | linkedin.com/in/spyrosigma              | Good    |


---



## 1. Headline (rewrite)

**Current (167/220 chars):**

> Lead Applied AI Engineer @ezAIx, USA | prev. ML Engineer @TunableLabs, USA | Working with LLMs (RAGs, Real-time Voice Agents, Multi Agent orchestration, MCP and more )

**Problems:**

- "and more" wastes chars and sounds vague
- No timezone/remote signal — recruiters filter by this
- "Working with LLMs (RAGs, Real-time Voice Agents...)" reads like a list dump, not a value prop

**Suggested headline (copy-paste, 215/220 chars):**

```
Lead AI Engineer @ezAIx, USA | Ex-Founding ML Engineer @TunableLabs | RAG Pipelines · Real-time Voice AI · LangGraph Agents | IIT Madras | IST, 4hr US overlap | Open to Remote
```

**Alternative (more concise, 198/220 chars):**

```
Lead AI Engineer @ezAIx (USA) | Built production RAG, Voice AI & LLM Agents at US startups | Django · Azure · LangGraph | IIT Madras | Open to Remote
```

Pick one. The key additions are: **"Open to Remote"** and **"IST, 4hr US overlap"** — these are the exact strings recruiters search for.

---



## 2. Banner Image (replace)

Your current banner is a generic night cityscape. It's wasted real estate.

**What to make (use Canva — free LinkedIn banner template, 1584 x 396 px):**

Design a clean, dark-themed banner with:

**Layout:**

```
Left side:                              Right side:
SATYAM NAMDEV                          [tech icons or subtle code graphic]
AI & Backend Engineer
                                       Django · Azure · LangGraph · RAG
Built production AI systems            Python · FastAPI · Redis · Celery
at US startups, from India.
                                       spyrosigma.in
```

**Design rules:**

- Dark background (charcoal/navy — matches your profile photo mood)
- Clean sans-serif font (Inter, DM Sans, or similar)
- No gradients, no neon, no stock photos
- Left-aligned text, right-aligned tech stack pills or subtle visual
- Your name LARGE on the left, role underneath, one-liner underneath
- Tech stack keywords on the right (recruiters scan these)
- Portfolio URL bottom-right corner

**Canva search terms:** "LinkedIn banner minimalist tech" or "LinkedIn cover developer dark"

---



## 3. About Section (rewrite)

**Current:**

> Heyy 👋 I am a Data Science enthusiast, currently working in Gen-AI field. I post insights on X (@Spyrosigma) How skilled I'm? - Heavily worked with Flask, FastAPI and I know how to debug a hellish-messy code...

**Problems:**

- "Heyy" — too casual, loses senior recruiters in the first word
- Self-deprecating ("is this a thing to worry about?") — never plant doubt
- List of skills with no context — reads like a student, not an engineer with production experience
- No quantified impact
- Only 3 lines show before "see more" — you're wasting them

**Rewritten About (copy-paste ready):**

```
I build production AI systems for US companies — real-time voice agents, RAG pipelines,
and LLM orchestration — from India (IST, 4hr US-Eastern overlap, 1.5+ years fully remote).

Currently: Lead AI Engineer at ezAIx, where I architected VoiceCoreIQ — an enterprise
contact center platform handling real-time AI voice calls via Azure OpenAI GPT-4o,
intelligent routing across 18 Django apps, and a RAG pipeline serving production
knowledge bases. Cut TTS costs by 85% and call setup latency by 70%.

Previously: Founding AI Engineer at TunableLabs (SF), where I built Tralyx — a Legal-AI
platform processing 5,000+ legal documents with LangGraph-based entity extraction at
92% accuracy, serving 200+ legal professionals with 99.9% uptime.

What I work with daily:
→ AI/LLM: Azure OpenAI, LangGraph, LangChain, RAG, Pinecone, vector search
→ Backend: Django (ASGI), FastAPI, Celery, Redis, WebSockets, SSE
→ Cloud: Azure (ACS, Event Grid, Blob, Document Intelligence), Docker
→ Data: MongoDB, PostgreSQL, Supabase

BS in Data Science — IIT Madras.

Open to remote backend/AI engineering roles. Let's talk: namdev2003satyam@gmail.com
```

**Why this works:**

- First 3 lines (visible before "see more") = who you are + what you build + remote proof
- Quantified impact in both roles
- Clean tech stack section that's scannable
- Ends with a clear CTA
- No casual filler, no self-doubt, no emojis

---



## 4. Featured Section (add these)

Go to your profile → "Add section" → "Featured"

Add in this order (first item shows largest):

1. **Portfolio website** — link to `spyrosigma.in`
  - Title: "Portfolio — AI & Backend Projects"
  - Description: "Production systems I've built: VoiceCoreIQ, Legal-AI, MedMitra, and more."
2. **VoiceCoreIQ post** — link to your LinkedIn post about getting PPO from ezAIx
  - Already exists: `https://www.linkedin.com/posts/spyrosigma_just-got-ppo-from-ezaix-joined-as-backend-activity-7381734793866219520-CBVU`
3. **Tralyx launch post** — link to your Tralyx launch post
  - Already exists: `https://www.linkedin.com/posts/spyrosigma_aiforlaw-legalai-legaltechstartup-activity-7326485798726356992-JIyP`
4. **GitHub profile** — link to `https://github.com/Spyrosigma`
  - Title: "GitHub — Open Source & Side Projects"
5. **(Future)** Once you record a Loom intro, add it here as the #1 item.
6. **(Future)** Once you write your first blog post, add it here.

---



## 5. Experience Section — Rewrite bullets for remote signal

Your current experience descriptions are likely focused on *what* you built. Rewrite to also show *how* you worked remotely.

### ezAIx Inc. — Lead AI & Software Engineer

```
Architected VoiceCoreIQ — a single-tenant Azure Communication Services-backed enterprise
contact center platform, owning the full backend across 18 Django ASGI applications.

Key contributions:
• Built production AI Voicebot bridging Azure OpenAI GPT-4o Realtime with ACS media
  streams — sub-second latency with tool-calling for order lookup and CSAT scoring.
• Engineered end-to-end RAG pipeline: Azure Blob → Document Intelligence & Firecrawl →
  llama-text-embed-v2 → Pinecone namespaces, serving real-time knowledge bases.
• Designed visual node-based workflow engine for dynamic call routing, IVR trees, and
  omnichannel orchestration.
• Built real-time Agent Presence Dashboard via ASGI SSE middleware + Redis Pub/Sub for
  live supervisor monitoring.
• Reduced TTS costs by 85% and call setup latency by 70% via 3-tier caching strategy
  (Redis → Blob Storage → Generation).
• Drove async engineering across US and India timezones — daily written standups, Loom
  walkthroughs, and PR-based code reviews as primary collaboration mode.
• Flew to Dubai for company kickoff (Dec 2025) — selected engineers gathered for
  strategic planning.

Stack: Django ASGI · Azure (OpenAI, ACS, Event Grid, Blob) · MongoDB · Redis · Celery ·
Pinecone · Docker
```



### TunableLabs — Founding AI Engineer

```
First engineering hire. Built Tralyx — an AI-powered Legal Intelligence Platform
from zero to production, end-to-end.

• Designed and shipped the full stack: FastAPI backend, Next.js frontend, Supabase
  (PostgreSQL) for multi-tenant chat sessions and document collections.
• Built LangGraph-based Entity Extraction Agent with schema validation and multi-agent
  orchestration across 5,000+ legal documents — 92% extraction accuracy.
• Implemented multi-LLM orchestration with streaming responses and real-time WebSocket
  updates; integrated web search via Tavily and Exa APIs.
• Refactored a tightly coupled Gradio monolith into modular FastAPI services, enabling
  API integration across multiple law firms.
• Served 200+ legal professionals with 99.9% uptime and 100+ concurrent users.
• Fully remote collaboration with SF-based founder — async-first workflow using GitHub,
  Notion, and Slack across IST/PST timezones.

Stack: FastAPI · LangGraph · Supabase · Weaviate · Next.js · Docker
```

**Note the additions:**

- "Drove async engineering across timezones" — remote signal
- "Async-first workflow using GitHub, Notion, and Slack" — tool fluency
- "Loom walkthroughs, PR-based code reviews" — async communication proof

---



## 6. Open to Work Settings (fine-tune)

From your screenshot, you have:

- **San Francisco, CA | Hybrid · Remote** — Good

But also add:

- **Job titles** (add multiple): "AI Engineer", "Backend Engineer", "ML Engineer",
"Software Engineer", "Senior AI Engineer", "Senior Backend Engineer"
- **Location types**: Make sure "Remote" is checked as primary
- **Start date**: "Immediately" or whenever accurate

---



## 7. Skills to Add / Reorder

Go to Skills section. Add these if missing and **reorder so the top 3 visible ones are:**

1. **Python** (most searched, most relevant)
2. **Machine Learning** (broad, high-search-volume)
3. **Django** or **LLMs** (depending on target role)

Then add / ensure these are listed:

- FastAPI
- Azure
- LangChain
- LangGraph
- RAG (Retrieval-Augmented Generation)
- Docker
- PostgreSQL
- MongoDB
- Redis
- REST APIs
- WebSockets
- Celery
- Git

**Take LinkedIn Skill Assessments for:**

- Python
- Django
- Machine Learning
- Git
- REST APIs

These are free, take 15 min each, and add a "Verified" badge that boosts search ranking.

---



## 8. Recommendations to Request

Send personalized messages (not LinkedIn's default text) to these people:

### Template for manager/lead at ezAIx:

```
Hi [Name],

Hope you're doing well! I'm updating my LinkedIn profile and was wondering
if you'd be open to writing a short recommendation about our work together
on VoiceCoreIQ.

Specifically, it would be great if you could mention:
- The scope of what I owned on the backend
- How I handled working async across timezones
- Any specific impact you noticed (cost reductions, system reliability, etc.)

Totally understand if you're too busy — no pressure at all. Happy to write
one for you too!

Thanks,
Satyam
```



### Template for TunableLabs founder:

```
Hi [Name],

I hope Tralyx is going well! I'm polishing up my LinkedIn and was wondering
if you'd be willing to write a brief recommendation.

If you could touch on any of these, it would mean a lot:
- Building the platform from zero as the first engineer
- The LangGraph entity extraction pipeline and its accuracy
- Working fully remote across IST/PST

Happy to return the favor. Thanks!

Satyam
```



### Also ask:

- A peer/colleague at ezAIx (Sambhav Seth, if comfortable)
- A professor or mentor from IIT Madras
- Anyone from a hackathon or open-source collaboration

**Target: 5 recommendations minimum.**

---



## 9. Activity / Posting Strategy

Your posting is sporadic. Here's a minimal sustainable plan:

### Post 1x per week (pick a day, e.g., Tuesday):

**Post types that work for your niche (rotate these):**

1. **"Here's what I learned building X"** — Technical insight from VoiceCoreIQ or Tralyx
  - Example: "How I reduced TTS costs by 85% with a 3-tier caching strategy"
  - Example: "What I learned building a LangGraph entity extraction agent over 5000 legal docs"
2. **"Hot take / opinion on AI tooling"** — Something you actually believe
  - Example: "LangGraph > vanilla LangChain for production agent systems. Here's why."
  - Example: "Most RAG tutorials skip the hardest part: chunking strategy matters more than your embedding model."
3. **"How I work remotely"** — Process posts
  - Example: "I work with a US team from India. Here's my async communication setup."
4. **"Something I shipped this week"** — Small wins, screenshots, demos



### Comment 3-5x per week:

- Follow: remote-first companies you'd want to work at
- Follow: engineering leaders at target companies
- Leave thoughtful 2-3 sentence comments on their posts (not "Great post!")
- This makes your name familiar before you ever apply

---



## 10. Location Field

**Current:** India

**Change to:** Either keep "India" (honest) OR if LinkedIn allows,
add to your headline/about that you're based in Delhi/NCR, IST timezone.

The key remote signal isn't your country — it's your **timezone and overlap hours**.
You already have this in the "Open to Work" settings pointing to SF,
which is smart. The About section rewrite above covers the rest.

---



## 11. Custom URL

**Current:** linkedin.com/in/spyrosigma — Already good. No change needed.

---



## 12. Projects Section (add if not already there)

Go to "Add section" → "Additional" → "Projects"

### Project 1: VoiceCoreIQ — Enterprise Contact Center Platform

```
Associated with: ezAIx Inc.
Date: May 2025 – Present
URL: (leave blank if NDA / internal)

Architected the full backend for an enterprise contact center platform on Azure.
18 Django ASGI applications handling real-time AI voice calls, intelligent call routing,
queue orchestration, RAG-powered knowledge bases, and live agent monitoring.

Reduced TTS costs by 85% and call setup latency by 70%.
Handled production traffic with real-time Azure OpenAI GPT-4o voice integration.
```



### Project 2: Tralyx — AI-Powered Legal Intelligence Platform

```
Associated with: TunableLabs, LLC
Date: Nov 2024 – Apr 2025
URL: https://www.tralyx.com

Built the core AI backend for a legal intelligence platform. LangGraph-based entity
extraction across 5,000+ legal documents (92% accuracy), multi-LLM orchestration,
streaming WebSocket responses, and web search integration.

Served 200+ legal professionals with 99.9% uptime.
```



### Project 3: MedMitra — AI Medical Case Management

```
Date: [whenever you built it]
URL: [GitHub link if public]

Multi-agent system using LangGraph for medical case analysis — processing 500+ patient
notes, lab reports (LlamaParse), and radiology images (Llama 4 vision) with 94% accuracy.
SOAP notes and diagnostic suggestions in under 3 seconds.
```

---



## Quick Checklist

- [ ] Rewrite headline (copy from Section 1)
- [ ] Replace banner (design on Canva, see Section 2)
- [ ] Rewrite About section (copy from Section 3)
- [ ] Add Featured items (Section 4)
- [ ] Rewrite Experience bullets (Section 5)
- [ ] Fine-tune Open to Work job titles (Section 6)
- [ ] Reorder skills + take assessments (Section 7)
- [ ] Send 5 recommendation requests (Section 8)
- [ ] Schedule first LinkedIn post (Section 9)
- [ ] Add Projects section (Section 12)
- [ ] Record 60-sec Loom intro (add to Featured when done)
- [ ] Write first technical blog post (add to Featured when done)