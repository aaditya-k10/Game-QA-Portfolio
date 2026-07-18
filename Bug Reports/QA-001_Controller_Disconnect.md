**Report Version:** v1.1

Last Updated: 2026-07-08


# Bug Report

Controller Disconnection

---

## Bug ID

QA-001

---

## Title

Controller disconnect message appears while controller remains connected during gameplay

---

## Game

Hotwheels Unleashed (2021)

---

## Build

Build 7530842

---

## Version

1.0.5.0 (PC)

---

## Platform

macOS via NVIDIA GeForce NOW

---

## Environment

Cloud Gaming (GeForce NOW - Free Tier)

---

## Severity

Medium

---

## Priority

P2

---

## Reproducibility

Frequently (75%)

---

## Reporter

Aaditya Kanpile

---

## Date

2026-07-07

---

## Preconditions

- Controller connected successfully
- User logged into GeForce NOW
- Game launched successfully
- Race ready to start

---

## Steps to Reproduce

1. Launch Hot Wheels Unleashed.
2. Connect an Xbox-compatible controller.
3. Start any race.
4. Play continuously for several minutes.

---

## Expected Result

Gameplay should continue without displaying an unexpected controller disconnect message while the controller remains connected.

---

## Actual Result

A controller disconnect message appears even though the controller remains connected and responsive. Gameplay pauses until the prompt is dismissed.

---

## Evidence

Screenshot:

Video:

---

## Possible Cause (Optional)

Possibly related to cloud streaming input synchronization, but not confirmed.

---

## Additional Notes

Issue observed while playing through GeForce NOW.
Native PC testing is required to determine whether the issue is cloud-platform specific.

---

## Status
    
Needs Investigation

## QA Learning

- Learned how to distinguish observations from assumptions.
- Understood the importance of writing clear and reproducible test steps.
- Learned that severity and priority are different concepts.
- Realized that QA reports should describe what happened, not speculate about the root cause without evidence.

