# Saaketh Chenna | Portfolio

Personal portfolio site: a single-page, static website (plain HTML, CSS and a little JavaScript). No build step.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html   the whole site (markup, styles, scripts)
assets/      photo, company and club logos, film posters, resume and IEEE paper pages
```

## Editing

- **Colors:** the `:root` block at the top of the `<style>` tag in `index.html` (`--background`, `--foreground`, `--muted`, `--accent`, `--border`, `--card`, `--k1` to `--k5`).
- **Content:** edit the text directly in `index.html`. Sections: hero, stats, About, Experience, Leadership, Projects, Documents, Skills, Off the Clock, Contact.
- **Images:** replace files in `assets/` keeping the same filenames.
- **Resume and paper viewers:** these show page images (`resume-page-1.jpg`, `ieee-paper-page-N.jpg`). To update them, export the PDF pages as JPEGs and replace the files.

## Deploy with GitHub Pages

Repo Settings > Pages > Build and deployment > Deploy from a branch > `main` / root.
The site will be live at `https://<your-username>.github.io/<repo-name>/`.
