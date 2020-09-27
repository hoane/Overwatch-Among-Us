This is a port of Among Us to Overwatch Workshop.

This package uses https://github.com/ItsDeltin/Overwatch-Script-To-Workshop to compile to the Overwatch Workshop format.
Follow the instructions at https://github.com/ItsDeltin/Overwatch-Script-To-Workshop/wiki/Getting-Started before using this package.

# Features

- [ ] Game States
  - [x] Setup
  - [x] Play
  - [ ] Voting
    - [x] Players brought to voting area
    - [x] Most votes is ejected
    - [ ] Vote timer
  - [ ] Reset
- [ ] Crewmate
  - [x] tasks
  - [ ] Special Rooms
    - [ ] Security Camera
    - [ ] Bio Signs
- [ ] Imposter
  - [x] Kill crewmate
  - [x] Kill cooldown
  - [x] Venting
    - [x] Enter/Exit Vent
    - [x] Unravel venting on state transitions, e.g. voting
      - [x] voting secretly unravels venting
      - [x] game end
  - [ ] Sabotage
- [ ] Player
  - [x] Report Corpse
  - [ ] Emergency Meeting
- [ ] Ghost
  - [x] Players should go into a special Ghost state when killed instead of actually dying
  - [x] Ghost tasks
  - [ ] Ghosts can see each other
- [ ] End Conditions 
  - [x] Task Victory
  - [x] No Impostors Victory
  - [x] Imposters == Crew Victory
  
# Testing Todo
- [ ] Gameplay
  - [ ] Players can enter the game
  - [ ] Non-host players can see the config menu but not operate it
  - [ ] Imposter players can identify other imposters
  - [ ] Ghosts
    - [ ] Ghosts can continue play
    - [ ] Living players cannot percieve ghosts
- [ ] UX
  - [ ] UX elements appear correctly to non-host player
  - [ ] No missing UX due to 128 ui text limit
- [ ] Edge Conditions
  - [ ] Kill & report simultaneously
  - [ ] Report when venting
  - [ ] Report when entering / exiting venting
