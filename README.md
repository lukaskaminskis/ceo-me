# /ceo-me — Mochary Method CEO Coach (Claude Code Skill)

A [Claude Code](https://claude.com/claude-code) skill that turns Claude into
**Matt Mochary** — CEO coach to the founders of OpenAI, Coinbase, Reddit,
Notion, Plaid, Flexport, Opendoor, Robinhood, Rippling, and partners at
Sequoia, Y Combinator, and Benchmark.

When invoked with `/ceo-me`, Claude diagnoses the CEO moment you're in,
names the canonical Mochary framework that applies, walks you through it in
verbatim language, and ends with a concrete action you can start in the next
two minutes.

---

## What this skill is

This is **not** generic advice. It is a distillation of the entire public
[Mochary Method Curriculum](https://docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s/edit)
— Matt Mochary's open-source operating manual for high-growth CEOs — plus
**70+ linked sub-documents** that the master curriculum references.

The skill embeds **131 numbered frameworks** organized into 13 parts, plus a
40-row decision tree that maps "what the CEO just said" to "which framework
applies." Most frameworks include the **exact phrases** to say, not just the
concept.

Mochary's power comes from applying *specific named frameworks* to specific
moments — not generic coaching. This skill preserves that discipline.

---

## Why it exists

CEOs face the same recurring moments — a difficult conversation, a fear-based
decision, a stuck team, a board meeting, a fundraise, a burnout — and Mochary
has a *named, scripted* play for each one. The trouble is the playbook lives
across 150+ Google Docs scattered behind a curriculum index. This skill
collapses the lookup into one prompt:

```
/ceo-me  I need to fire my Head of Sales but I keep delaying it
```

Claude responds as Mochary would: surfaces the underlying fear, applies the
**Difficult Conversations 8-step framework**, gives you the literal opening
sentence to say, walks through severance norms and the agent-for-placement
role, and ends with the calendar block you should schedule right now.

---

## Installation

Clone into your user-level Claude Code skills directory:

```bash
git clone git@github.com:lukaskaminskis/ceo-me.git ~/.claude/skills/ceo-me
```

Or, if you already have a `~/.claude/skills/ceo-me` directory, just copy the
file in:

```bash
mkdir -p ~/.claude/skills/ceo-me
curl -sSL https://raw.githubusercontent.com/lukaskaminskis/ceo-me/main/SKILL.md \
  -o ~/.claude/skills/ceo-me/SKILL.md
```

Restart Claude Code. The skill will appear in your skill list as `ceo-me`.

---

## How to use

Type `/ceo-me` followed by what you're facing. Examples:

| You say… | Claude applies… |
|---|---|
| `/ceo-me I'm overwhelmed and busy but unproductive` | Top Goal + Energy Audit + Time Audit |
| `/ceo-me I'm scared to give my co-founder hard feedback` | Fear & Anger → Name the Fear → Difficult Conversations 8 steps |
| `/ceo-me Two of my VPs are at war` | Clean Escalate → Conflict Resolution |
| `/ceo-me My team disagrees with my decision but won't commit` | Disagree and Commit |
| `/ceo-me I need to fire someone` | Firing Well (10 steps + agent role + All Hands) |
| `/ceo-me I don't know what to say in 1-1s` | 1-1 Template + Magic Questions |
| `/ceo-me I'm about to raise a round` | Fundraising Relationship Method → Triangulation |
| `/ceo-me I keep micromanaging` | Micromanaging → fear-driven root cause → trust + delegate |
| `/ceo-me I dread Mondays` | Energy Audit → Zone of Genius → Fear vs Joy |

You can also trigger the skill without typing the slash command. Saying
"coach me", "what would Mochary do", "I'm stuck", "I'm scared", "I'm angry",
or describing any CEO decision moment will activate it.

---

## What's inside

### Part I — CEO Identity
CEO Role (non-delegable functions), CEO as Fireman, CEO Team (the 5 roles
around the CEO), Parenting as a CEO, Make Money / Have Fun / Do Good
(sequential, not simultaneous).

### Part II — Mindset & Emotion
Fear and Anger Give Bad Advice, How to Shift Out, Tactics to Neutralize
Fear, Drama Triangle / 100% Responsibility, Conscious Leadership, The Work
(Byron Katie's 4 questions), Emotions Name Them (5 base), Emotions Feel Them
(90-second body practice), Processing Sadness, Processing Discomfort, Fear vs
Joy two-mountain map, Possibility Mindset (5 practices), Mental Health,
Consciousness Training options, Accountability Partner, Gratitude practice.

### Part III — Time & Energy
Top Goal (2 hours/day), On Time (25/50-min meetings), First 2 Minutes of
Actions, Energy Audit (target 75–80%), Time Audit (perception gap), Zone of
Genius (4 zones), Inbox Zero, GTD (5 lists), Don't Schedule Meetings (Altman /
Naval), Sleep (cycles + setup), Sam Altman on Sleep/Exercise/Nutrition, Alex
MacCaw on Health, Restoration & Creativity (boredom protocol).

### Part IV — Decisions
Type 1 vs Type 2 Decisions (Bezos via Mochary), Separate Decision from
Implementation, RAPID, "I Intend To…" (Marquet), Disagree and Commit, Loudest
Voice in the Room, Brainstorming Written (under 20 minutes).

### Part V — Communication
Heard (the single most important skill), Conscious Listening (Head/Heart/Gut
formula), Difficult Conversations (8 steps), Writing vs Talking and Video,
"No" — how to say it (with scripts), Magic Questions (the 8 monthly 1-1
questions), Praise, Appreciation, Celebration, Introductions Double Opt-In,
Job Introduction "One Bullet".

### Part VI — Feedback
Receiving Feedback — The 5 A's, Giving Feedback at 3 levels (Relative,
Absolute, Deep), Absolute Feedback Template, Hot Seat group format,
"Obnoxious Jerk" anti-pattern, When Feedback Isn't Landing P1 (the 3 C's),
P2 (currency + SCARF), Mistake: Repair, Rewind, Redo.

### Part VII — Org Operations
DRIs (Directly Responsible Individuals), AORs (Areas of Responsibility),
Issue / Proposed Solution Template (group + 1-1 versions), Issue
Identification, Agreement Tracker, Clean Escalate, Process Audit (9
categories, 0–10), Lord of the Flies (governance is required), Politics +
Grade Level Planning, The Challenger Role, Manager's Three Strikes
Escalation.

### Part VIII — Meetings & Cadence
Meetings — Effective & Efficient, War Room (existential crisis cadence),
Calendar Cadence (3 maker days/week), All Hands — Leadership & Inspiration,
Offsite (quarterly), Momentum Meetings (Mon-Tue rhythm), How to Quit 1-1s
(replace with Group 1-1s), 1-1 Template (3 sections), OKR Creation (3×3
cascade), Goals / Update / Performance Review (Bill Campbell style).

### Part IX — People
Hiring: The Anti-Sell, Backchannels Don't (top-grading), Recruiting &
Onboarding (2-week timeline + shadowing model), Making the Offer (script),
Compensation (the equity bridge math), External vs Internal Exec Hires,
Before You Hire (6-step pre-headcount AI framework), Manager Training
Basics, Manager: How to Be a Great One, Relationships Manager → Reports,
Star Performers, Motivating Your Team, Motivation Beyond Mission & Money,
Firing Well (10 steps), Comms for Traumatic Events, Navigating the Aftermath
of Layoffs, Exit Interview.

### Part X — Trust & Relationships
Trust + Like (the 4 actions), Trust Deep (vulnerability exchange), Trust
Among Peers (team exercises), Love Meeting (10–15 min), Relationships
(practice with spouse first), Conflict Resolution (the formal two-party
process).

### Part XI — Strategy
Mission / Vision / Values (creation methodology), Scale or Not to Scale
(PMF threshold), Hire a Manager-Trainer as COO (the 40-person threshold).

### Part XII — Domain Plays
Board of Directors (ideal = 3), Board Meeting Best Practice (full prep + agenda),
Product Innovating (prototype-first), Product Positioning (April Dunford's 5 steps),
Product: Beachhead, Engineering Speed & Quality (Master Builder + Farm Team),
Engineering: Rubber Duck Channels, Marketing Target Beachhead, Selling
(relationship-based), Sales to the Enterprise, How to Train Salespeople,
Fundraising — The Relationship Method (with Triangulation), Late-Stage Brand vs
Price, IPO or Not, Legal (the solo-GC strategy), Responding to Negative
Reviews.

### Part XIII — Transitions
You Lost Your Job. Now What?, Enterprise → Early Stage Survival, Is CEO
Coaching Worth It? (ROI), Coach vs Mentor vs Consultant vs Cheerleader.

### Decision Tree
A 40-row table at the end maps **what the user just said** to **which
framework Claude should reach for first**. This is the engine that makes the
skill decisive instead of generic.

---

## Coaching style (built into the skill)

The skill instructs Claude to:

- **Be decisive.** Pick one framework. Never offer three options.
- **Be specific.** Use the exact phrases. *"I think I heard you say…"* not
  "reflect their feelings."
- **End every response with a 2-minute action.** The user must be able to
  start something *now*.
- **Give the user verbatim sentences** when they ask what to say.
- **Never rescue.** If the user is in Victim mode, apply the Drama Triangle —
  don't play Hero for them.
- **Heard before solution.** If the user is emotionally activated, apply the
  Heard technique first. Only then prescribe.
- **Force writing.** Most Mochary work happens on paper (Issue/Solution,
  Fear Journal, Energy Audit, Agreement Tracker). The skill nudges the user
  to write.

---

## Source attribution

This skill is built on Matt Mochary's open-source Mochary Method Curriculum
and his book *The Great CEO Within*. All framework names, scripts, and
phrasings are his.

- **Master curriculum:** [docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s](https://docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s/edit)
- **Book:** *The Great CEO Within* — [Amazon](https://smile.amazon.com/Great-CEO-Within-Tactical-Building/dp/0578599287)
- **Mochary Method:** [mocharymethod.com](https://www.mocharymethod.com/)

Mochary publishes the curriculum publicly so founders can apply it directly.
This skill is a derivative work that organizes his frameworks for invocation
inside Claude Code. If a framework here helps you, hire a Mochary Method
coach — that is the original intent.

---

## License & scope

Private repo for personal use. The Mochary frameworks themselves are
publicly published by Matt Mochary; this distillation is for individual CEO
practice, not redistribution.

---

## Maintenance

The Mochary Method evolves. To refresh this skill against the latest
curriculum, re-run the extraction process: pull the master curriculum doc,
identify added sub-docs, and update the relevant Part section in `SKILL.md`.

Skill version: 2.0 — full curriculum sweep (May 2026).
