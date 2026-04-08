# Elakkiya Portfolio

Static personal website for Elakkiya Ramarajan.

## Files

- `index.html` contains the site structure and content.
- `styles.css` contains the visual design and responsive layout.
- `script.js` adds the mobile menu and scroll reveal behavior.
- `Elakkiya_Ramarajan_Resume.docx` is linked from the site as a downloadable resume.

## Run locally

If you want to preview it locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

This project is already set up for GitHub Pages with a workflow in `.github/workflows/deploy.yml`.

Once the repository is on GitHub:

1. Push the `main` branch.
2. In GitHub, open `Settings` -> `Pages`.
3. Under `Build and deployment`, set `Source` to `GitHub Actions`.
4. The workflow will publish the site automatically after each push to `main`.

Your GitHub Pages URL will usually be:

`https://<github-username>.github.io/<repository-name>/`

If you want the site to live at the root of a custom domain later, you can add that in the repository Pages settings.

## Notes

- Update the `url` value in the JSON-LD block inside `index.html` after you pick your final domain.
- If you add a headshot or project images later, they can be dropped into this folder and linked directly.
