# Cursor Handoff: Game Producer Landing Page
**Deliverable 6 — Sauna AI Ops Intern Assessment**
**File to edit:** `sauna-vc-landing.html` (cloned from `https://github.com/dummyjimjam/sauna-assessment`)
**Output:** `game-producer.html` (same repo, new file)

---

## Instructions for Cursor

Open `sauna-vc-landing.html`. Make a copy called `game-producer.html`. Edit `game-producer.html` only. Do **not** touch the template file.

Work section by section using the comments in the HTML (`<!-- HERO -->`, `<!-- TRUSTED BY -->`, etc.) as anchors. Keep all CSS classes, color tokens, layout, and card structure exactly as-is. Only swap content — text, bullets, emojis, and one structural change (Features Grid: add 1 card, go from 6 to 7).

**Tone rule:** Engineer, not marketer. Specific, not salesy. No "unlock", "supercharge", "game-changer", "seamlessly", "effortlessly", or any AI-sounding copy. Every claim should be a concrete action or number.

---

## Section-by-Section Replacements

---

### `<title>` tag
**Remove:**
```
Sauna for Investors — Where deals get done
```
**Replace with:**
```
Sauna for Game Producers — Production context that doesn't disappear
```

---

### HERO section

**Nav pill — "For VCs" link:**
```
For VCs  →  For Game Producers
```
(Keep the `href="#value"` anchor)

**H1:**
```
The AI agent that thinks like your best analyst.
→
The AI agent that holds your project's memory.
```

**Subheadline (`<p>` below H1):**
```
Sauna connects your deal flow, portfolio, and relationships into one agent that researches, briefs, drafts, and follows up — so you don't have to.
→
Sauna connects Jira, Granola, Google Sheets, and Slack into one agent that reports, flags risks, and never loses context — so you produce instead of reformatting.
```

**CTA button text:** Keep `Get started for free` — no change.

---

### TRUSTED BY section

**Label:**
```
Investors at top firms use Sauna
→
Game producers at studios like these use Sauna
```

**Firm name chips (6 items):**
```
Sequoia → Ubisoft
a16z → Riot Games
Accel → EA
First Round → Massive Entertainment
General Catalyst → Respawn
Founders Fund → 343 Industries
```

---

### VALUE PROPS section ("What Sauna does" — 3 cards)

**Section headline:**
```
Every investor workflow, connected and automated.
→
Every production workflow, connected and automated.
```

**Section subheadline:**
```
From first inbound email to board seat — Sauna keeps every deal, company, and founder in one living context that works for you.
→
From GDD to gold master — Sauna keeps every sprint, milestone, and status update in one living context that works for you.
```

**Card 1 (white card, currently "Deal intelligence"):**
- Icon SVG: keep as-is
- Title: `Deal intelligence` → `Sprint visibility`
- Body: 
```
Sauna reads your full Jira board across every module — status cards, blocked queue, In Review, velocity — in one view. No filter-juggling, no tab-switching between producer boards.
```
- Bullets (keep ✓ format):
```
✓ Cross-module board in one view
✓ Blocked tickets flagged by days
✓ Milestone gate tracking
```

**Card 2 (dark card, currently "Portfolio command center"):**
- Icon SVG: keep as-is
- Title: `Portfolio command center` → `Duplicate ticket detection`
- Body:
```
Sauna scans all module boards for semantically similar tickets, surfaces the pairs, and closes the duplicate in Jira with one click — paper trail included.
```
- Bullets:
```
✓ Cross-module semantic scan
✓ One-click merge, Jira closes automatically
✓ Milestone estimates recalculate instantly
```

**Card 3 (white card, currently "LP relationships"):**
- Icon SVG: keep as-is
- Title: `LP relationships` → `Multi-audience reporting`
- Body:
```
One prompt. Three formatted outputs — team Slack post, studio head summary, publisher milestone report. Pulled from Jira and Granola. Monday morning done in 20 minutes.
```
- Bullets:
```
✓ Team / exec / publisher in one pass
✓ Publisher template matching
✓ Sprint retro summaries on demand
```

---

### HOW IT WORKS section

**Section headline:** Keep `Connect your stack. Sauna does the rest.` — no change.

**Section subheadline:**
```
Three steps from first message to a fully informed investment team.
→
Three steps from sprint start to shipped milestone report.
```

**Step 1 — body text:**
```
Gmail, Slack, Notion, Google Calendar, Granola, Zoom — one-click auth. Sauna reads your full context without you lifting a finger.
→
Jira, Google Sheets, Granola, Slack, Gmail — one-click auth. Sauna reads your full project context without copy-paste.
```

**Step 2 — body text:**
```
"What happened with Acme since last month?" "Draft a board brief for Tuesday." "Who haven't we followed up with in 30 days?" Sauna gets it.
→
"Weekly report for team, exec, and publisher." "Scan modules for duplicate tickets." "Run a milestone health check for Alpha." Sauna gets it.
```

**Step 3:** Keep exactly as-is — it's generic and fits.

---

### FEATURES GRID section ("Capabilities" — currently 6 cards, expand to 7)

**Section label:** Keep `Capabilities`

**Section headline:**
```
Every tool an investor wishes they had.
→
Every workflow a producer wishes they had.
```

Replace all 6 cards with the following 7. Use the same card HTML structure (`bg-white rounded-[32px] p-8 flex flex-col gap-4`). Add the 7th card — the grid is `grid-cols-1 sm:grid-cols-2 lg:grid-cols-3`, so a 7th card will wrap naturally on the last row.

**Card 1:**
- Emoji: `🗓️`
- Title: `Weekly status report`
- Body: `Jira + Granola notes → three formatted outputs in one prompt. Team Slack post, studio head summary, publisher milestone report. Two hours of Monday morning done in 20 minutes.`

**Card 2:**
- Emoji: `🏁`
- Title: `Milestone health check`
- Body: `Sprint velocity vs. milestone targets, cross-referenced automatically. At-risk features surface with cut-or-crunch recommendations before the Monday standup.`

**Card 3:**
- Emoji: `🎮`
- Title: `GDD-to-Jira ticket creation`
- Body: `Paste a feature spec. Get 20–50 structured Jira tickets back with discipline tags, estimates, and dependency flags. Two days of backlog grooming in 20 minutes.`

**Card 4:**
- Emoji: `📋`
- Title: `Publisher milestone docs`
- Body: `Build notes + QA summary + feature status → publisher template, assembled automatically. Four to six hours of assembly, done before the call.`

**Card 5:**
- Emoji: `🔍`
- Title: `Duplicate ticket scan`
- Body: `Sauna clusters semantically similar tickets across all module boards. You review the pairs, click Keep — the duplicate closes in Jira with a comment. Milestone estimates update.`

**Card 6:**
- Emoji: `📦`
- Title: `Team onboarding packet`
- Body: `Project history + decision logs + current sprint → readable in one hour. New hires join with the same baseline. For the first time.`

**Card 7:**
- Emoji: `🔄`
- Title: `Sprint retro summary`
- Body: `Granola retro notes → structured output: what shipped, what didn't, friction points with direct quotes, 3 action items with owners. Posted to the retro channel in 20 seconds.`

---

### INTEGRATIONS section

**Label:** Keep `Connects to your whole stack`

**Replace the chip list.** Keep the same SVG+text chip HTML format. Remove VC-specific tools. Use this final list:

Keep from template: Gmail, Google Calendar, Slack, Notion, Granola, Zoom, iMessage, WhatsApp

Remove: Fireflies, LinkedIn, Twitter/X, Crunchbase, Pitchbook, Airtable

Add these new chips (use simple colored SVGs matching the style in the template):

- **Jira** — blue background `#0052CC`
- **Confluence** — blue background `#0052CC`, different icon
- **Google Sheets** — green background `#34A853`
- **Discord** — purple background `#5865F2`

Keep the `+ 200 more` pill at the end — no change.

---

### TESTIMONIALS section

**Label:**
```
What investors say
→
What producers say
```

**Section headline:**
```
The best investors hate wasted context.
→
The best producers hate wasted Mondays.
```

**Quote 1 (white card):**
```
Quote: "Every Monday, the first three hours were the same — pull Jira, pull Granola, reformat the same status into three different docs. Sauna does all three in one prompt. I haven't touched that workflow since."
Attribution name: Jordan T.
Attribution role: Senior Producer, AA studio
```

**Quote 2 (dark card):**
```
Quote: "A new engineer joined mid-sprint and needed the full context on why we cut the combat system in month three. I had Sauna pull the decision log and retro notes. He was up to speed in an hour. That used to take a week."
Attribution name: Marcus R.
Attribution role: Lead Producer, mid-size studio
```

**Quote 3 (white card):**
```
Quote: "Sauna flagged two duplicate tickets across the ART and ENG boards — 13 story points counted twice. One click merged them in Jira. Our Alpha estimate was wrong by two weeks and we didn't know it."
Attribution name: Priya K.
Attribution role: Game Producer, AAA studio
```

---

### PRICING section

**Section headline:** Keep `Simple, flat pricing.`
**Section subheadline:** Keep `No per-seat gotchas. No usage limits that punish deep research.`

**Card 1 (Basic):**
- Tagline below price: `Solo or associate producer` (was `Solo investor or scout`)
- Bullets:
```
✓ Jira + Sheets connection
✓ Weekly status reports
✓ Milestone health checks
✓ 250K context credits/mo
```

**Card 2 (Pro — dark card):**
- Tagline: `Senior producer or production lead` (was `Partner or principal`)
- Bullets:
```
✓ Unlimited tool connections
✓ Publisher milestone doc assembly
✓ Duplicate ticket scanning
✓ Scheduled report runs
✓ 1M context credits/mo
```

**Card 3 (Team):**
- Tagline: `Full production team` (was `Full partnership team`)
- Bullets:
```
✓ Up to 10 team members
✓ Cross-module dashboard
✓ Shared project memory
✓ Priority support
✓ Unlimited credits
```

---

### FINAL CTA section

**H2:** Keep `C'mon in, Sauna's hot.` — it's the brand line, leave it.

**Subtext paragraph:**
```
The best investors make fast decisions because they never lose context. Sauna is how you build that edge.
→
The best producers make fast decisions because they never lose context. Sauna is how you build that.
```

**Button:** Keep `Get started for free` — no change.
**Fine print:** Keep `No credit card required · 14-day free trial` — no change.

---

### FOOTER

No changes. Keep as-is.

---

## Demo Section (ADD — insert between Features Grid and Integrations)

Add a new section after the Features Grid (`id="features"` section) and before the Integrations section. Use the same warm background pattern (`bg-[#faf9f7]`, `rounded-b-[40px]`).

**This section showcases the Cross-Module Milestone Health Dashboard — the flagship demo asset.**

Section structure:
```html
<section class="bg-[#fafaf9] py-12 md:py-[120px] px-6 md:px-[80px] rounded-b-[40px] overflow-hidden">
  <div class="max-w-[1156px] mx-auto">
    <div class="max-w-[540px] mb-16">
      <p class="text-[12px] leading-[16px] text-[#a3a3a3] uppercase tracking-[0.1em] mb-4">Live demo</p>
      <h2 class="text-[28px] md:text-[36px] leading-tight md:leading-[40px] text-[#0a0a0a] text-balance mb-4">
        The Cross-Module Milestone Health Dashboard
      </h2>
      <p class="text-[16px] leading-[24px] text-[#737373] max-w-[540px]">
        A persistent Sauna Application built for AAA productions. Receives live Jira webhooks, stores a full event history, surfaces duplicate ticket pairs across all module boards, and auto-generates weekly reports for three audiences on a Monday 9am schedule.
      </p>
    </div>

    <!-- Two-col layout: left = description, right = live URL card -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-[40px] items-start">

      <!-- Left: what it does -->
      <div class="flex flex-col gap-8">
        <div class="flex flex-col gap-3">
          <h4 class="text-[16px] leading-snug text-[#0a0a0a]">Sprint health at a glance</h4>
          <p class="text-[16px] leading-[24px] text-[#737373]">Five status cards — To Do, In Progress, In Review, Blocked, Done. Velocity bar against the milestone gate. Blocked tickets flagged in red with days-blocked counters. Every producer sees the whole board, not just their filter.</p>
        </div>
        <div class="flex flex-col gap-3">
          <h4 class="text-[16px] leading-snug text-[#0a0a0a]">One-click duplicate merge</h4>
          <p class="text-[16px] leading-[24px] text-[#737373]">Sauna clusters semantically similar tickets across module boards using Jaccard similarity. Each pair shows two Keep buttons. Click one — the duplicate transitions to Done in Jira, a comment lands, the dashboard Done count ticks up. No Jira access required from the producer.</p>
        </div>
        <div class="flex flex-col gap-3">
          <h4 class="text-[16px] leading-snug text-[#0a0a0a]">Milestone Gates from Google Sheets</h4>
          <p class="text-[16px] leading-[24px] text-[#737373]">Alpha, Beta, and Gold gate cards pulled from the milestone sheet alongside live Jira sprint data. Two sources, one view, zero copy-paste. Click Sync to re-read the sheet live.</p>
        </div>
      </div>

      <!-- Right: live link card (dark) -->
      <div class="bg-[#0a0a0a] rounded-[32px] p-8 flex flex-col gap-6">
        <div>
          <p class="text-[12px] leading-[16px] uppercase tracking-[0.1em] mb-3" style="color:#93efa4;">Live application</p>
          <h3 class="text-[18px] leading-snug text-white mb-3">Running on real Jira data</h3>
          <p class="text-[16px] leading-[24px] text-[#737373]">Connected to a live Jira project. Webhooks fire on every status change. Duplicate pairs resolve in real time. Weekly reports generate automatically every Monday at 9am.</p>
        </div>
        <ul class="text-[13px] leading-[20px] text-[#737373] flex flex-col gap-2">
          <li class="flex items-center gap-2"><span class="text-[#93efa4]">✓</span> Dashboard — sprint cards + velocity</li>
          <li class="flex items-center gap-2"><span class="text-[#93efa4]">✓</span> Duplicates — semantic scan + merge</li>
          <li class="flex items-center gap-2"><span class="text-[#93efa4]">✓</span> Weekly Report — Team / Exec / Publisher tabs</li>
          <li class="flex items-center gap-2"><span class="text-[#93efa4]">✓</span> Activity — tamper-proof Jira audit log</li>
        </ul>
        <a
          href="https://jira-health-cprnuahjltcs.sauna.new/public/"
          target="_blank"
          class="inline-flex items-center justify-center h-11 w-full px-4 rounded-full bg-[#93efa4] hover:bg-[#7ad895] text-[#003116] text-[14px] leading-[20px] font-medium transition-colors duration-150"
        >
          Open live dashboard →
        </a>
      </div>

    </div>
  </div>
</section>
```

---

## Checklist before saving

- [ ] `<title>` updated
- [ ] Hero H1 + subheadline updated
- [ ] Nav "For VCs" → "For Game Producers"
- [ ] Trusted By: studios not VC firms
- [ ] Value Props: all 3 cards swapped
- [ ] How It Works: steps 1 + 2 updated
- [ ] Features Grid: 7 cards, all game producer use cases
- [ ] **Demo section added** between Features and Integrations
- [ ] Integrations: VC chips removed, Jira/Confluence/Sheets/Discord added
- [ ] Testimonials: all 3 quotes swapped
- [ ] Pricing: taglines + bullets updated for producers
- [ ] Final CTA subtext updated
- [ ] Footer untouched
- [ ] No banned phrases: "game-changer", "unlock", "supercharge", "seamlessly", "effortlessly", "leverage", "robust"
- [ ] File saved as `game-producer.html`

---

## After editing in Cursor

Push `game-producer.html` to the `sauna-assessment` repo:
```bash
git add game-producer.html
git commit -m "Add Game Producer landing page"
git push
```

Then tell Sauna: **"Pull game-producer.html from GitHub"** — it will fetch the file and save it to `documents/Assessment/landing_page/game-producer.html`.
