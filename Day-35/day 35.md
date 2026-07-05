# Day 35 — 🧩 Prompt Puzzle: Master AI Prompting Through Play

Part of the **#60DaysABTalksChallenge**

## Overview

Prompt Puzzle is a premium, single-file HTML application that teaches AI prompting through interactive play. It runs fully offline — just open the HTML file in a browser. There's a small recursion baked into the concept: it's a prompting game generated from a single prompt. A prompt that teaches prompting.

The app interviews you first (domain + difficulty), then generates 6–8 randomized scenarios and drops you into three distinct challenge types.

## The Three Challenge Types

1. **Build the Prompt** — Assemble the correct prompt blocks while ignoring distractor blocks.
2. **Clean the Prompt** — Strip an over-engineered prompt back down to what actually matters.
3. **Choose the Best Prompt** — Compare a weak, an optimized, and an over-engineered version and pick the one that earns its place.

## Features

- Fully offline, single-file HTML (zero dependencies required to run)
- Interview-first flow: pick your domain and difficulty before anything generates
- 6–8 randomized scenarios per session, stored in reusable JavaScript objects
- Live scoring across Accuracy, Time, Moves, Wrong Placements, Hints Used, and an Optimization Bonus
- A **Prompt Performance Report** with Prompt Score, Rating, Rank, a **Prompt DNA** visualization, personalized feedback, next milestone, and a final optimized prompt
- Replay with a fresh set of randomized scenarios
- Premium modern UI: drag-and-drop, hover effects, floating notifications, score animations, micro-interactions, and progress indicators

## Each Scenario Includes

- Desired Output
- Correct Prompt Blocks
- Distractor Blocks
- Weak Prompt
- Optimized Prompt
- Over-Engineered Prompt
- Weak AI Output
- Optimized AI Output
- Prompt Principle

## Tech Stack

- Single-file HTML, CSS, and vanilla JavaScript (React via CDN only where it works reliably as a standalone file)
- No build step, no server, no external assets needed to run

## Key Learnings

- **Most prompting problems are over-engineering problems, not knowledge gaps.** The over-engineered examples were the easiest to write because they mirrored my own early attempts — too much context, too many roles, too many caveats.
- **Good prompting is mostly good communication.** Know the outcome, say it plainly, trust the reader to do their job, and remove everything that isn't earning its place.
- **Designing the scoring taught me more than the scoring did.** Deciding to penalize clutter and reward optimization forced me to define what a "good" prompt actually is, not just a correct one.
- **The Prompt DNA visualization was the real payoff.** The goal was never a high score — it was helping the player notice their own patterns.
- **Constraints in the generation prompt matter.** Instructing it to reduce only the number of scenarios (rather than trimming features) when output gets large kept the app coherent under pressure.


*Day 35 of the #60DaysABTalksChallenge. The challenge keeps handing me small lessons disguised as builds.*
