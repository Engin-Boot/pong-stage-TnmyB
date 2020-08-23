# Path finder

## Feature

Gives path of the ball

## Acceptance Criteria

### Scenario:at start

Given: coordinates of center of board

When: new game is begin

Then: set coordinates of ball at center

### Scenario: when someone scores

Given: the player who scores and center

When: any player scores

Then: generate path in random direction towards
the other player

### Scenario: ball collides with bat or side boundary

Given: initial path of ball and coordinates of
bat or boundary

When: ball collides

Then: calculate new path

### Scenario: when game resume after pause

Given: initial path of ball and coordinates of
bat and ball

When: the player selects resume

Then: move bat and ball as per prior position
