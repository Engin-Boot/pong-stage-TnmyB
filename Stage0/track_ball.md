# track ball

## Feature

Tracks and controls movement of ball

## Acceptance Criteria

### Scenario: when ball moves as per path finder

Given: the initial coordinates of ball and path direction

When: there is no collision

Then: the ball moves as per the path in a straight line

### Scenario: initial positions

Given: the game is running

When: game begins or some player scores

Then: wait for 3 seconds, then move ball as per path finder
