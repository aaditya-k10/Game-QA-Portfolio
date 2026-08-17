# QA-003 — Race State Inconsistency After Repeated Reset/Respawn Actions

## Test Type
Functional / Exploratory Testing

## Status
Pending Verification

## Severity
Medium — if reproduced

## Priority
Medium — if reproduced

## Environment
- Game: Hot Wheels Unleashed
- Platform: PC / Cloud Gaming
- Controller: [Your Controller]
- Game Version: [Version]
- Date Tested: [Date]

## Description

Investigate whether race-state information remains consistent after repeatedly using reset/respawn functionality during different stages of a race.

## Preconditions

- A race is available.
- Player is controlling the vehicle normally.

## Steps to Reproduce

1. Start a race.
2. Drive for approximately 20–30 seconds.
3. Trigger the vehicle reset/respawn behaviour.
4. Observe the vehicle position.
5. Observe the race timer.
6. Observe the current lap.
7. Observe the player's race position.
8. Repeat the reset/respawn action multiple times.
9. Repeat the test near a checkpoint.
10. Repeat the test shortly before or after a lap transition.
11. Compare all race-state values after each reset.

## Expected Result

The vehicle should reset correctly while the race timer, lap count, race position, and other relevant race-state information remain consistent with the current race state.

## Actual Result

_To be completed after testing._

## Reproducibility

_To be completed._

## Evidence

_Add screenshot/video evidence here._

## Impact

If inconsistent race-state behaviour is reproduced, it could affect race progression, player position, timing, or competitive results.

## QA Assessment

_To be completed after verification._

## Notes

This is an exploratory regression target. Do not classify this as a confirmed defect unless inconsistent behaviour is actually reproduced.
