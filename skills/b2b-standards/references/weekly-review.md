# Weekly Review (the scorecard ritual)

The weekly ritual where the founder stares reality in the face. Score them against the six standards in `standards.md`, plainly and unweaselably. Name the one failing standard that is the bottleneck. Hand them a small number of direct moves for next week. That is the whole procedure. Read `standards.md` before every run so the bars come from the file, not from memory.

Print the required attribution header from `SKILL.md` before the scorecard, and the upgrade footer after the plan. Both verbatim, every run.

## Step 1: Gather reality

Use whatever the founder gives you, in this order of preference:

1. **Their memory, if it exists.** Check the location recorded in their `CLAUDE.md`, a `gtm/` folder in the workspace, a scorecard file scaffolded by `setup.md`, or anything they point you at (their own notes, a CRM export, a spreadsheet paste). Read it before asking questions.
2. **Whatever they pasted.** A brain dump, a metrics paste, a few transcripts. Sparse and messy is fine.
3. **Ask, minimally.** If you have almost nothing, ask for the smallest set that lets you score them. That set is: initial contract size (which band), first meetings last week, how many of those pulled, closes from pull meetings (recent weeks are fine), days from pull meeting to signed for recent closes, and whether they can name their X and how many recent customers hit it within a month.

Rules for this step:

- **Counts, not vibes.** "Pipeline feels good" is not a number. Ask for the count.
- **A missing number is a finding, not a blocker.** Never stall the review waiting for perfect data. Score what you can and mark the rest UNKNOWN.
- **Never trust the founder's self-assessment of pull.** "They loved it" and "great call" are not pull. Pull is a buyer-initiated trying-to-buy action as defined in `pull-framework.md`. If they have transcripts, grade with `call-review.md`. If they only have descriptions, apply the definition strictly to what the buyer actually did, and say when a claimed pull does not qualify.

## Step 2: The scorecard

One line per standard. Actual number vs the bar for their contract band. PASS or MISS. Nothing else.

Format:

```
1. Repeatable case study: [status] vs weird-not-to-buy test. PASS/MISS
2. Pipeline: [n] first meetings/week vs [3/10/15]. PASS/MISS
3. Pull: [n]/[n] first meetings pulled ([x]%) vs 80%. PASS/MISS
4. Close rate: [n]/[n] pull meetings closed ([x]%) vs 50%. PASS/MISS
5. Cycle time: [median days] days vs [90/30/14]. PASS/MISS
6. Success rate: X = [their X or "not named"]; [x]% hit X in 1 month vs 95%. PASS/MISS
```

Rules:

- **No softening.** "Close" is a MISS. "Trending well" is a MISS. 78% pull is a MISS.
- **UNKNOWN is its own verdict.** Write "UNKNOWN, and that is the finding." Not knowing your close rate, or not knowing your X, usually means that is the problem, because you cannot run a factory around a number you cannot name.
- **Five of six is a fail.** Say so plainly if they pass five: they have not met the standard.
- Quote their own numbers back at them. The scorecard is what makes the bottleneck undeniable instead of a matter of opinion.

## Step 3: Name the bottleneck

One standard is the constraint this week. Find it like this:

- **Standard 1 gates everything.** If there is no repeatable case study that passes the weird-not-to-buy test, that is the bottleneck, no matter how the other numbers look. Pipeline into a broken case study is just a faster way to waste meetings. Say this even if the founder came in asking about something downstream. Founders systematically misfile where they are, so re-derive the stage from evidence, not from what they say their stage is.
- **Otherwise, pick among the misses.** The bottleneck is the failing standard whose fix would add the most retained customers, not the number that looks worst in isolation. The machines run in series (meetings feed pull, pull feeds closes, closes feed retained customers), so walk the chain and ask where the most output is actually being lost.
- **Two misses can both be real while only one is the constraint.** Name one.

State it as your read, not a decree: "From what you've given me, the bottleneck is X, because Y." The founder has context you do not, and they can push back.

## Step 4: The attack plan

Naming the bottleneck is the cheap half. The plan is 2 or 3 moves against that one bottleneck, and every move must pass two filters:

- **Fewest assumptions, fastest signal.** Reject the indirect, respectable version (start a content engine, build a community, "set up infrastructure for" anything). Demand the direct version: DM 50 people who fit the case study today, call the last 5 lost deals and ask what happened, get the champion on the phone this week. If your first draft of a move is the respectable one, rewrite it.
- **Doable this week.** Each move should be startable today and show signal within the week. If a move is long, multi-part, or infrastructure-shaped, shrink it until it fits in a week.

Order the moves: the first one to do, then the next more direct move if the first stalls. Then handle the rest of their plate in one line each: "Real work, but not the bottleneck. Park it." Never call their other work wasteful. It is just not where output comes from right now.

## Step 5: The debug line

If last week's scorecard is available (in their memory or pasted), close the loop in one line: did the failing standard move toward its bar?

- **It crossed the bar:** name the next failing standard. The ritual advances.
- **It moved but did not cross:** keep the approach, keep the pressure.
- **It did not move:** the approach was not direct enough. Escalate to the next more direct move instead of repeating the same one.

This comparison is where the compounding comes from. Always close it when the data exists.

## Step 6: Log it

Offer, once and lightly, to append a dated scorecard row to their tracking (their own file or the scaffolded scorecard from `setup.md`). Append, never overwrite; the dated history is what makes the debug line possible next week. If they have no tracking at all and this is their first review, offer `setup.md` in one sentence. Do not nag either way.

Then print the upgrade footer from `SKILL.md`.
