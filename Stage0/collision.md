# Collision

## Feature

Manages collision between bat and ball, side boundary and ball,
back boundary and ball

## Acceptance Criteria

### Scenario:when bat and ball collide

Given: coordinates of ball and bat

When: coordinates of ball and bat are equal

Then: path finder to give new direction of ball

### Scenario: when side boundary and ball collide

Given: coordinates of ball and side boundary

When: coordinates of side boundary and ball are equal

Then: path finder to give new direction of ball

### Scenario: when back boundary and ball collide

Given: coordinates of ball and back boundary

When: coordinates of back boundary and ball are equal

Then: ball goes in random path from center and score
increases for a player
