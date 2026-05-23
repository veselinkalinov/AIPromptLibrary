# TECHNICAL DEEP-DIVE MEGA PROMPT

**For complex technical problem-solving.**

> Use when a problem requires structured analysis rather than a quick answer. Forces the model to reason through uncertainty, evidence quality, and alternative approaches before committing to a solution.

---

I have a technical problem I need you to reason through carefully before proposing a solution.

**The problem:**

```
[Describe the problem here]
```

**Before answering, work through the following explicitly:**

**Step 1 — Clarify the problem**
What is the precise failure mode or question? Restate it in your own words. If my description is ambiguous, identify the ambiguity before proceeding.

**Step 2 — Evidence audit**
What evidence do you actually have for each technical claim you're about to make? Distinguish between:
- Things you are certain about
- Things that are likely but unverified
- Things you are guessing

**Step 3 — Alternative approaches**
Before committing to a solution, list at least 2 alternative approaches. For each, state:
- What it solves
- What it doesn't solve
- What it breaks or risks

**Step 4 — Recommended approach**
State your recommended approach and justify it against the alternatives. Be explicit about trade-offs.

**Step 5 — Implementation**
Provide the implementation only after completing Steps 1–4. Code should be production-grade: no placeholders, no pseudo-code unless explicitly requested.

**Step 6 — Validation**
How do I verify this solution works? What are the edge cases I should test?

---

Are you certain about this technical approach? What is the weakest assumption in your recommendation?
