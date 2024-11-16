# Tiling with Three Polygons is Undecidable

This webapp implements the 2024 paper
“**[Tiling with Three Polygons is Undecidable](https://arXiv.org/abs/2409.11582)**”,
by Erik Demaine and Stefan Langerman.

Given *n* [Wang tiles](https://en.wikipedia.org/wiki/Wang_tile),
the app computes **three** polygons that tile the plane
if and only if the Wang tiles do.

## [Run App](https://edemaine.github.io/three-tiles/)

[Try out the app](https://edemaine.github.io/three-tiles/)
to see the implementation in action.
It starts with
[an example of 11 Wang tiles](https://en.wikipedia.org/wiki/Wang_tile#/media/File:Wang_11_tiles.svg)
that tile only periodically.
You can add or remove colors or Wang tiles with the +/− buttons.
You can change Wang tiles by dragging a color to a tile edge.

## Development

To develop locally, use the following commands on a checkout:

1. `corepack enable` (or otherwise install PNPM)
2. `pnpm install` (whenever dependencies change)
3. `pnpm dev` (to run a local development web server)
