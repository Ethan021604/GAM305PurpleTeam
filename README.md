# Module Two Team Project Plan

## Team Members

- Ethan McGlone: Artist
- Zion Johnson: Programmer
- Ian Barniskis: Team Lead | UX/UI
- Will VanHuss: Level Designer
- Jose Lucca: UI/UX Support | Project Coordination

---

## Scenario Choice

### Scenario 3: Top Down

Required features:

- Player equipment pickups:
  - Minimum 3 armor pickups
  - Minimum 3 weapons
  - Ammo or other pickups placed around the level
- Moving enemies:
  - 2 unique types
- Stationary enemies:
  - 2 unique types
- Stationary obstacles:
  - 4 unique types
  - Obstacles should block the player or cause an effect

---

## Brainstorming Ideas

- Diablo-style, medieval low-poly dungeon crawler
- Dark starting area, such as a dungeon or dead forest
- Crossbow-style stationary enemy
- Goblins, skeletons, or small creatures as moving enemies
- Spike pits, fire pits, trip wires, and crossbow traps
- Floating keys or room-clearing mechanics to unlock doors
- Portal ending that opens after enough enemies are defeated
- Possible shop area where players spend gold on weapons, armor, or powerups
- Possible trap-disable buttons
- Possible surprise boss

---

## Development Timeline

Class due dates are the priority. Weekly tasks will be planned around module requirements and milestone goals.

---

## Alpha Goals

- Basic room layout
- Game starts successfully
- Early enemy assets
- Rough UI/HUD layout
- Core player movement functional

---

## Beta Goals

- Game can be played from start to finish
- Main menu
- HUD
- Game Over screen
- Core gameplay systems functional

---

## Communication Methods

Discord will be used for team communication through text and voice channels. GitHub will be used for repository management, version control, task tracking, and bug tracking.

---

## Meeting Frequency

The team will meet at least once per week.

- Weekly meeting: Wednesday
- Meeting style: 10-minute Scrum

---

## Task Assignment Method

- Will: Level design and asset placement
- Jose: UI/UX support, project coordination, and task organization
- Ian: Team lead, UX/UI planning, and QA/testing organization
- Zion: Programming and implementation
- Ethan: Art assets and visual development

Tasks will be discussed during weekly meetings and in Discord. Work will follow the class timeline and milestone requirements.

---

# Module Three Project Log - Team Development: QA and Testing Plan

## QA Communication and Collaboration

Discord will be used for quick QA communication, screenshots, videos, and questions about expected behavior. GitHub will be used to manage the project files, track bugs, assign fixes, and confirm which build is ready for testing.

---

## Testing Schedule

### Play Test - Preproduction / Early Development

Early testing will focus on the foundation of the game.

Testing focus:

- Game starts correctly
- Player movement works
- Camera displays the player correctly
- Basic room layout is playable
- Walls and obstacles block the player
- Early enemies and pickups can be tested
- Rough HUD is visible

Goal: Make sure the core game structure works before adding polish.

---

### Demo - Before Project Demo

Before the demo, the team will test the game from start to finish.

Testing focus:

- Main menu works
- HUD displays correctly
- Player can complete the level
- Enemies behave as intended
- Pickups work correctly
- Obstacles block or damage the player correctly
- Game Over screen appears when the player dies
- End portal or win condition works

Goal: Make sure the demo is stable and understandable for someone outside the team.

---

### Code Release - Final Build Check

Before final release, the team will test the game against the project requirements.

Final checks:

- 3 armor pickups
- 3 weapons
- 2 moving enemy types
- 2 stationary enemy types
- 4 stationary obstacle types
- Main menu
- HUD
- Game Over screen
- Win condition or end portal
- Game can be completed from start to finish

Goal: Make sure the final build is ready for submission and matches the project plan.

---

## Pass/Fail Testing Checklist

| Test Item | Expected Result | Pass/Fail |
|---|---|---|
| Game launches | Game opens without crashing |  |
| Main menu works | Player can start the game |  |
| Player movement works | Player moves correctly in all intended directions |  |
| Camera works | Player remains visible during gameplay |  |
| Player collision works | Player cannot walk through walls or blocked objects |  |
| Level layout is playable | Player can navigate from start to finish |  |
| Weapons work | Player can collect and use at least 3 weapons |  |
| Armor works | Player can collect at least 3 armor pickups |  |
| Pickups work | Ammo or other pickups update the player correctly |  |
| Moving enemy type 1 works | Enemy moves and interacts with the player |  |
| Moving enemy type 2 works | Enemy moves and interacts with the player |  |
| Stationary enemy type 1 works | Enemy stays in place and functions correctly |  |
| Stationary enemy type 2 works | Enemy stays in place and functions correctly |  |
| Obstacles are present | At least 4 unique obstacle types are in the level |  |
| Obstacles function correctly | Obstacles block, damage, or affect the player |  |
| Player takes damage | Health decreases when hit |  |
| Player death works | Game Over screen appears |  |
| Enemies can be defeated | Player attacks damage or destroy enemies |  |
| HUD works | Health, armor, ammo, or other needed UI displays correctly |  |
| Win condition works | Player can complete the level |  |
| Final build is stable | No major crash or blocker prevents completion |  |

---

## Updating the Test Plan

The test plan will be updated whenever the game design changes. If the team adds or removes a feature, related test cases will be added, changed, or removed.

Examples:

- If a shop is added, tests will be added for gold, purchases, and item effects.
- If trap buttons are added, tests will confirm that buttons disable the correct traps.
- If the portal opens after enemy kills, tests will confirm the portal opens at the correct time.

Changes will be discussed during the weekly Scrum or in Discord.

---

## GitHub Bug Tracking Process

Bugs will be tracked using GitHub Issues inside the project repository. Each bug will be entered as its own issue so the team can discuss it, assign it, attach screenshots, and track the fix over time.

To report a bug in GitHub:

1. Open the project repository.
2. Go to the Issues tab.
3. Select New Issue.
4. Add a clear title, such as `Bug: Player can walk through spike pit`.
5. Fill out the bug details.
6. Assign the bug to the correct team member.
7. Add labels for severity or status.

Each bug report should include:

- Bug title
- Build/version tested
- Area of game affected
- Steps to reproduce
- Expected result
- Actual result
- Severity: Low, Medium, High, or Blocker
- Screenshot/video if helpful
- Assigned team member

### Example Bug Report

**Title:** Player can walk through spike pit wall  
**Build:** Alpha Build  
**Area:** Dungeon Room 2  
**Steps:** Start the game, enter Room 2, walk into the left side of the spike pit  
**Expected Result:** Player is blocked or damaged  
**Actual Result:** Player walks through the obstacle  
**Severity:** Medium  
**Assigned To:** Level Designer or Programmer  

---

## Bug Labels and Status Tracking

GitHub labels will be used to organize bugs by severity and status.

Severity labels:

- `low`
- `medium`
- `high`
- `blocker`

Status labels:

- `open`
- `in progress`
- `ready for retest`
- `closed`
- `wont fix`

If the team needs a clearer visual layout, GitHub Projects can also be used as a board. The board would organize bugs into columns such as:

- Open
- In Progress
- Ready for Retest
- Closed

This will help the team see which bugs still need work, which ones are being fixed, and which ones have already been verified.

The team will prioritize bugs that:

- Block progress
- Break gameplay
- Cause crashes
- Prevent the game from being completed
- Prevent the project from meeting the Scenario 3 requirements

- Prevent the project from meeting the Scenario 3 requirements

---

## UI/UX Playtesting Notes

During testing sessions, the team will also collect feedback related to player experience and interface usability.

UI/UX testing focus:

- HUD visibility during combat
- Menu navigation clarity
- Readability of text and UI elements
- Player understanding of objectives
- Visual feedback when taking damage or collecting items
- Screen layout on different monitor sizes
- Overall gameplay feel and accessibility

The goal is to make sure the game is easy to understand and comfortable to play for new players.

## UI/UX Playtesting Reflection

During testing, the team focused on making the game easy to understand for new players. UI and gameplay feedback helped identify areas where the HUD, level flow, and player guidance could be improved.

Communication through Discord also helped the team quickly share screenshots, gameplay clips, and feedback during testing sessions. This made it easier to identify confusing areas of the level and improve the overall player experience.
