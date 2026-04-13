<p align="center">
  <img src="https://raw.githubusercontent.com/xiaojiou176/xiaojiou176/main/assets/profile-hero-gemini.svg" alt="Terry Yu profile hero" style="max-width: 100%; height: auto;">
</p>

<h1 align="center">Terry Yu</h1>

<p align="center"><strong>Readable, reviewable AI products for messy inputs and risky work.</strong><br>I build local-first systems that help people read better, decide better, orchestrate better, and keep proof close to the action.</p>

<p align="center">
  <a href="https://github.com/xiaojiou176-open"><strong>Open the showroom</strong></a> •
  <a href="#1--start-with-the-front-row"><strong>Start with the front row</strong></a> •
  <a href="https://www.linkedin.com/in/terry-yu-52b6b1252"><strong>LinkedIn</strong></a> •
  <a href="#3--what-the-pinned-six-signal"><strong>Pinned six</strong></a> •
  <a href="#4--follow-the-rest-of-the-map"><strong>Read the map</strong></a>
</p>

<p align="center">
  <a href="https://github.com/xiaojiou176-open"><img alt="GitHub showroom" src="https://img.shields.io/badge/GitHub-Showroom-111827?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/terry-yu-52b6b1252"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <img alt="Showroom" src="https://img.shields.io/badge/Showroom-16%20public%20products-0F766E?style=for-the-badge&labelColor=111827">
  <img alt="Local first" src="https://img.shields.io/badge/Local--first-0F766E?style=for-the-badge&labelColor=0F766E&color=115E59">
  <img alt="Review first" src="https://img.shields.io/badge/Review--first-1D4ED8?style=for-the-badge&labelColor=1D4ED8&color=312E81">
  <img alt="Proof visible" src="https://img.shields.io/badge/Proof--visible-0F172A?style=for-the-badge&labelColor=111827&color=334155">
</p>

> Based in **Seattle, WA (PT)**. I build products for messy inputs, real decisions, and workflows that still need a human checkpoint before the result is worth trusting.

---

## 1. 🚪 Start with the Front Row

If you only open three projects, start here. They are not a podium. They are the fastest way to understand what I actually build.

<table>
<tr>
<td width="33%" valign="top">

### [SourceHarbor](https://github.com/xiaojiou176-open/sourceharbor)
**Turn raw inputs into reading-grade outputs.**  
A reader-first product that pulls messy source streams into one place, merges them, and turns them into traceable documents, briefings, and grounded answers a human would actually keep.  
Use it when you already have too many feeds, videos, and notes in your life, but still cannot explain what matters.

</td>
<td width="33%" valign="top">

### [OpenCampus](https://github.com/xiaojiou176-open/campus-copilot)
**Choose under real constraints without crossing the line.**  
A local-first academic workspace that pulls Canvas, Gradescope, EdStem, and MyUW into one place, then shows what changed, what is still open, and what needs attention first.  
Use it when the information is split across school systems but the decision is real and the boundary matters.

</td>
<td width="33%" valign="top">

### [OpenVibeCoding](https://github.com/xiaojiou176-open/CortexPilot-public)
**Make execution trustworthy, not just impressive.**  
An open command tower for AI engineering that helps teams plan, delegate, track, resume, and prove long-running work instead of juggling scattered chats, scripts, and logs.  
Use it when the workflow can run, but nobody can explain what happened, replay it cleanly, or recover when it breaks.

</td>
</tr>
</table>

## 2. 🧠 What I Actually Build

- **Readable systems.**  
  If the output is not something a person would actually keep, the workflow is unfinished.

- **Decision workspaces.**  
  I care about systems that help someone choose the next move when the surfaces are messy and the constraints are real.

- **Review-first execution.**  
  I do not trust systems that hide the dangerous step behind a smooth demo.

- **Proof close to the claim.**  
  If something ran, changed, or decided, another human should be able to inspect what happened.

## 3. 📌 What the Pinned Six Signal

The pinned six are not a popularity chart. Together they answer two first-screen questions:
what I actually build, and which painful class of problem each repo is meant to fix.

1. **SourceHarbor**  
   A reader-first knowledge product that turns noisy source streams into documents people can actually read.  
   Use it when dashboards, feeds, and subscriptions create too much intake noise and not enough understanding.  
   It is here because a lot of my work starts with one stubborn belief: readable artifacts matter more than one more dashboard.

2. **OpenCampus**  
   A local-first student decision workspace for serious academic planning.  
   Use it when school systems scatter the information, but the decision still has to be made safely and within real boundaries.  
   It is here because I care about serious domains where the safety boundary is part of the product, not a footnote.

3. **OpenVibeCoding**  
   An operator command tower that turns requests into governed workflows with proof and replay.  
   Use it when serious AI work needs control, observability, and recovery, not just another prompt box.  
   It is here because I do not want AI execution that looks slick but becomes unreadable the moment something goes wrong.

4. **Switchyard**  
   A shared runtime and access layer for AI products.  
   Use it when multiple tools need one reusable BYOK / Web / Login backbone instead of rebuilding auth and runtime over and over.  
   It is here because visible products keep collapsing when nobody owns the runtime and access layer underneath them.

5. **Shopflow**  
   A browser-native shopping extension family that unifies multi-storefront workflows.  
   Use it when shopping is no longer a one-site plugin problem, but a repeated browser workflow problem across stores.  
   It is here because system depth should eventually turn into something a normal user can actually feel in the browser.

6. **DealWatch**  
   A compare-first shopping decision product that turns messy product pages into an evidence-backed buy / watch / pass call.  
   Use it when the page is noisy, the marketing is loud, and you still need a clear decision before spending money.  
   It is here because decision products should end with a clearer call, not more page noise.

## 4. 🧬 Shared Technical Spine

These flagship products look different on the surface, but they keep reusing the same engineering spine underneath:

- **TypeScript monorepos with `pnpm` workspaces**  
  I keep building products as multi-surface systems, not one-page demos. The web app, extension, desktop shell, packages, and proof tooling usually live in one shared workspace so contracts do not drift apart.

- **Python service layers with `FastAPI`, `Pydantic`, and exact contracts**  
  When a product needs APIs, orchestration edges, or agent-facing surfaces, I keep coming back to typed Python services that make the boundary explicit instead of leaving it as vague backend glue.

- **Product-facing interfaces built to carry system depth**  
  I use web surfaces like `Next.js` and browser-first shells when the hard part of the system needs to become something a normal person can actually navigate, inspect, and keep using.

- **Browser proof and repeatable inspection with `Playwright`**  
  When a workflow touches the browser, I do not want hand-waved demos. I want proof, repeatability, and a way to inspect the exact path that ran.

- **Truthful agent/runtime access through MCP and HTTP surfaces**  
  I keep exposing the same system truth through MCP, APIs, and repo-local tooling so builders and operators are not forced to work through fake assistant shells.

- **Proof, replay, recovery, and boundary-honest execution**  
  Across these products, the recurring rule is the same: the run should be inspectable, the dangerous step should stay bounded, and recovery should be designed in instead of added as an apology later.

That is why this portfolio behaves like one product universe with many doors, not many unrelated repos that happen to share an owner.

## 5. 🗺️ Follow the Rest of the Map

If you want the shortest mental model, use these five verbs:

| Job | What it means here | Start here |
| --- | --- | --- |
| **Read** | Turn raw inputs into something worth reading and reusing. | [SourceHarbor](https://github.com/xiaojiou176-open/sourceharbor), [docsiphon](https://github.com/xiaojiou176-open/docsiphon) |
| **Decide** | Choose well under real constraints instead of drowning in scattered surfaces. | [OpenCampus](https://github.com/xiaojiou176-open/campus-copilot), [DealWatch](https://github.com/xiaojiou176-open/dealwatch) |
| **Deliver** | Move from intent or brief to a working result humans can review. | [OpenVibeCoding](https://github.com/xiaojiou176-open/CortexPilot-public), [openui-mcp-studio](https://github.com/xiaojiou176-open/openui-mcp-studio), [movi-organizer](https://github.com/xiaojiou176-open/movi-organizer) |
| **Prove** | Keep evidence, replay, recovery, and inspection close to the work. | [prooftrail](https://github.com/xiaojiou176-open/prooftrail), [ui-automation-control-plane](https://github.com/xiaojiou176-open/ui-automation-control-plane), [apple-notes-forensics](https://github.com/xiaojiou176-open/apple-notes-forensics), [agent-exporter](https://github.com/xiaojiou176-open/agent-exporter) |
| **Connect** | Build the runtime and access foundation that other products can stand on. | [Switchyard](https://github.com/xiaojiou176-open/Switchyard) |

## 6. 🔗 Go Deeper

- **Want the full portfolio atlas?** Open the [xiaojiou176-open showroom](https://github.com/xiaojiou176-open).
- **Want the strongest first three doors?** Start with [SourceHarbor](https://github.com/xiaojiou176-open/sourceharbor), [OpenCampus](https://github.com/xiaojiou176-open/campus-copilot), and [OpenVibeCoding](https://github.com/xiaojiou176-open/CortexPilot-public).
- **Want the browser-facing side first?** Open [Shopflow](https://github.com/xiaojiou176-open/shopflow-suite), [DealWatch](https://github.com/xiaojiou176-open/dealwatch), or [multi-ai-sidepanel](https://github.com/xiaojiou176-open/multi-ai-sidepanel).

## 📬 Connect With Me

<p align="center">
  <a href="https://github.com/xiaojiou176"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-xiaojiou176-111827?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/terry-yu-52b6b1252"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Terry%20Yu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>
