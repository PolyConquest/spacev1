# Spacev1

Default layout for the Space game version 1.

## Goal

Reach the endpoints which are the planets showing in red.
You start at the green planet.

## Actions

- `move <src> <dest>` : moves the ship from the source planet to the destination planet

## Available Input

- `readLine` : returns a stringified JSON object representing the solar system. {planets: [{id,name}], paths:[src,dest], startingPoint, endingPoints}

## Win Condition

You win by being on an ending point planet on your last action