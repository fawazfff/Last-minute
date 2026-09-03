# LastMinute

**When there isn't enough time to do everything.**

LastMinute is a deadline triage engine. Add your deadline, usable work time, and everything you think needs doing. It calculates whether the workload can actually fit, protects a buffer, triages work into **Must / Reduce / Defer / Kill**, and builds a realistic rescue timeline.

## Why it exists

Most planners reorganize impossible lists. LastMinute refuses to pretend 8 hours of work fits into 5. It protects the outcome instead of the todo list.

## Core flow

1. Define what you are trying to finish.
2. Set the deadline and genuine usable work time.
3. Dump all tasks and estimates.
4. Get a deterministic Reality Check.
5. Confirm the Minimum Viable Finish.
6. Triage tasks into Must, Reduce, Defer, or Kill.
7. Build a deadline timeline.
8. Start the next task and track actual time.
9. Replan when work overruns.
10. Finish and review what changed.

## Product rule

**Reality first. AI second.**

Time arithmetic is deterministic. The current hackathon build works without an external AI API, so there is no secret key required and no paid endpoint to abuse. The product is designed so AI suggestions can be layered on later without being allowed to override feasibility math.

## Local development

No framework is required. Serve the repository root with any static HTTP server.

Quick syntax check:

```bash
npm run check
```

## Demo

Use **Try an example** on the homepage. The seeded demo intentionally contains more than eight hours of desired work against five hours of availability. LastMinute triages it into a viable plan.

## Privacy

No account is required. Plans are stored locally in the browser for the hackathon MVP.
