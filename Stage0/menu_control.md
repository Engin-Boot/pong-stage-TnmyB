# Menu and UI

## Feature

To start, restart, pause, resume and exit game and manage game UI.

## Acceptance Criteria

### Scenario: when player selects start game

Given: start game option

When: player selects start game

Then: the game starts and ball and bat are placed
on initial position, path for ball is as per
path finder and score of both is at start

### Scenario: when player selects restart game

Given: restart game option

When: player selects restart game

Then: the game starts again with ball and bat
placed on initial position,
path for ball is as per path finder
and score of both is at start

### Scenario: when player selects pause game

Given: pause game option

When: player selects pause game

Then: the game pauses and ball and bat coordinates
and score are frozen

### Scenario: when player selects resume game

Given: resume game option

When: player selects resume game

Then: the game resumes from the frozen state

### Scenario: when player exit game

Given: exit game option

When: player selects exit game

Then: save the last states and scores in database
and exit game
