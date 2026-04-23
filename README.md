# Cars Story Spots

Interactieve storywebsite voor een individueel AR project.

## Bestanden

- `index.html`
- `style.css`

## Eigen 3D model gebruiken

1. Maak een map `models`.
2. Zet daar je `.glb` model in, bijvoorbeeld `racecar.glb`.
3. Vervang in `index.html`:

```html
src="https://modelviewer.dev/shared-assets/models/Astronaut.glb"
```

door:

```html
src="models/racecar.glb"
```

## GitHub Pages

Ga naar je repository:
Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → /root → Save.
