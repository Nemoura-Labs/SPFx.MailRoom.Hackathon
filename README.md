# SPFx Mail Room — Hackathon submission

This repository is for the **hackathon submission, presentation, and video** — not the application code.

- **Presentation:** [SPFx Mail Room — AI-powered document classification (Gamma)](https://copy-of-spfx-foundry-age-pjnsi8u.gamma.site/)
- **Video:** *(to be added — 8 min max per hackathon rules)*
- **Source code:** SPFx Mail Room (separate repo — private for the moment)

---

## What is SPFx Mail Room?

**AI-powered document classification in SharePoint and Teams.**

One app runs on **SharePoint pages** and **Teams** (desktop and mobile). Documents enter via the app, Power Automate (mailbox), or a scanner → **Incoming Documents library** → **Logic App + Azure AI Foundry agent** (Azure Search over clients and projects) → **Mail Room list** with AI prefill → **user validation** (classification, optional deadlines, final validation) → document filed in the right SharePoint library folder.

- **The problem:** Manual classification is slow; no single place; workflow scattered; repeated setup per department.
- **The solution:** One generic app — Client list, Project list, Mail Room list, Incoming Documents library, all **autoprovisioned** on deploy. Multiple entry points (app, email, scanner), one pipeline. **Group workflow** (first verification → deadline step → final validation). **Deadlines and reminders** with mailbox sync. Map "Client" and "Project" to your domain (Legal, HR, Marketing, etc.) — deploy once, use everywhere.
- **In short:** AI suggests, human validates — one app, many deployments.

**Categories:** Best use of SharePoint in AI agents · Most innovative SPFx experience · Best mobile experience.

---

*By [Némoura](https://nemoura.com) · [Youssef El Garmit](https://www.linkedin.com/in/youssefelgarmit/)*
