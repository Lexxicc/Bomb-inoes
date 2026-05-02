# Bomb-inoes — Ruleset

> Keep this file in sync with the How to Play page in `Bomb-inoes.html` whenever rules or mechanics change.

---

## Goal

A **best-of-5 domino match** against the AI. First to **3 round wins** takes the match. The draw is seeded daily — everyone plays the same tiles each day.

---

## Controls

- Tap a tile in your hand to select it
- Tap an open end of the chain that it matches to play it
- Tap **DRAW** if you have no playable tile

---

## Starting a Round

- The player holding the **highest double** goes first
- If neither player holds a double, the player with the **highest pip total** leads

---

## The Chain

- The chain grows from both ends
- Each open end shows a pip value — the tile you play must match that end
- You can play to either end on your turn

---

## Boneyard

- If you have no tile that matches either open end, tap **DRAW** to take one tile from the boneyard
- If the drawn tile fits you may play it immediately; if not, your turn passes
- Each draw costs you **10 points** at round end

---

## Round Endings

| Outcome | Score |
|---|---|
| Empty hand win | 100 + opponent's remaining pips − (draws × 10), min 100 |
| Blocked game (neither player can move) | 50 + pip differential − (draws × 10), min 50 |
| True draw (equal pip split in blocked game) | 50 pts each |

---

## Match Structure

- Best of 5 rounds — first to **3 round wins** takes the match
- Points accumulate across all rounds
- Final cumulative score is saved to the leaderboard
- The match carries over if you close mid-game (daily seed ensures fairness)

---

## Win / Loss Conditions

| Condition | Result |
|---|---|
| First to empty hand | Round win |
| Blocked game — lower pip total | Round win |
| Blocked game — higher pip total | Round loss |
| Win 3 rounds | Match win |
| Opponent wins 3 rounds | Match loss |

---

Last updated: 2026-05-02 — v0.0.3
