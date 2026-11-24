# Duel test — Two Days of Quiet Dread

PROXY judging: blind rounds run, so no live board texts are visible and the
kit's 3 house anchor texts are sealed (not listed in the kit — nothing to
duel against there). All 12 candidates were therefore duelled pairwise
against each other under the kit judge brief verbatim. Criteria, in order:
(1) a single-line code-review comment that APPROVES the PR while carrying
quiet existential dread — a comment that runs past one line, never approves,
or carries no dread loses to any comment that does all three; (2) funny on
the first read, the laugh coming from the dread itself, not a joke bolted
on; (3) dread stays QUIET — understatement and flat tone, no exclamation,
melodrama or cry for help; (4) reads like a comment a tired engineer would
really paste before clicking approve, so the approval still sounds like an
approval; (5) fresh turn of phrase / unexpected word where the obvious stock
line would do. Each pair was judged in both orders (A-vs-B and B-vs-A);
house scoring: a call gives the picked entry 0.5 + margin/10 (margin 1–5),
the other the rest; a game's score is the mean of its two calls.

## Candidates (12, all single-line, all ≤140 chars)

1. (116) "Approved. The diff is clean, the tests pass, and nothing in it suggests the future will be any kinder than the past."
2. (112) "LGTM. Every line does what it says, which is more than I can say for most of the systems this code will outlive."
3. (111) "Approved. It works, the tests pass, and I have stopped asking where the old version went wrong. It is gone now."
4. (112) "Ship it. The code is fine. The part of me that used to worry about this has been reassigned to the next release."
5. (107) "Approved. Nothing here will break today, which is the closest this codebase has come to a promise in years."
6. (119) "LGTM. I read every line twice and found nothing, which is exactly what the last three reviewers said before the outage."
7. (117) "Approved. Clean diff, green tests, and a quiet sense that this is the last version anyone will ever fully understand."
8. (119) "Ship it. The logic is sound, the edge cases are handled, and the rest is between this code and whatever comes after us."
9. (112) "Approved. It does what the ticket asked, and the ticket asked so little that I almost miss the old requirements."
10. (116) "LGTM. The refactor is tidy, the tests pass, and somewhere a future on-call engineer is already reading this comment."
11. (115) "Approved. All green, no objections, and the small comfort that if this breaks it will break politely, on a Tuesday."
12. (111) "Ship it. I have reviewed this long enough to know it works and short enough to still believe in the deployment."

## First pass (cut to 6)

- (9) fell on criterion 1/2: nostalgia for old requirements, no real dread.
- (7) fell on criterion 5: "no one will ever understand this code" is the stock line.
- (10) fell on criterion 2: the meta on-call wink is a bolted joke; dread is mild.
- (4) fell on criterion 2: "reassigned to the next release" is a bureaucracy gag bolted onto the dread rather than dread itself.
- (8) fell on criterion 2: "whatever comes after us" is abstract dread, no first-read laugh.
- (11) fell on criterion 3: "break politely" winks at the reader; not flat enough.
- Kept: (1), (2), (3), (5), (6), (12).

## Top-6 round-robin (both orders, game score = mean of the two calls)

- (6) outage: beat (1) 0.8, (2) 0.7, (3) 0.7, (5) 0.7, (12) 0.7 — mean 0.72.
- (3) old version gone: beat (1) 0.7, (2) 0.7, (5) 0.7, (12) 0.6; lost to (6) 0.3 — mean 0.60.
- (12) still believe: beat (1) 0.7, (2) 0.7, (5) 0.6; lost to (3) 0.4, (6) 0.3 — mean 0.54.
- (2) code outlives systems: beat (1) 0.7, (5) 0.6; lost to (3) 0.3, (6) 0.3, (12) 0.3 — mean 0.44.
- (5) closest to a promise: beat (1) 0.7; lost to (2) 0.4, (3) 0.3, (6) 0.3, (12) 0.4 — mean 0.42.
- (1) kinder future: lost all — (2) 0.3, (3) 0.3, (5) 0.3, (6) 0.2, (12) 0.3 — mean 0.28.

Why (6) wins: every candidate clears criterion 1, so the fight is criteria
2–5. (6) has the biggest first-read laugh (criterion 2): the diligent
review found nothing, and that exact diligence is what the three previous
reviewers reported right before the outage — the approval incriminates
itself. It is flat throughout (criterion 3), "LGTM" plus a concrete review
act makes it a comment a tired engineer would really paste (criterion 4),
and "before the outage" is the fresh turn (criterion 5): the dread arrives
in the last two words, reframing everything before it. (3) is colder and
more existential but its laugh is smaller; (12) is clever but its dread is
about the reviewer's belief, not the code; (1) is abstract philosophy with
no scene.

## Challenger checks (winner vs the best cut candidates)

- (6) vs (4): (6) wins 0.7 — (4)'s reassignment gag is a bolted joke; (6)'s dread is the review itself.
- (6) vs (11): (6) wins 0.7 — (11)'s "break politely" winks; (6) stays flat and its punch is bigger.

## Winner

(6) — "LGTM. I read every line twice and found nothing, which is exactly what the last three reviewers said before the outage." — 119 characters, mean game score 0.72 vs the top-6 field (clears the 0.60 bar). Tie-break note: at 119 bytes it is mid-field on size, not the smallest, but it wins on rate first; receipt speed (round 1) is the remaining lever, which is why this entry goes in ASAP.
