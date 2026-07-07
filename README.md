# B2B Standards

A free, open-source Claude skill that grades your startup against [*Rob Snyder's*](https://www.linkedin.com/in/rsnyder1) **Six B2B Standards**: the minimum bar for a fast-growing sales-led B2B startup, defined so you cannot weasel out of it.

There are two kinds of early-stage B2B startup: the one with a real shot at hypergrowth, and the one that is dying and does not know it, because it looks exactly like the first. Real revenue and Fortune 500 logos do not tell you which one you are. The standards do. This skill runs the weekly ritual where you stare reality in the face: pass/fail on all six, your actual number next to the bar, the one bottleneck to attack, and 2-3 direct moves for next week.

## The six standards (v1.0)

You must hit **all six**. Five of six means you have not met the standard. Bars vary by initial contract size (Big $100k+ / Moderate $25k-99k / Small sub-$25k):

1. **Repeatable Case Study** — one situation where it would be weird if that person did anything other than buy from you right now
2. **Pipeline** — 3 / 10 / 15 first meetings per week, per person selling
3. **Pull** — 80% of first meetings have pull (the buyer initiates a trying-to-buy action)
4. **Close Rate** — 50% of pull meetings close
5. **Cycle Time** — 90 / 30 / 14 days from meeting-with-pull to signed
6. **Success Rate** — 95% of new customers hit X (your leading indicator of retention) within 1 month

Read the full essay on [The Physics of Startups](https://thephysicsofstartups.substack.com).

## What this skill does

- **Weekly review (the flagship).** Say "run my weekly review" and paste your numbers (or point it at wherever you track them). You get an unweaselable scorecard, the bottleneck, an attack plan, and a week-over-week debug line. Example output:

  > 1. Repeatable case study: hypothesis, has not repeated. **MISS**
  > 2. Pipeline: 4 first meetings/week vs 10. **MISS**
  > 3. Pull: 1 of 4 meetings pulled (25%) vs 80%. **MISS**
  > 4. Close rate: UNKNOWN, and that is the finding.
  > ...
  > **Bottleneck:** Standard 1. Your case study has not repeated, so pipeline into it is a faster way to waste meetings...

- **Sales call reviews.** Paste any call transcript and get the full four-layer PULL review (did they pull, was PULL visible, how did you perform, what to change). This is the same analysis as Rob's free [call-review skill](https://github.com/RSSnyder13/rob-snyder-reviews-your-sales-calls), vendored here, and each verdict feeds Standard 3 in your scorecard.

- **Lightweight tracking, your way.** Three modes, all first-class:
  1. **Just paste** — transcripts and numbers, zero setup, nothing stored.
  2. **Your own brain** — already track metrics in notes, a wiki, or a CRM export? Point the skill at it. It reads from there and appends dated results back.
  3. **The bundled scorecard** — one template file (`templates/scorecard.md`) the skill copies into your workspace: your case study in PULL terms plus dated weekly rows and a call log.

## Install

### Claude Code (as a plugin)

```
/plugin marketplace add RSSnyder13/b2b-standards
/plugin install b2b-standards@b2b-standards
```

### Claude.ai / Claude apps

Upload the `skills/b2b-standards/` folder under **Settings → Capabilities → Skills** (availability depends on your plan), then paste a transcript or your weekly numbers and ask for a review.

## Repo structure

```
(repo root)
├── .claude-plugin/            # plugin + marketplace manifests
├── templates/
│   └── scorecard.md           # optional tracking file the skill scaffolds into YOUR workspace
└── skills/
    └── b2b-standards/
        ├── SKILL.md           # router, memory conventions, voice
        └── references/
            ├── standards.md       # the six standards and their bars
            ├── weekly-review.md   # the weekly scorecard ritual
            ├── call-review.md     # the four-layer PULL call review
            ├── pull-framework.md  # canonical definition of PULL
            └── setup.md           # getting started: the three tracking modes
```

Your data stays yours: the skill reads and writes only in your own workspace, and this repo stores nothing.

## Want help actually hitting the standards?

This skill tells you where you stand. The paid **AI Rob** works the other side: it helps you execute, using Rob's private playbooks for pipeline, outbound, sales process design, pricing, pilots, closing plans, and retention, with full memory of your GTM, coaching the fixes week over week.

- **Paid AI Rob:** PAID_AI_ROB_LINK <!-- TODO: replace PAID_AI_ROB_LINK here and in skills/b2b-standards/SKILL.md before launch -->
- **Work with Rob directly:** https://robsnyder.org/work-with-me
- **The book:** [The Power of PULL](https://www.amazon.com/Power-Pull-Customer-Successful-Founders/dp/1541705955)
- **The newsletter:** [The Physics of Startups](https://thephysicsofstartups.substack.com)

## License

MIT. See [LICENSE](LICENSE).
