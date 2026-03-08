# Jellyfish Yuruyurau

## What's inside

Single HTML file, no dependencies. Runs at 120fps via:

- Raw `Uint32Array` pixel buffer instead of canvas draw calls
- Sin/cos lookup tables (65,536 entries) replacing `Math.sin`/`Math.cos`
- Time-based animation so speed is framerate-independent

Glow effect achieved via:

- \*\*Additive blending\*\* — overlapping points accumulate brightness instead of overwriting, creating luminous cores at dense regions
- \*\*Fade-to-black trail\*\* — pixels decay toward background each frame instead of a hard clear, leaving motion trails

## Usage

Drop `sketch2.html` into your project and open it, or embed the `<canvas>` + `<script>` block into an existing page.

## Credit

Original algorithm by \[@yuruyurau](https://x.com/yuruyurau) for つぶやきProcessing.


