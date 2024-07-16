# Doodle Droider

A simple asteroid game built in a single vanilla HTML+CSS+JS file + images.

<img width="379" alt="image" src="https://github.com/user-attachments/assets/4dbb3242-c4f4-4259-b717-9280996ad67a">

## Play

https://paulohecht.github.io/doodledroider

## Description

Over the weekend, I challenged my 7-year-old kid to build a game with me. I asked him to draw
the assets to an asteroid-like game and I then used his designs in the game. He also demanded 
changes like replacing the ship bullets with flying rotating blades (he said we need blades to
cut asteroids in half 🤔).

This game is part of some experimenting I've been doing with single file HTML+CSS+JS capabilities. 
I wanted to build a fully featured game with rendering cycles, newtonian physics, and input handling
without any framework or library.

You can run the game locally in your file system, although the pixel collision detection will 
be disabled due to limitations of the canvas API (it falls back to simple circle collisions).

I recommend using `python -m http.server 8000` or npm's `http-server` to start a web server.

Have kids? Ask them to draw the ships and replace the images in the assets folder. It's quite fun!
