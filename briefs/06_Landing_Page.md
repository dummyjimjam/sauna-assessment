# Part 6: Landing Page
**Vertical:** Game Producer
**Assessment:** Sauna AI Ops Intern — Summer 2026

## Task

Build a single HTML landing page for Sauna targeting Game Producers. Built in Cursor using the design reference. This is a real candidate to go live as a programmatic SEO page.

### Content Requirements

**Opening (Google snippet)**
2–3 sentence direct answer to: *"What is Sauna and why does a Game Producer need it?"*
This is what appears in search results — make it count.

**Use Cases**
5–7 specific use cases with short, concrete descriptions. Pull from the automation opportunities in the ICP research. Examples:
- Cross-module duplicate ticket detection
- Multi-audience weekly status report
- Milestone health check
- Publisher milestone doc assembly
- GDD-to-Jira bulk ticket creation

**Demo**
At least one real workflow or Application demo — screenshot, GIF, or embedded sample. The Cross-Module Milestone Health Dashboard is the flagship demo asset.

**CTA**
Clear sign-up call to action.

### Design Standards (match reference exactly)

Reference page: `https://app.sauna.ai/share/sauna-vc-landing-dx4pjkbip7rm`

| Element | Spec |
|---------|------|
| **CSS** | Tailwind CSS CDN |
| **Fonts** | Google Sans Flex + Inter |
| **Background** | `#fafaf9` / `#faf9f7` warm tones |
| **Body text** | `#171814` |
| **CTAs** | `#93efa4` mint green, `#003116` forest green text |
| **Dark cards** | `#0a0a0a` |
| **Section corners** | `rounded-b-[40px]` alternating warm backgrounds |
| **Feature cards** | `rounded-[32px] p-8` |
| **Navigation** | Dark glass pill, `backdrop-blur-[15px] bg-[rgba(60,60,60,0.6)]` |
| **No** | Gradients on content, decorative shapes, AI-sounding copy |

**Tone:** Product page built by an engineer, not a marketer. Think specific, not salesy.

### Rules
- Built in Cursor, not inside Sauna
- Single self-contained HTML file
- Match the reference design closely — color tokens, section pattern, card style
- No AI-sounding copy (banned phrases apply: "game-changer", "unlock", "supercharge", etc.)
- Production-quality: if we deployed this tomorrow, it would be live-ready

---

## Inputs

- `documents/Assessment/deliverables/01_ICP_Research_Game_Producer.md` — Automation Opportunities section (Sub-section 03) provides the use cases to feature on the page. Pull the top 5–7 directly.
- `documents/Assessment/deliverables/03_application_notes.md` — The Cross-Module Milestone Health Dashboard is the flagship demo asset. Use the application description and demo walkthrough for the Demo section of the landing page.
- `documents/Assessment/deliverables/04_Video_Scripts.md` — (Optional) Hook lines from the video scripts can be repurposed as section headlines or feature card copy.

---

## Outputs

- `documents/Assessment/landing_page/game-producer.html` — Single self-contained HTML file, production-ready.

---

## Status
⬜ Pending
