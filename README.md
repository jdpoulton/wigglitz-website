# Wigglitz 3D (web)

A pseudo-3D heightmap sandbox in the browser: explore a procedurally generated
open world, **build towers**, **dig holes**, and **collect the Wigglitz**. Runs
entirely on an HTML5 canvas — no dependencies, no build step.

## Play

Open `index.html` in a browser, or visit the deployed site.

**Click the canvas** to capture the mouse, then:

- **Mouse** — look around
- **WASD** — move
- **Left click** — dig (lower a block / dig into the ground)
- **Right click** — build (raise a block / stack a tower)
- **1–4** — pick which block to build with
- **C** — your Wigglitz collection
- **Esc** — release the mouse
- **-** / **+** — mouse sensitivity

Find all the Wigglitz scattered across the world to complete your collection.

## Deploy (Vercel)

This is a static site with files at the repo root, so there's **no
configuration**: import the repo on [vercel.com](https://vercel.com), pick
Framework Preset **Other**, and deploy.

## About

The world generator is a 1:1 JavaScript port of a hand-written .NET IL routine
from the original desktop build — verified to produce an identical map. The
desktop version (C# + hand-written IL, built with only in-box Windows tooling)
lives at [github.com/jdpoulton/wigglitz](https://github.com/jdpoulton/wigglitz).

Branding inspired by [wigglitz.com](https://wigglitz.com).
