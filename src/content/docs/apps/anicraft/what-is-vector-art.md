---
title: What is vector art?
description: Understand the difference between vector and raster art
parent: drawing
sidebar:
  order: 0
prev:
  link: /apps/anicraft/drawing/
  label: "Drawing"
next:
  link: /apps/anicraft/stroke-vs-fill/
  label: "Stroke vs. Fill"
---

**Raster**

Most people are familiar with _raster_ artwork on a computer: a rectangular image made up of square **pixels** (picture elements). When you zoom in to enlarge a raster image, you can see the individual pixels that make up the image.

![Mona Lisa](/assets/uploads/monaLisa.png "Mona Lisa")

![Mona Lisa Zoom Level 1](/assets/uploads/monaLisaZoom1.png "Mona Lisa Zoom Level 2")

![Mona Lisa Zoom Level 3](/assets/uploads/monaLisaZoom2.png "Mona Lisa Zoom Level 3")

The computer stores this grid of pixels, and each pixel's individual colour.

When you enlarge part or all of a raster image, these pixels become more apparent.

If you select part of a raster image and move it away, it's like taking a pair of scissors to a painting's canvas: the section leaves a hole in the image!  When you place that piece of the image elsewhere, it fuses to the rest of the picture, overwriting all of the pixels that it overlaps.

![Mona Lisa move face](/assets/uploads/monaLisaMoveFace.png "Mona Lisa move face")

**Vector**

Vector artwork is drawn with math. When you draw a vector circle, the computer isn't remembering pixels: it's remembering the width and height of the circle, its fill colour, and its stroke. 

![blue ball zoom level 0](/assets/uploads/ball1.png "blue ball zoom level 0")

You can resize vector artwork without any quality loss. 

![blue ball zoom level 1](/assets/uploads/ball2.png "blue ball zoom level 1")

![blue ball zoom level 2](/assets/uploads/ball3.png "blue ball zoom level 2")

In many vector drawing packages, elements can overlap each other without destroying what's underneath. AniCraft _can_ work this way, but by default, the vector Shapes interact with each other in interesting ways.

Next: [Stroke vs. Fill](/apps/anicraft/stroke-vs-fill/)
