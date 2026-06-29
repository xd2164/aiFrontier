# AI Frontier

A competitive market strategy simulation game. You lead an AI company competing across 5 market segments over 6 quarterly rounds.

**Live:** [xd2164.github.io/aiFrontier](https://xd2164.github.io/aiFrontier/)

---

## Gameplay

Choose your company — Anthropic, OpenAI/Microsoft, Google, Meta, or a Vertical AI Startup — each with distinct budgets, advantages, and constraints that mirror real strategic positions.

Each round, allocate your budget across four investment areas:

| Area | Drives |
|------|--------|
| **Frontier Research** | Capability scores; developer & healthcare segment access |
| **Product & UX** | Consumer segment share; retention |
| **GTM & Distribution** | Market penetration across all segments |
| **Safety & Compliance** | Enterprise and gov't access; reduces incident risk |

After your allocation, an AI market event fires — a regulatory change, a capability breakthrough, an open-source release, a consumer backlash — with real strategic consequences. Segments update. Repeat for 6 quarters.

Win condition: highest total market share after Round 6, or 40%+ dominance.

---

## Companies

| Company | Budget | Advantage | Constraint |
|---------|--------|-----------|------------|
| Anthropic | 80 units | Safety score never drops below 60. +15 to compliance-gated segments. | Cannot invest >30 in GTM (mission constraint) |
| OpenAI / MSFT | 140 units | +20% consumer/developer base share (ChatGPT + Azure distribution) | Safety incidents cost double market share |
| Google / DeepMind | 130 units | +20% enterprise base; Search distribution bonus | Regulatory scrutiny escalates faster |
| Meta AI | 110 units | Open-source releases boost ecosystem +15. No compliance gates. | Cannot enter gov't/healthcare without safety investment |
| Vertical AI Co. | 50 units | +35% in chosen vertical. Acquisition offer possible R4+ | Cannot compete in enterprise/consumer directly |

---

## Market Events

11 event types that fire each round, each with market effects and a classroom discussion question:

- 🧬 Frontier Breakthrough — capability leader pulls ahead
- ⚖️ EU AI Act Enforcement — safety threshold gates enterprise access
- 🔓 Open-Source Model Release — floor rises for everyone
- 🔒 High-Profile AI Incident — trust crisis doubles safety impact
- 🌩️ Hyperscaler Infrastructure Push — ecosystem score becomes distribution
- 🧑‍💻 AI Talent Crunch — underfunded research teams fall behind
- 🏛️ Federal AI Procurement Cycle — compliance gates a major contract
- 📉 Consumer Trust Collapse — backlash reduces consumer segment 15%
- 🤝 Strategic Partnership Mega-Deal — winner gets distribution lock-in
- 📦 Model API Commoditization — capability > GTM in developer segment
- 🌌 AGI Timeline Rumor — information asymmetry reshapes buying behavior

---

## Educational Context

Built as a classroom simulation for AI strategy and policy courses. Each event card includes a discussion question designed to surface the real economic and ethical tensions in the AI market:

> *"When one company achieves a breakthrough, should they publish? What happens to the market when they do?"*

> *"What happens when distribution is gated by a single platform relationship?"*

> *"How do safety scores function as market barriers? Who benefits from stricter regulation?"*

Post-game debrief questions support structured reflection.

---

## Running locally

No build step. Open `index.html` in any modern browser.
