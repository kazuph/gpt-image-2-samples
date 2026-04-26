# GPT Image 2 Samples

AI-generated visual sample collections published with GitHub Pages. The site now includes both 360-degree panorama viewers and non-panorama character/game concept galleries.

## Preview

```bash
cd site
python3 -m http.server 8765
```

Open `http://127.0.0.1:8765/` after the server starts.

## Site

- Published URL: `https://kazuph.github.io/gpt-image-2-samples/`
- Static site source: `site/`
- Deployment: GitHub Actions deploys `site/` whenever `main` is updated.

## Contents

- `site/index.html`: collection entrance page.
- `site/vtuber/`: six VTuber character prototypes with character sheets, stream screens, 3D live visuals, and character-specific game mockups.
- `site/comike/`: six centered-character Comiket camera-kid panorama scenes.
- `site/shinkansen/`: three railway-photography panorama scenes.
- `site/parkour/`: three first-person scenic parkour panorama scenes.
- `site/space/`: four space-observation panorama scenes.
