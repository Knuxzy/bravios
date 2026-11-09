# Destroyer

A playable character with a bold crimson-and-iron look. The portrait and platform poses are stored in `images/`; `character.json` connects them to the game.

The color treatment is consistent across the portrait and every pose. Side views face right and the game mirrors them for leftward movement. The four `run-1` through `run-4` images make up the running cycle.

The folder is registered as `destroyer` in `../characters.json`. The character preparation step checks that the images are present and builds the runtime catalog.
