# Birth Rotation Lab

Interactive prototype for nursing students to practise PV interpretation and the mechanism of labour.

## Files
- `index.html` — complete interactive app
- `favicon.svg` — browser icon
- `.nojekyll` — makes GitHub Pages serve the site directly
- `netlify.toml` — Netlify publish configuration

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then **Save**.
6. GitHub will provide the public URL after deployment.

## Deploy to Netlify
Fastest method:
1. Sign in to Netlify.
2. Choose **Add new project → Deploy manually**.
3. Drag the entire `birth-rotation-lab` folder (or this ZIP after extracting it) into the deploy area.
4. Netlify will generate a public URL immediately.

## Notes
- No build step or external library is required.
- The app is a single-page static site and works on current desktop/mobile browsers.
- This is a 2D teaching model; it does not reproduce all 3D biomechanics of labour.
