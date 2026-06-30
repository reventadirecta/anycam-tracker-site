# AnyCam Tracker Website v0.1

This repository is only the public landing site for AnyCam Tracker.

It does not contain AnyCam application code, installers, runtime assets, private downloads, or activation systems.

## Local preview

Open `index.html` directly in a browser for a quick preview.

For a cleaner local test, you can also serve the folder with a simple static server, for example:

```powershell
cd C:\Workspaces\Codex_CLEAN\01_Active\anycam-tracker-site
python -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open `Pages`.
3. Set the source to deploy from the `main` branch root.
4. Save and wait for GitHub Pages to publish the site.

The `.nojekyll` file is included so GitHub Pages serves the static files directly.

## Future placeholders

- Demo video: replace the placeholder block in `index.html` with the future YouTube embed.
- Payment or contact CTA: update the placeholder CTA in `founder.html`.
- Private download flow: update the Founder delivery wording in `download.html` without exposing real private links publicly.

## Never upload

- AnyCam source code
- `anycam-tracker` repo contents
- `anycam-tracker-app` repo contents
- installers
- builds
- zips
- runtime files
- logs
- secrets
- real licenses
- real private download URLs
- private Dropbox links
- activation systems
