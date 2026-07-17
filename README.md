# LiveStage Pro website

The public landing site for [LiveStage Pro](https://livestagepro.app), a local-first live performance system for working bands.

The site uses plain HTML, CSS, and a small amount of JavaScript. It has no framework, package dependencies, or build step, and is ready to host on GitHub Pages.

## Preview locally

You can open `index.html` directly in a browser. For a more accurate local preview, run a small static server from this folder:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). Stop the server with `Control-C`.

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. Open the repository’s **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the publishing branch (normally `main`) and the `/ (root)` folder, then save.
5. In the Pages settings, enable **Enforce HTTPS** after the custom domain is active.

The included `CNAME` file configures the custom domain `livestagepro.app`. The domain’s DNS records must also point to GitHub Pages according to GitHub’s current custom-domain instructions.

## Project files

- `index.html` — site structure and content
- `styles.css` — responsive visual design
- `script.js` — navigation, reveal effects, and current year
- `stage-background.jpg` — optimized public splash artwork used by the hero
- `CNAME` — GitHub Pages custom domain

## Content boundary

This repository contains only public website content. It does not include or copy private source code from the LiveStage Pro application.
