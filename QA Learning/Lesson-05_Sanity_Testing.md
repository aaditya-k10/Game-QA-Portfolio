# Sanity Testing

## What is Sanity Testing?

Sanity Testing is a focused type of testing performed after a bug has been fixed or a small change has been made to the software.

Its purpose is to verify that the specific issue has been resolved and that the related functionality still works correctly.

---

## Why is Sanity Testing Important?

- Confirms that the reported bug has been fixed.
- Ensures nearby functionality has not been affected.
- Saves testing time by focusing only on the changed area.
- Prevents unnecessary execution of the complete test suite.

---

## When is Sanity Testing Performed?

- After receiving a build containing a bug fix.
- After a minor enhancement.
- Before Regression Testing begins.

---

## Characteristics

- Narrow and focused.
- Covers only the affected functionality.
- Fast to execute.
- Usually performed after Smoke Testing.

---

## Example

Bug:

Restart Race does not reset the timer.

Developer fixes the issue.

Sanity Testing includes:

- Verify timer resets.
- Verify countdown starts correctly.
- Verify lap counter resets.
- Verify player position resets.
- Verify AI positions reset.

If all checks pass, the fix is considered successful.

---

## Sanity Testing vs Smoke Testing

Smoke Testing

- Checks whether the build is stable.
- Covers critical functionality.
- Performed on a new build.

Sanity Testing

- Checks whether a specific fix works.
- Covers only the affected functionality.
- Performed after a bug fix.

---

## Interview Tip

Remember this sentence:

Sanity Testing answers:

"Did the specific fix work correctly?"

It does NOT answer:

"Does the whole application work?"

---

## Key Takeaways

- Performed after bug fixes.
- Focuses on the changed functionality.
- Quick and targeted.
- Usually followed by Regression Testing if required.