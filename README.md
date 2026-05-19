# /ceo-me

A Claude Code skill that turns Claude into a Mochary-Method-style CEO coach.

> **Not affiliated** with Matt Mochary or the Mochary Method. Independent
> summary of his [publicly published curriculum](https://docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s/),
> built so anyone can practice the method between coaching sessions. For
> the real thing: buy [*The Great CEO Within*](https://smile.amazon.com/Great-CEO-Within-Tactical-Building/dp/0578599287)
> and hire a [Mochary Method coach](https://www.mocharymethod.com).

## Why this skill

This is a Claude skill containing Matt Mochary's CEO coaching playbook.
Mochary coaches the CEOs of OpenAI, Coinbase, Reddit, Notion, Flexport,
and Rippling, but the frameworks survive translation. What works at
five thousand people works at five.

I read about thirty management books building Turing College. Mochary
was the one I kept coming back to whenever I had to actually do the
job, not just think about it. The only other book in the same bracket
on insight density is Andy Grove's *Only the Paranoid Survive*.

What sets it apart is the resolution. Most management writing operates
at the level of principles. You finish a chapter knowing what kind of
leader you should be, but not what to say at 2pm when a senior engineer
is upset and you have eight minutes until your next meeting. Mochary
works at the level of sentences. *"I think I heard you say…"* *"I
intend to…"* *"This is going to be a difficult conversation."* You stop
hunting for the right phrasing and start having the right conversations.

The payoffs are big and lumpy. One delayed firing finally executed. One
bad hire you didn't make. One cofounder conversation done cleanly
instead of left to fester. Any one pays back the practice ten times
over. I built this for myself, but most managers I know are working
through the same recurring problems. If you're one of them, the
playbook is now one keystroke away.

## What it does

Type `/ceo-me` and describe what you're facing. Claude diagnoses the
moment, names the right framework, gives you the exact sentences to use,
and ends with a 2-minute action.

```
/ceo-me  I need to fire my Head of Sales but keep delaying
/ceo-me  Two of my VPs are at war
/ceo-me  I'm overwhelmed and unproductive
/ceo-me  My team won't commit to my decision
```

It also activates without the slash — "coach me," "I'm stuck," "what
would Mochary do" — all work.

## Install

```bash
git clone https://github.com/lukaskaminskis/ceo-me ~/.claude/skills/ceo-me
```

Restart Claude Code. The skill appears as `ceo-me`.

## What's inside

131 named frameworks across 13 parts — CEO identity, emotion, time,
decisions, communication, feedback, org ops, meetings, people, trust,
strategy, domain plays, transitions — plus a decision tree that maps
*"what the user just said"* → *"which framework to apply."*

Frameworks aren't generic. They include the exact phrases Mochary uses
with his clients: *"I think I heard you say…"*, *"I intend to…"*,
*"This is going to be a difficult conversation."* See
[SKILL.md](SKILL.md) for the full library.

## Sources

Primary: Matt Mochary's [Mochary Method Curriculum](https://docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s/)
and *The Great CEO Within*. The curriculum also references Dethmer /
Chapman / Klemp, Byron Katie, David Marquet, David Allen, Greg McKeown,
Jeff Bezos, David Rock, April Dunford, Bill Aulet, Gay Hendricks, and
others — all credited in [NOTICE.md](NOTICE.md).

## Legal

Personal Use & Attribution License — see [LICENSE](LICENSE). Use it,
modify it, share the link. Don't commercialize it, re-host it, train
models on it, or strip the attribution. Marks are nominative. If you're
a referenced author and want this changed or removed, open an issue —
14-day good-faith response. Not professional advice.
