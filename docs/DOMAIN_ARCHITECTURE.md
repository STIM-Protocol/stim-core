# STIM Project: Domain & Entity Architecture

**Date:** March 27, 2026
**Owner:** George Steward

---

## Two Entities, One Root

| Domain | Purpose | Audience | Tone |
|---|---|---|---|
| **stim.bio** | Open-source community hub. The living document. Links to GitHub, documentation, and the STIM Guard library. | Developers, researchers, alignment community, indie builders | Open, accessible, scientific, community-driven |
| **veraculum.ai** | Enterprise platform. Certification, orchestration, compliance dashboards, commercial API. | CISOs, CTOs, compliance teams, regulated industries, enterprise procurement | Professional, credible, governance-oriented |

The relationship: **stim.bio is the root system. veraculum.ai is the canopy. Both are alive.**

stim.bio grows the protocol in the open. veraculum.ai gives the ideas public life -- enterprise credibility, policy engagement, certification authority, and the commercial engine that funds the roots. Neither is secondary. They are two expressions of the same organism.

---

## stim.bio — Informational Hub & Community

### Site Structure
```
stim.bio/
├── / (Landing page)
│   ├── "Grounding Intelligence in Nature"
│   ├── One-paragraph STIM explanation
│   ├── CTA: GitHub / Documentation / Veraculum for Enterprise
│   └── Animated visualization of the three-loop architecture
│
├── /axioms (The Eight Truths of Nature)
│   ├── Interactive axiom explorer
│   ├── Axiom interaction matrix
│   └── Downloadable axiom packs
│
├── /how-it-works (Three-Loop Architecture)
│   ├── Entropy Check (with thermodynamic visualization)
│   ├── Mycelial Check (with network visualization)
│   ├── Security Check / MAIM Protocol
│   └── Recursive refinement flowchart
│
├── /science (Research & References)
│   ├── Link to arXiv paper
│   ├── Expert scrutiny panel (Leopold, Kimmerer, Meadows, etc.)
│   ├── Active inference / free energy principle explainer
│   └── Bibliography (30+ references)
│
├── /docs (STIM Guard Documentation)
│   ├── Quickstart (3-line usage example)
│   ├── API reference
│   ├── Integration guides (LangChain, CrewAI, OpenClaw, etc.)
│   ├── Axiom pack creation guide
│   └── Contributing guide
│
├── /github (Links to repositories)
│   ├── stim-guard (core library)
│   ├── stim-priors-core
│   ├── stim-priors-enterprise
│   ├── stim-priors-healthcare
│   ├── stim-priors-finance
│   └── stim-priors-urban
│
├── /community
│   ├── Discord link
│   ├── Office hours schedule
│   ├── Blog / changelog
│   └── "Good first issues"
│
└── /veraculum (Redirect / bridge)
    ├── "Need enterprise deployment?"
    └── Link to veraculum.ai
```

### Technical Stack (stim.bio)
- **Framework:** Static site (Astro or Next.js static export)
- **Hosting:** Cloudflare Pages (free, fast, global CDN)
- **Domain:** stim.bio (already owned)
- **Analytics:** Plausible or Fathom (privacy-respecting)
- **Content:** Markdown source files in the GitHub repo

---

## veraculum.ai — Enterprise Platform

### Site Structure
```
veraculum.ai/
├── / (Enterprise landing)
│   ├── "The Ecological Alignment Standard"
│   ├── Enterprise value proposition
│   ├── CTA: Request Demo / Contact Sales / Read White Paper
│   └── Trust signals (arXiv paper, pilot results, certifications)
│
├── /platform (STIM Orchestrator)
│   ├── Sidecar container architecture
│   ├── Multi-agent swarm governance
│   ├── Entropy monitoring & compute waste detection
│   ├── Agent isolation detection
│   └── Dynamic equilibrium enforcement
│
├── /compliance (STIM Compliance Dashboard)
│   ├── Real-time ecological alignment scoring
│   ├── Per-agent, per-loop metrics
│   ├── SOC 2 / ISO 27001 audit export
│   └── Alert system for axiom violations
│
├── /certification (STIM Certification Standard)
│   ├── Certification criteria (Layer 0 compliance)
│   ├── Audit process
│   ├── Certified systems directory
│   └── Apply for certification
│
├── /api (STIM as a Service)
│   ├── API documentation
│   ├── Pricing (per-check, volume discounts)
│   ├── Self-hosted option
│   └── Sandbox / playground
│
├── /case-studies
│   ├── Enterprise pilot results
│   ├── Before/after metrics (compute waste, coordination overhead)
│   └── Customer testimonials
│
├── /policy (MAIM & Governance)
│   ├── MAIM policy paper download
│   ├── Regulatory engagement (EU AI Act, NIST)
│   └── Briefing request form
│
├── /about
│   ├── The STIM story
│   ├── Team / contributors
│   ├── Advisory board
│   └── Press kit
│
└── /stim (Bridge to open source)
    ├── "STIM is open source"
    └── Link to stim.bio
```

### Technical Stack (veraculum.ai)
- **Framework:** Next.js (SSR for dynamic content, API routes for SaaS)
- **Hosting:** Vercel or AWS (for API endpoints)
- **Domain:** veraculum.ai (already owned)
- **Backend:** STIM Orchestrator API (to be built in Phase 3)
- **Auth:** Auth0 or Clerk (enterprise SSO)
- **Billing:** Stripe (usage-based per-check pricing)

---

## Revenue Model (veraculum.ai)

| Product | Pricing Model | Target |
|---|---|---|
| STIM Guard (open source) | Free (MIT) | Developers, researchers |
| STIM Orchestrator (enterprise) | Per-seat + usage | Mid-market and enterprise |
| STIM Compliance Dashboard | Per-seat subscription | Compliance teams |
| STIM Certification | One-time audit fee + annual renewal | AI system operators |
| STIM as a Service API | Per-constraint-check | Any developer at scale |
| STIM Priors Packs | Free (community) / Paid (enterprise) | Domain-specific users |
| Policy consulting | Retainer / project-based | Governments, NGOs |

---

## Brand Voice

### stim.bio
- Scientific but accessible
- "Here's how nature works. Here's how we encoded it."
- Community-first, open-source values
- Technical documentation with biological metaphors

### veraculum.ai
- Authoritative, governance-focused
- "The ecological alignment standard for enterprise AI."
- Credibility through academic grounding (arXiv paper, expert panel)
- Compliance language that procurement teams and CISOs understand

The name "Veraculum" evokes truth (Latin: verum) and verification. It signals: this is where AI alignment gets certified, audited, and proven.

---

## Immediate Actions

1. [ ] Set up stim.bio landing page (static, links to GitHub)
2. [ ] Create GitHub org: `stim-protocol`
3. [ ] Initialize repos: stim-guard, stim-priors-core, docs
4. [ ] Register veraculum.ai DNS (if not already pointed)
5. [ ] Draft veraculum.ai landing page copy
6. [ ] Cross-link the two domains

---

*The root system (stim.bio) feeds the canopy (veraculum.ai). Neither survives without the other.*
