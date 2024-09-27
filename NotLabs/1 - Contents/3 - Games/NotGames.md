# Not Games

## 1 - Abstract

Not Games is a web service which hosts a variety of online games, both single player and
multiplayer, all of which may be accessed through its website.

## 2 - Contents

### 2.1 - Data

#### 2.1.1 - Profiles

Not Games shall allow users to optionally create profiles to which game data may be attached.

#### 2.1.2 - Persistence

Not Games shall store save data and settings for registered users, and shall store high scores for
all users, the high score data being publically visible via leaderboards.

### 2.2 - Interface

Each game hosted by Not Games shall have its own frontend accessible via the URL argument "game",
whereas the site, when accessed with no such argument, shall display a hub interface of all the
available games.

Each game shall have a name, and shall have an icon associated with it. Options for each game shall
be rendered in an smartphone-menu-esque format in alphabetical order.

Each site shall feature a navigation bar at the top with access to sign in options if signed out,
profile options if signed in, and with home and fullscreen buttons if in a game. The home button
shall be in the form of the site logo, which shall still be visible on the hub screen. If in a
game, the name and logo of the game shall be visible on the hub screen.