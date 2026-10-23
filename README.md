# Mansard Bungalow – 3D walkthrough

Interactive concept model of the proposed mansard / gambrel conversion.

* **Orbit** – drag to turn, scroll or pinch to zoom, right-drag to pan.
* **Walk** – drag to look, W A S D or arrow keys to move, Shift to hurry. On a phone: left pad moves, drag elsewhere to look.
* **Tour** – guided walk at head height through every main room (skipping the cloakroom WC and the stores), easing off at turns and peeking into dead-end rooms, up the main stair, down the hidden back stair, out of the back door, then an aerial loop. Speeds 1×, 1.5×, 2×, 2.5×.
* Toggle the roof and first floor off to look down into the rooms ("dollhouse" view).

## Files
| File | What it is |
|---|---|
| `index.html` | the viewer (three.js 0.160, loaded from jsDelivr) |
| `house_data.js` | the house geometry, generated from the same model as the drawings (v4) |
| `bungalow.glb` | the same model as a standard glTF file – opens in Blender, Windows 3D Viewer, or https://gltf-viewer.donmccurdy.com |

## Put it on GitHub Pages (free)
1. On github.com click **New repository**, name it e.g. `bungalow-3d`, set it **Public** (Pages on private repos needs a paid plan), create it.
2. **Add file → Upload files**, drag in everything in this folder (including `.nojekyll`), **Commit**.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch: `main`, folder `/ (root)`, **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/bungalow-3d/`.

To preview locally instead: run `python3 -m http.server` in this folder and open http://localhost:8000.

Concept model only – dimensions approximate (±0.5 m), not for construction.

## Drawings

The **Drawings** section in the control panel links to these files (keep the names as they are):

| File | Contents |
|---|---|
| `assets/ground-floor.pdf` / `.png` | Ground floor – proposed |
| `assets/first-floor.pdf` / `.png` | First floor – proposed |
| `assets/roof-plan.pdf` / `.png` | Roof plan |
| `assets/elevation-front.pdf` / `.png` | Front elevation (north-west) |
| `assets/elevation-rear.pdf` / `.png` | Rear elevation (south-east) |
| `assets/elevation-side-office.pdf` / `.png` | Side elevation – office / sunroom end |
| `assets/elevation-side-bedroom3.pdf` / `.png` | Side elevation – bedroom 3 end |
| `assets/all-drawings.pdf` | The whole set in one PDF |
| `assets/thumbs/*.png` | The small icons shown in the panel |

To update a drawing, replace the file with a new one of the same name.
