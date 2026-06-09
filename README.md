<p align="center">
  <img src="banner.png" alt="Verifiable Agentic Engineering. Because you can't audit a vibe." width="100%">
</p>

> **AI agents write code fast, and forget why.**
> Close the chat and the plan, the decisions, the dead ends are gone.

I build **[BeastForge](https://github.com/skybeast42/beastforge)**, an open template
(built for [Claude Code](https://claude.com/claude-code), for now) where a project's
memory lives in the repo, not the chat. The plan, the live state, every decision, the
open questions sit in version-controlled files the agent re-reads each session. You
resume cold, every change traces back to a logged decision, and a human can read it,
check it, and re-run it without the AI.

- 🧠 **Memory in the repo** — `STATE`, `DECISIONS`, `MASTERPLAN`, open questions
- 🔁 **Resume cold** — the agent picks up where it left off, no re-explaining
- ✅ **You stay the auditor** — every change traces to a decision; reproduce it without the AI

You spawn a project (a "beast") and it keeps its own memory, decisions, and reproducible
trail as you work. Run more than one and they form a fleet: beasts that learn from each
other, inheriting conventions and hard-won knowledge.

---

#### Beasts I run

It is also just useful, and it saves me time. Nothing here burns tokens for show.

- ✈️ **Flying and the everyday.** Small specialists: flight planning and weather, the
  aircraft's maintenance log, the weekly meals, a bit of investing. Each stays legible on
  its own, and I spawn a new one from a sibling without touching any git plumbing. A trip
  only makes sense when the weather, the calendar, and the aircraft's hours before its
  next maintenance all agree, so they hand me one briefing instead of me running between
  them.
- 🩺 **Recovery.** A gym accident left me with some back trouble. One beast helps me make
  sense of the medical side and spawned a second that writes and tracks the exercise
  plans. The two talk to each other, and both check with my doctor and physiotherapist
  before adjusting anything. The agents do the legwork; the judgement stays with the
  people accountable for it.
- ☕ **[ROASTBEAST](https://github.com/skybeast42/roastbeast)** *(write-up to follow).*
  Out of pure curiosity: a complete modelling problem end to end, from study design and
  simulation to the report, scored against a hidden ground truth and reproducible from a
  single command. How much would today's agents have changed the work I did for a living
  in a previous life, if real subject-matter expertise were distilled into their
  onboarding? No business interest, just something I want to know.

---

#### A note on the account

It is new, and BeastForge is new too, built over the last few weeks, thanks to agentic
development. What is not new is the experience behind it: around twenty years in pharma,
eleven of them building and running a pharmacometrics consultancy, in a field where
reproducibility and audit trails are the job, not an add-on. I have maintained
open-source scientific tooling for two decades ([SBTOOLBOX2](https://www.sbtoolbox2.org),
[IQM Tools](https://iqmtools.intiquan.com/), [IQRsbml](https://iqrsbml.intiquan.com/),
[RHEM](https://rhem.intiquan.com/), the IQR Tools lineage, AGPLv3, still in use). My old
GitHub account went with the company when I sold it; this is the restart. BeastForge
ships here as tested, versioned releases, developed in a private workspace and pushed
when a version is solid, so you will see clean releases rather than a day-by-day history.

---

Naming and framing help, people tell me, so here is what I landed on:

> **Verifiable Agentic Engineering**
> *Because you can't audit a vibe.*

---

📍 Riehen, Switzerland · 🔗 [skybeast.ch](https://skybeast.ch) · ✉️ henning@skybeast.ch · 💼 [in/henningschmidt1](https://linkedin.com/in/henningschmidt1)
