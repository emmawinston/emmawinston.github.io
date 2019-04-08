---
layout: project
title: My Face When
summary: Local multiplayer game
tags:
- Project
---

![Screenshot of game start screen encouraging players to build their own emoji](https://emmawinston.me/assets/images/myfacewhen1.png)
![Screenshot of gameplay showing two winning composite emoji, one with a halo blowing a kiss and the other with three eyes, a protruding tongue and a snoring symbol](https://emmawinston.me/assets/images/myfacewhen2.png)

Commissioned for [Now Play This 2019](https://nowplaythis.net/2019-festival/), an independent games festival running at Somerset House in London with the theme of 'community', *My Face When* is a quick-fire, single-round, multiplayer game, in which players race against the clock to put together the best (or maybe just funniest) emoji face from a stack of components in response to a surreal, procedurally-generated prompt. The commission was to build a game to create momentary communities within the space of the exhibition; the game will not run until four players have stated intent to play, and chaotic interaction (including stealing each other's emoji components and voting for the player's own emoji) is encouraged.

*My Face When* is built as a low-overhead, static interactive website for the Chrome browser, currently hosted on Github Pages, but rather than being controlled by a keyboard and mouse it uses the Gamepad API so that four players on four Xbox controllers can interact with the game at once. You can [try it out here](https://emmawinston.me/myfacewhen), but interaction will be unpredictable without gamepads available, and it is also built for a site-specific 1920x1080 display; when zoomed out, performance seems to be affected on some computers. Prompts are generated using the [RiTa library](https://rednoise.org/rita/).

My JavaScript programming is at this point far from advanced, and this game is by far the most ambitious programming project I have ever undertaken, not least due to the tight timescale under which the game was commissioned. Both [v21](http://v21.io) and [Darius Kazemi](http://tinysubversions.com) were invaluably helpful in completing the project, I learned an astonishing amount of JavaScript in the process, and am far more confident as a programmer as a result of completing the project.
