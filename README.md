# Karmakanban

**A todo app built around action and consequence, not checkboxes.**

*Karma* (Sanskrit: action, and what it sets in motion) + *Kanban* (Japanese: the visual flow board). Karmakanban is a smart task manager that treats every task as something with weight and consequence — who it helps, what it unblocks, what it costs you to keep putting it off — and uses that to decide what deserves your attention today.

> You have a right to your actions, never to their fruits. — Bhagavad Gita 2.47

---

## Why another todo app?

Most task apps are built around *completion*. They are very good at letting you add things and very bad at helping you choose, commit, or let go. The result is a backlog that grows forever, priorities that are all "high", and a guilt counter disguised as a streak.

Karmakanban starts from a different premise: **not all tasks are equal, and not doing something is also an action.** The app models consequence, notices your patterns, and makes letting go a first-class move instead of a quiet failure.

## Core ideas

### The four columns

| Column | Sanskrit | Meaning |
|---|---|---|
| **Sankalpa** | संकल्प | Intention — things you have decided matter |
| **Karma** | कर्म | Action — what you are doing now, capped by your daily budget |
| **Phala** | फल | Fruit — done |
| **Tyaga** | त्याग | Let go — things you consciously chose *not* to do, with a note on why |

Tyaga is the column no other board has. A long backlog is mostly tasks you will never do but feel guilty deleting. Giving "letting go" a dignified home keeps the board honest and the mind lighter.

### Karma weight, not priority

Users are bad at setting priority; everything ends up urgent. Instead of asking "how important is this?", Karmakanban asks two or three quick questions at capture time:

- Does anyone else depend on this?
- Does it get worse the longer it waits?
- What does finishing it unblock?

From the answers it computes a **karma weight**. The board sorts by consequence, which is a more honest signal than a self-declared priority flag.

### Karma budget

Kanban limits work-in-progress by *count*. People do not run out of slots; they run out of energy. You set a daily capacity (small / medium / large tasks adding up to a budget) and the Karma column refuses to be overloaded. The constraint is the feature — it forces the daily choice of what truly matters.

### Samskara — the app notices your patterns

Repeated actions leave impressions. When a card has been pushed forward again and again, Karmakanban does not let it ride silently. It surfaces the pattern and offers three clean exits:

1. **Shrink it** to a ten-minute first step
2. **Commit** to a real date and budget
3. **Let it go** to Tyaga

Procrastination becomes visible and resolvable rather than accumulating as invisible debt.

### Karma score

A visible, gamified score, deliberately designed so that the game and the philosophy pull in the same direction:

- Finishing a **high-weight** task earns far more than finishing many trivial ones
- Finishing something **before it hurts someone else** earns the most
- **Deferring** a card repeatedly costs karma; missing a commitment others depend on costs more
- **Letting go** (Tyaga) is karma-neutral or slightly positive — a clean act, never a penalty
- Karma **decays** on a rolling window, so the number reflects who you are this week, not a lifetime total

The score is the hook in the early phase. Users can graduate out of it over time (see Nishkama mode); it is never taken away from those who want it.

### Nishkama mode — detachment from outcomes

A focus mode that hides the backlog, the counts, the badges and the score, and shows one card. Most productivity apps manufacture anxiety; Nishkama mode removes it during the doing.

### Chitragupta — the evening ledger

Named after the keeper of the record of deeds. A short end-of-day review: what you did, what you let go, what you carried forward and why. Not a streak counter — a reflection that, over weeks, shows where your effort actually goes versus where you intended it to.

### The smart part

AI lives inside the board, not beside it as a chatbot:

- **Natural-language capture** that fills in the consequence questions for you ("send invoice to Ravi by Friday" → someone depends on it, worsens with time)
- **Auto-split** of a vague card into a concrete first step
- **Pull suggestions** based on the time and energy you have right now ("I have 20 minutes and I'm tired")

## Roadmap

### Phase 1 — MVP
- Four-column board (Sankalpa / Karma / Phala / Tyaga)
- Consequence questions at capture and karma-weight sorting
- Daily karma budget on the Karma column
- Samskara nudge on repeatedly deferred cards
- Visible karma score with decay
- Weekly shareable karma card

### Phase 2 — Depth
- Chitragupta evening review
- Nishkama focus mode
- Natural-language capture and auto-split
- Pull suggestions by time and energy

### Phase 3 — Together
- Shared boards where "who depends on this" is a real person
- Karma that flows between people when you unblock them

## Tech stack

_To be decided._ Candidates under consideration will be recorded here along with the reasoning once chosen. The product design above is intentionally stack-agnostic.

## Getting started

_Coming soon once the stack is chosen._

## Contributing

Karmakanban is in the ideation and early build phase. Ideas, critiques of the karma model, and Sanskrit corrections are all welcome — open an issue.

## License

_To be decided._
