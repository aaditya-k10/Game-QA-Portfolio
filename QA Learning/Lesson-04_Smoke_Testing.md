# Smoke Testing

## What is Smoke Testing?

Smoke Testing is a quick verification process performed on a new software build to determine whether the build is stable enough for detailed testing.

It focuses only on the most critical functionalities of the application.

---

## Why is Smoke Testing Important?

- Prevents wasting time on unstable builds.
- Confirms core features are working.
- Decides whether detailed testing should continue.

---

## When is Smoke Testing Performed?

- After receiving a new build.
- Before Functional Testing begins.
- Before Regression Testing begins (if required).

---

## Characteristics

- Quick
- Covers only critical features
- High-level testing
- Does not test every functionality
- Performed on every important build

---

## Typical Smoke Test Checklist

- Application launches successfully.
- User can log in.
- Main menu loads.
- Settings menu opens.
- User can start the main feature.
- Core controls work.
- Application does not crash immediately.
- User can exit the application normally.

---

## Game QA Example

Game:
Hot Wheels Unleashed

Smoke Test Checklist:

- Game launches.
- Login successful.
- Main menu loads.
- Controller detected.
- Settings open.
- Race starts.
- Car can be controlled.
- Race finishes.
- Game exits normally.

If all critical checks pass:

PASS → Continue detailed testing.

If any critical feature fails:

FAIL → Return build to developers.

---

## Smoke Testing vs Functional Testing

Smoke Testing

- Tests only critical features.
- Quick verification.
- Determines build stability.

Functional Testing

- Tests every feature.
- Detailed verification.
- Finds functional defects.

---

## Interview Tip

Remember one sentence:

Smoke Testing answers:

"Is this build stable enough to continue testing?"

It does NOT answer:

"Is the application bug-free?"

---

# Key Takeaways

- Smoke Testing is the first health check of a build.
- It focuses on critical functionality.
- It is fast and high-level.
- If Smoke Testing fails, detailed testing usually does not begin.