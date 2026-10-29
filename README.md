# Deep End

An original floating lido built with Three.js and Vite.

## Develop

```sh
npm ci
npm run dev
```

## Build

```sh
npm run build
```

The scene uses an orthographic camera, a low-resolution render target, depth-based edges and a fixed 64-colour palette matched in OKLab. Controls change the camera, rendering resolution, event, weather and lighting. Click either pool to excite its finite-difference wave field.

Diving trajectories use gravity and conserved angular momentum with different moments of inertia for tuck and extension. Five generated judge marks discard the highest and lowest before applying difficulty.

Current simplifications: floor caustics are animated highlights, springboards pivot instead of deforming elastically, recovery routes are illustrative and independent of individual competitors, judge scores appear in the panel while physical cards are static, and swimming strokes/turns are stylized. No browser visual validation has been performed.

## GitHub Pages

Run `npm run build:pages` after changing the app, then commit the source files and `docs/` together. GitHub Pages serves `docs/` from the `main` branch.
