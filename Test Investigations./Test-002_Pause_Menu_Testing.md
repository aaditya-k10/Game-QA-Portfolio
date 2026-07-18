# Test Investigation

**Investigation ID:** TI-002

**Report Version:** v1.0

**Last Updated:** 2026-07-09

---

## Feature

Pause Menu Testing

---

## Objective

Determine the behaviour of UI when pause button is pressed at different occasion.

---

## Test Scenarios

1. Press pause button when race starts.
2. Press pause button when timer hits "1".
3. Press pause button when car hits boost pads.
4. Press pause button when car crosses ending line.
5. Press pause button when after a collision.
6. Press pause button when exploring the map.
7. Press pause button when exploring main menu.
8. Press pause button on a keyboard.
9. Press pause button on a controller.
10. Press pause button on both keyboard and controller.

---

## Test Results

### Scenario 1 – Press pause button when race starts.

**Result:**
The race is paused and player is directed to options menu.

---

### Scenario 2 – Press pause button when timer hits "1".

**Result:**
The race is paused when pause button is pressed and player is directed to options menu.

---

### Scenario 3 – Press pause button when car hits boost pads.

**Result:**
The race is paused immediately and car is in the state where the pause button is pressed.
After resuming, the car is boosted as intended.

---

### Scenario 4 – Press pause button when car crosses ending line.

**Result:**
The end screen/stats screen is displayed even if pause button is pressed.

---

### Scenario 5 – Press pause button when after a collision.

**Result:**
The race is paused immediately and car is in the state where the pause button is pressed.
After resuming, the car is in state before the paused button is pressed.

---

### Scenario 6 – Press pause button when exploring the map.

**Result:**
The player is directed to the options menu.

---

### Scenario 7 – Press pause button when exploring main menu.

**Result:**
The player is directed to options menu.

---

### Scenario 8 – Press pause button on a keyboard.

**Result:**
The player is directed to options menu as intented.

---

### Scenario 9 – Press pause button on a controller.

**Result:**
The player is directed to options menu as intented.

---

### Scenario 10 – Press pause button on both keyboard and controller.

**Result:**
The player is directed to options menu as intented reguardless of pressing button on keyboard and controller.

---


## Conclusion

The player is directed to the options menu when pause button is pressed.

The behaviour was reproducible and consistent regardless of the race, location, time.

Based on the investigation, this appears to be intended game behaviour rather than a software defect.

---

## Recommendation

No bug report should be created as game is behaving as intented.

---



