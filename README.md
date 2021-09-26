# Explorers

This is meant to be a web game where you control a character exploring the
world.

## Goals
The goal is to use this project as a test of a set of Javascript tools.

The project needs to be complex enough as to evaluate the tools in a close to
real-world scenario. 

The game avoids the use of the canvas element as the tools to be tested are
focused on HTML/CSS/Javascript development.

The game will avoid as much as possible the use of any tooling outside of the
browser environment.

The game will avoid as much as possible any tool that is not under test.

## Tools under test

The tools are assumed to exist in a sibling folder called tools.
Symbolic links are used to invoke the tools

- Chips https://github.com/isacvale/chips

## The game

The core ideas of the game are:
- player can choose among a set of possible avatars
- each avatar has a different skillset
- players can explore a huge world in an HTML page, lazyloading as they explore it
- battles are held between players and NPCs in a turn-based fashion where each select their attacks/defenses and the results are computed per turn
- players have an inventory where they can store items
- players can save and load game states, which contain the characters and the location. The state of the world is to be determined by the server. The world may continue to change while the players are offline.

### Art
Art is made of static images like cards. Special effects are applied in some situations.

### Sound

Ambience and music are provided by http://tabletopaudio.com.

# Development

## Milestones

### Toy / tools
We are to "build the toy first", so the first milestone is to build the toy upon which the game is to be built.

Features:
- Character: selection, movement, inventory, healtht points, power points
- Scenario: Continents with cities, forests, Mountains.
- Vessels: Ships and Carriages for transportation (allowing users to quickly jump to other parts of the map).

### Game mechanics
Mostly to be developed. So far the idea is to have a turn based RPG-like game.

