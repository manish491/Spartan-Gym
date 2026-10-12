# Spartan Gym Website — GitHub Ready

## Deploy on GitHub Pages or Vercel

- The main website entry point is `index.html`.
- Upload the **contents of this folder** to the root of your GitHub repository.
- No build command is required; this is a static HTML site.
- For Vercel, choose **Other** as the framework preset and leave the build command empty. The output directory can be `.`.
- For GitHub Pages, open **Settings → Pages**, select the `main` branch and `/ (root)` folder, then save.

## Files
- `index.html` — main Spartan Arena gym website, including the 3D muscle targeting/exercise demo section.
- `demos/shader.html` — standalone shader animation demo.
- `demos/threejs.html` — standalone Three.js animation demo.
- `demos/spartan-arena-alternate.html` — alternate version of the main landing page.

## Notes
The site loads Tailwind CSS, Google Fonts, and Three.js from public CDNs, so those effects require an internet connection. No local image assets or build dependencies were referenced by the HTML. Third-party CDN availability and browser/device WebGL support can affect animation rendering.
