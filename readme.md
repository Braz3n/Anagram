# Anagram
A simple anagram game for my students built using [Phaser](https://phaser.io). Originally created in June 2019.

It was designed to be run on a touch screen at the back of the classroom, so it requires a full-screen browser window at 1980x1080 to view normally.

Users can select any combination of the three word classes (colors, animals, places), and upon hitting start, are presented with letters at the top of the screen, and slots to place them in. Users drag and drop letters into the slots to complete the puzzle.

A scoreboard is also available, where the score is the time required to finish the puzzle.

## Music
The in-game background track is "The Triumph of the Clock Maker" by Eric Matyas of [soundimage.org](https://soundimage.org/looping-music/).

Other sound effects were aquired via various [Humble Bundle](https://www.humblebundle.com) sound effect bundles.

## Execution
The project was only ever hosted locally, running Python's built-in http server at system boot:
```
python -m http.server 8000
```