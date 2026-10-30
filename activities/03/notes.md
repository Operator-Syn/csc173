# Lecture 03 Activity: Notes
Name: John-Ronan S. Beira · Student ID: 2023-0638

## My photos (Parts 0 to 6)
I used four photos:
- `1793244685183.png`: a shell on a rock with leaves behind it.
- `1793246199099.png`: a cat sitting on pavement near a tiled entryway.
- `1793247631335.jpg`: a barred window with a roof above it; I used this one for the edge filters.
- `test.png`: a stylus on a bug zapper racket.

## My dataset (Part 7)
Categories: stylus vs. watch

Photos per category: 20 and 20

How I took them: I photographed both objects from different angles and distances. The stylus is shown by itself, in a hand, and with a tablet, paper, or notebook. The watch is shown on a wrist and by itself from the front, side, and back. The backgrounds include a dark tabletop, a tablet, and notebooks, with indoor lighting.

Final validation accuracy: transfer 100% · from scratch 30%

## My kernel (Part 2c)
The kernel is `[[2, 1, 0], [1, 0, -1], [0, 0, -2]]`. It gives more weight to the top-left of a patch and subtracts more from the bottom-right, so it responds to brightness changes across that diagonal. In my photo, it brings out the window bars and some wall texture.

## AI and outside help
- DeepSeek AI
