# SPFx Mail Room — SharePoint Hackathon 2026 Submission

This repository is for the **SharePoint Hackathon 2026** submission: **presentation**, **video**, and **supporting materials**. It does **not** contain the application source code.

---

## Presentation & video

- **Gamma presentation:** [SPFx Mail Room — AI-powered document classification](https://copy-of-spfx-foundry-age-pjnsi8u.gamma.site/)
- **Video:** *(to be added — 8 min max per hackathon rules)*

---

## What is SPFx Mail Room?

**SPFx Mail Room** is an AI-powered document classification app for SharePoint and Teams. One generic app for many use cases — deploy once per site or department.

- **Documents** → **Incoming Documents library** → **AI (Logic App + Azure AI Foundry agent)** → **Mail Room list** → **User validation**
- All lists and libraries (Client list, Project list, Mail Room list, Incoming Documents library) are **autoprovisioned** on deploy.
- **Multiple entry points:** SPFx UI (manual or batch), Power Automate (mailbox attachments), or Scanner/MFD — same library, one AI pipeline.
- **Multi-surface:** Same app on **SharePoint** (pages) and **Teams** (desktop and mobile). Same behavior, different surfaces.
- **Group workflow:** First verification (adjust AI suggestion) → Deadline step (optional deadlines, reminders, mailbox sync) → Final validation → document classified into the right SharePoint library folder.
- **Generic:** Map "Client" and "Project" to your domain (e.g. Legal: client/case; HR: employee/request; Marketing: brand/campaign). Deploy once, use everywhere.

**In short:** AI suggests, human validates — one app, many deployments.

---

## Hackathon categories

- **Best use of SharePoint in AI agents** — SharePoint as surface and context; agents meet content where work happens.
- **Most innovative SPFx experience** — Reusable, multi-surface, plug-and-play, no extra infrastructure.
- **Best mobile experience** — Full Mail Room on Teams mobile, touch-first.

---

*Submitted for [SharePoint Hackathon 2026](https://github.com/SharePoint/sharepoint-hackathon).*

*Nemoura Labs · [Youssef El Garmit](https://www.linkedin.com/in/youssefelgarmit/)*
