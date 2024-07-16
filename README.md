# Doodle Droider

A simple asteroid game built in a single vanilla HTML+CSS+JS file + images.

<img width="379" alt="image" src="https://github.com/user-attachments/assets/4dbb3242-c4f4-4259-b717-9280996ad67a">

## Play

https://paulohecht.github.io/doodledroider

## Description

This weekend, I asked my 7-year-old kid to draw the assets for an asteroid-like game, and I then used his designs to build the game. Like a real game artist, he also demanded some changes, like replacing the ship bullets with spinning ninja blades (he said we need blades to cut asteroids in half 🤔🤷‍♂️).

This is part of some experimenting I've been doing with single-file HTML+CSS+JS. I wanted to build a simple yet fully-featured game with rendering cycles, simple newtonian physics, and flexible input handling without any framework or library.

You can run the game locally in your file system, although the pixel collision detection will 
be disabled due to limitations of the canvas API (it falls back to simple circle collisions).

I recommend using `python -m http.server 8000` or npm's `http-server` to start a web server.

Have kids? Ask them to draw the ship and asteroids, scan the art, and replace the images in the assets folder. It's quite fun!
