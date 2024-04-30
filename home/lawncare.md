# Lawncare
Nick's approach to lawn care

## Overview
General principles
* Let nature do its thing
* Avoid using chemicals
* Avoid mowing too frequently, too short, and too early inthe year
* Choose your battles carefully in this neverending war between man and nature

## Hardware
Current tools being used for lawn care

### Mower
EGO Cordless Lawn Mower

### String Trimmer
EGO Cordless String Trimmer

### Blower
EGO Cordless Blower

## Software
Algorithms used to complete lawn care activities

### Mowing pattern 1
Useful for enclosed areas (e.g. back yard with fences)

1. Start in a corner
2. Mow a straight line along the edge until encountering an angle
3. Mow along the angle until reaching the next edge
4. Back to step 2 until you are back in the starting position
5. Shift the lawn mower so that the next mowing path will overlap the prior path
6. Back to step 2 until the entire area is mown

The next time this algorithm is used, mow in the opposite direction (e.g. anti-
clockwise instead of clockwise).

### Mowing pattern 2
Useful for non-enclosed areas (front yard without fences)

1. Start in a corner
2. Mow a straight line along the edge until encountering an edge
3. Rotate the mower 180 degrees
4. Shift the lawn mower so that the next mowing path will overlap the prior path
5. Back to step 2 until the entigit@github.com:HAL-Software-LLC/HAL5433.gitre area is mown

The next time this algorithm is used, aim to mow in the perpendicular direction (
e.g. 90 degrees clockwise).
