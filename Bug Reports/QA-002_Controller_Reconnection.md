# QA-002 — Controller Input Does Not Recover Correctly After Reconnection

## Test Type
Regression / Compatibility Testing

## Status
Pending Verification

## Severity
High — if reproduced

## Priority
High — if reproduced

## Environment
- Game: Hot Wheels Unleashed
- Platform: PC / Cloud Gaming
- Controller: [Your Controller]
- Connection: Wired / USB Dongle
- Game Version: [Version]
- Date Tested: [Date]

## Description

Investigate whether controller input is correctly restored after the controller is disconnected and reconnected during an active race.

Historical reports have described controller-recognition issues in Hot Wheels Unleashed, making this a useful regression scenario to investigate.

## Preconditions

- Game is running.
- Controller is connected and functioning.
- A race has started.
- Player has control of the vehicle.

## Steps to Reproduce

1. Launch Hot Wheels Unleashed.
2. Connect the controller.
3. Start a race.
4. Drive normally for 20–30 seconds.
5. Disconnect the controller.
6. Wait several seconds.
7. Reconnect the controller.
8. Resume gameplay.
9. Test steering, acceleration, braking, boost, and pause controls.

## Expected Result

After the controller reconnects, all supported controller inputs should be restored and the player should be able to continue the race normally.

## Actual Result

_To be completed after testing._

## Reproducibility

_To be completed._

## Evidence

_Add screenshot/video evidence here._

## Impact

If reproduced, the issue can prevent the player from controlling the vehicle after reconnecting the controller and may interrupt or invalidate the current race.

## QA Assessment

_To be completed after verification._

## Notes

This report is based on a regression investigation target and should only be classified as a confirmed defect if the behaviour is reproduced during testing.