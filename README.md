# Block by Block Fitness

A twelve-week beginner strength and mobility program that runs entirely
in one HTML file. Built for someone starting from a sedentary baseline.

## The program

Three sessions a week, twelve weeks, in four blocks of three weeks:

| Weeks | Length | Focus |
|-------|--------|-------|
| 1–3   | ~8 min | Five movements, identical every session — habit first |
| 4–6   | ~15 min | Three additions, stretches held longer |
| 7–9   | ~20 min | Four additions, first core work |
| 10–12 | ~25 min | Push-ups move to the counter, step-ups and balance added |

Every movement is done standing, seated in a chair, or against a wall
or counter. Nothing on the floor. Equipment: a sturdy chair, a wall,
a counter, a doorway, and a low step.

## Features

- Tap any movement for full instructions, what it should feel like
  and where, and the signs form has slipped
- Short version of each session for low-energy days
- Notes from the previous session surface at the top of the next one
- History log with backfill and editing
- Progress shows as a quilt: one pieced block per completed session,
  sixteen traditional patterns, fabrics deepening week by week

## Technical

Single `index.html`, no build step, no dependencies, no network calls.
Progress persists to `localStorage` under `block-by-block-progress`.
Add to an iPhone home screen to run as a standalone app.
