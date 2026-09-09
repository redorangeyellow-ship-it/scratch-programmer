# Scratch Program: Draw a Square

This guide explains how to program a sprite to draw a perfect square on the stage using Scratch's **Pen Extension** blocks.

## Code Block Structure

Position the blocks exactly as shown in this logical sequence:

```text
[When green flag clicked]
       │
[Go to x: (0) y: (0)]
       │
[Point in direction (90)]
       │
[Erase all]
       │
[Set pen color to (#00FF00)]
       │
[Set pen size to (4)]
       │
[Pen down]
       │
[Repeat (4)] ──┐
       │       │
       ├── [Move (100) steps]
       ├── [Turn right (90) degrees]
       └── [Wait (0.5) seconds]
```

## Step-by-Step Instructions

1. **Add the Pen Extension:** Click the **Add Extension** button in the bottom-left corner of the Scratch interface and select **Pen** to reveal the drawing blocks.
2. **Setup the Canvas:** Start with a `when green flag clicked` event. Use `go to x: 0 y: 0` and `point in direction 90` to center and align your sprite before drawing.
3. **Clear Previous Drawings:** Add the `erase all` block right after the setup so your canvas resets cleanly every time you click the green flag.
4. **Configure the Pen:** Snap down your `set pen color` and `set pen size` blocks, then lock the marker onto the canvas with `pen down`.
5. **Build the Loop:** Use a `repeat 4` loop from the Control palette (since a square has 4 equal sides).
6. **Program the Movement:** Inside the loop, add a `move 100 steps` block for the edges and a `turn right 90 degrees` block for the perfect right-angle corners.
7. **Add an Animation Delay:** Include a `wait 0.5 seconds` block at the bottom of the loop to slow down the sprite so you can watch the square being drawn line by line.
