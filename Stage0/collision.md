# Collision

## Feature

Manages collision between bat and ball, side-boundary and ball, back-boundary and ball

## Acceptance Criteria

### Scenario:when bat and ball collide

Given: coordinates of ball and bat

When: coordinates of ball and bat are equal

Then: path_finder to give new direction of ball

### Scenario: when side_boundary and ball collide

Given: coordinates of ball and side_boundary

When: coordinates of side_boundary and ball are equal

Then: path_finder to give new direction of ball

### Scenario: when back_boundary and ball collide

Given: coordinates of ball and back_boundary

When: coordinates of back_boundary and ball are equal

Then: ball goes in random path from center and score increases for a player
