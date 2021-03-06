# ROADMAP

*NB:* This roadmap is subject to change at any moment. If there's any feature you'd like me to add please make an issue with the `enhancement` tag & if you're interested, make a new branch proposing the changes.

### v0.2-a2 - RELEASED:

- [x] Handle damage
- [x] Add a handler for different types of weapons/items 
- [x] Create a consistent firearms definition
- [x] Add handler to load map data from different files
- [x] Add different types of projectiles & re-write Projectile sprite class

### v0.3-a3 - RELEASED:

- [x] Add GUI:
  - [x] Add Menus
  - [x] Add Text
  - [x] Add Buttons
  - [x] Add Typping entry
- [x] Create a consistent map definition format & filetype
- [x] Add spawnpoints
- [x] Add full shared screen multiplayer support

### v0.4-b1 - IN DEVELOPEMENT:

- [ ] Make a compiling script to easilly distribute game
- [x] Fix transparency
- [ ] Replace Pygame rectangles by drawn sprites
- [ ] Add animations
- [ ] Add settings:
  - [ ] FPS setting
  - [ ] Controls settings
- [ ] Add resolution scaler

### v0.5-b2:

- [ ] Add more types of projectiles such as explosive ones
- [ ] Add melee weapons
- [ ] Add perks

### v0.6-b3:

- [ ] Add explosives
- [ ] General code improvement:
  - [x] Re-write the `start()` function with loops to handle different maps
  - [ ] Improve weapons handler & re-write
  - [x] Improve Groups handler 
  - [ ] Add *premonition* collisions for better visual feedback & gameplay
- [ ] Add throwables


### v1.0:

- [ ] Fix various bugs:
  - [ ] Fix sprite update order
  - [ ] Shooting interval
  - [x] GFX glitches with "ghost" bullets
  - [ ] Reloading weapon issues
  - [ ] Bullets which can pass through `non-crossable` if they're fast
  - [ ] Players who can jump through `non-crossable` if they're too close
  - [ ] Improve collision checks
  - [ ] Lots of small bugfixes

*From there none of the planned update are confirmed to be released. They are only ideas I've had or suggestions I've received which are non essential but would be a great addtion. I will implement them if I still have motivation to both: continue this game and find out how to make the said features work out. Don't be surprised if they never get more than ideas though, that's part of the deal which I myself did ;).

### v1.1:

- [ ] Create Map Editor


### v1.2:

- [ ] Add online multiplayer support