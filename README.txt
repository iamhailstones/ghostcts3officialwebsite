# Hailstones

Personal portfolio for **Hailstones** — developer, game creator, and the person behind [GHOST CTS-3: Code to Survive](https://iamhailstones.github.io/GHOST-CTS-3/).

A single-file site (HTML, CSS and vanilla JS) with a 3D phone in the hero: hailstones bounce on a line inside the screen while cards and orbs fly out toward you. Tilt it with your mouse or finger; scroll to push the pieces further out.

## Features

- 3D phone hero with parallax tilt (mouse and touch)
- Hailstones bouncing on a glowing line (canvas)
- Mobile-friendly layout, slide-down menu, notch and safe-area support
- Reduced-motion support: animations switch off for users who prefer it
- No build step, no dependencies (only Google Fonts)

## Run locally

Open `index.html` in a browser. Or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy (GitHub Pages)

1. Push `index.html` and `README.md` to a repository.
2. Go to **Settings → Pages**, choose the main branch, root folder, and save.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Customise

| What | Where in `index.html` |
| --- | --- |
| Social links | the `.links` block near the bottom |
| Typed role lines | the `R` array in the script |
| Hailstone sizes and speed | the `S` array in the script |
| Colours | the `:root` variables at the top of the CSS |

## Links

- X: [@iamhailstones](https://x.com/iamhailstones)
- Instagram: [@iamhailstones_](https://www.instagram.com/iamhailstones_/)
- TikTok: [@iamhailstones](https://www.tiktok.com/@iamhailstones)
- GitHub: [iamhailstones](https://github.com/iamhailstones)