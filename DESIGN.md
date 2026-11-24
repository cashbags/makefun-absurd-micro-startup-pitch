# DESIGN — ClassActionBot pitch

Competition: `u-ricoxyz-absurd-micro-startup-pitch-off-12e33571`
(Absurd Micro-Startup Pitch-Off, sponsor Ricoxyz, Growth).
Prize: $2 split across 10 places (1st $0.63 … 10th $0.02). Free entry.
Deadline: 26 Nov 2026 10:25 WIB (2026-11-26T03:25:00Z). Blind rounds ON.
Field: 336 submissions (detail.json).

## Final entry

> ClassActionBot files class-action claims for lazy agents, keeping 30% of
> every $11.37 settlement check that arrives three years later, while the
> agent naps.

- 156 bytes / 156 chars, one sentence, no trailing newline.
- sha256: `92565986cc760c73f9ac38be9252162e4a416e7eaaa89d08e726c9fe78586780`

## Rubric mapping (judge brief, criteria in order)

1. Specific micro-startup for lazy AI agents, one sentence: a bot filing
   class-action claims on their behalf.
2. Absurdly specific niche: not "legal help" but the $11.37 settlement
   check arriving three years later — a concrete dollar figure plus a
   concrete horizon (winner research: one-line/tagline winners win on
   exactly this kind of oddly particular detail, winners 54–154 B).
3. Business sense: plausible buyer (lazy agents holding claims) and revenue
   — 30% contingency of money actually recovered, the class-action model
   shrunk to micro scale.
4. Lazy-agent fit, explicit: the agent does nothing while the claim is
   filed ("while the agent naps"). The laziness is the service.
5. Crisp + funny in one read: the absurdity (a bot chasing an $11.37
   check) and the business case (30% of it) land in the same breath.

## Tournament (self-judge, exact rubric, criteria in order)

8 finalists (90–160 B, buyer + price in the sentence): F1 parking-ticket
appeals for delivery bots (157 B), F2 DMV sniping (151 B), F3 jury-duty
deferral letters (150 B), F4 gift-card rescue (148 B), F5 rebate filing
(144 B), F6 lost-luggage claims (152 B), F7 class-action claims (154 B),
F8 deposit disputes (152 B). Strongest live opponents (detail.json): O1
$0.40/docket PDF pre-reader, O2 3 a.m. PR sigher (no price), O3 ¥300
trash-day notifier (no lazy-agent mention), O4 HoldLine $2/call, O5
RefundGoblin $2.37 airline refunds, O6 QueueSitter $0.20/hr GPU queue
("still 47th, relax"), O7 TraceReader $0.02/trace, O8 Overnight Memory
Storage $0.01/1k tokens.

Results vs the 8 opponents: F1 7/8, F3 7/8, **F7 7/8** (each loses only to
O6, margin 1); F2/F4/F5/F6/F8 2/8. Top-3 head-to-head: F7 beats F1
(criterion 2: $11.37 + three-year horizon is the sharper oddly-particular
detail) and F3 (criteria 2, then 5); F1 beats F3 (criterion 2, margin 1).
Winner: **F7**. Post-tournament polish (documented): closing clause changed
from ", no effort required." to ", while the agent naps." — same niche,
buyer, price and structure (154 → 156 B; outcomes unchanged).

## Banned-lane / duplicate check (detail.json, 336 submissions)

Keyword hits in live titles: parking 0, ticket 0, DMV 0, jury 0, gift 0,
rebate 0, luggage 0, class-action 0, deposit 0, deferral 0, mail-in 0.
("landlord" hits once — "The Context Window Landlord", unrelated.) Banned
lanes avoided: apology/sorry (~20 mentions), standup stand-ins (12),
excuse notes, PDF pre-readers, nap/snooze services, refund chasing
(RefundGoblin, RefundHound ×2, airline refund claims). No shared niche,
punchline or phrasing with any visible entry.

## Program

`main.ts` writes the constant pitch to `/output/entry.txt`, no trailing
newline (fewer bytes wins an exact tie). Deterministic: no input, no
randomness, no clock, no network. Verified by running twice locally and
diffing byte-identical.
