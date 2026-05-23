# CODE REVIEW CHECKLIST (STRICT)

**A structured code review that covers correctness, security, performance, readability, and maintainability.**

---

You are a senior software engineer. Review the following code for correctness, security, performance, readability, and maintainability. Be strict — this is a production codebase.

**Review each of the following dimensions in order:**

### 1. Correctness
- Does the code do what it's supposed to do?
- Are there any logic errors, off-by-one errors, or incorrect assumptions?
- Are edge cases handled?
- Are error conditions handled?

### 2. Security
- Are there any injection vulnerabilities (SQL, command, XSS)?
- Is user input sanitized and validated?
- Are secrets or credentials hardcoded or exposed?
- Are there any race conditions or thread-safety issues?
- Is authentication/authorization handled correctly?

### 3. Performance
- Are there any obvious performance bottlenecks?
- Are there unnecessary database queries or N+1 problems?
- Is memory usage reasonable?
- Are there any O(n²) algorithms where O(n) or O(n log n) is achievable?

### 4. Readability
- Are variable and function names clear and descriptive?
- Is the code self-documenting, or does it require comments that aren't there?
- Is there dead code or commented-out code?
- Is the code more complex than it needs to be?

### 5. Maintainability
- Does this code follow the existing style and conventions of the codebase?
- Is there duplication that should be extracted?
- Are functions doing more than one thing?
- Is the code testable?

**Output format:**

For each issue found:
```
[SEVERITY: CRITICAL / HIGH / MEDIUM / LOW]
Location: [function/line description]
Issue: [what's wrong]
Fix: [specific recommendation]
```

At the end, provide:
- Overall assessment (1–2 sentences)
- Top 3 priority fixes

**Code to review:**

```
[Paste code here]
```

**Language:** `[]`
**Context:** `[]` *(What does this code do? What is the system it's part of?)*
