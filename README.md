# /ceo-me

A Claude Code skill that turns Claude into a Mochary-Method-style CEO coach.

> **Not affiliated** with Matt Mochary or the Mochary Method. Independent
> summary of his [publicly published curriculum](https://docs.google.com/document/d/18FiJbYn53fTtPmphfdCKT2TMWH-8Y2L-MLqDk-MFV4s/),
> built so anyone can practice the method between coaching sessions. For
> the real thing: buy [*The Great CEO Within*](https://smile.amazon.com/Great-CEO-Within-Tactical-Building/dp/0578599287)
> and hire a [Mochary Method coach](https://www.mocharymethod.com).

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
