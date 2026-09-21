<a href="https://ralphabejuela.com">
  <img src="https://ralphabejuela.com/images/og-default.png" alt="Ralph Abejuela — backend and full-stack developer" height="220"/>
</a>

# Ralph Abejuela

**2026 BSIT graduate (Cum Laude, 1.4 GWA) · backend & full-stack · SQL · TypeScript · Python · Java · open to junior and entry-level roles**

Four months as a Backend Developer Intern at DOST Region V, leading a 3-person intern team on REST microservices
(TypeScript, Node.js, Docker, PostgreSQL, Jest). I write up what I ship — every project below has a README, and
the longer ones have a deep-dive on [my blog](https://ralphabejuela.com).

---

## About Me

- 🎓 **BS Information Technology**, STI College Legazpi — Cum Laude, 1.4 GWA, 2026
- 💼 **Backend Developer Intern, DOST Region V** (4 months) — led a 3-person intern team building REST microservices with PostgreSQL, Docker and Jest
- 🔧 **Debugging, and writing it up** — traced and fixed bugs upstream in two projects I don't own, both merged; every project here ships with a README
- 🧠 **LLM/AI tooling** — on-device classification with Transformers.js, and a GEPA prompt optimizer scored against a held-out eval set
- ⚙️ **Delivery** — CI/CD with GitHub Actions, Docker, Nginx, Jest, Agile/Scrum, Linux daily driver

---

## Patches in other people's repos

Two of these are merged into projects with 27,382 and 3,223 stars:

- **[Kilo-Org/kilocode#2849](https://github.com/Kilo-Org/kilocode/pull/2849)** *(merged)* — the rate-limit countdown started when the request was sent, so generation time ate the user's configured delay. Added a setting to start it after the stream ends instead.
- **[mnemosyne-oss/mnemosyne#915](https://github.com/mnemosyne-oss/mnemosyne/pull/915)** *(merged)* — `run_cli` crashed with `UnicodeEncodeError` on Windows pipes (cp1252 default). Forced UTF-8 stdout/stderr; the regression test fails on `main`.
- Open: **[4fuu/pi-pwsh#17](https://github.com/4fuu/pi-pwsh/pull/17)** — `stop()` refused tasks belonging to another session, so leaked process trees could never be killed. Dropped the session gate on that path only.

---

## Projects

### Agri-Connect — warehouse management for a government agency

Full-stack system built for and deployed to a government client: warehouse and inventory management, automated
reporting, and a Facebook chatbot that absorbs routine inquiries so staff stop answering the same questions by
hand.

React · Node.js · TypeScript · PostgreSQL · Docker · GitHub Actions · Nginx — CI/CD deploys over SSH behind Nginx.
The client repo is private; happy to walk through the architecture, schema and pipeline on a call.

### [ejobtrack](https://github.com/Ralph-Abejuela/ejobtrack)

Job-tracking SPA. Syncs Gmail over OAuth 2.0, classifies applications from 50+ ATS senders with regex parsers and
an on-device Transformers.js fallback, and stores everything in IndexedDB. There is no backend of mine, so user
data never leaves the browser. React · TypeScript · Cloudflare Pages.

### [Automated-HoloCure-Fishing](https://github.com/Ralph-Abejuela/Automated-HoloCure-Fishing) · 84★

Real-time computer vision in Python/OpenCV: screen capture plus template matching tuned to be
windowed-resolution agnostic, correct across Windows and Linux/X11, and shipped to users as a standalone
executable packaged with Nuitka. The domain is a game; the CV pipeline and the release packaging are the point.

### [skill-optimizer-gepa](https://github.com/Ralph-Abejuela/skill-optimizer-gepa)

GEPA-based prompt optimizer: mines eval sets from real work artifacts, scores output with hard format checks plus
an LLM judge, evolves prompts with a checkpoint/resume loop, and A/B tests candidates. Raised one skill's
measured score from 0.725 to 0.850 on a held-out set. Python · litellm · any OpenAI-compatible endpoint.

### [portfolio + blog](https://github.com/Ralph-Abejuela/portfolio) · [live](https://ralphabejuela.com)

Where the write-ups live: local LLMs, GEPA prompt optimization, an ejobtrack deep-dive. Astro · TypeScript.

---

## Competition

- 🥇 **1st Place** — STI Local Codefest (campus): designed and built a movie reservation app in **Java** / Android Studio
- 🥈 **2nd Place** — STI Regional Cluster, ahead of teams from 8 schools

---

## Stack

TypeScript · JavaScript · Java · Python · SQL (PostgreSQL) · React · Node.js · Jest · Docker · GitHub Actions · Nginx · Linux · Git · Agile/Scrum

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ralph-abejuela)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abejuela.ralph.balatucan@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ralphabejuela.com)

---

<p align="center">
  <i>2026 graduate, open to junior and entry-level backend, full-stack, SQL/data and AI/LLM tooling roles<br/>
  Mandaluyong, Metro Manila · abejuela.ralph.balatucan@gmail.com</i>
</p>
