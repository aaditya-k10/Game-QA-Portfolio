# Requirement Analysis

## Feature

Restart Race

---

## Functional Requirements

When the player selects "Restart Race":

1. The race timer resets to 00:00.
2. The countdown starts from 3.
3. The player's car returns to the starting position.
4. AI cars return to their starting positions.
5. The selected track remains unchanged.
6. The selected car remains unchanged.
7. The selected difficulty remains unchanged.

---

## Missing Requirements

- Boost meter should be empty 
- Music restarts
- AI cars are unchanged

---

## Questions for the Designer

- Will lap progress reset
- Will obstacle get respawned
- If player passes the checkpoint and restarts the race, would the player respawn at start or checkpoint 

---

## Risks

- If the difficulty is changed, would be unfair to the player
- If obstacle are spawned at diiferent places, would be unfair for player
- If boost meter is not set to empty after the restart, will be unfair to the player
- 
---

## What I Learned

- Requirements are not always complete.
- A QA engineer should identify missing information before testing.
- Missing requirements should be discussed with the designer instead of being assumed.
- Risk analysis helps identify possible gameplay problems before development is complete.