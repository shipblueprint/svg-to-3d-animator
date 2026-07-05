# SVG to 3D Animator

Turns flat SVGs into 3D extruded animations using Three.js.

## Usage

1. Place your `.svg` file in the **`assets/`** folder
2. Open `index.html` and update the filename on line:

```js
loader.load('assets/your-file.svg', (svgData) => {
```

3. Open `index.html` in a browser (or serve via live-server / vite)

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

- Works best with flat vector illustrations (not complex gradients or raster embeds)
- Single SVG at a time — no batch support yet
