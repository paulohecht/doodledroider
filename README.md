# Doodle Droider

A simple asteroid game built in a single vanilla HTML+CSS+JS file + images.

![image](https://github.com/user-attachments/assets/4229a415-66f4-4a06-aef3-0fe23666d746)


## Play

https://paulohecht.github.io/doodledroider

## Description

Over the weekend I've challenged my 7yo kid to make a game with me. I asked him to draw
the assets to an asteroid like game and I then used his designs in the game. He also changed 
demanded some changes like replacing the ship bullets with flying rotating blades (he said we
need blades to cut asteroids in half 🤔).

This game is part of some experimenting I've been doing with single file HTML+CSS+JS capabilities. 
I wanted to build a fully featured game with rendering cycles, newtonian physics, input handling
without any framework or library.

You can run this game locally in your file system although the pixel collision detection will 
be disabled due to limitations of the canvas api (it fallbacks to simple circle collisions).

I recommend using `python -m http.server 8000` or npm's `http-server` to start a web server.
