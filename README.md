# Overview

This is a port of Among Us to Overwatch Workshop.

# Custom Game Codes

## v0.2
Code: `1VMRP`

This version is stable, and tracks the commit with tag `v0.2`.

## Testing
Code: `H4TN2`

This version is still in development and may have bugs. It tracks the master branch.

# Screenshots

[Image of Gameplay](https://hoane.github.io/images/Among-Us-Overwatch.png)

# How To Play

## Lobby

On game start, a lobby menu will appear. The menu is only operable by the host player.
Use WASD to navigate the menu and Interact (usually F) to select an option.

Available Options:
* Imposter Count: The number of imposter players in the game.
* Voting Time: Seconds of each voting round
* Task Count: The number of tasks to give each crew member
* Kill Cooldown: Seconds the imposters must wait between kills
* Kill Distance: Range in meters of the imposter kills
* Move Speed: Speed of characters
* Fool Enabled: Whether to include the Fool role. No to never include, Yes to include with a 50% chance, Always to always include.
* Bot Count: Number of bot characters. Used for testing.
* ForceHostRole: Whether to force the host to play a specific role. Used for testing.

## Gameplay

Each player will be assigned a role: One of Crew, Imposter, or (when enabled) Fool.

### Controls

All players have the following controls available:
* Interact (F): Use. Perform tasks, hit the emergency button, or fix sabotage.
* Reload (R): Report. Report a dead player to start a round of voting.
* Crouch (Ctrl): Hide the unique identifier pip above the player's head.

### Voting

When the emergency button is used or a dead player is reported, gameplay will pause and a round of voting will begin.
The player receiving the most votes will be ejected.

Navigate the voting menu with Forward (W) and Back (S). Select your vote with Interact (F).

## Crew

Crew members win when all crew tasks are complete or all the imposters are dead.
Crew tasks will be marked with a green ▼.

## Imposter

Imposters win when there are an equal number of imposter and non-imposter players still living.

Imposters have the following additional controls available:
* Primary Fire (Mouse1): Kill player under targeting aura.
* Ultimate (Q): Open/close sabotage menu.

Additionally, imposters can also use vents with Interact (F).
While venting, imposters are invisible, but cannot kill.
Vents are marked to imposters with a purple ▦.

### Sabotage

Navigate the sabotage menu with Forward (W) and Back (S). Select your vote with Interact (F).

Each sabotage has a unique effect:
* Power Overload: The players have 60 seconds to use each breaker box, or the imposters win.
* Wine Shortage: The players have 60 seconds to stand next to both wine locations simultaneously, or the imposters win.
* Disable Communications: Until the players reprogram the comms hub, they will not be able to see task locations.

The sabotage locations are marked to all players with a red ▽.

## Fool

The Fool wins when they are ejected during a voting round.

## Misc

Controls in this guide are marked with the default key (e.g. Interact (F)), but may change based on player settings.
The in-game hints will show the correct key.

# Development

This package uses https://github.com/ItsDeltin/Overwatch-Script-To-Workshop to compile to the Overwatch Workshop format.
Follow the instructions at https://github.com/ItsDeltin/Overwatch-Script-To-Workshop/wiki/Getting-Started before using this package.
