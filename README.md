# SVG to 3D Animator

Turns flat SVGs into 3D extruded animations using Three.js.

## Usage

Click **Open SVG** in the top-left and pick any `.svg` file. That's it.

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

- Single SVG at a time — open a new one to replace
- Works best with flat vector illustrations
- SVGs are gitignored — they won't be committed
