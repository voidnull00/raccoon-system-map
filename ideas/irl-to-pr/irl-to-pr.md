# IRL → PR

## Core Idea

Between something noticed in real life and a merged change, there are two
compression stages that usually get skipped:

> IRL idea → abstraction → integration → PR

Interface pattern. Execution side.
Sibling of the Thinking Layer (cognitive side).

---

## Problem

Raw lived experience does not merge.

Collapsing `IRL → PR` into one step produces:

- over-scoped changes
- context-free commits
- premature integration
- PRs that encode the feeling, not the system need

---

## Insight

The arrows matter more than the endpoints.

- **abstraction** — name the idea as a reusable shape
- **integration** — locate where that shape belongs in an existing system

Without these, `IRL → PR` is a leak, not a pipeline.

---

## Pattern Definition

```txt
IRL idea
↓
abstraction
↓
integration
↓
PR
```

Where:

- **IRL idea** — raw, situational input (friction, observation, desire)
- **abstraction** — the idea restated as a named shape (primitive, pattern)
- **integration** — placement inside an existing system (repo, folder, gate)
- **PR** — the smallest merged artifact that carries the idea forward

Each arrow is a compression, not a copy.

---

## Components

1. **Capture** — record the IRL idea as-is, no rewriting.
2. **Abstraction** — restate as a named shape.
3. **Integration** — pick the system location and justify it.
4. **PR hook** — the smallest change that lands the abstraction.

---

## Relationship to Other Primitives

### Raw Signal

Owns the entry. The IRL idea must be captured before interpretation,
otherwise abstraction inherits bias.

### BeepBoop Principle

Governs the arrows. Each stage transition is a `beep → boop`:
observe current form, make the smallest useful adjustment toward the next stage.
Keeps the pipeline from turning into a waterfall.

### Thinking Layer

Sibling interface pattern.

```txt
Thinking Layer  : intent   → decision
IRL → PR        : decision → artifact
```

The Thinking Layer often sits inside the **abstraction** or **integration**
stage as a sub-interface.

### Latent Constrained Vectors

Guards the pipeline. Most IRL ideas should stop at abstraction with an
activation condition — not advance to PR.

### Rangespeaking

Used at integration to decide *how much* of the abstraction lands in this PR.
Not binary ship / don't-ship.

---

## When to Use

- turning a recurring friction into a repo change
- converting an insight into a primitive in `ideas/`
- promoting an idea from latent to active via PR

Do NOT use for:

- quick fixes where abstraction adds no clarity
- explorations that should stay latent
- artifacts that belong outside any repo

---

## Failure Modes

### Skipping abstraction

```txt
IRL idea → PR
```

Result: commits encode context that the repo does not share.

### Skipping integration

```txt
IRL idea → abstraction → PR
```

Result: an orphan file that no existing system references.

### Over-abstracting

Staying in abstraction without ever integrating.

Result: stalled ideas, no merged artifact.

---

## One-Line Summary

A pipeline that compresses lived input into a merged artifact
without losing signal or overshooting scope.

🦝
