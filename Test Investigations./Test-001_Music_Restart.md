# Test Investigation

**Investigation ID:** TI-001

**Report Version:** v1.1

**Last Updated:** 2026-07-09

---

## Feature

Race Restart Audio

---

## Objective

Determine whether the background music restarting after restarting a race is intended behaviour or a software defect.

---

## Test Scenarios

1. Restart race once
2. Restart race multiple times
3. Pause the game, then restart the race
4. Finish the race, then restart
5. Change music volume, then restart
6. Test on different tracks
7. Test using different cars

---

## Test Results

### Scenario 1 – Restart Race Once

**Result:**
Background music restarted from the beginning.

---

### Scenario 2 – Restart Race Multiple Times

**Result:**
Background music restarted after every race restart.

---

### Scenario 3 – Pause Then Restart

**Result:**
Background music continued while the game was paused.
After restarting the race, the music restarted from the beginning.

---

### Scenario 4 – Finish Race Then Restart

**Result:**
Background music restarted after the race was restarted.

---

### Scenario 5 – Change Music Volume Then Restart

**Result:**
Changing the music volume did not affect the behaviour.
Background music restarted after restarting the race.

---

### Scenario 6 – Different Tracks

**Result:**
The same behaviour was observed across multiple tracks.

---

### Scenario 7 – Different Cars

**Result:**
The same behaviour was observed regardless of the selected car.

---

## Conclusion

The background music restarted consistently across all test scenarios.

The behaviour was reproducible and consistent regardless of the selected track, car, or audio settings.

Based on the investigation, this appears to be intended game behaviour rather than a software defect.

---

## Recommendation

No bug report should be created unless the game design documentation specifies that background music should continue playing after restarting a race.

---

## QA Learning

- Learned that not every unusual behaviour is a software bug.
- Understood the importance of validating behaviour through multiple test scenarios.
- Learned to base conclusions on evidence instead of assumptions.
- Practiced documenting test investigations in a structured and objective manner..

