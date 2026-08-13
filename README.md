# Skill-2-Work — India Skills Atlas

A free, filterable atlas of **156 micro-skills** for the Indian job market — how long each takes to reach job-ready, what it costs, how exposed it is to AI, how to prove you have it, and exactly where the jobs, apprenticeships and freelance work are.

**Live site:** https://prathit-mukesh.github.io/Skill-2-work/

## What's in it

| Tab | Contents |
|---|---|
| **Skills** | 156 micro-skills across 11 clusters, each with a plain-English explanation of what the work actually is, who it suits, and a ten-dimension aptitude profile. Filterable by cluster, AI exposure, time to job-ready, cost, the education you already have, and opportunity type (works abroad / freelance / high demand) |
| **Find my fit** | A 17-question aptitude and situation check that scores all 156 skills against your strengths, education, budget, timeline, working-conditions tolerance and appetite for risk, then returns your top ten paid roles, the cross-cutting foundations to build alongside them, and the ones blocked by exactly one thing. Runs entirely in the browser; nothing is transmitted |
| **Pathways** | Seven staged routes — no degree, Class 10/12, graduate, engineering graduate in a soft IT market, overseas, women re-entering work, and rural/agricultural |
| **Where to apply** | Verified job portals by segment, government channels, internships and apprenticeships with current stipends, freelance platforms with commission rates, gig platforms with realistic earnings, and free learning portals |
| **Proving skill** | The four kinds of proof ranked by what employers believe, how to verify a course before paying, credentials worth the money, and credentials to avoid |
| **Money & tax** | Payment rails for overseas income, FIRA/GST/44ADA compliance, and how to formalise a micro-business |
| **Scam safety** | The six live job-fraud patterns in India, employer verification, overseas recruitment law, and what to do after |
| **Sources** | What to verify before committing money, where the numbers are soft, and what changed since the source document |

## Data notes

- Built from *The Encyclopaedia of Skills: India's Skill Demand, Future Requirements and the AI Transition*.
- Figures verified against primary sources (PIB, MoSPI/PLFS, NCVET, DGT, NISM, MNRE, DGCA, company filings) in **August 2026**.
- Where sources conflict, both are shown rather than one being picked. Where a figure is a consulting or staffing-firm estimate rather than official statistics, it is labelled as such.
- **Always confirm fees, stipends and scheme status on the official portal before acting.** Government schemes change; several free offers referenced by other sites have quietly closed.

## Technical

Single self-contained HTML file. No build step, no dependencies, no external requests, no tracking, no cookies. Works offline. Light and dark themes. Mobile-first.

```
index.html    the entire site
og.png        social preview image
.nojekyll     tells GitHub Pages to serve files as-is
```

## Publishing this yourself

**GitHub Pages** — create a public repository, upload these files to the root of the `main` branch, then go to *Settings → Pages*, set **Source: Deploy from a branch**, **Branch: main / (root)**, and save. The site appears at `https://<username>.github.io/<repo>/` within a couple of minutes.

**Any static host** — Netlify, Cloudflare Pages, Vercel, or plain web hosting all work: upload the folder as-is. There is nothing to build.

## Licence

Content is provided for public benefit. Reuse and adapt it freely — a link back is appreciated. No warranty; verify anything you're about to spend money on.
