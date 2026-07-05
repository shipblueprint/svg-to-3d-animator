# SVG to 3D Animator

Turns flat SVGs into 3D extruded animations using Three.js.

## Usage

1. Place **one** `.svg` file in the `assets/` folder
2. Open `index.html` and change the filename near the top:

```js
const SVG_FILE = 'assets/your-file.svg';
```

3. Serve the page:

```bash
npm install
npm run dev
```

> **Single SVG only** — no batch or auto-detect yet. You edit the filename manually.

## Controls

| Key | Action |
|-----|--------|
| Drag | Orbit camera |
| `P` | Export transparent PNG |
| `V` | Record 3s WebM video loop |

## Notes

- Works best with flat vector illustrations (not complex gradients or raster embeds)
- SVGs in `assets/` are gitignored — they won't be committed
