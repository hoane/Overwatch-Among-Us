This is a port of Among Us to Overwatch Workshop.

This package uses https://github.com/ItsDeltin/Overwatch-Script-To-Workshop to compile to the Overwatch Workshop format.
Follow the instructions at https://github.com/ItsDeltin/Overwatch-Script-To-Workshop/wiki/Getting-Started before using this package.

# Features

- [ ] Game States
  - [x] Setup
  - [x] Play
  - [x] Voting
    - [x] Players brought to voting area
    - [x] Most votes is ejected
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
    - [ ] Unravel venting on state transitions, e.g. voting
      - [x] voting secretly unravels venting
      - [ ] game end
  - [ ] Sabotage
- [ ] Player
  - [x] Report Corpse
  - [ ] Emergency Meeting
- [ ] Ghost
  - [ ] Players should go into a special Ghost state when killed instead of actually dying
  - [ ] Ghost tasks
  - [ ] Ghosts can see each other
- [ ] End Conditions 
  - [x] Task Victory
  - [x] No Impostors Victory
  - [x] Imposters == Crew Victory
  