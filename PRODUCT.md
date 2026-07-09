# Product

## The Problem

Knowing what to do and doing it are two different systems, and most
productivity tools only address the first one. A to-do list assumes the
hard part is remembering the task. A habit tracker assumes the hard part is
counting streaks. Neither addresses the actual failure point: the specific
moment — usually small, usually unnoticed — where a plan starts to drift
and nobody, including the person living it, registers what happened until
days later.

## Product Direction

Tre-Up is built around reading behavioral signals — timing patterns,
consistency, self-reported intent, and eventually passive signals like
sleep and activity — and turning them into short, specific, honest guidance
about where things stand right now and what the next reasonable move is.
Not a longer list. Not a score to chase. A read on the moment.

## Hawk, at a High Level

Hawk is the internal name for Tre-Up's signal-to-guidance layer. Without
getting into implementation specifics (kept intentionally high-level here),
the design commitments behind it are:

- It doesn't state certainty it doesn't have — low-confidence situations
  get a quieter, more limited response, not a confident-sounding guess.
- It reads against the user's own pattern, not a comparison to other users.
- It's meant to expand what the user can decide, not replace the decision.

## Why Decision Timing Matters

A plan doesn't usually fail all at once. It fails at a specific point — the
moment someone decides to skip "just this once," or doesn't notice that
energy and intent have quietly diverged from the plan for three days
running. Most tools are blind to that moment because they only look at
outcomes (did you check the box) rather than the pattern leading up to it.
Tre-Up's core bet is that surfacing that moment early, and without
judgment, is worth more than any amount of task-list polish.

## Why This Isn't a To-Do / Habit / Mood App

- A to-do app tracks tasks. Tre-Up tracks the gap between intent and
  behavior.
- A habit tracker counts streaks. Tre-Up looks at what's actually driving a
  drop, not just that one happened.
- A mood tracker asks how you feel right now. Tre-Up is built around what
  you're about to do, given how things are actually going.

This document intentionally stays high-level. The specific scoring and
prediction logic is part of the product's internal constitution and isn't
detailed publicly at this stage.
