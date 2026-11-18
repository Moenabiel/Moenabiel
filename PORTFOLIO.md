# Portfolio Overview

Every public project on this account, with what it is, what it proves, and its honest status.
Statuses are not marketing: **active** = shipping now · **research** = built, under validation,
no performance claims · **experimental** = working concept, not production · **sandbox** = studies.

Live site → [moenabiel.github.io](https://moenabiel.github.io/)

---

## 1. Websites & motion engineering

### quality-house-v4 — **active**
`astro` · `typescript` · `gsap` · `lenis` · `design-tokens` · `accessibility`

A portfolio-grade site for a Sudanese agricultural export house — the Consignment Dossier.
Paper-and-ink motion physics, page-turn transitions, a scroll-driven 360° gum-tree rotation,
a token law that keeps colour literals out of component files, and axe-clean accessibility
gates at two viewports.

**Proves:** scroll choreography, motion physics, design-system discipline, performance and
accessibility budgets, deployment pipelines (GitHub Pages + Actions).

---

## 2. Trading research & expert advisors

### smt-lab — **research**
`python` · `pandas` · `quantitative-finance` · `backtesting` · `walk-forward` · `streamlit`

Smart Money Concepts backtesting research lab: event-driven fill simulation (fills at the
real price, not the ideal one), walk-forward validation instead of single-window optimisation,
and a Streamlit desktop app for inspecting the results.

**Proves:** quantitative rigour — modelling fills honestly, rejecting overfitted parameter
sets, refusing to publish a performance number that was not validated.

### memo-smt-ea — **research**
`mql5` · `metatrader5` · `expert-advisor` · `trading` · `algorithmic-trading` · `finance`

MetaTrader 5 Expert Advisor for XAUUSD/XAGUSD Smart Money Technique divergence trading.
Nine analysis engines and six control managers behind one entry point, with twelve ordered
steps where every gate can veto a trade. Live trading ships **off** (`InpAllowLiveTrading =
false`); the strategy tester still runs signals, logs and setup history.

**Proves:** systems decomposition in a language most people write monoliths in, risk logic as
a first-class citizen, and research hygiene — walk-forward before any claim.

### SMT-Divergence-EA — **research**
`mql5` · `metatrader5` · `expert-advisor` · `trading` · `xauusd`

MetaTrader 5 expert advisor for SMT divergence entries on XAUUSD with disciplined risk sizing.

**Proves:** the same discipline applied to a tighter, single-setup mandate.

---

## 3. AI tooling research

### mimo-vscode — **research**
`vscode-extension` · `ide-tool` · `development` · `productivity` · `ai-tooling` · `mimo-code`

> **Attribution:** the extension source is **Xiaomi's MiMo Code** (MIT, © 2026 Xiaomi MiMo) —
> this repository is a snapshot mirror of the pre-release extension stage, kept for evaluation.
> **My work:** the feature-gap analysis, the evaluation notes, and the architecture diagram.

A competitive analysis of MiMo Code against **OpenHands, Cline, Aider, Continue, Mem0,
LangGraph, Browser Use, Crawl4AI, MCP Inspector and Open WebUI** — a feature-by-feature matrix
that separates what the tool genuinely does well (self-evolution via `/dream`, `/distill`,
`/evolve`; a judge/goal model; voice input; built-in skills) from where it is absent (IDE-first
agents, agent frameworks, browser automation, web crawling, MCP debugging, enterprise
readiness), ending in a prioritised "what to build next" list.

**Proves:** research method — competitor teardown with checked facts, a prioritised gap matrix
with impact ratings, and the judgment to know the difference between *using* a tool and
*studying* one.

---

## 4. Brand & design systems

### vintage-streetwear — **experimental**
`branding` · `web-design` · `static-site` · `marketing` · `design-system` · `responsive`

Brand identity and website build for VNTGE CULTURE: a seven-token design system (warm black,
gold, cream, one gray), two typefaces split by job — Montserrat for the brand voice, Space
Grotesk for reading — and a single-file static site with CSS-drawn product art, so the build
ships no raster images at all. A fixed translucent nav, a gold hairline kicker, and a
wholesale marquee carry the archival tone. Behind it sits a document pipeline that generates
the company profile PDF, analytics dashboard XLSX and pitch deck PPTX from the same brand
tokens.

The venture is pre-launch: the figures and retailer names inside the site are **illustrative
placeholder copy**, not results or partnerships.

**Proves:** identity systems, token-driven design, accessible responsive craft, and the
discipline to keep business material out of a public repository.

---

## 5. Tooling, ML & sandboxes

### fable5-pipeline — **experimental**
`machine-learning` · `quantization` · `python` · `ml-pipeline`

ML model quantization and conversion pipeline, documented with an ethics-first README that
states what the pipeline does not guarantee.

**Proves:** model-conversion tooling and honest documentation of its limits.

### motion-lab — **sandbox**
`animation` · `css` · `javascript` · `motion-design` · `experiments`

Easing studies, scroll-behaviour tests and reference shots in vanilla HTML/CSS/JS. Techniques
that prove out here graduate into real builds.

**Proves:** the habit of studying a technique in isolation before spending it in production.

---

## Skills demonstrated across the portfolio

| Skill | Where it shows |
|---|---|
| Scroll choreography & motion physics | quality-house-v4, motion-lab |
| Design tokens & systems | quality-house-v4, vintage-streetwear |
| Brand identity | vintage-streetwear |
| Accessibility & performance gates | quality-house-v4, vintage-streetwear |
| Quantitative modelling & honest backtesting | smt-lab |
| Expert-advisor architecture & risk control | memo-smt-ea, SMT-Divergence-EA |
| Competitive research & technical writing | mimo-vscode, all READMEs |
| AI-agent tooling evaluation | mimo-vscode |
| Document & office automation | vintage-streetwear, fable5-pipeline |
| Zero-leak engineering & release discipline | every public repo (Gitleaks tree + history gate) |
| CI/CD & static deployment | quality-house-v4, moenabiel.github.io |

## Portfolio-wide rules I hold to

1. **Nothing ships unscanned.** Every public repository passed a Gitleaks gate on both the
   working tree and the full git history before publish.
2. **No borrowed work presented as mine.** Where a repository contains third-party code, the
   README says so in the first screen and links the upstream.
3. **No claims without validation.** Research projects state explicitly what has *not* been
   proven yet.
4. **Mockups are labelled.** Concept copy in a brand site is marked illustrative, never
   presented as business results.
