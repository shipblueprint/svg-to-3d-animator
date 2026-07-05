# SVG to 3D Animator

Turns flat SVGs into 3D extruded animations using Three.js.

## Usage

**Drag & drop** any `.svg` file onto the page, or click **Browse** to pick one. No code editing needed.

Alternatively, place an SVG in the `assets/` folder and uncomment the default load line in `index.html`.

```bash
npm install
npm run dev
```

## Controls

| Key | Action |
|-----|--------|
| Drag | Orbit camera |
| `P` | Export transparent PNG |
| `V` | Record 3s WebM video loop |

## Notes

- Single SVG at a time — drop a new one to replace
- Works best with flat vector illustrations
- SVGs are gitignored — they won't be committed
